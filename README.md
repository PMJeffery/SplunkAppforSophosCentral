# SplunkAppforSophosCentral
Revised Splunk App for Sophos Central Endpoint

Pre-Requisites:
1. Splunk Enterprise 8.x : https://www.splunk.com/en_us/download/splunk-enterprise.html
  1a. Not tested in Splunk Cloud, but app should be able to be uploaded as a "custom app"
2. Sophos API Key: https://support.sophos.com/support/s/article/KB-000036372?language=en_US
3. Create a new index "sophos" as set up the maximum size to 10GB or greater
4. Install and install Sophos Central Add-on: https://splunkbase.splunk.com/app/4647/ 
5. Download and configure Sophos Central Python Scripts: https://github.com/sophos/Sophos-Central-SIEM-Integration 


Installation:
1. Log into Splunk Enteprise
2. Apps->Manage Apps->Install App from File
