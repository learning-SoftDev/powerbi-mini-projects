# powerbi-projects

<h3>KPI Tracker Dashboard</h3>
<img src="https://user-images.githubusercontent.com/96763817/218354449-7d65cde3-f6ac-464f-a145-16ac0f764ba7.png" alt="appImage_1" width="600">
This dashboard computes the KPI from different data sources for tracking purposes. It was used by the management to check if the team is reaching the automation savings target for the current fiscal year. <br> <br>
The challenge here is the size of the data sources. Since the powerquery pulls out the data from the said data sources and appends it for visual representation, even a little update in the powerquery transformation causes it to refresh all of the data sources. The workaround I did is to append the inputs using DAX instead of powerquery, in this way, we can update anything in the powerquery without worrying that it will take some time again.

<h3>Project Management Dashboard</h3>
<img src="https://user-images.githubusercontent.com/96763817/218354666-3538b06f-89b8-4462-833a-f12a178fb89a.png" alt="appImage_2" width="600">
The dashboard above was used by a sub department to monitor/track the current progress of the deliveries. It was presented daily to the heads for project monitoring and avoid escalations during busy season. 

<h3>Follow Up Dashboard</h3>
<img src="https://user-images.githubusercontent.com/96763817/218354693-7ed38ea9-1520-480e-b163-d961455c9703.png" alt="appImage_3" width="600">
This dashboard was build using Microsoft PowerBI and Power Automate. It can be manually triggered and automatically. It connects to a datasource in sharepoint and displays the resources that will be followed up by the tool by clicking the "Send Follow Up" button. Power Automate will then send an email to all of the resources listed. This dashboard also auto refreshes and tracks the resources which needs a follow up  and sends an email automatically.
