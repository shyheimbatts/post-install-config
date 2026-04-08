<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket. 
<p>
Two URL's are used to complete the tasks for osTicket, The first one is to login → </head>
<body>
	<a href="https://localhost/osTicket/scp/login.php">Admin/Analyst Login Page:</a>
</body>
</html><br /> and The second one is used for End users → <body>
	<a href="https://localhost/osTicket">End Users osTicket URL:</a>
</body>
</html><br />
</p>


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 11 Pro</b> (24H2)

<h2>Post-Install Configuration Objectives</h2>

- Task 1 Login through Admin/Analyst Login Page
- Task 2 Configure Roles (For Grouping Permissions)
- Task 3 Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
- Task 4 Configure Teams
- Task 5 Allow Ticket Creations (Anyone)
- Task 6 Configure Agents (Workers)
- Task 7 Configure Users (Customers)
- Task 8 Configure SLA
- Task 9 Configure Help Topics (For when users create a ticket)

<h2>Configuration Tasks↓</h2>

<p>

**Task 1-** Begin by logging into the web portal with the admin/analyst account that was created during the osTicket installation process.  
→ </head><body>
	<a href="https://localhost/osTicket/scp/login.php">Admin/Analyst Login Page:</a>
</body>

<p>
	Username - adminuser
	<p>
	Password - Password123!
	</p>	
</p>
	
</p>
<p>
<img width="619" height="403" alt="Screenshot 2025-11-05 at 10 24 18 PM" src="https://github.com/user-attachments/assets/1475d51a-0d4e-46ea-919b-4212d8f67420" />
<p>

**Task 2-** Configure Roles (For Grouping Permissions)

<p>
	
**Step 1-** Select Admin Panel ↓

</p>
		
</p>
  <img width="955" height="345" alt="Screenshot 2025-11-05 at 11 12 56 PM" src="https://github.com/user-attachments/assets/b8c8932d-64a0-4c9f-a72e-e36935d05124" />
<p>

**Step 2-** Select Agents↓
	
</p>
  
  <img width="958" height="750" alt="Screenshot 2025-11-05 at 11 15 37 PM" src="https://github.com/user-attachments/assets/a93f8229-2444-4710-81a4-759f0230ea32" />
  <p>

**Step 3-** Within the Agents Tab Select Roles↓
	  
  </p>
  <img width="891" height="169" alt="Screenshot 2025-11-05 at 11 28 56 PM" src="https://github.com/user-attachments/assets/c09b6338-a7f4-41af-bed2-2ae450891bd6" />

  <p>

**Step 4-** Create/Add New Role↓ New Role Title(Supreme Admin) From here, Go to Permissions → Tickets & Check each box to give Permissions to everything. Then, go to Tasks and check each box as well to allow them to do every single thing. Lastly, Go to Knowledgebase..Check Premade and click Add Role. (Supreme Admin should now be visible under the options for roles.)
	  
  </p>
<img width="661" height="75" alt="Screenshot 2026-04-08 at 2 01 33 PM" src="https://github.com/user-attachments/assets/d1a0085d-80b4-43a7-bc18-8de079d91b9e" />
<img width="954" height="562" alt="Screenshot 2025-11-05 at 11 33 34 PM" src="https://github.com/user-attachments/assets/c2e00ed1-27d6-4c1d-afce-dcf46520a8c8" />
<img width="957" height="706" alt="Screenshot 2025-11-05 at 11 34 34 PM" src="https://github.com/user-attachments/assets/4110652a-6e47-48c8-b76a-bce27c3f0097" />
<img width="426" height="485" alt="Screenshot 2025-11-05 at 11 35 07 PM" src="https://github.com/user-attachments/assets/7a1d8502-d15a-4c2f-88f8-4227e362a7a5" />
<img width="956" height="403" alt="Screenshot 2025-11-05 at 11 36 59 PM" src="https://github.com/user-attachments/assets/172645cb-bb7c-42db-ad48-631ad124618e" />
<img width="432" height="287" alt="Screenshot 2026-04-08 at 2 00 07 PM" src="https://github.com/user-attachments/assets/534f857c-421f-4f21-b5c4-707a5ef2a080" />

