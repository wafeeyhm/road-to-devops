# road-to-devops
My road to DevOps | Linux, AWS, Scripting, Jenkins, Ansible, Docker, K8s, Projects and ChatGPT

## Table of Contents
- [Chocolatey](#Chocolatey)
- [Softwares](#Softwares)
- [About](#About)
- [Scenario](#Scenario)
- [Tools](#Tools)
- [Acknowledgments](#acknowledgments)

## Chocolatey
- Tools to install software through the command line
- Download it from [here](https://chocolatey.org/install)

## Softwares
- choco install virtualbox --version=7.0.8 -y
- choco install vagrant --version=2.3.4 -y
- choco install git -y
- choco install corretto11jdk -y
- choco install maven -y
- choco install awscli -y
- choco install intellijidea-community -y
- choco install vscode -y
- choco install sublimetext3.app -y

## About
- I'll be practising a multi-tier web application stack
- The setup will be locally on a laptop/desktop
- I'll be practising containerized my applications, deploy the applications on kubernets cluster, etc
- I'll be building a social networking app with multiple services

## Scenario
- Local setup - automated, repeatable and Code
- There will be multiple services running like database - MySql, PostgreSQL. Web services - Apache Engine. Application services - Tomcat
- Runbook/setup document
- The architecture will NGINX, TOMCAT, RABBITMQ, MEMCACHED, MYSQL

## Tools
- Hypervisor - Oracle VM virtualbox
- Automation - Vagrant
- CLI - Git Bash
- IDE - Visual Studio Code / Notepad ++

## Objective
- VM automation locally
- Baseline for upcoming projects
- Real work project setup locally

## Architecture
- NGINX - will be used as a load balancer, it will route the request to the TOMCAT SERVER.
- TOMCAT - java web application service, most of the codes will be here.
- RABBITMQ - will be treated as a queuing agent to connect the applications together.
- MEMCACHED - is a database caching service, that will be connected to MySQL.
- MYSQL - will be the main database to store all the information.

## Acknowledgments
- Thanks to [imnowdevops](https://github.com/imnowdevops) for their inspiration.
- This project uses [DDC Material](https://github.com/imnowdevops/ddc-material).
