<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h2> Description </h2>
OsTicket stands for open source ticket. OsTicket is a tool used by businesses and support teams to manage customer service requests. It helps organize and track issues or questions that customers submit through email, web forms, or other channels. Now that we have it installed, we are going to administer it as a help desk analyst. This tutorial will cover how to add user roles, customize ticket forms, and enable SLAs. 

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Admin Control Panel
- Help desk 

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)
  
<h2>List of Prerequisites</h2>

- Enable Internet Information Services (IIS)
- Web Platform Installer
- Install OsTicket
- SLA
- Configure Help Topics 

<h2>Installation Steps</h2>

<p>
Configure Roles (for grouping permissions). Admin Panel -> Agents -> Roles. Supreme Admin
<br />
  
</p><img width="492" alt="Screen Shot 2025-02-20 at 12 12 51 PM" src="https://github.com/user-attachments/assets/13f72581-ccae-4c97-8d6d-110fc589b4d2" />
<img width="486" alt="Screen Shot 2025-02-20 at 12 13 42 PM" src="https://github.com/user-attachments/assets/b9c57c3b-6c8e-4d7a-bd99-35ae4e5f2ac8" />
<img width="488" alt="Screen Shot 2025-02-20 at 12 13 55 PM" src="https://github.com/user-attachments/assets/32a9b283-d395-4018-9b2e-b3e25a40f240" />


<p>

<p>
Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
Admin Panel -> Agents -> Departments. SysAdmins
</p>

<p>
  
<img width="574" alt="Screen Shot 2025-02-20 at 12 15 20 PM" src="https://github.com/user-attachments/assets/4bc461e4-2aac-48af-9748-c783e779d300" />
<img width="567" alt="Screen Shot 2025-02-20 at 12 15 41 PM" src="https://github.com/user-attachments/assets/a238eb3c-2864-4a48-a5ff-75c943a4167e" />
  
</p>

<br />

<p>
Allow anyone to create tickets
Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets)
Registration Required: Require registration and login to create tickets 
</p>
<br />
<p>
<img width="401" alt="Screen Shot 2025-02-20 at 12 16 31 PM" src="https://github.com/user-attachments/assets/dfd803a0-8784-4147-8b60-9a80ef5dc931" />
</p>

<p>
Configure Agents (workers)
Admin Panel -> Agents -> Add New
Jane (Dept: SysAdmins)
John (Dept: Support)
</p>
<img width="679" alt="Screen Shot 2025-02-20 at 12 20 48 PM" src="https://github.com/user-attachments/assets/b8975ff8-4541-4892-abc8-0d6afa74425c" />

<img width="683" alt="Screen Shot 2025-02-20 at 12 20 05 PM" src="https://github.com/user-attachments/assets/eac02662-e536-4d9c-aace-79b7f905db3b" />

<p>

<p>
Configure Users (customers)
Agent Panel -> Users -> Add New
Karen
</p>
<p> <img width="726" alt="Screen Shot 2025-02-20 at 12 21 54 PM" src="https://github.com/user-attachments/assets/fe872d44-9a2e-4e29-84b9-67ec0a9a42ce" />
<img width="733" alt="Screen Shot 2025-02-20 at 12 22 06 PM" src="https://github.com/user-attachments/assets/a79817dc-e187-4ab3-9b5a-2c89bb931ea8" />

  <img width="493" alt="Screen Shot 2025-02-20 at 9 43 53 AM" src="https://github.com/user-attachments/assets/a22a5d30-af32-4352-a8ee-8e3328c6d638" />
</p>

<p>
Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (Grace Period: 1 hour, Schedule: 24/7)
Sev-B (Grace Period: 4 hours, Schedule: 24/7)
Sev-C (Grace Period: 8 hours, Business Hours)
</p> 
<img width="668" alt="Screen Shot 2025-02-20 at 12 24 50 PM" src="https://github.com/user-attachments/assets/0951803b-8631-46cb-aefb-b09ee35fc521" />
<img width="669" alt="Screen Shot 2025-02-20 at 12 25 01 PM" src="https://github.com/user-attachments/assets/c215732a-4ff6-47a9-b163-e9a3e3f2a157" />

</p>

<p>
Configure Help Topics (For when users create a ticket)
Admin Panel -> Manage -> Help Topics Business Critical Outage Personal Computer Issues Equipment Request Password Reset Other Help users categorize topics 

<img width="499" alt="Screen Shot 2025-02-20 at 12 25 58 PM" src="https://github.com/user-attachments/assets/4b538efa-31d6-486a-95b6-fab0f2bf3293" />
<img width="496" alt="Screen Shot 2025-02-20 at 12 26 05 PM" src="https://github.com/user-attachments/assets/18bdf820-7170-483a-b562-9b356f284c8b" />

</p>



