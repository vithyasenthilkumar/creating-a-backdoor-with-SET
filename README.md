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
![image](https://github.com/vithyasenthilkumar/creating-a-backdoor-with-SET/assets/127177445/4d239d3f-f118-41a1-afa4-03710ba9a087)
The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
![image](https://github.com/vithyasenthilkumar/creating-a-backdoor-with-SET/assets/127177445/2ecd192b-7fbc-49e7-bed0-0ff6b7c5535f)
It displays the following menu and select 2 for Website Attack Vectors:
![image](https://github.com/vithyasenthilkumar/creating-a-backdoor-with-SET/assets/127177445/a872530f-de6f-4abf-9c70-4bd0ea144bab)
The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
![image](https://github.com/vithyasenthilkumar/creating-a-backdoor-with-SET/assets/127177445/77f92910-e476-45e2-b693-a927c9703719)
The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
![image](https://github.com/vithyasenthilkumar/creating-a-backdoor-with-SET/assets/127177445/63ea173f-f972-497a-826a-54f1a2ea1cc2)
It shows the following screen in which the ip address of the attacker need to be given which is the default value:
![image](https://github.com/vithyasenthilkumar/creating-a-backdoor-with-SET/assets/127177445/b980a8bc-26b6-4558-9acf-c5bcb1c27890)
It shows the following screen in which the option Google can be selected:
![image](https://github.com/vithyasenthilkumar/creating-a-backdoor-with-SET/assets/127177445/8890235b-4895-4590-9e92-d296679eea5c)
SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
![image](https://github.com/vithyasenthilkumar/creating-a-backdoor-with-SET/assets/127177445/11c90951-32b4-4bb2-9645-0dbb67f93ad7)
In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password
![image](https://github.com/vithyasenthilkumar/creating-a-backdoor-with-SET/assets/127177445/f71932e1-23ed-417f-a7e5-7d2d1180179a)
SET logs the information regarding the Google credentials:
![image](https://github.com/vithyasenthilkumar/creating-a-backdoor-with-SET/assets/127177445/b7ef7748-a10c-4314-a7c6-e83e9e0e284b)
SET logs the information in the xml file under /root/.set directory: 
![image](https://github.com/vithyasenthilkumar/creating-a-backdoor-with-SET/assets/127177445/793bc8e0-6b64-495d-8b49-0359b9669581)



## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
