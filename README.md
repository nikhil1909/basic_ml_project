# ml_project
ineuron machine learning project
### Software and account requirements.

1. [Github account](https://github.com)
2. [Heroku account](https://dashboard.heroku.com/login)
3. [VS Code IDE](https://code.visualstudio.com/download)
4. [GIT cli](https://git-scm.com/downloads)
5. [GIT Documentation](https://git-scm.com/docs/gittutorial)

Creating conda environment
```
conda create -p venv python==3.7 -y
```

```
conda activate venv/
```
OR
```
conda activate venv
```

```
pip install -r requirements.txt
```

To add files to git
```
git add .
```
OR
```
git add <filename>
```

> Note: To ignore file /folder, we can write name of file/folder in .gitignore file

To check git status
```
git status
```

To check all versions maintained by git
```
git log
```

To create a version or commit all changes by git
```
git commit -m "message"
```

To send version/changes to github
```
git push origin main
```
To check remote url
```
git remote -v
```

To setup CI/CD pipeline, we need 3 information
1. HEROKU_EMAIL = jaiswalnikhil28@gmail.com
2. HEROKU_API_KEY = <>
3. HEROKU_APP_NAME = ml-regression-app-0

BUILD DOCKER IMAGE
```
docker build -t <image_name>:<tagname> .
```

> Note: Image name for docker must be lowercase

To list docker images:
```
docker images
```

Run docker images
```
docker run -p 5000:5000 -e PORT=5000 <image_id>
```

To check running container in docker
```
docker ps
```

To stop docker container
```
docker stop <container_id>
```