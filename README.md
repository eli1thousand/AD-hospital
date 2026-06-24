<h1>Active Directory: Hospital</h1>

<h2>Objective</h2>
<p>In this lab, I will be utilizing a Virtual Machine sandbox to simulate the tasks and managements of help desk specialist. I will be using Virtual Box, Active Directory, Windows Server 2022, and Windows 10 for this lab. I will demonstrate basic AD tasks like account management, group policy issuing, and  <p>

<h3>Materials</h3>
<ul>
  <li>Virtual Box</li>
  <li>Active Directory</li>
  <li>Windows Server 2022</li>
  <li>Windows 10</li>
</ul>

<h4>Tasks</h4>
<ul>
  <li>User Creation</li>
  <li>Domain Joining</li>
  <li>Account Troubleshooting</li>
  <li>Group Policy Management</li>
  <li>Drive Mapping</li>
</ul>

<h5>User Creation</h5>
<p>To create a user, you must access the AD Users and Computers tab in the Start menu. This will then pull up the organization's forest. Within this folder,you then locate the proper OU and group and simply right-click New and slect User. </p>
<img width="955" height="790" alt="Screenshot (3)" src="https://github.com/user-attachments/assets/95e0bd33-f032-4b4a-aafc-9913d02890e1" />

 <p>Next, you must fill out the form of the new user with their information. This includes their name, username, passwords, and other information that identifies and distinguishes them. </p>
<img width="758" height="587" alt="Screenshot 2026-06-09 121512" src="https://github.com/user-attachments/assets/be661bd7-9478-4378-95f4-a94e3ba78c75" />

<h6>Domain Joining</h6>
<p>In this lab, we are onboarding new doctors onto the Stockbridge location directory. Dr. Myers must be able to log onto his work PC. We do this by connecting the client PC to the DNS server of the domain. The IP address of the client PC must be within the network of the DC and point to the DNS server. </p>
  <img width="1517" height="751" alt="DJ3" src="https://github.com/user-attachments/assets/3c4fc767-98f9-4968-8e73-8593fa3fe9f0" />

Once these are set, I must make sure a connection has been established. On the client computer, I ping the DNS server to see if it responds without any errors. And it does!
<img width="1227" height="801" alt="DJ4" src="https://github.com/user-attachments/assets/2631b08c-f66d-4598-b0b0-f2174405ff20" />

