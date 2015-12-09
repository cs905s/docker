# DockerHub - dmahajan/mongo-datavolume
#
This is an example from https://devops.profitbricks.com/tutorials/creating-a-mongodb-docker-container-with-an-attached-storage-volume/

It creates a MongoDB cluster with a data volume that can be mapped to a host volume.

One of the great things about Docker is with little effort you can spin up a container and begin to work with a new technology. In this case, we'll be spinning up MongoDB within a container using an external path on the host for data storage.

We will introduce you to two Docker concepts: mapping volumes between containers and using a Dockerfile to automate the build.


