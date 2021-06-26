# CI/CD using Cloud Native Tooling

# Intro

# Prerequisite
- Basic use Git
- Basic use Docker

# Use Case

# Preparation


# CI Implementation 

## Github Action
All `file` action will be stored on folder `.github/workflows`. 

### Run unit test of our apps
Because our application is built using python, we will use `pytest` pacakge to create 

### Build and push image to docker hub
We will using [Build and Push Docker Images](https://github.com/marketplace/actions/build-and-push-docker-images) upstream action. You can open the link to see more detailed uses of the action.
-   prepare `Dockerfile` to create image
-   prepare action file named `docker-build.yml`
-   [get docker token](https://www.docker.com/blog/docker-hub-new-personal-access-tokens/)
-   [create github secret for actions](https://docs.github.com/en/free-pro-team@latest/actions/reference/encrypted-secrets)



![image-20210624142750651](/home/purnanugraha/.var/app/io.typora.Typora/config/Typora/typora-user-images/image-20210624142750651.png)

![image-20210624142619739](/home/purnanugraha/.var/app/io.typora.Typora/config/Typora/typora-user-images/image-20210624142619739.png)
