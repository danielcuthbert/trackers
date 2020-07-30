# Microsoft Teams Endpoints

Microsoft Teams has grown in popularity since the global lockdown, and whilst Microsoft do list the endpoints that are required for Teams to function, I found it to be missing a number of tracking endpoints too. This document hopefully adds to this so you can better make an informed decision on what to allow and what to block.

The official Microsoft Teams page can be found at https://docs.microsoft.com/en-us/office365/enterprise/urls-and-ip-address-ranges

There are many missing endpoints, for example:

teams-events-data.trafficmanager.net is one frequently used by the app but not listed by Microsoft in the document above.


- *.search.production.apac.trafficmanager.net
*.search.production.emea.trafficmanager.net
*.search.production.us.trafficmanager.net

There are more, for example

- asm-api-golocal-geo-eu-teams.trafficmanager.net
  asm-api-prod-eu-teams.trafficmanager.net
  asm-api-prod-us-teams.trafficmanager.net

This will be an ongoing project looking at all the endpoints that such popular tools call out to and what their function is.
