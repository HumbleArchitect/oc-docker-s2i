# simple dockerfile to test OCP s2i using Dockerfile 

FROM registry.access.redhat.com/ubi7:latest

# Change the parameter at the Docker file, in order to trigger the webhook for testing
# CMD ["/bin/bash", "-c", "sleep infinity"]
# Uncomment the following link, so that the process only sleep 30 seconds and then exit
 CMD ["/bin/bash", "-c", "--", "while true; do sleep 30; done;"]
