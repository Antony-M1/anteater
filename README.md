Anteater

**Prerequisite**
`Python3.10`
`Docker`


# SETUP DEVELOPMENT MODE
Pull the code to your local machine

Create the `env` using this command
```
python3.10 -m venv env
```

Run the Project
 ```
 flask run
 ```
 
 
 # DOCKERIZE
 After finishing all the setup create build from the code
 ```
 docker build --tag <TAG_NAME> .
 ```
 
 Run the project usign `docker run` command like this
 ```
 docker run -d -p 5000:5000 --name <CONTAINER_NAME> <IMAGE_NAME>
 ```
 
