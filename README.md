<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used</h2>

- Windows 10 (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Access osTicket interfaces
- Understand the Agent vs Admin panels
- Configure roles and permissions
- Set up departments and teams
- Configure SLAs and help topics

<h2>Configuration Steps</h2>

<!-- Step 1 -->
<p>
  <img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="osTicket Interface URLs"/>
</p>
<p>
  <strong>✅ Step 1: Access osTicket Interfaces</strong><br />
  After installation, you will have access to two key interfaces:
  <ul>
    <li><strong>Admin/Analyst Login Page:</strong><br />
      🔗 <a href="http://localhost/osTicket/scp/login.php" target="_blank">http://localhost/osTicket/scp/login.php</a><br />
      Used by agents and administrators to log into the Staff Control Panel.
    </li>
    <li><strong>End User Portal:</strong><br />
      🔗 <a href="http://localhost/osTicket" target="_blank">http://localhost/osTicket</a><br />
      Where users can submit and track support tickets.
    </li>
  </ul>
</p>
<br />

<!-- Step 2 -->
<p>
  <img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Agent vs Admin Panel"/>
</p>
<p>
  <strong>✅ Step 2: Understand the Agent Panel vs Admin Panel</strong><br />
  osTicket separates functionality based on role:
  <ul>
    <li><strong>Agent Panel:</strong> For responding to and managing tickets. Accessible by support staff.</li>
    <li><strong>Admin Panel:</strong> For system configuration and settings. Accessible only to administrators.</li>
  </ul>
</p>
<br />

<!-- Step 3 -->
<p>
  <img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Configure Roles"/>
</p>
<p>
  <strong>✅ Step 3: Configure Roles</strong><br />
  Navigate to <strong>Admin Panel → Agents → Roles</strong> to define what agents are allowed to do.<br />
  <ul>
    <li><strong>Example Role:</strong> <code>Supreme Admin</code> - full access to all admin settings.</li>
    <li>Roles help you control access and assign responsibilities efficiently.</li>
  </ul>
</p>
<br />
