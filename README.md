# Honeypot Project

**Time spent:** **10** hours spent in total

**Objective:** Create a honeynet using MHN-Admin. Present your findings as if you were requested to give a brief report of the current state of Internet security. Assume that your audience is a current employer who is questioning why the company should allocate anymore resources to the IT security team.

### MHN-Admin Deployme

**Summary:** How did you deploy it? Did you use GCP, AWS, Azure, Vagrant, VirtualBox, etc.?
I used Google Cloud Platform to deploy MHN-Admin. After setting up Google SDK and configuring firewall, I created a Vertual Machine, updated, downloaded, installed and configured MHN-Admin.

<img src="mhn-admin.gif" width=500>

### Dionaea Honeypot Deployment

**Summary:** Briefly in your own words, what does dionaea do?
Dionaea simulates the target by having several ports open and traps different malwares.

<img src="dionaea-honeypot.gif" width=500>

### Database Backup
<img src="database backup.gif" width=500>

**Summary:** What is the RDBMS that MHN-Admin uses? What information does the exported JSON file record?
As we used command mongoexport --db mnemosyne --collection session > session.json to get the file, I assume that MHN-Admin uses MongoDB. The exported JSON file contains id, source and destination ip address, port, protocol, timestamp.

*Be sure to upload session.json directly to this GitHub repo/branch in order to get full credit.*



## Notes

Challenges:
When i first finished the assignment I could't see attacks in the Attack tab due to python versions
