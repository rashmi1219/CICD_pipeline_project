# CICD_pipeline_project
### Software and account requirements.
1. [Github Account](https://github.com)
2. [Heroku Account](https://dashboard.heroku.com/login)
3. [Vs Code IDE](https://code.visualstudio.com/download)
4. [GIT cli](https://git-scm.com/doenloads)


Creating conda environment
```
conda create -p venv python==3.7 -y
```


BUILD DOCKER IMAGE
```
docker build -t <image_name>:<tagname> .

```
Note: Name of image must be in lowercase
To list docker image command is
```
docker image

```
To run docker image
```
docker run -p 5000:5000 -e PORT=5000 image_name
```
To check the running container command is
```
docker ps
```
to stop any container command is 
```
docker stop <container_id>
