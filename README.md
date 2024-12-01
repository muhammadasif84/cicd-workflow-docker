# cicd-workflow-docker
<h3>Creating CICD Workflow of Docker Container</h3>
<h5>Follow these steps to setup a CICD Workflow of Docker Container</h5> 
1- Clone Repo https://github.com/muhammadasif84/cicd-workflow-docker.git
<br/>
2- Generate access token on docker-hub profile
<br/>
3- Create 2 repository secrets with following names
<br/>
    i- DOCKERHUB_SECRET and paste you generated docker-hub token in description
    <br/>
    ii- DOCKERHUB_USERNAME and paste your dockerhub username in description
<br/>
<h4>NOTE:</h4>
<h4>Create new branch from main, commit and push some changes, create pull request and It should passed all jobs mentioned in .github\workflows\deploy.yml, for workflow status check Actions</h4>

