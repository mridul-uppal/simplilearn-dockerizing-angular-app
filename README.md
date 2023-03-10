# SimpliLearn MEAN Stack Developer - Dockerizing Angular Application
Deploy an Angular application on Docker container on an EC2 instance

# Following requirements should be met:  
* Source code should be tracked on GitHub repositories. You need to document the tracked files that are ignored during the final push to the GitHub repository.
* The submission of your GitHub repository link is mandatory in order to track your task.
* The step-by-step process involved in completing this task should be documented.

# You must use the following:
AWS EC2 instance, Docker, Node JS, Angular CLI, GitHub

# Screenshots 
**Docker Repository
![Screenshot](/Screenshots/Docker%20Repo.png)

**Run Docker image (Local Instance)
![Screenshot](/Screenshots/Local%20Instance.png)

**Amazon EC2 Instance
![Screenshot](/Screenshots/Amazon%20EC2.png)

**Docker image pull into EC2 intance and run it (terminal interface)
![Screenshot](/Screenshots/Server%20Instance.png)

**App running on EC2 instance 
![Screenshot](/Screenshots/EC2%20Instance.png)



## Steps to run App
**Type it on terminal!**
1. Pull the App from docker 
       ** ```
        docker pull mriduluppal/dockerizing-angular-ec2:latest
        ```
        
2. Run the docker image 
        ** ```
        docker run –d –p 80:80 mriduluppal/dockerizing-angular-ec2:latest
        ```
        
3. Paste this link on your browser the app will run
    http://localhost

4. Amazon EC2 Instance running on
    http://100.27.2.203/
