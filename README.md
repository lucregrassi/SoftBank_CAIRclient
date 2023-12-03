# CAIR client for Nao and Pepper
This repository contains the CAIR applications, available for the SoftBank robots Pepper and Nao.

If you want to use the internal microphone of the robots you have to install the ASR2 application as a first thing. 
Otherwise, you can use the CAIRclient_single application that connects through a socket to an external microphone of your choice.

To interact with the CAIR system, open the CAIRclient_single_ASR application folder in Choregraphe, deploy it on the robot and launch it using one of the following trigger sentences:

* Let's talk
* Talk with me

The application can also be launched directly from Choregraphe.
Please note that the other versions of the CAIRclient application are for research purposes and are still under testing. 

Once started, the application allows interacting with the CAIR Cloud.

To stop the application you can say one of these sentences:

* Stop talking
* Quit the application

All the other applications are integrated with the main one and allow the robot to perform extra actions during the conversation. For a better and more complete experience, it is advised to install all the applications on the robot.

For a detailed description on how to install and use the software, please consult the following Handbook: [CAIR_SW_Handbook.pdf](https://github.com/lucregrassi/cairclient_softbank/CAIR_SW_Handbook.pdf)
