# metamr

Meta-stuff for the MR family.

## Docker images

The images are organized by folder and are automatically built on `DockerHub`
at https://hub.docker.com/u/mrchemsoft/ `DockerHub` does not allow dashes in user
and organization names.

For example you can download the `circleci_ubuntu18.04` container locally with:

    docker pull mrchemsoft/circleci_ubuntu18.04

Then get a shell inside the container with

    docker run -it mrchemsoft/circleci_ubuntu18.04
