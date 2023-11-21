# Rising of the DevOps

For this project we try to create a CI/CD pipeline for a simple webapp. **GitHub Actions** would be a good choice to solve this task.
The task is ready when the build is green.

## Tasks

1. Create a basic GitHub Actions workflow to run the lint test of my JavaScript app.
    - There is a pull request in GitHub with Github Actions workflow.
    - There is a running lint test in GitHub Actions for the app.

2. Fix the failing build
    - No errors show up in the build logs, the build is green.
    - No lint errors occur when running `npm lint`.

3. Create a Dockerfile which builds and runs the app without the uneccessary files and folders.
    - Dockerfile is valid, the image starts the app.
    - Valid `.dockerignore` file that excludes `.git` and `node_modules` folders.

4. Modify the GitHub Actions workflow to build and push the Docker image to DockerHub.
    - DockerHub access information (`DOCKERHUB_USERNAME` and `DOCKERHUB_PASSWORD`) are added as secret environment variables to GitHub Actions.
    - The workflow builds and pushes the docker image to DockerHub.
  
## What are we going to learn?

- Create a CI/CD pipeline with GitHub Actions workflow.
- Set running conditions for GitHub Actions workflow.
- Build a Docker image.
- Push the Docker image to image registry.

