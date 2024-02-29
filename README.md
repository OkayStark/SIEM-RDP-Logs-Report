A World Map representing all 13k failed RDP login brute force attempts on my Remote Honeypot 🌐 only up for 10 hours

![RDP fail map](https://github.com/OkayStark/SIEM-RDP-Logs-Report/assets/66514398/9ca5b675-0d41-4432-88b8-1c41e053a17d)

(Used Azure Sentinel to deploy a sophisticated Security Information and Event Management (SIEM) system. Intentionally left uncovered, the honeypot developed into a dynamic observatory that relentlessly recorded attacks from all around the world.)

Here's the breakdown:

1. Used a customized PowerShell script that is adept at obtaining IP addresses from unsuccessful login attempts. Integrated seamlessly with an API to extract geolocation data. 🛠️

2. Configured Azure Log Analytics, ingesting and organizing custom logs to create a detailed record of attempted breaches. 📊

3. Enhanced granularity of the logs for subtle insights with the configuration of custom fields in Azure Log Analytics. 🔍

4. Skillfully crafted an Azure Sentinel workbook, transforming raw data like geolocation and magnitude into an insightful world map. 🗺️

-In summary, anything online without a firewall is like an open invitation for bots to snoop around. To stay safe, it's crucial to ditch default or easy-to-guess passwords. Considering multi-factor authentication adds an extra layer of security. Remember, beefing up your digital defenses isn't just a good idea – it's a must in the face of savvy online threats. 🛡️