<p>

**Task 3-** Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)

<p>

**Step 1-** Within the Admin Panel go to Agents → Departments → Add New Department
	
</p>
	
</p>
<img width="464" height="51" alt="Screenshot 2026-04-08 at 2 45 19 PM" src="https://github.com/user-attachments/assets/75ffd68c-0615-4e21-9bcc-12b924135590" />
<p>
<img width="279" height="59" alt="Screenshot 2026-04-08 at 2 48 42 PM" src="https://github.com/user-attachments/assets/42408b7f-e347-447c-bf7c-7a35e94b9a56" />
</p>
<p>
<img width="665" height="58" alt="Screenshot 2026-04-08 at 2 49 57 PM" src="https://github.com/user-attachments/assets/72506549-a63b-4bf7-92aa-a2ba822a00ed" />
</p>

<p>

**Step 2-** Enter in the Department Information Below↓
<p>
PARENT → Top Level Department
</p>	
<p>
NAME → SysAdmins
</p>
Click Create Department
</p>
<img width="954" height="326" alt="Screenshot 2025-11-05 at 11 41 05 PM" src="https://github.com/user-attachments/assets/09595254-579b-4775-82a2-03a11ff83033" />
<p>
 <img width="332" height="76" alt="Screenshot 2025-11-05 at 11 41 19 PM" src="https://github.com/user-attachments/assets/76ffc971-f513-4661-8e93-ca00303d26d9" />

   </p>
   <img width="669" height="220" alt="Screenshot 2025-11-05 at 11 44 27 PM" src="https://github.com/user-attachments/assets/a552dd3e-c3b0-42e6-ad8b-319a3c67b30b" />

 <p>

**Task 4-** Configure Teams- Teams allow you to pull Agents from different Departments and organize them to handle a specific issue or user via a Help Topic or Ticket Filter.

<p>

**Step 1-** From the Admin Panel go to Agents → Teams → Add New Team.
<p>
Fill in Team information↓
</p>
<p>
NAME: Online Banking
</p>
<p>
Status: Active
</p>

Click Create Team
</p>
	 
 </p>  
  <img width="853" height="259" alt="Screenshot 2025-11-05 at 11 45 37 PM" src="https://github.com/user-attachments/assets/b559de32-d502-4f98-87d6-a507e0432357" />
  <img width="734" height="665" alt="Screenshot 2025-11-05 at 11 46 43 PM" src="https://github.com/user-attachments/assets/2fcb50aa-9213-4d70-91f7-d02a44fd8b02" />

<p>

**Task 5-**  Allow Ticket Creations (Anyone)

**Step 1**  Start in this order: Admin Panel → Settings → Users → Settings (Under authentication settings please make sure that registration is not required by keeping the box next to it unchecked, This gives unregistered users the ability to create tickets.)

<p>

**→SAVE CHANGES**
	
</p>
	
</p>


 <p>
  <img width="826" height="673" alt="Screenshot 2025-11-05 at 11 48 20 PM" src="https://github.com/user-attachments/assets/bc4e6e9f-4db4-4985-8044-6f2a36cd4fbc" />
</p>  

<p>

**Task 6-** Configure Agents (Workers) To resolve and respond to tickets Agents(Workers) are given access to help desk.

**Step 1-** Start in this order: Admin Panel → Agents → Add New Agent

	
</p>
  <img width="847" height="300" alt="Screenshot 2025-11-05 at 11 49 15 PM" src="https://github.com/user-attachments/assets/7bb2b125-4de8-47ff-badb-f792fad0b285" />
<p>

**Step 2-** Fill in Account Information↓	  

<p>

<p>
Name: Jane Doe
</p>
<p>
Email: Jane@lognpacific.com
</p>
<p>
Username:jane
</p>
<p>
Password: Password1
</p>
<p>
→ Click Update to Save Account Information.	
</p>
	
