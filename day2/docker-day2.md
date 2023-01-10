-Do you know there is a free #docker play ground. where you can create up to 5 free nodes and play with docker commands. 

-Visit the website given below and run your first container with me :)🐳 
![image](https://user-images.githubusercontent.com/32546363/211547540-5af95c62-3ebd-46a5-be97-94affae3b434.png)

-link: https://labs.play-with-docker.com

- Signup on this link and create Docker ID.
- Once logged in you will get 4 hrs. of time before instance gets refreshed and deletes all you data.
-okay now lets run our first container▶️

-Type command: docker pull <image name> 
-here we are pulling nginx webserver so command is:
-"docker pull nginx"
-you can see all available image here: https://hub.docker.com
  
![image](https://user-images.githubusercontent.com/32546363/211547702-5a57ea76-fac2-44b2-9d4e-d9aeb4ca4b2a.png)

-now type command: "docker images"
- it shows all the images we have pulled to local systems so far

 ![image](https://user-images.githubusercontent.com/32546363/211547782-a48f6376-c7d3-4c0a-8f54-93a10e2d4a9c.png)

-now lets run our first container with command: 
"docker container -d --name nginx-demo -p 80:80 nginx"
Here: -d = detached mode which keeps running our image in background
--name = name of container
-p = port to which our container will run
nginx is the name of image

![image](https://user-images.githubusercontent.com/32546363/211547968-a018af6c-cf40-4e30-a930-ee4e4ba0a6dc.png)

one this command is executed you can see there open port 80
click on that and viola you have just run you first container🕺🪩
 
![image](https://user-images.githubusercontent.com/32546363/211548146-0e2922e4-5890-4a12-a4fd-f509e213bd4a.png)

Go through this official documents to know more about docker commands : https://docs.docker.com/engine/reference/run/

Follow for more DevOps threads ♾ 🚀
#DevOpswithMeet
