# jenkins-docker
Docker setup for Jenkins CI server, with a separate data container

In this setup, 2 containers are created:  One container for Jenkins server and one container for retaining the data produced by the Jenkins server (logs, cache, plugins, jobs, etc).

Reference: https://engineering.riotgames.com/news/thinking-inside-container
