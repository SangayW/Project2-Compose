# Task2 Container and Jenkins Configuration

## Create a Docker Compose file/stack to run.

### Docker-In-Docker(DinD) Container

- Stands for Docker in Docker.

- Running Docker container inside another docker.

- Useful in running Docker commands in a CI/CD pipeline.

- It can be used to run Docker on the host which does not have Docker
  installed.

1.  Create docker network called Jenkins

<img src="./media_dir/media/image1.png"
style="width:6.26806in;height:1.80556in"
alt="A screenshot of a computer program Description automatically generated" />

Figure 1 Jenkins Network Creation

2.  docker-compose.yml file content having **dind** and **jenkins**
    services.

<img src="./media_dir/media/image2.png"
style="width:5.45861in;height:4.88219in"
alt="A screenshot of a computer screen Description automatically generated" />

Figure 2 dind and Jenkins container creation

<img src="./media_dir/media/image3.png"
style="width:6.26806in;height:3.36111in" />

Figure 3 Running docker-compose file to create dind container

<img src="./media_dir/media/image4.png"
style="width:6.18056in;height:3.07639in" />

## Commit and push the Docker Compose file to the \`main\` branch of the \`Project2-Compose\` repository.

<img src="./media_dir/media/image5.png"
style="width:3.96548in;height:0.34724in" />

<img src="./media_dir/media/image6.png"
style="width:5.50723in;height:2.14594in"
alt="A screenshot of a computer program Description automatically generated" />

Figure 6 Using Personal Access Token to while pushing code to GitHub

<img src="./media_dir/media/image7.png"
style="width:6.26806in;height:1.68472in"
alt="A screenshot of a computer Description automatically generated" />

Figure 7 docker-compose file in the Project2-Compose file in the GitHub.
