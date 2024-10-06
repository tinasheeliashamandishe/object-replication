<h1>Azure Storage Account: Object replication</h1>

<h2>Description</h2>
This lab will configure an Azure Storage account object replication.<br /><br />

Azure Storage Object Replication refers to the capabilities provided by Microsoft Azure to replicate data stored in Azure Blob Storage across different regions or within the same region to ensure data durability, availability, and disaster recovery.


<h2>Environments Used </h2>

- <b>Microsoft Azure</b>

<h2>Lab walk-through:</h2>

<p align="center">

<h4>Step 1</h4> 
Create 2 Storage Account resources and create containers.<br/>
<img src="https://i.imgur.com/ZSdcwpC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/th6llVb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


<h4>Step 2</h4> 
Enable blob versioning and chnage feed on your blobs.<br/>
<img src="https://i.imgur.com/OgjCPzN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h4>Step 3</h4> 
Create a replication rule.<br/>
<img src="https://i.imgur.com/AYnwzO7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h4>Step 4</h4> 
Confirm that objects have been replicated.<br/>
<img src="https://i.imgur.com/SuS0aoZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/JDDSocA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
