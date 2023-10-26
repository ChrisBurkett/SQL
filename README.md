<h1>SQL - Structured Query Language</h1>


<h2>Description</h2>
Project consists of a simple walkthough of MySQL.  Creating a new database, building and using a Entity Relationship Diagram (ERD), manually add 10 records in a table, create a new SQL View

PowerShell script that walks the user through "zeroing out" (wiping) any drives that are connected to the system. The utility allows you to select the target disk and choose the number of passes that are performed. The PowerShell script will configure a diskpart script file based on the user's selections and then launch Diskpart to perform the disk sanitization.
<br />


<h2>Languages and Utilities Used</h2>

- <b>MySQL</b>

<h2>Environments Used </h2>

- <b>Codio</b>

<h2>Navigating MySQL:</h2>

<p align="center">
Creating a Databes and Listing the Databases available: <br/>
<img src="https://i.imgur.com/cPtXXSx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Using a entity relationship diagram (ERD) as a reference, I created the following tables with the appropriate attributes and keys:  <br/>
<img src="https://i.imgur.com/SszxVNY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Created a table requested by Customer Service. Using a Primary Key to link data with foreign keys to build a usable table: <br/>
<img src="https://i.imgur.com/U4ZYIjE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Created an RMA table as reqeusted on the entity relationship diagram ERD:  <br/>
<img src="https://i.imgur.com/BcG0LjL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
