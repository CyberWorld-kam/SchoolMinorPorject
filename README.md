<h1>Achieving Sarbanes-Oxley (SOX) compliance through Industry Simulation Design and its Security controls </h1>

 ### [I am also doing Security Awareness](https://www.facebook.com/profile.php?id=100086563703368&mibextid=ZbWKwL)

 <h2>Project Descrption</h2>
Project consists of a simple PowerShell script that walks the user through "zeroing out" (wiping) any drives that are connected to the system. The utility allows you to select the target disk and choose the number of passes that are performed. The PowerShell script will configure a diskpart script file based on the user's selections and then launch Diskpart to perform the disk sanitization.
<br />

<h2>Aim and objectives of the project</h2>
Attain Sarbanes-Oxley (SOX), is always being challenge for organisations, particularly those operating in the domain of Finance. Knowing how to implement practically security controls to meet the internal control requirement of Sarbanes-Oxley is a must. This project aims to design and simulate industry-based IT intrastate through network simulation environment and implement appropriated security controls.
<br />
<h3>As objectives, the project seeks to:</h3>
<p>
•	Design an industry or Corporate network infrastructure that aligns with the requirements of SOX compliance. 
The designed network will replicate a real-world IT infrastructure and will be used to implement and test security.<br />
•	Identify the specific security controls needed to achieve SOX compliance within the designed network. This includes analysing access control mechanisms, encryption techniques<br />
•	Implement the identified security controls within the network infrastructure simulated. This involves configuring and deploying appropriate technologies.
</p>

<h2>Requirement of the New system (After Literature Review)</h2>

The new system has a huge number of requirements, such as:<br/>
<b>A Virtual Lab</b><br/>
<b>•	Hardware requirements:</b> it needs a super powerful machine that can run the simulation software smoothly. At least a machine with 32GB of RAM or more, CPU, and good storage.<br/>
<b>•	Software requirement:</b> Gns3 and VMware pro (The recommended) setup. Also, as the projects will run a corporate real network simulation, it requires windows images and windows 2012 R2 setup for Active directory.<br/>
<b>•	Network and security devices requirements:</b>  a Firewall, switches, routers, as well as network management tools.<br/>

<h2>Requirements of the Sarbanes-Oxley Act</h2>
The Sarbanes-Oxley Act imposes several requirements on companies to promote accountability and transparency in financial reporting. These requirements include:<br/>
<b>•	Prevent Data Tampering and monitor for breaches:</b> Implement measures to prevent unauthorized tampering with financial data and monitor for any breaches or unauthorized access.<br/>
<b>•	Document activity timelines and encrypt the data:</b> Maintain detailed records of activities related to financial data and implement encryption measures to protect the confidentiality of sensitive information.<br/>
<b>•	Install access tracking controls that identify breaches:</b> Implement controls that track and monitor access to financial systems and detect any unauthorized breaches.<br/>
<b>•	Check consistently to ensure defense systems are working:</b> Regularly assess the effectiveness of defense systems and controls to ensure they are functioning as intended.<br/>
<b>•	Analyse security system data, improving when needed: </b>Analyse data from security systems to identify potential weaknesses or areas for improvement and take appropriate action.<br/>
<b>•	Implement security breach tracking that works in real time:</b> Establish mechanisms to track security breaches in real time, allowing for immediate response and mitigation.<br/>
<b>•	Grant auditors defense system access for complete transparency:</b> Provide auditors with access to relevant defense systems to ensure transparency and facilitate their evaluation of controls.<br/>
<b>•	Disclose security to auditors for fast response: </b>Share information about security measures and incidents with auditors promptly to facilitate a timely response.<br/>
<b>•	Report technical difficulties to auditors and avoid stalls or hangups: </b>Communicate any technical difficulties or issues to auditors promptly to prevent delays or disruptions in the audit process.

<h2>Internal controls checklist:</h2>
In this project our concern is the internal control which includes IT controls. Internal controls checklist can be resume to:<br/>
<b>•	Access control:</b> This refers to both the physical and electronic controls that prevent unauthorized users from viewing sensitive financial information. This includes keeping servers and data centers in secure locations, implementing effective password controls, and other measures.<br/>
<b>•	Security and cyber security:</b> Ensure that proper controls are in place to prevent data breaches and have tools ready to remediate incidents. Invest in services and equipment that will monitor and protect your financial database<br/>
<b>•	Change management:</b> This involves the IT department process for adding new users and computers, updating and installing new software, and making any changes to databases or other data infrastructure components. Keep records of what was changed, in addition to when it was changed and who changed it.<br/>
<b>•	Backup systems: </b>Maintain backup systems to protect sensitive data. Data canters containing backed-up data, including those stored off-site or by a third-party are also subject to the same SOX compliance requirements as those hosted on-site.

