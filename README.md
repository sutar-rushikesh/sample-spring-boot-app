# Sample spring boot application build for Multi-Environment Deployment on Amazon EKS

> A declarative Jenkins pipeline that builds a Spring Boot application with Maven, analyses it with SonarQube, packages it as a Docker image, pushes it to DockerHub, and deploys it to **dev**, **test** and **prod** namespaces on Amazon EKS - with a **manual approval gate before production** and email notifications on success or failure.


