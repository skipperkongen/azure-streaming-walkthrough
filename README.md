# README

This walkthrough shows your how to set up a small stream processing system
in Azure. The system is built with the following Azure components:
- EventHub to hold streaming events
- Azure functions app with functions to produce (HTTP trigger) and consume (EventHub trigger) events in EventHub.
- CosmosDB to hold and update state (simple counter) as events are consumed
- KeyVault to hold the CosmosDB and EventHub access secrets or just use function variables (optional)


## About web analytics frameworks

GA alternatives:
https://mofluid.com/blog/best-google-analytics-alternatives/
https://clicky.com/

Can I get raw web logs from web analytics?
https://developers.google.com/analytics/devguides/reporting/core/v4/ (Google)
https://mixpanel.com/help/reference/data-export-api (MixPanel)
