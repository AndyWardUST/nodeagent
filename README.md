# nodeagent
podman run -v /etc/docker/:/etc/docker/ -v /etc/sysconfig/docker:/etc/sysconfig/docker -v /usr/bin/docker:/usr/bin/docker -v /var/run/docker.sock:/var/run/docker.sock -e AZP_URL=https://dev.azure.com/<organisation>/ -e AZP_TOKEN=<secret> -e AZP_AGENT_NAME=Node1 -e AZP_POOL='Node Pool' nodeagent
