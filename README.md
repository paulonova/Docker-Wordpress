# Docker – AWS – Wordpress. Documentation

## Install Wordpress using docker:

Link: https://docs.docker.com/samples/wordpress/

In https://hub.docker.com/

- Search for Wordpress, Mysql and phpmyadmin

Create a yaml file

> touch docker-compose.yml

> docker ps

> docker-compose up -d (Will generate the wordpress)

> docker-compose up

# Jenkins:

https://www.jenkins.io/

• Install the latest LTS version: brew install jenkins-lts
• Start the Jenkins service: brew services start jenkins-lts

After start I need to open in http://localhost:8080/ and a password will be required:
Copy the url provided after start and use the terminal to get the password:

- In terminal: cat <url-privided>

<ol>
  <li>Create your account</li>
  <li>Set all default installation</li>
  <li>Create a Job</li>
  <li>Choose Pipeline</li>
  <li>Pipeline Script and in the right side choose Scripted Pipeline</li>
  <li>Scripted Pipeline starts with node {}</li>
  <li>Declarative Pipeline starts with pipeline{}</li>
</ol>
