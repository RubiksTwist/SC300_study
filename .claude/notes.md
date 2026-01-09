QI) Your organization uses a Microsoft 365 subscription and plans to implement a Conditional Access policy that leverages a Global Secure Access security profile. The goal is to block access to websites containing the word "gambling"jn the URL.
What is the first step you should take to fulfill this web content restriction requiremen ?

A. Define a web content filtering policy.
appropriate for web filtering
B. Set up a named location.
define geographic or ip base condition

C. Modify the Adaptive Access settings.
adjust based on risk signals does not filter url or enforce content restrictions 

D. Deploy a network security group (NSG).
NSGs apply to azure virtual networks, doesnt integrate with M365 conditional access or global secure access

Q2) Your organization uses a Microsoft 365 subscription integrated with Microsoft Entra
Permissions Management. You've been asked to identify managed identities with
unused permissions for the past 95 days and automatically clean up those
permissions while keeping administrative overhead Iow.
What action should you take in the portal to fulfill this unused permissions cleanup
requirement ?
A. Set up an Autopilot rule.
detection and remediation of inactive thresholds
B. Generate and schedule a Permissions analytics report.
reports provide insight but do not perform clean ups
C. Navigate to Microsoft Entra Insights and analyze Service principals with privileged
role assignments.
doesnt automate permissions or cleanup
D. Use the audit query feature.
activity logs and do not enforce clean up

Q3) Your organization has assigned Microsoft Office 365 Enterprise E3 licenses to 2,700 users individually. You've now assigned Microsoft Office 365 Enterprise E5 licenses to a group that includes all users using the Groups blade in the Microsoft Entra admin center. To streamline license management, you want to remove the E3 licenses from individual users with minimal administrative effort.
What tool should you use to fulfill this license cleanup requirement ?

A. Use the Licenses blade in the Microsoft Entra admin center to remove individual license
assignments in bulk.
license blade allows removal of bulk or individual licenses
B. Execute the Set-WindowsProductKey cmdlet to update product keys on user devices.
Set-WindowsProductKey manages licensing for windows OS but not O365 Enterprise licenses
C. Go to the Identity Governance blade in Microsoft Entra to manage licensing workflows
and access packages.
Identity Governance manages access reviews and entitlement management not licensising
D. Run the Update-MgUser cmdlet in Microsoft Graph PowerShell to script changes per
user account.
Update-MgUser command can update user properties requires scripting and manual administration effort

Q4) Your organization recently licensed Microsoft Entra Permissions Management for your Azure subscription Sub3. You've been assigned the task to onboard Permissions Management to begin analyzing and controlling access. Which two actions should you perform to fulfill this onboarding initiation requirement ?

A. Deploy a Microsoft Entra application proxy to enable access to on-premises applications
through the cloud.
Entra Application Proxy is used for publishing permissions on on-premises applications.
Not related to onboarding permissions management
B. In Microsoft Entra Permissions Management, activate data collection to scan identities,
roles, and permissions.
Data collections must be enabled to capture activity logs and builds insights into permission usage
C. Assign appropriate roles for access by creating a role assignment for Sub3 within Entra
Permissions Management.
Subscriptions must delegate appropriate rules such as cloud infrastructure initiatives to collect delemetry and build insight into permission usage.
D. Configure Diagnostic settings in the Microsoft Entra admin center to stream logs and
usage metrics.
Diagnostic settings control logging and monitoring but not used for permission management.

Q5) Your organization holds a Microsoft 365 E5 subscription and an Azure subscription connected
to a Microsoft Entra tenant. A user named User5 is part of the tenant. You are preparing to deploy
Microsoft Entra Permissions Management and want to ensure that User5 can onboard the Azure
subscription while adhering to the principle of least privilege.
Which role assignment will fulfill this onboarding authorization requirement ?

A. Permissions Management Administrator.
Can admin permissions management
B. Global Administrator.
Full permission for entra environment
C. Security Administrator.
Role focuses on security configurations and monitoring
D. Application Administrator.
Role manages application registrations and permissions

Q6) Your organization uses a Microsoft 365 E5 subscription, and you've been asked to ensure
that users are required to accept a custom Terms of Use (TOU) agreement when signing in to
access corporate resources. You want to enforce this requirement during the sign-in process.
What configuration should you apply to fulfill this user acknowledgment enforcement
requirement ?
A. Access package.
Manages access control workflows but dont enforce ToU prompts
B. Conditional Access policy.
Enforces user acknowledgement of ToU
C. Lifecycle workflow.
D. Authentication method.