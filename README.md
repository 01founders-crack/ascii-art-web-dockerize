# ascii-art-web-dockerize

created 'Dockerfile'

building your project:

docker build -t ascii-art-web-dockerize:latest .

showing images:

docker images

to run:

docker run --name ascii-art-web-dockerize -p 3000:3000 ascii-art-web-dockerize:latest

to remove:

docker rm ascii-art-web-dockerize
