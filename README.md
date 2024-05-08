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
![326166857-1ca49026-9435-470e-a42d-1434087f897a](https://github.com/gowriganeshns/creating-a-backdoor-with-SET/assets/131433133/b7ce8ce6-c6c4-4e77-ac86-2d2be4480405)
The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
![326166869-34c489fc-51c7-414a-b33d-79bc4cd8291c](https://github.com/gowriganeshns/creating-a-backdoor-with-SET/assets/131433133/90c267c0-e772-480c-96d9-dc48b5d99587)
It displays the following menu and select 2 for Website Attack Vectors:
![326166878-1677f3a3-70f8-48c1-a2ad-00a6c4ca89b8](https://github.com/gowriganeshns/creating-a-backdoor-with-SET/assets/131433133/79dcc196-5fc7-4e3c-b3d1-b6416bdd3fa3)
The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
![326166895-e0c76e8f-9408-4819-b4ef-3c57be0300ef](https://github.com/gowriganeshns/creating-a-backdoor-with-SET/assets/131433133/cd9a6941-2ac4-4367-a777-d30a5e188812)
The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
![326166904-2ea86427-f0ac-4d28-b7ec-b7b07b060e0b](https://github.com/gowriganeshns/creating-a-backdoor-with-SET/assets/131433133/5d4367f0-2e1f-4078-88e6-f5d6d00960a5)
It shows the following screen in which the ip address of the attacker need to be given which is the default value:
![326166911-36fd6b02-6a93-49e8-84a2-890d197789cb](https://github.com/gowriganeshns/creating-a-backdoor-with-SET/assets/131433133/63b2894e-cb22-4f01-b2b4-d0a5208511cb)
It shows the following screen in which the option Google can be selected:

![326166928-91865649-580d-433e-9cc7-a7c03d86319c-1](https://github.com/gowriganeshns/creating-a-backdoor-with-SET/assets/131433133/f24b81fa-323e-4af6-9d60-3c06a64af64f)
SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done: 325268959-11c90951-32b4-4bb2-9645-0dbb67f93ad7

![326166947-57f2e4fe-c91a-4533-b614-08007f57707e-1](https://github.com/gowriganeshns/creating-a-backdoor-with-SET/assets/131433133/0dfd4ea6-db4b-4e8f-b92b-c0bc0701014e)
In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

![326166953-886311dd-40f4-4821-99d0-879523e494a7](https://github.com/gowriganeshns/creating-a-backdoor-with-SET/assets/131433133/17a93e87-9271-405a-ba6a-6b1917bfeb08)
SET logs the information in the xml file under /root/.set directory:
![325269417-793bc8e0-6b64-495d-8b49-0359b9669581](https://github.com/gowriganeshns/creating-a-backdoor-with-SET/assets/131433133/19180f1f-715e-435a-be25-bf557630515c)
## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
