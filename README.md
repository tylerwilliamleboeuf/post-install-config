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
  <strong>✅ Step 2: Understand the Agent Panel vs Admin Panel</strong><br />
  osTicket separates functionality based on role:
  <ul>
    <li><strong>Agent Panel:</strong> For responding to and managing tickets. Accessible by support staff.</li>
    <li><strong>Admin Panel:</strong> For system configuration and settings. Accessible only to administrators.</li>
  </ul>
</p>
    <p>
  <img src="https://i.imgur.com/sZJhpmk.png" height="80%" width="80%" alt="osTicket Interface URLs"/>
</p>
    <p>
  <img src="https://i.imgur.com/vge6pgB.png"/>
</p>
<br />

<!-- Step 3 -->
<p>
  <strong>✅ Step 3: Configure Roles</strong><br />
  Navigate to <strong>Admin Panel → Agents → Roles</strong> to define what agents are allowed to do.<br />
  <ul>
    <li><strong>Example Role:</strong> <code>Supreme Admin</code> - full access to all admin settings.</li>
    <li>Roles help you control access and assign responsibilities efficiently.</li>
  </li>
  </ul>
</p>
<p>
  <img src="https://i.imgur.com/OUltzxU.png"/>
</p>
<p>
  <img src="https://i.imgur.com/GeaIClR.png"/>
</p>
<p>
  <img src="https://i.imgur.com/vf1SvM8.png"/>
</p>
<br />


<!-- Step 4 -->
<p>
  <strong>✅ Step 4: Configure Departments</strong><br />
  Departments control ticket visibility and help you organize your support structure.<br />
  Navigate to <strong>Admin Panel → Agents → Departments</strong> to create them.
  <ul>
    <li><strong>Example Departments:</strong></li>
    <li><code>SysAdmins</code> - Handles system-related issues</li>
    <li><code>Support</code> - General help desk staff</li>
    <li><code>Networking</code> - Network-specific support</li>
  </ul>
  Each department can have its own ticket assignments and response workflows.
</p>
<p>
  <img src="https://i.imgur.com/DjAovqv.png"/>
</p>
<p>
  <img src="https://i.imgur.com/W0f127I.png"/>
</p>
<br />

<!-- Step 5 -->
<p>
  <strong>✅ Step 5: Configure Teams</strong><br />
  Teams allow you to group agents from different departments to work collaboratively.<br />
  Navigate to <strong>Admin Panel → Agents → Teams</strong>.
  <ul>
    <li><strong>Example Team:</strong> <code>Online Banking</code> - Includes agents from both Support and SysAdmins.</li>
    <li>Teams can be assigned tickets and improve coordination on cross-functional tasks.</li>
  </ul>
</p>
<p>
  <img src="https://i.imgur.com/9mTVaiQ.png"/>
</p>
<p>
  <img src="https://i.imgur.com/Zzluis6.png"/>
</p>
<br />

<!-- Step 6 -->
<p>
  <strong>✅ Step 6: Adjust User Access Settings</strong><br />
  By default, osTicket may allow unregistered users to create tickets. To require registration:
  <ul>
    <li>Go to <strong>Admin Panel → Settings → User Settings</strong></li>
    <li><strong>Uncheck:</strong> “Allow anyone to create tickets”</li>
    <li><strong>Enable:</strong> “Registration Required” - Users must create an account and log in to submit tickets.</li>
  </ul>
  This ensures better tracking and communication with users.
</p>
<p>
  <img src="https://i.imgur.com/N0Y1JfA.png"/>
</p>
<p>
  <img src="https://i.imgur.com/Th8P84O.png"/>
</p>
<p>
  <img src="https://i.imgur.com/OQ1cO96.png"/>
</p>
<p>
  <img src="https://i.imgur.com/nhLt2cn.png"/>
</p>
<p>
  <img src="https://i.imgur.com/LvuzM6A.png"/>
</p>
<p>
  <img src="https://i.imgur.com/Lg7lcdp.png"/>
</p>
<p>
  <img src="https://i.imgur.com/S2bFpAR.png"/>
</p>
<br />

  </ul>
</p>
<br />
