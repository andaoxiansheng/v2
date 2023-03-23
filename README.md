## Project name
Intelligent classroom face attendance system

## Project introduction
The system is mainly used in the classroom attendance scene based on face recognition, and the technical implementation is as follows:
### ①client
It includes a micro-computing device equipped with a camera, which has face recognition function based on deep learning AI, and sends face features to the server through socket network communication. The program runs on embedded systems such as single chip microcomputer.
### ②server
Including student personal information database, can receive face features through socket network communication and match with the information in the database, and reply to the client matching results and personal information; The program runs on a personal PC. 

## Effect display

## Innovation point
The system cleverly applies network communication, embedded edge AI and face recognition technology to the classroom attendance scene. It does not need to use third-party applications such as Dingdou and Xuetong, but only needs to conduct face recognition before entering the classroom. The system can verify the identity of students and automatically summarize the class check-in results, realizing the intelligent class attendance function. The system has low cost and strong reuse, which will play a great positive role in the realization and promotion of smart classroom in colleges and universities in the future.

## Project schedule
**6.7  hardware packaging and testing**  
6.5  processing of 3D printed shell    
5.24 finish client and server GUI    
5.3  achieve check-in management system  
5.2  add function of database based on SQLite   
4.28 add function of person's img display  
4.21 deploy on Jetson Nano and send Mat directly  
4.18 face recognition/match and socket  

## requirements
opencv_python==4.5.1.48  
numpy==1.19.3  
pandas==0.24.2  
face_recognition==1.3.0  
PyQt5==5.15.4  
