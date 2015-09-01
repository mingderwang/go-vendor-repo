docker run --rm -v $PWD:/app -w /app treeder/go vendor

docker run --rm -v $PWD:/app -w /app treeder/go build

docker run --rm -v $PWD:/app -w /app -p 8080:8080 iron/base ./app

refer to: http://www.iron.io/blog/2015/08/the-easiest-way-to-develop-with-go%E2%80%8A-%E2%80%8Aintroducing-a-docker-based-go-tool.html

copyright belong to owner
