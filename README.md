# Wordpress docker-compose example
wordpress, mysql and phpmyadmin docker-compose.yml example
## How to use it aka Quickstart

### Prerequisite
you must have installed docker and docker engine on your machine to run this docker-compose.yml.
 Here's an installation reference
```
https://docs.docker.com/engine/install/ubuntu/
```
1. Git clone: 
   Open the terminal
   ``` 
   :~$ git clone https://github.com/tareqanam/wordpress_docker.git
    ```
   Open the wordpress_docker directory from your terminal
   
   ```
   :~$ cd wordpress_docker/
   ```

    
2. Run the docker-compose file :

    ```
    :~/wordpress_docker$ sudo docker-compose up
    ```
3. To run in detached mode: Use '-d' to run containers in the background 
    
    ```
    :~/wordpress_docker$ sudo docker-compose up -d
    ```
