## commands
1. docker build -t app_name .
2. docker images - to view images built
3. docker run -p 5001:5001 welcome-app 
4. docker ps "to view Containers running"
5. docker stop container_id 
6. download an image from docker hub 
eg. docker pull docker/getting-started
7. You can run it locally with the following command:
docker run -d -p 80:80 docker/getting-started
8. To verify if Containers is running
docker ps
9. To stop running 
docker stop container_id
10. Rename image name 
docker tag rohan2939/welcome-app rohan2939/welcome-app1
11. to push 
docker push rohan2939/welcome-app

12. docker compose up : run docker-compose.yml
13. Remove images from container : docker image rm -f container_id