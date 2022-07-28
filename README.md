# MachineLearningProject
My first machine learning end-to-end project

Software and account Requirement.
Github Account
Heroku Account
VS Code IDE
GIT cli
GIT Documentation

Creating conda environment

conda create -p venv python==3.7 -y
conda activate venv/
OR

conda activate venv
pip install -r requirements.txt

To Add files to git
git add .
OR
git add <file_name>

Note: To ignore file or folder from git we can write name of file/folder in .gitignore file

To check the git status
git status

To check all version maintained by git
1) git log

To create version/commit all changes by git
1) git commit -m "message"

To send version/changes to github
1) git push origin main

To check remote url
1) git remote -v

To setup CI/CD pipeline in heroku we need 3 information
1) HEROKU_EMAIL = thapadeep234@gmail.com
   HEROKU_API_KEY = <>
   HEROKU_APP_NAME = ml-regression-app

BUILD DOCKER IMAGE
1)docker build -t <image_name>:<tagname> .
  Note: Image name for docker must be lowercase

To list docker image
1) docker images

Run docker image
1) docker run -p 5000:5000 -e PORT=5000 f8c749e73678

To check running container in docker
1) docker ps

To stop docker conatiner
1) docker stop <container_id>

python setup.py install
1) Install ipykernel
    pip install ipykernel

Data Drift: When your datset stats gets change we call it as data drift

Write a function to get training file path from artifact dir