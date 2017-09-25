# Container for Housing a Development Environment
[![Build Status](https://travis-ci.org/justin-vanwinkle/Docker-Dev-Utils.svg?branch=master)](https://travis-ci.org/justin-vanwinkle/Docker-Dev-Utils)
 
__THIS CONTAINER IS NOT FOR PRODUCTION USE BUT FOR LOCAL DEVELOPMENT__

## Container information
This container extends the justinvanwinkle/dev-base docker image.  It provides several useful utilities with X forwarding.

This container is set up to have access to your local file system, so everything you do will persist.

## Know Issues:

- Your working directory must be with-in your host user's home directory. Attempting run
  any of the containers outside of this will result in failure.
