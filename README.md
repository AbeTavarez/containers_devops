# Containers

## Build & Run

Build the image:
`docker build .` at the main dir.

Then run the container:
`docker run -p 3000:80 <Container ID>`

To list running container:
`docker ps`

To list all containers:
`docker ps -a`

To stop a running container:
`docker stop <Container ID>`