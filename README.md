# Demo Setup Information

* How to setup a Demo using IBM UrbanCode, Jetbrains TeamCity and Atlassian Jira.

## UrbanCode

### UrbanCode Configuration Overview

CentOS 8, MySQL/MariaDB, UCD V7.0.5.2, running on VMWare Fusion
Created using this Ansible project: <https://github.com/osmanburucu-ibm/deploy-urbancode-deploy>

More detailed Description about the UrbanCode setup, like component configuration and deploy process: [UrbanCode Setup](README_UrbanCode-Setup.md)

## Jira

### Jira Configuration Overview

I am using a container provided by Atlassian on Dockerhub

* <https://hub.docker.com/r/atlassian/jira-software>

More details about Jira setup are here: [Jira Setup](README_Jira-Setup.md)

## Team City

Also TeamCity runs as a container on my laptop

* Server:
  * <https://hub.docker.com/r/jetbrains/teamcity-server>
* Agents:
  * <https://hub.docker.com/r/jetbrains/teamcity-minimal-agent/>
  * <https://hub.docker.com/r/jetbrains/teamcity-agent/>

More details about TeamCity setup are here: [TeamCity Setup](README_TeamCity-Setup.md)

## URLs in my environment

* UCD demo URL: <https://192.168.62.190:8443>
* JIRA demo URL: <http://192.168.62.1:8080>
* TC demo URL: <http://192.168.62.1:8111>
