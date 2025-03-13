# JAVA Web development with AWS CI/CD

## Description
Welcome to this project combinig of Java web devlopment and AWS CI/CD tools
<br>


## Table of content
- [JAVA Web development with AWS CI/CD](#java-web-development-with-aws-cicd)
  - [Description](#description)
  - [Table of content](#table-of-content)
  - [Introduction](#introduction)
  - [Technologies](#technologies)
    - [Setup](#setup)
  - [Contact](#contact)
  - [Conclusion](#conclusion)
  
<br>


## Introduction
- This project is used for an introduction to creating and deploying a Java-based web app using AWS, especially their CI/CD tools.
  
The deployment pipeline i am building around the java web-app in this repository is inviscible to the end-user, but makes a big impact by automating the software release processes.

- I am doing this project to learn more about CI/CD and get hands on expereince in automating the flow from developing code to deployed web app
- This fits into my career goals because i want to be an experienced DevOps Engineer


## Technologies
Here is what i am using for this project

- **Amazon EC2**- I am devloping my web app on Mmazon EC2 virtual servers, so that software development and deployment happens on the cloud.
- **Key Pairs** SSH Connections, Git, Maven and Java. 
- **VS Code**- For my IDE, I chose Virtual Studio Code. It connects direvtly to my development EC2 Instance, making it easy to edit and manage files deployed in the cloud.
- **Github**- All my web app code is stored and versioned in my personal github repositories.
- **AWS CodeArtifact**- Once it's rolled out, CodeArtifact will store my artficats and dependencies, which is great for high availability and speeding up my project's build process
- **AWS CodeBuilder**- Once it's rolled out, CodeBuild will take over my build process. It will compile the source code, run test, and produce ready-to-deploy software packages automatically.
- **AWS CodeDeployer**- Once it's rolled out, CodeDeploy will automate my deployment process across EC2 Instance
- **AWS CodePipeline**- Once it's rolled out, CodePipeline will automate the entire process from Github to CodeDeploy, integrating build, test, and deployment steps into one different workflow.


<br>



### Setup
To get this code running on your local machine, follow these steps

```sh
# Clone the repository
```bash
git clone https://github.com/OkoyeF/Nextwork-project.git

# Navigate into the project directory
```bash
cd yourproject

# Install dependencies
```bash
mvn install
```

<br>

## Contact
If you have any comment or complaints about the Next-work web-app project, please contact:
Fortune Okoye - okoyefortune87@gmail.com

<br>


## Conclusion
Thank you for exploring this project, I'll continue to build this pipeline and apply my leaning to future projects

A big shoutout to
