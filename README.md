# What is this?
This project is based on the official stable nginx image (linux Alpine) and the nginx brotli module, coming from the [fork currently maintained by eustas](https://github.com/eustas/ngx_brotli). It is inspired by the [docker image from fholzer](https://github.com/fholzer/docker-nginx-brotli) but without adding other extensions than brotli compared to the official nginx stable image.

# How to use this image
As this project is based on the official [nginx image](https://hub.docker.com/_/nginx/) look for instructions there. In addition to the standard configuration directives, you'll be able to use the brotli module specific ones, see [here for official documentation](https://github.com/eustas/ngx_brotli#configuration-directives)

# Versions
This dockerfile is based on the latest version of the official nginx Dockerfile:
https://github.com/nginxinc/docker-nginx/tree/2364fdc54af554d28ef95b7be381677d10987986/stable/alpine

Unfortunately, the nginx-brotli plugin is currently unmaintained, so we used this fork that is still maintained, in particular the latest release tag:
https://github.com/eustas/ngx_brotli/tree/v0.1.2