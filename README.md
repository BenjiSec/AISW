# AISW
Advanced Interactive Security Workshop (AISW) is set of instructions that can be used for hands-on learning of Microsoft 365 Security and Compliance stack. For AISW it is recommended to open M365 E5 trial subscription (contact your Microsoft representative if help needed), add 20 test users, and preconfigure tenant with configuration below. For each feature in this document, I have had provided step-by-step instructions how the feature is enabled, as well as description how to test the feature and how to tune it more for your needs.

All heading is linked to Microsoft docs if you want to learn more about specific feature or to find How-to guide or Tutorial on Microsoft docs.

Since I’m maintaining this document alone, errors and inaccuracies can happen. If you detect inaccuracy or you would like see specific feature in AISW or you have any other feedback, please submit your response on this form:
https://forms.office.com/Pages/ResponsePage.aspx?id=DQSIkWdsW0yxEjajBLZtrQAAAAAAAAAAAAN__rvUg1ZURE5ZOEVIQjkxVFc2RzY4S0RGRU9SSURGOC4u 

Advanced Interactive Security Workshop includes following pillars:
1.	Identity protection
2.	Device and app management
3.	Information Protection
4.	Threat Protection
5.	Compliance

IDENTITY PROTECTION
1.	Enable basic Identity protection like Conditional Access, Passwordless log-in, Self-Service Password Reset, Custom banned password list, Azure AD B2B for secure guest access
2.	Enable advanced Identity Protection & Governance like Identity Protection with Sign-in risks and User risk, Privileged Identity Manager, Identity Governance

DEVICE & APP MANAGEMENT
1.	Configure basic device and app management policy – Windows, Android, iOS
2.	Push Microsoft 365 Apps (Office 365 ProPlus) to all Win devices
3.	Add custom .msi application – ex. AIP UL client

INFORMATION PROTECTION
1.	Configure DLP and Endpoint DLP, Retention policy, Unified Labeling 
2.	Enable Unified Labeling (including support for Teams, OneDrive and SharePoint Online)

THREAT PROTECTION
1.	Configure Microsoft Defender for Office 365 (Safe Links, Safe Attachments) for EXO, SPO, and Teams – execute Attack Simulator; fine tune policies using Configuration Analyzer
2.	Configure MD for Endpoint (enable all integrations and advance features, web content filtering, MCAS integration) plus do Evaluation labs and testing scenarios
3.	Configure MCAS (make demo report, integration with AIP, MD for Endpoint, enable policies, admin quarantine, Configure Conditional Access App Control with AAD CA)
4.	What is Microsoft 365 Defender and how it can help
5.	How to use Secure Score
Note: Microsoft Defender for Identity is not included in this workshop – but there is Security lab for Microsoft Defender for Identity available on Microsoft docs. Instructions for the same you can find in the MD for Identity segment of the document.

COMPLIANCE IN MICROSOFT 365
1.	Compliance Manager and Compliance Score
2.	Information Barriers, Insider Risk Management, and Communication Compliance
3.	eDiscovery and GDPR Data Subject Requests


IMPORTANT NOTE
1.	Purpose of this document is to provide learning material about Microsoft Security solutions from Microsoft 365
2.	It is recommended to use Trial tenant and that all devices and documents aren’t connected to production environment in any way. If you are using your production tenant and environment, you are doing it on your own risk! Some of configuration CAN and WILL impact live environment!
3.	This document doesn’t state official Microsoft recommended configuration steps! This document cannot be used as set of instructions how to configure production tenant; it’s made for testing purposes only. Because Microsoft must respond to changing market conditions, this should not be interpreted to be a commitment on the part of Microsoft, and Microsoft cannot guarantee the accuracy of any information provided after the date of this document.
4.	Microsoft recommended configuration/best practices can be found only on official Microsoft Docs
5.	Microsoft and/or Microsoft employees cannot be held responsible for any issues on customer environment/s while preforming Advanced Interactive Security Workshop.
