---
title: Add SSL certificates
description: Learn how to add SSL certificates to secure your subdomains.
feature: Control Panel
jira: KT-4219
thumbnail: 31317.jpg
doc-type: feature video
activity: use
team: PM
role: Admin
level: Experienced
exl-id: 7937499a-8267-4ce6-a93c-65c0c5e4e582
---
# Add SSL certificates

Adobe Campaign [!UICONTROL Control Panel] allows you to add SSL certificates to secure your subdomains.

## Accessing Control Panel Subdomain Management

To access the Subdomain Management in Control Panel, go to:

* [Experience Cloud Home](https://experience.adobe.com/#/home) > Solution picker: **[!DNL Campaign]** > **[!UICONTROL Control Panel]** card > **[!UICONTROL Subdomains & Certificates]** card
  
  or
* Directly from the URL: [https://experience.adobe.com/#/controlpanel/domain](https://experience.adobe.com/#/controlpanel/domain)

## Steps to add SSL certificates

Adding SSL certificates requires three steps:

### 1. Generate Certificate Signing Requests

The Certificate Signing Request (CSR) is required for the purchase of an SSL certificate. It must be generated for the instance and the subdomains you are planning to secure.

 The video below describes how to generate a Certificate Signing Request in Control Panel.

>[!VIDEO](https://video.tv.adobe.com/v/31317?quality=12&learn=0n)

*Generate Certificate Signing Requests (02:36 min)*

>[!NOTE]
>
>Several enhancements have been made to the CSR generation process:
>
>* When generating a CSR, you can now select one of the included subdomains as the Common Name.
>* You can now copy the CSR summary before generating the CSR.
>* Once a CSR has been generated, you can download it again from the job logs. This capability does not apply to certificates generated before this release.
>
>![Download CSR](/help/assets/download-csr.gif)
>
>See the [product documentation](https://experienceleague.adobe.com/docs/control-panel/using/subdomains-and-certificates/renew-ssl/renewing-subdomain-certificate.html?lang=en) to learn more.
>

### 2. Purchase SSL Certificate

After obtaining the CSR, you must purchase the SSL certificate from a Certificate Authority approved by your organization.

### 3. Install SSL Certificates

Once you have obtained the SSL certificate, it must be installed for the subdomains you are planning on securing.

The video below explains how to install SSL certificates in [!UICONTROL Control Panel].  

>[!VIDEO](https://video.tv.adobe.com/v/31166?quality=12&learn=0n)

*Install SSL Certificates (01:25 min)*


