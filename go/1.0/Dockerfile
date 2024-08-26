# Use the official BusyBox image as base
FROM registry.hub.docker.com/akshaydocker/busybox:1.0.0

# Set a maintainer label for the image
LABEL maintainer="your_email@example.com"

# Run commands to configure the container
# For example, create a directory and add a file
RUN mkdir -p /myapp \
    && echo "Hello BusyBox!" > /myapp/hello.txt

# Define the default command to run when the container starts
CMD ["/bin/sh"]

