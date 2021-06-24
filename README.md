# Table of Contents
- [Table of Contents](#table-of-contents)
- [Please implement exercise below](#please-implement-exercise-below)
  - [Basic](#basic)
    - [Build sample laravel (php framework) site](#build-sample-laravel-php-framework-site)
    - [Please implement mysqldump backup shell (shell script)](#please-implement-mysqldump-backup-shell-shell-script)
    - [Build your application to container images and manage your service with docker-compose](#build-your-application-to-container-images-and-manage-your-service-with-docker-compose)
    - [Upload your git repository to public github and must have content below](#upload-your-git-repository-to-public-github-and-must-have-content-below)
  - [Plus](#plus)
    - [Write an simple RESTful API (Using Python Flask or Golang gin)](#write-an-simple-restful-api-using-python-flask-or-golang-gin)
    - [Build your application to container images and manage your service with docker-compose](#build-your-application-to-container-images-and-manage-your-service-with-docker-compose-1)
    - [Upload your git repository to public github and must have content below](#upload-your-git-repository-to-public-github-and-must-have-content-below-1)
- [Note](#note)

# Please implement exercise below
## Basic
### Build sample laravel (php framework) site
- php required package: php7.4,php7.4-fpm,php7.4-mysql
- sql server: mysql-5.7
- web server: nginx
- please config nginx and add new site for laravel default page
- virtual hostname: smartclouds.site

### Please implement mysqldump backup shell (shell script)
- Import sample database (https://github.com/datacharmer/test_db) data to mysql
- use sed & awk to dump every database for mysql backup
- backup file name: mysql-(%Y%m%d%H)-database_name.tar.gz
- Delete Backupfiles older than 10 days using shell script

### Build your application to container images and manage your service with docker-compose
- Dockerfile
- docker-compose.yml

### Upload your git repository to public github and must have content below
``` shell
app                   # application location
.env.example
Dockerfile
docker-compose.yml
README.md             # How to use
```

## Plus
### Write an simple RESTful API (Using Python Flask or Golang gin)
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

### Build your application to container images and manage your service with docker-compose
- Dockerfile
- docker-compose.yml

### Upload your git repository to public github and must have content below
``` shell
app                   # application location
.env.example
Dockerfile
docker-compose.yml
README.md             # How to use
```

# Note
- We will clone your git repository and verify in local dev environment