</p>



	  
  </p>
 <img width="885" height="648" alt="Screenshot 2025-11-05 at 11 54 53 PM" src="https://github.com/user-attachments/assets/5593a0da-b9b3-4907-a8a4-6b2d9c89926a" />

 <p>
 <img width="386" height="109" alt="Screenshot 2025-11-06 at 12 07 21 AM" src="https://github.com/user-attachments/assets/2f9d14fa-0fe2-4e91-9440-74b04258a883" 
 </p> 
<img width="634" height="378" alt="Screenshot 2025-11-06 at 12 10 35 AM" src="https://github.com/user-attachments/assets/74e1f3fd-b81b-412c-8ec9-587ff7df081b" />

<p>

**Step 3-** Go to the Access tab, For the Primary Department place Jane in **(Support/SysAdmins)** and for her role make her **(Supreme Admin)** so that she has access to everything.
	
</p>	 
<img width="901" height="534" alt="Screenshot 2025-11-05 at 11 58 48 PM" src="https://github.com/user-attachments/assets/3ff1cdf2-7ae0-451b-9db7-2448c0bf022d" />

<p>

**Step 4-** Go to the Teams tab, Add Jane to the **Online Banking Team** and click Create.
	
</p>
<img width="895" height="423" alt="Screenshot 2025-11-05 at 11 59 14 PM" src="https://github.com/user-attachments/assets/20cf921b-326c-41d3-bf23-17413305ff6b" />

<p>
Jane was Successfully Added as an Agent(Worker)	
</p>
<img width="834" height="185" alt="Screenshot 2025-11-05 at 11 59 50 PM" src="https://github.com/user-attachments/assets/0621a194-5fdf-4882-9042-c3b17375e54f" />

<p>

**Step 5-** Start in this order: Admin Panel → Agents → Add New Agent
	
</p>
   
<img width="895" height="310" alt="Screenshot 2025-11-06 at 12 00 27 AM" src="https://github.com/user-attachments/assets/ba4cceca-8291-4f5a-9950-cbf81f045bf6" />
<p>

**Step 6-** Fill in Account Information↓	  

<p>

<p>
Name: John Doe
</p>
<p>
Email: John@lognpacific.com
</p>
<p>
Username:john
</p>
<p>
Password: Password1
</p>
<p>
→ Click Update to Save Account Information.	
</p>
	
</p>
<img width="878" height="666" alt="Screenshot 2025-11-06 at 12 01 44 AM" src="https://github.com/user-attachments/assets/e7555190-4e76-42ca-9d2c-e297c7ee0d68" />
<img width="386" height="109" alt="Screenshot 2025-11-06 at 12 07 21 AM" src="https://github.com/user-attachments/assets/e9c5d405-cd2e-4335-973f-b411539400b7" />
<img width="634" height="378" alt="Screenshot 2025-11-06 at 12 10 35 AM" src="https://github.com/user-attachments/assets/3c7e9aaa-0469-4867-992e-fbe7b346658a" />

<p>

**Step 7-** Go to the Access tab, For the Primary Department place John in **(Support)** and for his role make it so that he has **(View Only)** Access.
	
</p>
<img width="894" height="528" alt="Screenshot 2025-11-06 at 12 02 11 AM" src="https://github.com/user-attachments/assets/2909fa47-f3bc-4b78-8a9d-a33590156d1e" />

<p>

**Step 8-** Go to the Teams tab, and leave the team section **Blank** for John..Then click Create.
	
</p>
<img width="897" height="422" alt="Screenshot 2025-11-06 at 12 02 50 AM" src="https://github.com/user-attachments/assets/12809b66-1162-4448-9c95-917d9a861a8f" />
<p>

<p>
John was Successfully Added as an Agent(Worker)
</p>

