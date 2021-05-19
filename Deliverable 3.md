# Setup a MineCraft Server

## Table of Contents
- [Setup a MineCraft Server](#setup-a-minecraft-server)
  - [Table of Contents](#table-of-contents)
  - [Hardware Requirements](#hardware-requirements)
  - [Software Specifications](#software-specifications)
  - [Downloading all the requirements](#downloading-all-the-requirements)
  - [Steps To Create Server](#steps-to-create-server)
  - [Connecting Server to MineCraft](#connecting-server-to-minecraft)
  
## Hardware Requirements
- DDoS Protection
- 2.8Ghz+ CPU
- 6+ GB RAM (if running the server and game on your own computer)
- 1+ GB RAM (if using a hosting company for your server)
- Automatic backup capabilities
- fast connection 

## Software Specifications
- MineCraft Game (Any version)
- MineCraft Server 
- Java 

## Downloading all the requirements

Step 1 : Downloading MineCraft (can skip this step if you have MineCraft installed)
To install the game, go to mineCraft.net/download and download the game client. 

![Step 1 downloading](../images/../cis106-1/images/game.png)

As you can see the website recognizes your Operating System and give a download button

Step 2 : Open a web browser of your choice, type in Minecraft Server in th search base, you should download the latest version available at Minecraft.net
Click the purple link , a file named server.jar should appear in your file system. 

![Step 2 downloading](../images/../cis106-1/images/minecraft_server.png)

Step 3 : Open a new tab and go to https://www.java.com/en/ or type in Java download. Download Java, install completely. 

![Step 3 downloading](../images/../cis106-1/images/java.png)

## Steps To Create Server

Step 1 : Find the file server.jar and put it in the a folder on your desktop
- Inside the folder you created should only have the file server.jar

Step 2 : Open Terminal 

Step 3 : Type PWD

- The pwd command is a command line utility for printing the current working directory. It will print the full system path of the current working directory to standard output.

Step 4 : Type cd Downloads 
- As you can see you're in your home directory, we need to go to downloads since our server.jar file is there. To change working directories you can type cd then the destination. 

Step 5: Type touch start.sh 
- Touch creates a file, so we just created a start script file. 

So far your terminal should look like this 
![screenshot 1](../images/../cis106-1/images/Picture1.png)

Step 6: Type java -jar -Xmx2G -Xms 2G server.jar --nogui
    - Control x / to execute
    - Yes / Y 
    - Enter 


This command is the flag Xmx specifies the maximum memory allocation pool for a Java virtual machine (JVM), while Xms specifies the initial memory allocation pool. The 2 stands for GB, you can change it to 6 or any number you want. The server.jar is the file name we want the max memory too. 


![screenshot 2](../images/../cis106-1/images/Picture2.png)

One of the ways to check if this command worked is to go into your folder with the file server.jar. It should have multiple files now. 

- Like Below: 

![screenshot 3](../images/../cis106-1/images/Picture3.png)

Step 7 : Type Cd mincraft 
- we are moving to the minecraft directory 

Step 8 : Type ./start.sh
- This will open the hidden files, the . before the file name stands for hidden. 
  
This should be your terminal 
![screenshot 4](../images/../cis106-1/images/Picture4.png)

Step 9 : Type nano eula.txt to accept 
- Since there is a error stating to accept the eula.txt file, we can use nano to accept it. 
- Nano is an easy to use command line text editor

Step 10 : This is will pop up. In order to accept the file. We need to make sure eula is true. 

- So type in true instead of false 

![screenshot 5](../images/../cis106-1/images/Picture5.png)

Step 11 : Since the file is accepted we can run ./start.sh again. It should give an output like this. 
![screenshot 6](../images/../cis106-1/images/Picture6.png)

Step  12 : Server is up ! 
![screenshot 7](../images/../cis106-1/images/Picture7.png)


## Connecting Server to MineCraft

Step 13 : In order to play minecraft on the server , open up minecraft , click add server 

![screenshot 8](../images/../cis106-1/images/Picture8.png)


Step 14: Click done will search servers up in network, click the play button when appears and youre in 

![screenshot 9](../images/../cis106-1/images/Picture9.png)