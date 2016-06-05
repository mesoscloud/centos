[![Build Status](https://travis-ci.org/mesoscloud/centos.svg?branch=master)](https://travis-ci.org/mesoscloud/centos) [![Docker Stars](https://img.shields.io/docker/stars/mesoscloud/centos.svg)](https://hub.docker.com/r/mesoscloud/centos/) [![Docker Pulls](https://img.shields.io/docker/pulls/mesoscloud/centos.svg)](https://hub.docker.com/r/mesoscloud/centos/)

# centos

[![Join the chat at https://gitter.im/mesoscloud/mesoscloud](https://badges.gitter.im/mesoscloud/mesoscloud.svg)](https://gitter.im/mesoscloud/mesoscloud?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

CentOS

https://www.centos.org/

### What is the purpose of this repository?

To create a set of images that are ready to be consumed by mesoscloud.

**Here's an example**

CentOS 7:

```text
MAJOR=7
```

GitHub release:

```text
GITHUB_RELEASE=20160605
```

The following images are produced when the GitHub release is created:

```text
mesoscloud/centos:$MAJOR-$GITHUB_RELEASE  # This image is created
mesoscloud/centos:$MAJOR                  # This image is updated
```