<p>
<img width="261" height="44" alt="Screenshot 2025-11-06 at 12 04 10 AM" src="https://github.com/user-attachments/assets/e83571b7-47c7-41d5-9331-e7a7ec334a29" />
</p>

<p>

**Task 7-**  Configure Users (Customers) Start in this order: Agent Panel → Users → Add User

**Step 1-** Click on Agent Panel
	
</p>
   <img width="281" height="59" alt="Screenshot 2025-11-06 at 12 11 20 AM" src="https://github.com/user-attachments/assets/6792bac7-c626-4ef5-8bbd-6f325d297fd3" />

   <p>

**Step 2** Click Users → Add User
	   
   </p>
   <img width="904" height="230" alt="Screenshot 2025-11-06 at 12 11 57 AM" src="https://github.com/user-attachments/assets/94a46d0f-4443-4acd-9754-7d682635cd2a" />

   <p>

**Step 3-** Fill in User information↓
<p>
	Email Address: karen@lognpacific.com
</p>
<p>
	Name: Karen
</p>

**Click Add User**
   </p>
   <img width="639" height="386" alt="Screenshot 2025-11-06 at 12 13 47 AM" src="https://github.com/user-attachments/assets/4c4d1334-4f9b-4d8c-81f6-98ae6b5309b4" />

   <p>
	   
**End User(Customer) Profile Created, They can now create a Ticket.**
	   
   </p>
<img width="670" height="403" alt="Screenshot 2026-02-18 at 12 58 33 PM" src="https://github.com/user-attachments/assets/30de9a0d-a327-4753-a131-518d06aad576" />


<p>

**Task 8-** Configure SLA, (The purpose of the SLA Plan is to provide a length of time in which the help desk Administrator expects tickets to be closed.)

**Step 1-** Start with returning back to Admin Panel↓

</p>
	
   <p>
   <img width="309" height="48" alt="Screenshot 2025-11-06 at 12 20 30 AM" src="https://github.com/user-attachments/assets/d39faef4-22f1-4036-a880-ee9ac2521c18" />
   </p>

<p>

**Step 2-** Click Manage Tab↓	
</p>
<img width="957" height="143" alt="Screenshot 2026-02-18 at 1 04 30 PM" src="https://github.com/user-attachments/assets/d8f377d2-0c48-4921-b02f-43cd61218568" />

<p>

**Step 3-** Click SLA↓	
</p>
<img width="957" height="190" alt="Screenshot 2026-02-18 at 1 06 30 PM" src="https://github.com/user-attachments/assets/0572148f-fdee-471e-a57d-7ffed18dae3b" />

<P>

**Step 4-** Click Add New SLA Plan↓	
</P>
<img width="959" height="187" alt="Screenshot 2026-02-18 at 1 07 21 PM" src="https://github.com/user-attachments/assets/139d1d82-bd73-46a8-b1c3-3c8b4955c3f2" />

<p>

**Step 5-** Fill in the information for SLA Plan↓
<p>
	NAME: Sev-A
</p>
<p>
	STATUS: Active
</p>
<p>
	GRACE PERIOD: 1-Hour
</p>
<p>
	SCHEDULE: 24/7
</p>

<p>

**Click ADD PLAN**
</p>
	
</p>
<img width="887" height="513" alt="Screenshot 2025-11-06 at 12 23 30 AM" src="https://github.com/user-attachments/assets/f644b639-ce67-4b8a-bd7e-a4e39c013193" />

<p>

**Step 6-** Start by Clicking Add New SLA Plan, Then fill in the information for SLA Plan↓
<p>
	NAME: Sev-B
</p>
<p>
	STATUS: Active
</p>
<p>
	GRACE PERIOD: 4-Hours
</p>
<p>
	SCHEDULE: 24/7
</p>

<p>

**Click ADD PLAN**	
</p>




<img width="168" height="38" alt="Screenshot 2025-11-06 at 12 23 55 AM" src="https://github.com/user-attachments/assets/b3e533a5-e17f-458b-91fd-e915a9efffaf" />
<img width="879" height="518" alt="Screenshot 2025-11-06 at 12 24 21 AM" src="https://github.com/user-attachments/assets/9395ec70-ef26-4f7f-8b9c-aeb48ebd07ea" />


