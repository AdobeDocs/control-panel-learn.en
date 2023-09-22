---
title: Trouble Shooting Control Panel
description: Learn how to troubleshoot Control Panel.
feature: Control Panel
jira: KT-2938
doc-type: article
activity: use
team: PM
role: Admin
level: Experienced
exl-id: 92d32589-7763-4895-8117-abfd47d808e3
---
# Trouble shooting [!UICONTROL Control Panel]

## Login and Homepage

### Symptom: Unable to log in to Experience Cloud

**What to do:**
The user must locate their IMS Org ID (xxx). The Administrator must add the user to the Product Profile “Campaign-xxx-Admins”  for each instance that they would like to manage. If the user is an admin of all instances, they must add themselves as users.

### Symptom: Links in the Experience Cloud Home to access [!UICONTROL Control Panel] do not appear for a user 

**Cause:**
Users do not see the links until they are added as users to Product Profile _Campaign-xxx-Administrators/Admin_.

**What to do:**
The Administrator must add the user to the Product Profile _Campaign-xxx-Admins_  for each instance that they would like to manage. If the user is an admin of all instances, they must add themselves as users. 

### Symptom: An Instance is not listed in the [!UICONTROL Control Panel]

**Cause:**
Most likely user must be added as a *user* Product Profile _Campaign-xxx-Administrators/Admin_ for the instance that is missing

**What to do:**
The Administrator must add the user to the Product Profile _Campaign-xxx-Admins_  for each instance that they would like to manage. If the user is an admin of all instances, they must add themselves as “users”.

### Helpful videos

>[!VIDEO](https://video.tv.adobe.com/v/27183?learn=on){transcript=true}

*Check IMS Org ID (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?learn=on){transcript=true}

*How to add an administrator to the product profile administrators to be able to use [!UICONTROL Control panel] (01:03 min)*

### Helpful Documentation

* [Discover the Control Panel](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)
* [Managing permissions to the [!UICONTROL Control Panel]](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)

## Establishing Connection to SFTP Server (Client or API)

Connecting to SFTP servers requires:

* [!UICONTROL Allow listing] the IP address from which you are connecting to the SFTP server  
* Private/public key pair that must be registered with Adobe Campaign
* To connect to the SFTP server directly, you also need SFTP client software

### Helpful documentation {#helpful-docs}

* [Logging into your SFTP server](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)
