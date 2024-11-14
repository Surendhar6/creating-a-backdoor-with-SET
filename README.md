# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:
![image](https://github.com/user-attachments/assets/00026b21-7602-45a7-963c-1a5899ab4ddd)


It displays the following menu and select 2 for Website Attack Vectors:
![image](https://github.com/user-attachments/assets/c2cd06a5-1995-4f76-8427-7813cc7389b3)


The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
![image](https://github.com/user-attachments/assets/f03ef137-352f-4922-857f-4434c52d7846)


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
![image](https://github.com/user-attachments/assets/b2e32bd6-a04a-42b5-8e21-1f558947e0c9)


It shows the following screen in which the ip address of the attacker need to be given which is the default value:
![image](https://github.com/user-attachments/assets/e05fae6b-fa46-4c1c-85cd-59ca1803ab41)


It shows the following screen in which the option Google can be selected:
![image](https://github.com/user-attachments/assets/5c379c0d-6987-4679-8f16-4895896866e0)


SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
![image](https://github.com/user-attachments/assets/a2744d7c-8163-494f-8c06-b491bc17a1c1)


In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed.
The victim can enter the username and password
![image](https://github.com/user-attachments/assets/c34e6998-c420-40ff-9cf1-2947fd10d541)


SET logs the information regarding the Google credentials:
![image](https://github.com/user-attachments/assets/c99060ae-4009-4495-869d-78e2c5d78497)


SET logs the information in the xml file under /root/.set directory:
![image](https://github.com/user-attachments/assets/a8d39ba3-b946-4c81-aa98-3cc90ac3e7fe)



## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
