# Installing-and-running-nessus
This is a nessus intalation guide made for my own learning purposes.
----
Step-1: Install nessus
Link : https://www.tenable.com/downloads/nessus?_gl=1*12spwab*_ga*MTgxOTA1NDIwOS4xNzU3MTU1MzA2*_ga_HSJ1XWV6ND*czE3NTcxNTUzMDUkbzEkZzEkdDE3NTcxNTUzMjgkajQzJGwwJGgxNzk4MDA0NTAy&loginAttempted=true
---
Step-2: extract the deb pakage and installing 
# dpkg -i Nessus-10.9.3-ubuntu1604_amd64.deb

<img width="1022" height="918" alt="" src="https://github.com/user-attachments/assets/7bf79235-1581-4ada-8811-4949dc619e78" />

---


Step-3: start nessus service and check nessus service status:
# service nessusd start & service nessusd status
<img width="1022" height="918" alt="" src="https://github.com/user-attachments/assets/4ad41dd7-dd5f-470f-80b5-30804f81fd5c" />

---
Step-4: Go to https://localhost:8834/ 

<img width="1022" height="918" alt="" src="https://github.com/user-attachments/assets/59e18e2f-3eb2-45bd-971a-52bce9d7524c" />

---


Step5: For setup click and register offline.
if: 
  you want to use nterprise of paid version with key.
  Else: 
  Continue online and register for essential.
  <img width="1022" height="918" alt="" src="https://github.com/user-attachments/assets/7b41ee33-ab2b-41cc-ab04-8cec3a025dec" />
  
---

Step-4: follow the screen and create username and password and login to your nessus account:

<img width="1022" height="919" alt="" src="https://github.com/user-attachments/assets/5710f2ce-4ca0-4652-a88f-6bbb599dd2b4" />


After creating account it will start installing plugins :

<img width="1022" height="918" alt="" src="https://github.com/user-attachments/assets/436b803e-55e7-43b7-9225-7b94b4fe0d81" />

---

Step 5:  Create a new scan :
Basic Network Scan: scaning Basic Network Vulnerability
Advance Scan : provides details controls over scan parameters
Webapplication Scan: To scan for Vuln in Web based Applications

---
Step 6: 
You can configure you scan as per target name , IPaddress and specific port you want to scan . feel free to try explore it .
