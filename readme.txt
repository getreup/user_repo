https://blog.golang.org/docker

$ docker run --publish 6060:8080 --name test --rm outyet
The --publish flag tells docker to publish the container's port 8080 on the external port 6060.

The --name flag gives our container a predictable name to make it easier to work with.

The --rm flag tells docker to remove the container image when the outyet server exits.