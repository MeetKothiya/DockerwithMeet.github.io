-Lets learn some basic #docker command today⬇️

- docker pull:
- we can pull images from the Docker hub using the command docker pull.

![image](https://user-images.githubusercontent.com/32546363/211553235-d7398591-3806-4aab-8ca7-ca7396356be5.png)

- docker images:
- now we should have some images in our local machine, and to confirm, let’s run the this command to list all the local images. 

![image](https://user-images.githubusercontent.com/32546363/211553371-764992d8-3d5c-4ada-8052-fa37440d8a95.png)

- docker run :
- now that we have some images, we can try to create a container. we can use the --name option to assign a name to the container and--detach option to run the container in the background and -p for port.

![image](https://user-images.githubusercontent.com/32546363/211553457-1d1702df-b1af-464e-a7da-e0ed4cad5e4f.png)

- docker ps :
- We can list all the running containers by using the following command.

![image](https://user-images.githubusercontent.com/32546363/211553549-c6a2fe51-59e0-455e-ae79-df6f6766683a.png)

- docker stop :
- To stop a container, use the docker stop command with either the container id or container name. We may stop a container if we want to change our docker run command.

![image](https://user-images.githubusercontent.com/32546363/211553639-c37f30a1-5cda-4c76-97bf-30ff64b6879c.png)

- docker restart :
- we can restart our stopped contained by using this command. We may want to use this after we reboot our machine.

![image](https://user-images.githubusercontent.com/32546363/211553708-018ec238-1bd2-4e01-9c5e-fbf39edc9dd7.png)

- docker rename :
- we can change the container name from demo to test. We may want to change the name to keep track of our containers more easily.

![image](https://user-images.githubusercontent.com/32546363/211553792-26faf5ba-e525-4885-b1a6-5544f35a6645.png)

-  docker logs :
- This command is helpful for debugging our Docker containers. It will fetch logs from a specified container.

![image](https://user-images.githubusercontent.com/32546363/211553857-df876d4a-72aa-4373-8d2a-9da15a769ec8.png)

- docker rm:
- If we want to remove a container, we can use the following command. You may encounter an error like
- Error: You cannot remove a running container. Stop the container 
- As it suggests, we can stop the container first and then remove it.

![image](https://user-images.githubusercontent.com/32546363/211553971-15f624ab-6133-462e-815f-3c3a049aef94.png)

- docker rmi : 
- Finally, if we want to free some disk space, we can use the docker rmi command with the image id to remove an image.

![image](https://user-images.githubusercontent.com/32546363/211554065-fc814775-51eb-4711-b702-05449402e90b.png)

Follow for more DevOps threads ♾ 🚀
#DevOpswithMeet