<h2>Tools and Technology used</h2>:
HP Z2 Tower (Host machine)	<br/><br/>
GNS3 server VM	(Virtual machine)<br/>
GNS3 Client (	Software)<br/>
VMware Pro	(software)<br/>
Cisco layer2 Switch	(Network virtual device)<br/>
Ethernet switch	(Network virtual device)<br/>
Windows 10	(Software /OS )<br/>
Ubuntu client	(Docker image)<br/>
Windows server 2012 R2	(Software /OS)<br/>
ManageEngine EventLog Analyzer	(Software)<br/>
Urbackup	s(oftware)<br/>
QMU image(qcow2)	(appliance)<br/>


<h2>Nework block Diagram</h2>

![image](https://github.com/CyberWorld-kam/SchoolMinorPorject/assets/157485250/851f3782-d4c3-49b5-818b-25579b77edd3)
<h3>architecture in GNS3:</h3>


![image](https://github.com/CyberWorld-kam/SchoolMinorPorject/assets/157485250/b79e2572-8043-4d92-8b4d-7044bb4972dd)


<h2>Implementation<h2>
<h3>Backups Systems:</h3> 
<b>•	Objectives: </b>backup financial data and critical systems data that save the organization and help restore its operations.<br/>
<b>•	Methodology:</b> Achieve this goal a tool called Urbackup is installed and configured. We also tested the effectiveness of the tool and its availability.
 
![image](https://github.com/CyberWorld-kam/SchoolMinorPorject/assets/157485250/06121584-5ade-4cd0-a44d-dc30879ae306)


![image](https://github.com/CyberWorld-kam/SchoolMinorPorject/assets/157485250/59558503-9079-4a88-ac1a-55bccb78ba8c)


<h3>IT security and Audit:</h3>
<b>•	Objectives:</b> track activities in order to prevent data breaches, detect and respond to incident<br/>
<b>•	Methodology:</b> we installed a log collection and monitoring tools called ManageEngine EvnetLog Analyzer which collects logs from the devices and facilitate their analysis.

![image](https://github.com/CyberWorld-kam/SchoolMinorPorject/assets/157485250/08efd3c4-77ee-4549-93b7-73a5b5fa9470)

 ![image](https://github.com/CyberWorld-kam/SchoolMinorPorject/assets/157485250/7eedadc5-63ab-46fa-8746-9b81ebd2655d)

Event Loging – compliance and security assessments
 

![image](https://github.com/CyberWorld-kam/SchoolMinorPorject/assets/157485250/d8ad8536-6ee0-433e-a8a0-4d07d2e652e0)


<h3>Access controls: using ACtive Directory and Firewall</h3>

<b>•	The objective:</b> access controls implementation aims Prevent unauthorized users from viewing sensitive financial information. <br/>
<b>	Methodology: </b>to achieve access control requirement, we installed and configured Active directory and domain controller to:<br/>
1. join computers for access management, <br/>
2. manage user access privilege,<br/>
3. user account and access provisioning.<br/>
4. Shared folders and permission settings <br/>
5. Group policy creation


 ![image](https://github.com/CyberWorld-kam/SchoolMinorPorject/assets/157485250/24e5f9fa-8e61-4131-a32b-97419ad8091b)

![image](https://github.com/CyberWorld-kam/SchoolMinorPorject/assets/157485250/1770dd05-20d2-4049-a1d3-e3735d9ce5de)

![image](https://github.com/CyberWorld-kam/SchoolMinorPorject/assets/157485250/d04a634f-663d-4b33-99c2-263b3c0163b1)

Network segmatation

![image](https://github.com/CyberWorld-kam/SchoolMinorPorject/assets/157485250/7f456dc1-1259-43c3-9b8d-48f6478b04d0)

Firewall rules

![image](https://github.com/CyberWorld-kam/SchoolMinorPorject/assets/157485250/b8407e4e-4242-4fcf-992c-73e342c3b7cf)


<h2>Future scop of the project</h2>
The project has significant future scope for advancements including:<br/>
•	Exploring more sophisticated industry simulation design,<br/>
•	 Incorporating advanced IT security controls,<br/>
•	Addressing compliance challenges in cloud computing,<br/>
•	 Enhancing continuous compliance monitoring, expanding to other regulatory frameworks, and promoting industry collaboration and best practices. <br/>
•	Conduct full audit approve the effectiveness of the implementations.<br/>
•	Install financial management software or application and implement appropriate security.
•	Implement a Disaster and site <br/>
These avenues of exploration promise to strengthen compliance practices, improve data security, and foster a culture of trust and transparency within organizations.<br/>

<h2>Conclusion</h2>
To summarize, this project provides a structured and effective approach to ensure compliance with SOX regulations. It equips organizations with the necessary tools, strategies, and knowledge to navigate the complexities of SOX compliance, protect financial data, and strengthen their overall security posture



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
