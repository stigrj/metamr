# metamr

Meta-stuff for the MR family.

## Docker images

The images are organized by folder.

The image used on CircleCI for testing is built automatically on [Quay.io](quay.io)
You can download it locally with:

    docker pull quay.io/metamr/circleci_ubuntu-18.04
    
and ehen get a shell inside the container with

    docker run -it metamr/circleci_ubuntu18.04
    
This can be useful to troubleshoot CI failures.

We also provide another image to run MRChem directly. This is built automatically on [DockerHub](https://hub.docker.com/u/mrchemsoft).
You can run it with:

    docker run mrchemsoft/mrchem_ubuntu18.04 </path/to/input/file>
