# Updated as of Aug 16, 2017
# FROM specified which image i want to download
# Needs to be provided before any other section of code.
FROM nginx:latest
#Author of the Docker File
# MAINTAINER Pictolearn Note: MAINTAINER has been deprecated for LABEL, 
# LABEL is a key value pair 
LABEL "Maintainer"="ms"

# Copy the following directory
COPY Landing_page/ /usr/share/nginx/html/Landing_page 

# Copy httpd.conf with changes to the root directory
COPY default.conf /etc/nginx/conf.d/
