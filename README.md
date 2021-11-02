# Web Based API Simulator / Developer Portal from Docker

This repository is a docker compose for replicating the local development environment.

### Install Prerequisites
- Download and install Docker Desktop (v2.3.0.3 is tested)
    - https://www.docker.com/products/docker-desktop
    - You can follow the instructions if you are stuck at some point.
        - Windows: https://docs.docker.com/docker-for-windows/install/
        - Mac: https://docs.docker.com/docker-for-mac/install/
- Run the Docker executable and start when installing is done.

### Clone Repos

- Clone this repository first via the command below:
  - `git clone https://github.com/astafford2/Web-based-API-Simulator-Developer-Portal-Docker.git`
- Then, cd into the folder and clone the other repository:
  - **If you will contribute, fork this repository first and clone your copies into a *bsu.developer-portal* folder.**
    -  https://bitbucket.org/accutechdev/bsu.developer-portal/src/master/
  - You can do it via command line (or choose your own way of cloning a repository, NOT DOWNLOADING).  

    -  (Windows) **Shift+Right-click** to an empty place on that folder to open a command line.
    -   Run the following command (it assumes you have **git** installed and **git** command accessible in PATH environment variable):
        - `git clone https://bitbucket.org/accutechdev/bsu.developer-portal/src/master/ bsu.developer-portal`

### Run

- Run the following docker-compose command in the root folder (where docker-compose.yml is):
  - `docker-compose up --build`
  - This might take some time for the initial build.
  - If Docker prompts to share folder(s), confirm them.
- If you want to rebuild from scratch, try using --nocache option.
  - `docker-compose build --no-cache`
  - Then running `docker-compose up`

### Browse

* Go to developer portal [http://localhost:8080/](http://localhost:8080/), and experience!
