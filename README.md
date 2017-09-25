# Container for Housing a Development Environment
[![Build Status](https://travis-ci.org/justin-vanwinkle/Docker-Azure-Storage-Explorer.svg?branch=master)](https://travis-ci.org/justin-vanwinkle/Docker-Azure-Storage-Explorer)
 
__THIS CONTAINER IS NOT FOR PRODUCTION USE BUT FOR LOCAL DEVELOPMENT__

## Container information
This container extends the offical debian docker image.

This container is set up to have access to your local file system, so everything you do will persist.

## Know Issues:

- Your working directory must be with-in your host user's home directory. Attempting run
  any of the containers outside of this will result in failure.
