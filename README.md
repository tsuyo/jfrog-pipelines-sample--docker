# JFrog Pipelines Sample: Docker

A Go source and Dockerfile are from [Hello Application example](https://github.com/GoogleCloudPlatform/kubernetes-engine-samples/tree/master/hello-app)

## Prerequisites

- Integrations
  - tsuyo_github: GitHub
  - artifactory: Artifactory
- Repos 
  - sample-docker-local (docker/local)
  - sample-docker-remote (docker/remote)
    - URL: https://registry-1.docker.io/
  - sample-docker (docker/virtual)
    - includes: sample-docker-local, sample-docker-remote
