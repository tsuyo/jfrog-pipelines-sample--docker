# JFrog Pipelines Sample: Docker

## Prerequisites

- Integrations
  - tsuyo_github: GitHub
  - artifactory: Artifactory
- Repos 
  - sample-docker-local (docker/local)
  - sample-docker-gcr (docker/remote)
    - URL: https://gcr.io
  - sample-docker-hub (docker/remote)
    - URL: https://registry-1.docker.io/
  - sample-docker (docker/virtual)
    - includes: sample-docker-local, sample-docker-gcr, sample-docker-hub
