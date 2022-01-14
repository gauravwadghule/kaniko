# kaniko


# Build Multi Architecture

docker manifest create \
wadghulegaurav/kaniko-multiarch-poc \
--amend wadghulegaurav/kaniko-multiarch-poc:amd64 \
--amend wadghulegaurav/kaniko-multiarch-poc:arm

# Push Image 
docker manifest push docker.io/wadghulegaurav/kaniko-multiarch-poc:latest