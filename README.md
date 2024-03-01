<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-learn/docker-volumes/blob/master/README.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

# Docker Volumes Tutorial

[![BoltOps Badge](https://img.boltops.com/boltops/badges/boltops-badge.png)](https://www.boltops.com)

This tutorial goes through Docker Volumes and how to use them in 2 ways:

1. -v option
2. --mount option

## Commands

    docker run -v $(pwd)/data:/data -P --rm -d httpd
    docker run -v $(pwd)/htdocs:/usr/local/apache2/htdocs -P --rm -d httpd
    docker run --mount source=htdocs,target=/usr/local/apache2/htdocs -P --rm -d httpd

## Video

[![Watch the video](https://uploads-learn.boltops.com/yyw92ywpbkyorc89veuasekhvw5s)](https://learn.boltops.com/courses/docker/lessons/docker-volumes-tutorial-how-they-work)

Note: Premium video content requires a subscription.
