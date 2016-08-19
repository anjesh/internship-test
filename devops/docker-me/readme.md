## Docker me

If this is the first time you have heard of 'Docker', you should be excited! You get to learn something new! Take your time to explore and learn, and show us what you can do. 

### What you need to do

* If you haven’t already done so, take a [git class in codeschool](https://www.codeschool.com/courses/try-git).
* Create a private repo called “yipl-docker-me” in [bitbucket](https://bitbucket.org)
* Solve the problem detailed below
* Push your code to the repo (make sure that you have multiple numbers of commits with proper messages) 
* Invite internship-bitbucket@yipl.com.np to that particular private repo

#### Problem

Create a Dockerfile which can automate the following tasks:

* Use the alpine linux image
* Setup nginx server
* Clone the given repo https://github.com/anjesh/internship-test
* Copy this [folder](https://github.com/anjesh/internship-test/tree/master/devops/docker-me/site) from the cloned repo to the nginx document root folder
* Expose the port 9000 in the host and link with the default nginx port
* Push your Dockerfile to the repo.

When the docker is run, the [html file](https://github.com/anjesh/internship-test/blob/master/devops/docker-me/site/index.html) should be accessible from the browser at http://localhost:9000/site/index.html

* Write the docker run command with the port mentioned in readme.md



