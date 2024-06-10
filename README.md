# COBOL by oyaabuun
COBOL a still relevant but less known language. COBOL runs 70% of financial institutions . When i started learning this all you get videos and content but where to practice it..  Now i will help you where to do it , Setup of opencobol and running it is not a real practice. Doing it on a z/OS is actual deal with JCL. 
In Today's guide i will help you with all the resources you can follow to setup the practice environemnt. 
Soon i will make a opensource cobol course on youtube and teach it for free 
There are people who are charging money also for this setup but guys after seeing opensource community for all these languages i believe this guide will help you learn this a lot 
***********************************************************************************************************************************************************************************************************************************
So Entreprise COBOL V6.4 which is currently the latest at the time of me writing this guide.
I have done all the setup necessary for running a IBM z/OS V3.1 sep 2023 release on a host windows machine with windows 11 

There are few thing you need to keep in mind when doing it

** THIS GUIDE IS ENTIRELY FOR LEARNING PURPOSE 

** THIS GUIDE DOESNT SUPPORT ANY KIND of PIRACY OF IBM z/OS 3.1 

** THIS GUIDE is only meant to help people out there who want to learn how these BIG IRONs operate or are already working in the industry and looking to upgrade their skills 

** COBOL developers numbers are decreasing day by day and the world needs more COBOL developers becasue many many many big organissation daily mission critical workloads are still on these systems

** I donot personally support any migration of COBOL, This language is very close to assembly language and the beauty of this thing is it can process millions and billions of records really fast .

** There is a reason why big businesses still are dependent on it.  COBOL Bro is reliable , resilient and COBOL is still one of the fastest way to process batch and transactions data 

** Next time you do a ATM transaction or online transaction through you credit card or netbanking (SAY ALL HAIL BOSS COBOL for my sweet purchase). 

** Many things wont be woring as smooth as they do on the z/OS architecture but like i said its important you learn it 

** you can reach me on telegram @aroy52


**HOW TO INSTALL z/OS and practice COBOL **
1. In google itself you can find where to download it z/OS ADCD 1.10,1.11,1.13 downlaod all the necessary cckd files
2. The IBMDEVSECOPS test image for z/OS 2.2 2.5 3.1 are also available on that same website
3. You need a hercules emulator to load the z/OS ckd cckd DASD images and do the system IPL
4. Download the emualtor from google or github page of hercules , keep in mind from ADCD Z/OS 1.11 TILL 2.5 only the hercules 4.7 will work ,but for z/OS 3.1 you need version 4.8 of hercules
5. After all downnloads are completed you need to configure the hercules.cnf file and Run the hercules.exe
6. connect to the HCD using 3270 , you can use vista320 which comes with a 30 days trial
7. for ipl of z/OS 1.10,1.11,1.13 follow this guide       https://leo.leung.xyz/wiki/Z/OS_Emulation_with_Hercules
8. For ipl z/OS 2.2 2.5 and 3.1 you dont need to do the coupling setup
9. once booted you have to use tso then username in all of these are IBMUSER, password for login will be mentioned in the description of the website from where you are downloading
10. few places where you can get error are hercules config and vista 3270 ip connection , you can reach me out on my telegram for this , soon i will create a youtube video for this entire setup
11.  
