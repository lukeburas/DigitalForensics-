<h1>Full Project</h1><br />
<br />
<h2>Investigative Plan of Action - Part 1/2</h2>


<h3>Description</h3>
This project outlines an investigative plan to address a suspected data breach involving proprietary information. The plan involves seizing relevant devices, acquiring and analyzing data, and drawing conclusions based on the evidence. Key strategies include minimizing disruption to the organization, preserving evidence integrity, and utilizing advanced forensic tools. The goal is to provide clear and compelling evidence to support or refute the allegations.
<br />


<h3>Scenario</h3>
An oil company’s senior management has reason to suspect that John Smith, one of the company’s mechanical engineers, allegedly took information that was clearly identified as proprietary. The company’s legal office has requested digital evidence regarding the potential violation of company policy, which prohibits the sharing of proprietary information without prior approval. The employee was not authorized to access proprietary information. All employees sign nondisclosure agreements (NDAs) and acceptable use policies (AUPs). Senior management and the legal office have approved the request for digital evidence.<br />
<br />

You are a member of the investigative team asked to develop an investigative action plan.



<h3>Project Documentation:</h3>

<p align="center">
<br/>
  <br />
<img src="https://i.imgur.com/iaWuia6.png" height="80%" width="80%" alt="Investivative POA"/>
<img src="https://i.imgur.com/2ydCMjZ.png" height="80%" width="80%" alt="Investivative POA"/>
<img src="https://i.imgur.com/9SqxkXz.png" height="80%" width="80%" alt="Investivative POA"/>
<img src="https://i.imgur.com/Y7FdQ6Q.png" height="80%" width="80%" alt="Investivative POA"/>
<img src="https://i.imgur.com/8VFKyTi.png" height="80%" width="80%" alt="Investivative POA"/>
<img src="https://i.imgur.com/H4jx6vd.png" height="80%" width="80%" alt="Investivative POA"/>
<br />
<br />
  
</p>





<h2>Forensic Investigation - Part 2/2</h2>


<h3>Description</h3>
This project involves using Autopsy to analyze a storage device for evidence related to a suspected data breach. The goal is to identify data files, deleted files, directories, or partitions that may indicate a policy violation. The findings will be documented in a report for senior management.
<br />


<h3>Tools Used</h3>

- <b>Autopsy (4.19.1)</b> 

<h3>Environments Used </h3>

- <b>Windows 10</b>

<h3>Scenario</h3>
An oil company’s senior management has reason to suspect that John Smith, one of the company’s mechanical engineers, allegedly took information that was clearly identified as proprietary. The company’s legal office has requested digital evidence regarding the potential violation of company policy, which prohibits the sharing of proprietary information without prior approval. The employee was not authorized to access proprietary information. All employees sign nondisclosure agreements (NDAs) and acceptable use policies (AUPs). Senior management and the legal office have approved the request for digital evidence.<br />
<br />

You are a member of the investigative team that has been assigned to examine the digital evidence captured from the suspect’s office laptop computer. You will create an incident report to present the findings to senior management.
  
<h3>Investigation Walk-through:</h3>

<p align="center">
I began with opening Autopsy, selected new case, and I gave it the name,
“Johnputdownthedatanojohndontdothatbadjohn.” After naming the case, I set the Base
Directory as, “C:\Users\LabUser\Desktop\Evidence Files”: <br/>
<br />
<img src="https://i.imgur.com/z99A739.png" height="80%" width="80%" alt="Select New Case in Autopsy"/>
<br />
<br />
After inputting my information, I began adding a data source. I then selected, “Generate new host name based on data source name.”:<br />
<br/>
<img src="https://i.imgur.com/HbzpE7p.png" height="80%" width="80%" alt="Generate New"/>
<br />
<br />
I moved on to Data Source Type and chose Disk Image or VM File then clicked next: <br/>
<br />
<img src="https://i.imgur.com/UvA4R6a.png" height="80%" width="80%" alt="Select Disk Image or VM File"/>
<br />
<br />
Select Data Source. I clicked browse under the path options and went to: “C:\Users\LabUser\Desktop\Evidence Files\JSmith_Q1.001”:  <br/>
<br />
<img src="https://i.imgur.com/h02I6w2.png" height="80%" width="80%" alt="Select Data Source"/>
<br />
<br />
Configure ingest. Accepted the defaults and clicked next:  <br/>
<br />
<img src="https://i.imgur.com/VnrdFnu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
I added the Data source then clicked on, “Finish.”:  <br/>
<br />
<img src="https://i.imgur.com/HLaEIq5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
I found 6 deleted files, 8 images, and 7 PDF files.:  <br/>
<br />
<img src="https://i.imgur.com/PZw2rLv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
After closer examination, I found that John had confidential and restricted PDF files about Business Strategy (can also be seen on desktop) and the Drilling Methodology. On top of that. I also found two deleted files regarding the research of suspicious cryptocurrency transactions and how to not be traced through cryptocurrency.:  <br/>
<br />
<img src="https://i.imgur.com/R5rAUC4.png" height="80%" width="80%" alt="Confidential Files Found"/>
<br />
<br />
It can also be seen in the 7 PDF files, that there are three that were not deleted containing information about illegal bitcoin transactions and the Oil Company data strategy:  <br/>
<br />
<img src="https://i.imgur.com/efZfHUs.png" height="80%" width="80%" alt="Illegal Bitcoin Transactions/Oil Company Data Strategy"/>
<br />
<br />
In the 8 images, some had blueprints and drawings of projects the oil company was working on:  <br/>
<br />
<img src="https://i.imgur.com/gREbQ6h.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<h3>Summary</h3>
This analysis showed evidence that John Smith was interested in confidential, restricted information regarding the business plans, drilling methodology, images regarding the drilling procedures, and research of how to make illegal transactions through cryptocurrency. This is enough evidence to be able to show that John Smith sold the documentation for monetary gain by using cryptocurrency as a transaction means, which would explain why some confidential files were deleted in hopes that his tracks would be covered.<br />
<br />
<h3>Proof of Illegal Behavior</h3>
The scenario mentions that John Smith was not authorized to access proprietary data, it mentions that employees must sign nondisclosure agreements, and lastly, the scenario mentions that senior management and the legal office approved of a digital evidence request, which indicates that there were prior concerns about John Smith’s illegal behavior.<br />
<br />
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
