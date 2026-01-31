<h1>Keylogger Deployment and Log Management 🔑</h1>


<h2>Description</h2>
This project explores keylogging from a defensive cybersecurity perspective, focusing on the development and deployment of a keylogger within a controlled virtual environment. The keylogger was installed on a Windows 10 virtual machine and configured to securely collect and transmit keystroke data for analysis, demonstrating how such tools operate and how they can be detected and mitigated in real-world systems.
<br />
<br />
<b>Disclaimer</b> 🚨
<br />
This project was conducted strictly for educational and research purposes within a controlled environment. The techniques demonstrated are intended to improve understanding of cybersecurity threats and defenses and must be used responsibly, ethically, and in compliance with all applicable laws and privacy regulations.
<br />


<h2>Technology Tools Used</h2>

- <b>Windows 11 Pro</b>

<h2>Environments Used </h2>

- <b>Windows 11 Pro</b> (23H2)
  
- <b>Microsoft Visual Studio 2026: Community Edition </b>

<h2>Key Takeaways 📝</h2>

- This project enhanced my understanding of how keyloggers function by providing hands-on experience with their development, deployment, and data collection within a controlled virtual environment.
- Working through the lab reinforced the importance of ethical responsibility in cybersecurity, highlighting how tools designed for learning and defense can be misused if not handled in accordance with legal and privacy standards.

<h2>Program walk-through:</h2>

<p align="center">
<b>Install Microsoft Visual Studio 2026:</b> <br/>
<img width="1900" height="806" alt="image" src="https://github.com/user-attachments/assets/a41cd180-2fb6-46ec-a4c0-bbeafcdfdfcd" />
  <img width="537" height="110" alt="image" src="https://github.com/user-attachments/assets/fd5338ed-7abf-4a1e-8a47-da492e0c6c8a" />

<br />
<br />
<b>Install Keylogger Master Zip File as a zip file:</b>  <br/>
<img width="797" height="323" alt="image" src="https://github.com/user-attachments/assets/55fad61d-3f76-460c-9fd2-17ac3e3cbc85" />
<br />
<br />
<b>Open Keylogger file then go to C# Program.cs for Source Code: </b>  <br/>
<img width="1916" height="1034" alt="image" src="https://github.com/user-attachments/assets/cac709a0-a05a-4a14-9f22-e8f3f55aa3e3" />
<br />
<br />
<b>Here you can set the location of where the text is getting logged, and also set the limit for characters before the log gets archived, resulting in it being sent to the email you have listed:</b>  <br/>
<img width="698" height="222" alt="image" src="https://github.com/user-attachments/assets/c5737301-9cef-40e5-b0ec-42005c469740" />
<br />
<br />
<b>Keystroke input is continuously captured and stored in a structured text log:</b>  <br/>
<img width="1916" height="1000" alt="image" src="https://github.com/user-attachments/assets/4dae67d2-2113-4464-8280-aade56e47bc0" />
<img width="1912" height="920" alt="image" src="https://github.com/user-attachments/assets/5975c025-38b5-4720-a276-fc76833b84d8" />
<br />
<br />
<b>To prevent the console window from appearing, the project output type was changed from a Console Application to a Windows Application, and the solution was then cleaned and rebuilt:</b>  <br/>
<img width="1912" height="847" alt="image" src="https://github.com/user-attachments/assets/7265cbd7-7347-477a-a7e4-d54d0af3fb2f" />
<br />
<br />
<b>To access the compiled executable, navigate to the bin\Debug directory using File Explorer:</b>  <br/>
<img width="602" height="48" alt="image" src="https://github.com/user-attachments/assets/db959f6d-3910-42db-b9e9-c27bb6027a7d" />
<br />
<br />
<b>Automatic execution at user logon was configured using Windows Task Scheduler:</b>  <br/>
<img width="775" height="667" alt="image" src="https://github.com/user-attachments/assets/73e0bfce-2db7-49e1-b12f-f276c52926fa" />
<br />
<br />
<b>The trigger was configured to run the application at system startup:</b>  <br/>
<img width="593" height="209" alt="image" src="https://github.com/user-attachments/assets/529b0032-976f-400d-892d-fcfb999b4083" />
<br />
<br />
<b>The task action was updated to Start a program and linked to the application’s executable file:</b>  <br/>
<img width="491" height="248" alt="image" src="https://github.com/user-attachments/assets/6376a5e6-c6b1-4c76-a31c-cb3b3b0e53b4" />
<br />
<br />
<b>The compiled executable was analyzed using VirusTotal to evaluate antivirus detection rates and assess how similar tools are identified by security engines:</b>  <br/>
<img width="1373" height="847" alt="image" src="https://github.com/user-attachments/assets/3dffa1c0-65e3-4667-bb60-1f4d8a52c2fb" />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
