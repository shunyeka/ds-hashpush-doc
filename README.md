# DS HASH PUSH - External file hash reputation threat intelligence integration with Deep Security
## Deep Security and Cloud One Workload Security


Multiple threat database provides malicious file hash values. e.g. Virustotal. Trend micro deep security supports external threat intelligence to identify and block malicious files. Currently, Trend Micro is doing this by adding hash value of malicious file in the application control module. Cloud one workload security (formally known as DSaaS) and Deep security on-premises both supports adding the hash value of the malicious file and block the same with the application control modue. Deep Security application control module can become the first line of defence to prevent the execution of known malicious file execution.

 Customers can leverage this application control feature by adding malicious file hash value to application control global ruleset. Application control will block any file execution that is having simiar hash value as added to the global ruleset.

Currently, this feature is available through API call. more details on application control global rule are available here. Details on API documentation is available here . Deep Security cannot accept external File hash value  CRUD operation from GUI. hence, We have developed a small electronJS + Angular based tool to add multiple file hash value.

 To know more about Deep security application control visit https://help.deepsecurity.trendmicro.com/application-control-rulesets.html
 
 
DISCLAIMER: This tool is not supported officially supported by Trend Micro.  Feel free to comment on this page if you find any issue or wants to request for any additional feature.


## DS HASH PUSH - Pre-requisite
 - Deep Security (Cloud one workload security) agent has to be installed on a system that needs protection.
 - The Application Control module has to be enabled at policy or computer level
 - Windows 10 or higher system to run "DS Hash push tool"
 - Network connectivity and admin role user authentication with on-premises Deep security manager or Cloud One Workload security


### Supported file Hash 
AES-256
  

In order to generate AES256 hash, you can use online hash generators like https://emn178.github.io/online-tools/sha256_checksum.html


