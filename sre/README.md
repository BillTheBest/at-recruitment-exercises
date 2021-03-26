## Recruitment Exercises for SRE

**NOTE**: Do no make any pull request with the exercise results, create a zip or tar file with the results, this file will be sent to your recruiter e-mail

### Recruitment Exercise

The idea of this exercise is to assess your level of knowledge, you are not obliged to do all the topics, the idea is precisely to know your level of expertise on the subjects, Cloud Native, Docker, Infrastructure as code.

The exercise consists of a few steps described below

- Create an application in a container that displays some message on the screen, the message is up to your imagination, the application can be written in any language, it is important to have the application's Dockerfile so that we can create the docker image.
- Create the k8s manifests for this application, considering three main components: Deployment file, Service, and a Configmap if needed.
- This 'Hello World!' app must print some [ENV VARS](https://en.wikipedia.org/wiki/Environment_variable) freely created by you on the Kubernetes manifests.
- Build a simple infrastructure using Terraform 12 or higher on AWS. You can choose between an RDS database or Elasticache, stay free to use modules

### We also expect the following:

- We expect you to structure the results generated in a folder organizing the exercise with the code, Dockerfile, README.md, and Terraform files.
- We expect you to follow the best and most optimized configuration for the components involved.
- Even though we're asking for an RDS or an Elasticache your 'Hello World!' app does not need to use it.

### What will not be evaluated:

- The 'Hello World!' app itself. Yes, [Keep It Stupid Simple](https://en.wikipedia.org/wiki/KISS_principle)
- The language you choose.

### Good luck! =)

Feel free to ask **any questions** you might have during the development of the exercise.

Thank you!
