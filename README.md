artifactory-vagrant-docker
==========================

This is a Vagrant Environment for [JFrog Artifactory Open Source](https://www.jfrog.com/open-source/)

Overview
--------
It creates an Ubuntu 16.04 VM in Virtual Box with vagrant and installs the last version of Artifactory server with docker.
See the description of "Installing with Docker" [here](https://www.jfrog.com/confluence/display/RTF/Installing+with+Docker) from the official documentation.

The Vagrant "install.sh" file contains also the commands to install Artifactory without docker if you prefer to not use docker(#2).
It installs the version 5.6.2 of Artifactory.

Artifactory server will be running on port 8081.
