# Hello Jerry! (from Uncle Leo and Newman)
NGINX Hello World Image - but better

Purpose

This image is used to demonstrate a better Hello World Docker image using NGINX using Hello Jerry. It serves up a single HTML page that shows the hostname of the container.

Usage

Start the container and publish port 80 mapped to port 9090 on the host using:

docker run -d -p=9090:80/tcp bobquillin/hello-jerry:latest
