<h1>Active Directory: Network Mapping</h1>

<h2>Objective</h2>
<p>In this lab, I will be utilizing a Virtual Machine sandbox to simulate the tasks and managements of help desk specialist. I will be using Virtual Box, Active Directory, Windows Server 2022, and Windows 10 for this lab. Here, I will be demonstrating network mapping. This allows certain users to shared access to folders and files within a network.   <p>
<h3>Materials</h3>
<ul>
  <li>Virtual Box</li>
  <li>Active Directory</li>
  <li>Windows Server 2022</li>
  <li>Windows 10</li>
</ul>

<h4>Task</h4>
<p>The monthly information for the upcoming quarter is here. We will need all managers of the departments to be able to access this folder.
  First, we are going to access Group Policy Management in Windows Administrative Tools. Underneath the domain, we are going add a new Group Policy Object. This will be titled "Mapped Drives". </p> 
<img width="500" height="345" alt="Netmap2 1" src="https://github.com/user-attachments/assets/5b133ff4-0011-454b-bcd6-559dae52aa3f" />
<p>Next, we are going to edit this GPO so the configuration corresponds to the correct policy. The mapped drive wil be under user preferences.</p> 
<img width="1005" height="737" alt="Netmap2 2" src="https://github.com/user-attachments/assets/ed68c56d-2eb8-4222-82e8-d3668abc1119" />
<p>Here, under user preferences, we will then select the Windows Setting configuration and then open Drive Maps</p>
<img width="1002" height="647" alt="Netmap2 3" src="https://github.com/user-attachments/assets/736bb0f8-e769-42f1-ae23-da30e220aced" />

<p>Once this is accessed, we now create a folder that houses the information that needs sharing. </p>
<img width="476" height="351" alt="Netmap1" src="https://github.com/user-attachments/assets/d6cc27c8-ff0b-41c7-822e-e505f58a439f" />

<p>Next, we then give access to the managers/users of this folder by adding them to the permissions.</p>
<img width="476" height="345" alt="Netmap3" src="https://github.com/user-attachments/assets/3fd4fc8a-0471-4fad-8faa-716c2f57a601" />

<img width="476" height="345" alt="Netmap2" src="https://github.com/user-attachments/assets/2fa93f49-0152-4b2c-a824-9fb97b7005b2" />

<img width="476" height="345" alt="Netmap4" src="https://github.com/user-attachments/assets/8ffa9fa3-481a-4ce4-a4b3-3e239220f5df" />

<p></p>

