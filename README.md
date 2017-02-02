[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/caruby-tissue.svg)](https://hub.docker.com/r/rubygem/caruby-tissue/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/caruby-tissue.svg)](https://hub.docker.com/r/rubygem/caruby-tissue/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/caruby-tissue.svg)](https://hub.docker.com/r/rubygem/caruby-tissue/)
[![Gem Downloads](https://img.shields.io/gem/dt/caruby-tissue.svg)](https://rubygems.org/gems/caruby-tissue/)
# caruby-tissue

Auto-Generated Docker image for caruby-tissue to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/caruby-tissue`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/caruby-tissue`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/caruby-tissue`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/caruby-tissue/)
