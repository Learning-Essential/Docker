# Basic-Dockerfile


First You should create a Directory (New Folder) with Any Name by the following command

                " mkdir (Directory Name) "

                
Go Inside that Directory with command " cd /Path where Directory Created/Directory Name "Press Enter"


Now, Create Dockerfile | open vim editor by the help of command 


                " vi Dockerfile "

                
Make Sure File must be Start With Capital "D" letter 


Once vim editor open, press shift + i from keyboard for writing docker file


In Dockerfile keep in mind every "Instruction" (Instruction are start from very left hand side) must be write in "Capital Letters" and "Argument" (Argument are start from right hand side) must be in "Small Letters" type command as following : 


                " FROM  alpine:latest
                  CMD  ["echo", "Hello, Rahul!"]  "


                
after write file save it, press shift and colon key (:) from keyboard and type "wq", press enter key


Now, build Docker Image from Dockerfile with following command


               "  docker build -t (Image Name whatever you want put on here)  . (this dot means from current directory) " and press enter
               Example:  docker build -t project-a (Image name)  .


               
After build image create container with help of command 


              "  docker run --name web (container name)  project-a (Image name)" and press enter 

              
While creating container, CMD command print a output on terminal


              " Hello, Rahul! "

              
That's It. You Have Done.





PROJECT LINK HERE





[project URL](https://roadmap.sh/projects/basic-dockerfile)











