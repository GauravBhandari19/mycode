# Autobuild a Simple Docker Image Creation 

1. index.js: Has bare minimum code for running a server
2. Dockerfile: Has info for builoding a docker image
3. package.json: Min code for node app

# Create Auto build
1. Go to Docker Hub:

```
https://hub.docker.com/
```

2. Create a repository (if not already created), link to GITHUB account

Create Repo Github

![Image of Create repo GITHUB](https://github.com/GauravBhandari19/docker/blob/master/img/createRepository.png)

Create Repo - Docker Hub

![Image of Create repo Dockerhub](https://github.com/GauravBhandari19/docker/blob/master/img/createRepositoryDockerHub.png)

3. Navigate to Builds tab
4. Click "Configure Automated Builds"

Create Automated build - Docker Hub

![Image of Automated Build](https://github.com/GauravBhandari19/docker/blob/master/img/createAutomatedBuilds.png)

Fill Automated Build Details - Docker Hub

![Image of Fill Auto Build](https://github.com/GauravBhandari19/docker/blob/master/img/FillAutomatedBuildDetails.png)

5. Select the following
    1. Source repository
    1. Build Location: This should already be preselected to Docker Hub Infrastructure
    1. Set "AUTOTEST" to "Off"
    1. Set "REPOSITORY LINKS" to "Enable for Base Image"
    1. Click + on build rules
        1. Select Source Type: Branch
        1. Select Source: master
        1. select Docker Tag: latest
        1: Provide Dockerfile location
        1. Enable Autobuild
        1. Enable Build Caching
    1. Click "Save"

6. Go to GIT HUB and commit file
7. A build should be automatically triggered in Docker Hub (when you Commit anything in your reppository)



# Reference
1. MD Markers markdown: https://guides.github.com/features/mastering-markdown/
