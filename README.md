# Pen-Testing
 <h2>Description</h2>

<br />

<h2>Project walk-through:</h2>

<p align="center">
My first step was to run a port scan using nmap against the IP address of the vulnerable machine : <br/>

![image alt](https://github.com/Samuel-James971/Pen-Testing/blob/main/1.png?raw=true)
<br />
<br />
In the command I used the -sV option for version enumeration and -p- to conduct a full port scan, the results of the scan showed that port 80 is being used for the HTTP service and port 22 is being used for SSH. :  <br/>
![image alt](https://github.com/Samuel-James971/Pen-Testing/blob/main/2.png?raw=true)
<br />
<br />
Next, I wanted to run an enumeration scan on the targets IP address to identify any hidden directories, I used the tool Drib for this which is preinstalled on Kali Linux. I was able to identify a few files and directories from the scan and decided to enter a few of them into a search engine. One of the directories lead me to an interesting discovery. The robots.txt file contained the name of another directory.: <br/>
![image alt](https://github.com/Samuel-James971/Pen-Testing/blob/main/3.png?raw=true)
<br />
<br />
However, this identified directory could not be found. There could be other directories starting with the same ~ character, however. In an attempt to find more directories I used a method called “fuzzing” which is the process of guessing directory names. I used an automated tool called FFUF for this process:   <br/>
![image alt]()
<br />
<br />
The workflow automation use an AI action to summarise the incoming webhook alert into a concise sentence and genrate bullet points for analysts. The AI proccesses the alert using a prompt and passes the output to an email action which send an email alert to the analsyt:  <br/>
![image alt](https://github.com/Samuel-James971/AI-Workflow-Automation/blob/main/Screenshot%202025-07-08%20161240.png?raw=true)
<br />
<br />
Here is the email alert sent to the analyst:  <br/>
![image alt](https://github.com/Samuel-James971/AI-Workflow-Automation/blob/main/Screenshot%202025-07-08%20161352.png?raw=true)
<br />
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
