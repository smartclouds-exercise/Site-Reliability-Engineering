# Table of Contents
- [Table of Contents](#table-of-contents)
- [Please implement exercise below](#please-implement-exercise-below)
  - [Write an simple RESTful API (Using Python Flask or Golang gin)](#write-an-simple-restful-api-using-python-flask-or-golang-gin)
  - [Build your application to container images and manage your service with docker-compose](#build-your-application-to-container-images-and-manage-your-service-with-docker-compose)
  - [Upload your git repository to public github and must have content below](#upload-your-git-repository-to-public-github-and-must-have-content-below)
- [Note](#note)
    - [We will clone your git repository and verify in local dev environment](#we-will-clone-your-git-repository-and-verify-in-local-dev-environment)

# Please implement exercise below
## Write an simple RESTful API (Using Python Flask or Golang gin)
- Employee Data Management
- Must have CRUD function
- Authentication and validation (plus)
- Data format
``` json
{
    "id": "<username>",
    "email": "<email>",
    "mobile": "<mobile>",
    "position": {
        "title": "<title>",
        "department": "<department>"
    }
}
```

## Build your application to container images and manage your service with docker-compose
- Dockerfile
- docker-compose.yml

## Upload your git repository to public github and must have content below
``` shell
app                   # application location
.env.example
Dockerfile
docker-compose.yml
README.md             # How to use
```

# Note
### We will clone your git repository and verify in local dev environment
