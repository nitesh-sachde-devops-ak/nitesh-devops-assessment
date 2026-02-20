# DevOps Assessment - Nitesh Sachde

### DevOps Assessment contains tasks related to Git & GitHub, Linux, Nginx and Python. This file will provide step-by-step details, output and brief explaination of all performed actions across all sections.

<div align="center">
  <img src="./images/git-logo.png" width="100" style="margin: 10px; vertical-align: middle;" alt="Git Logo">  
  <img src="./images/github-logo.png" width="100" style="margin: 10px; vertical-align: middle;" alt="GitHub Logo">
  <img src="./images/linux-logo.png" width="100" style="margin: 10px; vertical-align: middle;" alt="Linux Logo">
  <img src="./images/nginx-logo.png" width="100" style="margin: 10px; vertical-align: middle;" alt="Nginx Logo">
  <img src="./images/python-logo.png" width="100" style="margin: 10px; vertical-align: middle;" alt="Python Logo">
</div>

## Initial Setup

- First of all created user named **webuser-n** on provided EC2 instance and configured for SSH connection by generating pair of key using `ssh-keygen` and also added configuration in `~/.ssh/config` so we don't have to repeatedly enter full command instead we just run `ssh webuser-n-aws-ec2`.

#### The most important and basic thing we need to do before we start performing tasks we need to create root directory, also initialize git and make remote repository on GitHub to ensure smooth flow throughout all sections. 

- Now created our root directory **devops-assessment** in our home directory.
- Also initialized git in `~/devops-assessment` using `git init` command.
- We also generated another pair of SSH key for GitHub access and provided public key to GitHub.
- Added remote repository **nitesh-devops-assessment** to our local repository **devops-assessment** using `git remote add origin git@github.com:nitesh-sachde-devops-ak/nitesh-devops-assessment.git`.
- Now we created empty `README.md` and `.gitignore` files in our root directory and after commit we pushed this to remote branch.

### With that now we complete our initial setup which will provide base for our further tasks.