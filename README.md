<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
In this comprehensive tutorial, we take a deep dive into the entire lifecycle of a ticket, elucidating the journey from initial intake to ultimate resolution within the framework of osTicket—an open-source help desk ticketing system. Understanding the holistic ticket lifecycle is paramount for users seeking a nuanced grasp of how osTicket manages and streamlines the support process. The tutorial meticulously breaks down each phase of the ticket lifecycle, starting with the moment a ticket is initially raised or created, traversing through various stages of assignment, prioritization, communication, and collaborative resolution efforts. It expounds on how osTicket facilitates seamless communication between users, support agents, and other stakeholders, ensuring transparency and efficiency throughout the entire lifecycle. By exploring the intricacies of ticket management within osTicket, this tutorial aims to equip users with a comprehensive understanding of how to optimize the platform for effective issue tracking, resolution, and overall help desk management.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to create, work, and resolves tickets within osTicket](https://www.youtube.com/watch?v=l_xQASSZoYU)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>
1. This is a continuation from osTicket - Prerequisites and Installation at https://github.com/Gleejr/osticket-prereqs, as well as osTicket - Post-Install Configuration at https://github.com/Gleejr/post-install-config. Both of these are required for this tutorial.
</p>

<h3>Createing Tickets as an enduser</h3>
<p>
2. Begin by using this link (http://localhost/osTicket/) to access osTicket as an end user. Then, click on 'Open a New Ticket.'
</p>
<p>
<img width="860" alt="Screen Shot 2023-11-19 at 3 56 39 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/3a4e406c-2295-4ade-af97-0671297511b0">
</p>

<p>
3. Enter the email 'karen@osticket.com,' the user's name 'Karen Karen,' select the help topic 'Business Critical Outage,' and enter 'Entire mobile banking is down' for the issue summary.
</p>
<p>
<img width="850" alt="Screen Shot 2023-11-19 at 4 09 21 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/d9aece5b-688a-4412-9590-6701f2f7b173">
</p>

<p>
4. Enter 'Customers are reporting they are getting a 404 error when browsing to online banking.' for the description of the issue. Click 'Create Ticket.'
</p>
<p>
<img width="829" alt="Screen Shot 2023-11-19 at 4 14 21 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/4252c6bb-719d-4b28-9557-cfc7b4895013">
</p>

<p>
5. Repeat the same steps and create another ticket for Ken Ken. Select 'Personal Computer Issues' as the topic and enter 'Entire account dept Adobe Reader isn't working' as the issue summary.
</p>
<p>
<img width="723" alt="Screen Shot 2023-11-19 at 4 21 21 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/1cdc2e2b-409e-40bc-96ab-72af5e83f0e8">
</p>

<p>
6. Enter 'Ever since the upgrade, nobody in accounting can use Adobe Reader.' for the description of the issue. Click 'Create Ticket.'
</p>
<p>
<img width="834" alt="Screen Shot 2023-11-19 at 4 22 20 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/51fbca14-9f05-4ff6-8b88-4c19899b9bf1">
</p>

<p>
7. Create an additional ticket for Karen Karen. Select 'Password Reset' as the topic and enter 'Locked out of my computer' as the issue summary.
</p>
<p>
<img width="839" alt="Screen Shot 2023-11-19 at 4 28 09 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/501b6578-dfbe-402a-81dc-8523978d9ee7">
</p>

<p>
8. Create another ticket for Karen Karen. Choose 'Password Reset' as the topic and enter 'Unable to access computer' as the issue summary.
</p>
<p>
<img width="839" alt="Screen Shot 2023-11-19 at 4 28 09 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/501b6578-dfbe-402a-81dc-8523978d9ee7">
</p>

<p>
9. Enter 'Tried entering my password three times, and they were all incorrect. I am now locked out.' for the description of the issue. Click 'Create Ticket.'
</p>
<p>
<img width="839" alt="Screen Shot 2023-11-19 at 4 28 09 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/501b6578-dfbe-402a-81dc-8523978d9ee7">
</p>

<p>
10. Sign into osTicket as jane.doe (Supreme Admin).
</p>
<p>
<img width="405" alt="Screen Shot 2023-11-19 at 4 55 21 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/0a31dab4-30c2-4275-b80e-779b50ddafad">
</p>

<h3>"Entire mobile banking is down" Ticket</h3>
</p>
11. Access the ticket with the subject 'Entire mobile banking is down.'
<p>
<img width="963" alt="Screen Shot 2023-11-19 at 4 57 13 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/65a56a22-894b-4c8b-a212-cc29fffb2334">
<img width="966" alt="Screen Shot 2023-11-19 at 5 01 20 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/6c46fd5f-a2a8-4b9c-ae08-8607628b831b">
</p>

<p>
12. Given the critical nature of this issue, click on 'Priority,' change the priority to 'Emergency,' and add the comment 'Business Impacting Event.' Click 'Update.'"
</p>
<p>
<img width="643" alt="Screen Shot 2023-11-19 at 5 04 05 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/273f558e-fde8-46f7-bb9d-cfd56ba66de8">
</p>

<p>
13. Click on 'Assigned To,' assign this ticket to Jane Doe, and click 'Update.'
</p>
<p>
<img width="646" alt="Screen Shot 2023-11-19 at 5 06 08 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/23722979-64c7-4d35-b9ea-c2fee922081c">
</p>

<p>
14. Click on 'SLA Plan,' change the SLA to 'SEV-A,' and click 'Update.'
</p>
<p>
<img width="646" alt="Screen Shot 2023-11-19 at 5 11 37 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/5f1852f9-679f-4d14-8a8a-082b2e52ad3b">
</p>

<p>
15. Click on 'Department,' change it to 'System Administrators,' and click 'Transfer.' The ticket will reflect the updates that were made to the ticket.
</p>
<p>
<img width="642" alt="Screen Shot 2023-11-19 at 5 16 05 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/dcfaf528-7c13-4064-b58c-e7cfa41eae65">
<img width="948" alt="Screen Shot 2023-11-19 at 5 21 12 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/57d4a716-a5be-46ed-8d26-8aaba36505f7">
</p>

<p>
16. Scroll down to the bottom, add the response 'Coordinating with Sys. Admin team to bring mobile banking back online,' and click 'Post Reply.'
</p>
<p>
<img width="955" alt="Screen Shot 2023-11-19 at 5 25 34 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/5960abaf-b33b-4bed-9da7-cfddc74b42f7">
</p>

<p>
17. You can view the update to this ticket by clicking on 'Tickets' to see an overview of all the tickets in the queue.
</p>
<p>
<img width="971" alt="Screen Shot 2023-11-19 at 5 28 53 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/beb8a3aa-95c6-4a80-a5b4-05ecbc368d1d">
</p>

<p>
18. Go back into the ticket and add a response: 'Glenn from System Administrator fixed the issue. Mobile banking is back online.' Change the ticket status to 'Resolved' and click 'Post Reply.'
</p>
<p>
<img width="956" alt="Screen Shot 2023-11-19 at 5 38 38 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/5000f7bb-5e98-4b4c-a748-8cd5f169d4a6">
</p>

<p>
19. The ticket is now closed and removed from the queue. 
</p>
<p>
<img width="966" alt="Screen Shot 2023-11-19 at 5 41 38 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/6c0fd1f3-31dc-4f71-ad00-60cdc06817ad">
</p>


<h3>"Entire account dept adobe reader isn't working" Ticket</h3>

<p>
20. Access the ticket with the subject 'Entire account dept Adobe Reader isn't working.'
</p>
<p>
<img width="961" alt="Screen Shot 2023-11-19 at 5 45 37 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/22af9953-2f79-4cef-a1fe-eaf8b39596fb">
<img width="973" alt="Screen Shot 2023-11-19 at 5 46 39 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/1edda4d4-f54b-46cf-880b-c84b9f82007f">
</p>

<p>
21. Since this ticket is also an important issue but doesn't affect the company's ability to make money, repeat steps 12-15 for this ticket. Set the priority to 'High,' change the department to 'Support,' assign the ticket to John Doe, and set the SLA Plan to 'SEV-B.'
</p>
<p>
<img width="972" alt="Screen Shot 2023-11-19 at 5 51 15 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/9a871d86-a964-456e-b26e-5a00f2a96c78">
</p>

<p>
22. Since this ticket is being assigned to John Doe (not Jane Doe, the user currently logged in), scroll down to post a response: 'Re-assigned to SEV-B, reached out to John Doe for a warm handoff.' Click 'Post Reply.'
</p>
<p>
<img width="967" alt="Screen Shot 2023-11-19 at 5 53 38 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/b74dcd3a-09ac-457d-a05b-a064be719ddd">
</p>

<p>
23. Log out of jane.doe and log in as john.doe. Then, go back into the ticket that was just assigned to john.doe.
</p>

<p>
24. Scroll down to the bottom, post a response: 'Issue is now fixed. Accounting dept can now use Adobe Reader.' Change the ticket status to 'Resolved' and click 'Post Reply.'
</p>
<p>
<img width="946" alt="Screen Shot 2023-11-19 at 6 01 38 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/52bf7b82-479e-47ee-9971-3afa7c27c83d">
</p>

<p>
25. The ticket is now closed and removed from the queue.
</p>

<h3>"Locked out of my computer" Ticket</h3>

<p>
26. Log out of john.doe and log back in as jane.doe. Then, go into the ticket 'Locked out of my computer.'
</p>

<p>
27. Since this is a fairly common issue affecting a single user, repeat steps 12-15 for this ticket. Set the priority to 'Normal,' change the department to 'Support,' assign the ticket to John Doe, and set the SLA Plan to 'SEV-C.'
</p>
<p>
<img width="960" alt="Screen Shot 2023-11-19 at 6 50 01 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/e9e9fd4a-52ef-400c-99b3-ad1b1aef7d2a">
</p>

<p>
28. Since this ticket is being assigned to John Doe (not Jane Doe, the user currently logged in), scroll down to post a response: 'Re-assigned to SEV-C, reached out to John Doe for a warm handoff.' Click 'Post Reply.'
</p>
<p>
<img width="952" alt="Screen Shot 2023-11-19 at 6 55 05 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/90667ade-59c4-4305-b2c9-9d6101c30acc">
</p>

<p>
29. Log out of jane.doe and log in as john.doe. Then, go back into the ticket that was just assigned to john.doe.
</p>

<p>
30. Scroll down to leave a response: 'User account is now unlocked. User will be prompted to change their password next time they log in.' Change the ticket status to 'Resolved' and click 'Post Reply.' 
</p>
<p>
<img width="954" alt="Screen Shot 2023-11-19 at 6 59 07 PM" src="https://github.com/Gleejr/ticket-lifecycle/assets/148407820/5bc3c601-c0b1-44f9-91ae-656dda100941">
</p>




<br />

