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

<h3>Tasks</h3>
<ul>
  <li>User Creation</li>
  <li>Domain Joining</li>
</ul>

<h3>User Creation</h3>

<p>To create a user, you must access the AD Users and Computers tab in the Start menu. This will then pull up the organization's forest. Within this folder,you then locate the proper OU and group and simply right-click New and slect User. </p>
<img width="465" height="355" alt="Screenshot (3)" src="https://github.com/user-attachments/assets/95e0bd33-f032-4b4a-aafc-9913d02890e1" />

<p>Next, you must fill out the form of the new user with their information. This includes their name, username, passwords, and other information that identifies and distinguishes them. </p>
<img width="465" height="355" alt="Screenshot 2026-06-09 121512" src="https://github.com/user-attachments/assets/be661bd7-9478-4378-95f4-a94e3ba78c75" />

<h3>Domain Joining</h3>

<p>In this lab, we are onboarding new doctors onto the Stockbridge location directory. Dr. Myers must be able to log onto his work PC. We do this by connecting the client PC to the DNS server of the domain. The IP address of the client PC must be within the network of the DC and point to the DNS server. </p>
<img width="465" height="355" alt="DJ3" src="https://github.com/user-attachments/assets/3c4fc767-98f9-4968-8e73-8593fa3fe9f0" />

<p>Once these are set, I must make sure a connection has been established. On the client computer, I ping the DNS server to see if it responds without any errors. And it does!</p>
<img width="465" height="355" alt="DJ4" src="https://github.com/user-attachments/assets/2631b08c-f66d-4598-b0b0-f2174405ff20" />

<p>On the client PC, we can now join the domain. We do this by accessing the System settings and selecting About. From here, we go into the advanved system settings and then rename computer and change member. Enter the domain.local and we are set. Dr. Myers is now inside the directory and can access his work computer for the organization. </p>
