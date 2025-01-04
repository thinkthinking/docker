git tag -a 2.6.10-thinkthinking.7 -m "Local development optimization version 2.6.10-thinkthinking.7 for docker"

git push origin 2.6.10-thinkthinking.7

edit Dockerfile :
```
ARG WALLABAG_VERSION=2.6.10-thinkthinking.7
```