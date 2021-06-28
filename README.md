# Rapid7-Universal-Adapter

ConnectALL Rapid7 Adapter is developed as an extension to the Universal Adapter capability of ConnectALL. The adapter specifications will let the user sync vulnerabilities found by a InsightAppSec security scan to another endpoint using the ConnectALL Integration Hub. A common use is that to monitor and resolve vulnerabilites using an issue trsacking system like JIRA or Azure DevOps. The vulnerabilities can also be synched to a database (like ConnectALLs' Insights database) for futher analysis. As the vulnerability is worked on any changes to status, priority, etc. can be synched back to the smart sheet.

Please refer to https://wiki.connectall.com/ca/latest/adapters/universal-adapter for more information

# How to use

## Import specifications
* Import Rapid7_config.zip into ConnectALL using "Install custom adapter" feature.

## Define application links
* Create an application link in ConnectALL between Rapid7 and another application of your choice.
* Navigate to `Configuration -> Connections` screen and create a new connection to Rapid7 using your Rapid7 access token.
* In the Entity mapping tab under Advanced Properties choose "Sync Type" as POLL
* In the field mapping tab add the field that you want to sync between the applications.

> In order to use the Rapid7 adapter you will need to get the license from ConnectALL sales team. Please reach out to sales@connectall.com for licenses and quotes.

