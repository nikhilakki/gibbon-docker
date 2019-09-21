Setup Instructions


1. Install docker & docker-compose [link](https://computingforgeeks.com/install-docker-and-docker-compose-on-debian-10-buster/)
2. Run the following commands in bash shell (Linux) or Powershell/command prompt on(Windows)
   1. Build image 
        ```bash
        docker-compose build
        ```
    2. Run docker image
        ```bash
        docker-compose up -d
        ```
    3. To check status of docker containers
        ```bash
        docker-compose ps
        ```
3. Visit http://0.0.0.0 or http://<ipaddress-of-server>
4. Follow install instructions
   1. 