# DevOps-Pre-Requisite-Course-Notes

## Introduction

There are several tools used in DevOps. Let's visualize the DevOps in practice. 

Suppose you want to build a website for a startup. You start coding, and after a huge amount of efforts, it's done. And now it's available in http://localhost:8000 or http://127.0.0.1:8000 . To make this site available to everyone, you need to host it to any kind of hosting platform like GCP, AWS, DigitalOcean, BrilientCloud or any cloud provider like this. 

You code the application. Now its time to build it. Building means to convert the code to a executable format. And converting a text code to a binary or executable format is called <strong> Building the code</strong>. 

There are several tools that helps to build application. Tools like Python Setup tools, Meven, Gradle etc.Once build, the executable move to production environment. In this case, our production environment is our server. And it's called deploy stage. 

In the build process, a executable file like <code> ./build.sh </code> file created. and in deploy stage, the build file is run by <code> ./app </code>. 

Now you want to update some code and add some features. And you hire some of your friends to work on your project. For this colaboration process, source code management tools like <strong> Git </strong> comes into play. And to manage it on a publicly hosted platform like <strong> GitHub, GitLab, BitBucket </strong> works. 

To build this code, you need a centralized server where the code will build and make it executable or binary. 


### CI/CD
### Container (Docker)


## Let's think about Production server only

How do we ensure, when any container stop, how the backup process will work? Then <strong> Container Orchestration </strong> like <strong> Kubernetes </strong> comes into play. It ensure how container should be deployed and how it will run as decleared. It will help to manage container, resources and use the underline storage to optimal resource optimization. 

Now you want to add more server to handle your large used. Here is a big issue. If you want to make the server as previously configured server, you can do it manualy or use <strong>Teraform </strong>. Teraform help to atomate the provisioning and configaration on server. It ensure, server configaration alwaye in the same stage. 

Its called Infrastacture as Code.

For monitoring the server, we need, <strong> Prometheus </strong>. And to vialize this graphecally, we need <strong>Grafana</strong>.


DevOps is a combination of people, processes, and tools,that work together and going from a idea to execution and delivering a high quality software consistently. 