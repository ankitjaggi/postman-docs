---
category: "docs"
title: "Integrating Datadog with Postman"
page_id: "datadog_integration"
tags: 
  - "integrations"
warning: false
---

[Datadog](https://datadoghq.com) is a cloud-based network monitoring service. Integrating Datadog with Postman Monitors allow you to create metrics and events from Postman Monitor Run results which can be used in your Datadog dashboards and alerts.

### Connecting Datadog

1. Go to your Datadog account and [Create an API Key](https://app.datadoghq.com/account/settings#api).
![](https://cloud.githubusercontent.com/assets/6972850/21480435/efe2b122-cb82-11e6-955c-8786db9c0460.png)

2. After logging into your account on Postman, go to [Integrations](https://app.getpostman.com/dashboard/integrations) and select Datadog. Click on the `Add` button next to `Send Monitor Run Results`.
![](https://cloud.githubusercontent.com/assets/6972850/21480506/8cdfbaa6-cb83-11e6-8379-adaea3a1c1ef.png)

3. Enter the created API Key and chosse the Monitor for which you want this integration to be enabled. Also, you can configure advanced options to send specific data to Datadog.
![](https://cloud.githubusercontent.com/assets/6972850/21480555/09ddd45c-cb84-11e6-909f-c8459d168225.png)


### Metrics

- Total Response Time
- Number of Requests
- Errors
- Passed Tests
- Failed Tests
- Warnings


Each event and metric will be tagged with information about the user, monitor, collection and environment (if applicable).