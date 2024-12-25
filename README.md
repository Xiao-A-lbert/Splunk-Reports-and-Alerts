# Splunk-Reports-and-Alerts

<h2>Description</h2>
In this SIEM task, I generated a report and an alert from my Splunk search queries.


<h2>Languages and Utilities Used</h2>

- <b>linux CLI</b>

<h2>Environments Used </h2>

- <b>Splunk</b>
- <b>Unbuntu</b> 

<br />
<br />
Saving my geostats country clustermap as a report.

![1) save as](https://github.com/user-attachments/assets/250741c1-acc2-4448-aae1-05f9451ab31a)

<br />
<br />
Titling report and allowing viewers to pick a time range. 

![2) Report title](https://github.com/user-attachments/assets/834b895b-7f5b-4e8f-9e9c-0a0c53be6407)

<br />
<br />  
Viewing the report and the time range options. 

![3) report generated along with timerange](https://github.com/user-attachments/assets/258598e7-f288-495a-b85c-6c8b5df4b1b3)

<br />
<br />
In the reports tab, viewing report details and editing permissions. 

![4)  reports tab editting permissions](https://github.com/user-attachments/assets/6c0f2f77-1b6e-403d-83bb-8d991e515f65)

<br />
<br />
Allowing read permissions for everyone.

![5) editting report permissions](https://github.com/user-attachments/assets/f0bbd22c-7305-47b8-a4c8-da1a1a71b0be)

<br />
<br />
From the http_sample index, using search uri_query="*%2e%2e%2f*" saving this query to generate a rule for path traversal attacks.   

![6) uri query as an alert](https://github.com/user-attachments/assets/fb7991e4-cb55-4574-9cf3-4471727acbad)

<br />
<br />
Titling the rule alert_LFIdetection and triggering an alert with medium severity. 

![7) alert details](https://github.com/user-attachments/assets/61059406-fdde-4938-8760-e1bb3d0ad35b)

<br />
<br />  
