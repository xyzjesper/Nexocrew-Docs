---
icon: server
---

# Self Host

## Setup the Docker Setup



* You need a Docker Runtime on a Server
* The Server need 1 Core and 1 GB of Ram.

## Start and Run the app

* Go to [https://github.com/nexocrew-HQ/linkr.li](https://github.com/nexocrew-HQ/linkr.li)
* And copy the [Docker Compose File ](https://github.com/nexocrew-HQ/linkr.li/blob/master/docker-compose.yml)
* Create a Folder or only the docker-compose.yml
* Past the File and configure the ENV Variables
* Then run `docker compose up -d` &#x20;

## Deloy the Page with a Domain

* If you have a domain setup the Domain with a Reverse Proxy on the Container and setup the ENV Variables.
* Then do the same for the Link-Server.&#x20;
* After that you are done and you can use the domain. (Please not that the Host is the setup Domain like [linkr.li](https://links.xyzjesper.link/))