<p>
	 
**Step 7-** Start by Clicking Add New SLA Plan, Then fill in the information for SLA Plan↓
<p>
	NAME: Sev-C
</p>
<p>
	STATUS: Active
</p>
<p>
	GRACE PERIOD: 8-Hours
</p>
<p>
	SCHEDULE: Mon - Fri, 8am - 5pm with U.S. Holidays(Normal Business Hours)
</p>

<p>

**Click ADD PLAN**	
</p>


</p>

<p>
<img width="168" height="38" alt="Screenshot 2025-11-06 at 12 23 55 AM" src="https://github.com/user-attachments/assets/be0b47bd-b1a1-499e-83c5-dd381e853673" />
</p>

<img width="859" height="513" alt="Screenshot 2025-11-06 at 12 25 09 AM" src="https://github.com/user-attachments/assets/b6a52362-98ce-43f4-a7c0-ac9edbc23d2a" />

<p>

**Task 9-** Configure Help Topics (For when users create a ticket)↓

<p>
	
**Step 1-** Click Manage Tab↓

</p>
	
</p>

<img width="957" height="143" alt="Screenshot 2026-02-18 at 1 04 30 PM" src="https://github.com/user-attachments/assets/1eafbeca-ec68-433e-951a-82cfa8e2e485" />

<p>
	
**Step 2-**	Click Help Topics Tab↓
</p>
<img width="962" height="141" alt="Screenshot 2026-02-18 at 1 25 04 PM" src="https://github.com/user-attachments/assets/9e195718-26cc-43de-b5d5-f1729e2567c9" />

<p>

**Step 3-** Click Add New Help Topic↓	
</p>
<img width="957" height="189" alt="Screenshot 2026-02-18 at 1 27 29 PM" src="https://github.com/user-attachments/assets/f51401ec-1602-48cb-a208-437917c5ab56" />
<img width="892" height="493" alt="Screenshot 2025-11-06 at 12 27 28 AM" src="https://github.com/user-attachments/assets/82ded156-3d27-43f5-a36d-d76f7e1e9783" />
<p>
  <img width="179" height="40" alt="Screenshot 2025-11-06 at 12 28 16 AM" src="https://github.com/user-attachments/assets/162baa77-48a0-47bb-af59-0c124438f59e" />
</p>

<img width="958" height="376" alt="Screenshot 2026-02-18 at 1 13 27 PM" src="https://github.com/user-attachments/assets/1d3e1d1c-f855-4817-ab5c-f124bd21d999" />
 <img width="179" height="40" alt="Screenshot 2025-11-06 at 12 28 16 AM" src="https://github.com/user-attachments/assets/162baa77-48a0-47bb-af59-0c124438f59e" />
 <img width="896" height="488" alt="Screenshot 2025-11-06 at 12 29 59 AM" src="https://github.com/user-attachments/assets/013126c1-e32c-4e6a-8e58-4f4989543ac0" />
  <img width="179" height="40" alt="Screenshot 2025-11-06 at 12 28 16 AM" src="https://github.com/user-attachments/assets/162baa77-48a0-47bb-af59-0c124438f59e" />
  <img width="899" height="488" alt="Screenshot 2025-11-06 at 12 30 52 AM" src="https://github.com/user-attachments/assets/b5029eba-ba4f-42d8-87ab-21801e5c2259" />
   <img width="179" height="40" alt="Screenshot 2025-11-06 at 12 28 16 AM" src="https://github.com/user-attachments/assets/162baa77-48a0-47bb-af59-0c124438f59e" />
   <img width="889" height="485" alt="Screenshot 2025-11-06 at 12 31 27 AM" src="https://github.com/user-attachments/assets/7de57bdb-1533-4270-98e2-76a3c31901c9" />










