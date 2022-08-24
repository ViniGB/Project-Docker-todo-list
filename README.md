# Project Docker To-do list

- Project to create Docker configurations to a full-stack application.

## Requirements

### Dockers commands

1. Create `01container` in interactive mode, using `alpine v3.12` image ✔️
2. Initiate `01container` ✔️
3. List containers filtering by `01container` ✔️
4. Execute `cat /etc/os-release` on `01container` without docking with it ✔️
5. Remove `01container` ✔️
6. Download `nginx v1.21.3-alpine` without creating nor running a container ✔️
7. Run a background new container with `ngix v1.21.3-alpine` image, naming it `02images`, and mapping its standard port as `3000` in hosting system  ✔️
8. Stop running `02images` container ✔️

### Dockerfile

9. Generate a build from the todo-app backend Dockerfile, naming image as `todobackend` ✔️
10. Generate a build from the todo-app frontend Dockerfile, naming image as `todofrontend` ✔️
11. Generate a build from the todo-app tests Dockerfile, naming image as `todotests` ✔️

## Bonus Requirements

### Docker-compose

12. Upload a background orchestration with docker-compose so that backend, frontend and tests can communicate ✔️
 
## Language and Tools

<a href="https://www.docker.com/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="30" height="30"/> </a>
Docker

## Get started

<details>
  <summary><strong> Install it locally </strong></summary>
  </br>
  
  👉 /tests/e2e was provided by Trybe
  
  - Open terminal and create a directory in your preferred location:
  ```sh
  $ mkdir <Your directory name here>
  ```
  
  - Access directory then clone the repository:
  ```sh
  $ cd <Your directory name here>
  $ git clone git@github.com:ViniGB/Project-Docker-todo-list.git
  ```
  
  - Access the newly created directory:
  ```sh
  $ cd Project-Docker-todo-list
  ```
  
  - Install dependencies:
  ```sh
  $ npm install
  ```
</details>
