<!-- loio19611ddbe82f4bf2b493283e0ed602e5 -->

# Getting Started

Here's a checklist for setting up your system so you can develop applications using SAP Business Application Studio.

> ### Note:  
> If you are working in a trial account, follow the procedure in [Getting Started with a Trial Account](getting-started-with-a-trial-account-48ed55e.md).


<table>
<tr>
<th valign="top">

Step



</th>
<th valign="top">

Description



</th>
<th valign="top">

Links/Information



</th>
</tr>
<tr>
<td valign="top">

 **Sign up for a global account.** 



</td>
<td valign="top">

You require a global account to enable SAP Business Application Studio.



</td>
<td valign="top">

[Getting a Global Account](https://help.sap.com/viewer/65de2977205c403bbc107264b8eccf4b/Cloud/en-US/d61c2819034b48e68145c45c36acba6e.html)



</td>
</tr>
<tr>
<td valign="top">

**Create subaccounts in the Cloud Foundry environment.**

Select a region according to the guidelines in the [Neo and Cloud Foundry Regions](https://help.sap.com/viewer/825270ffffe74d9f988a0f0066ad59f0/CF/en-US/975b3207acf94599a9a48beb36257ebc.html) topic.



</td>
<td valign="top">

When you create a subaccount in the SAP BTP, Cloud Foundry environment, a Cloud Foundry organization is automatically created for that subaccount.



</td>
<td valign="top">

[Create a Subaccount](https://help.sap.com/viewer/65de2977205c403bbc107264b8eccf4b/Cloud/en-US/05280a123d3044ae97457a25b3013918.html)



</td>
</tr>
<tr>
<td valign="top">

 **Assign members to your Cloud Foundry organizations and spaces.** 



</td>
<td valign="top">

Enable your developers to work with your SAP BTP, Cloud Foundry environments.

Your developers need to be assigned to the space developer role to be able to use the space from SAP Business Application Studio.



</td>
<td valign="top">

[Managing Members](https://help.sap.com/viewer/65de2977205c403bbc107264b8eccf4b/Cloud/en-US/cc1c676b43904066abb2a4838cbd0c37.html)



</td>
</tr>
<tr>
<td valign="top">

**Configure entitlements for your global account**.

Relevant for Feature Set B accounts only.

To check if your global account belongs to Feature Set A or Feature Set B, see [Cloud Management Tools — Feature Set Overview](https://help.sap.com/viewer/65de2977205c403bbc107264b8eccf4b/Cloud/en-US/caf4e4e23aef4666ad8f125af393dfb2.html).



</td>
<td valign="top">

Assign entitlements to subaccounts by adding service plans and distribute the quotas available in your global account to your subaccounts using the SAP BTP cockpit.



</td>
<td valign="top">

[Configure Entitlements and Quotas for Subaccounts](https://help.sap.com/viewer/65de2977205c403bbc107264b8eccf4b/Cloud/en-US/5ba357b4fa1e4de4b9fcc4ae771609da.html)



</td>
</tr>
<tr>
<td valign="top">

 **Subscribe to SAP Business Application Studio.** 



</td>
<td valign="top">

You need to subscribe to the SAP Business Application Studio.



</td>
<td valign="top">

 [Subscribe to SAP Business Application Studio](subscribe-to-sap-business-application-studio-6331319.md) 



</td>
</tr>
<tr>
<td valign="top">

**Grant user permissions.**



</td>
<td valign="top">

To enable working with SAP Business Application Studio, developers need to be assigned the `Business_Application_Studio_Developer` role.



</td>
<td valign="top">

 [Manage Authorizations and Roles](manage-authorizations-and-roles-01e69c5.md) 



</td>
</tr>
<tr>
<td valign="top">

**OPTIONAL: Enable identity provider \(IdP\)-based authentication for SAP Business Application Studio applications \(optional\).**



</td>
<td valign="top">

If you define a custom identity provider for your subaccount, be sure to configure the assertion-based attributes mapping for this IdP.



</td>
<td valign="top">

 [Configure Trust to the SAML Identity Provider](https://help.sap.com/viewer/65de2977205c403bbc107264b8eccf4b/Cloud/en-US/dc618538d97610148155d97dcd123c24.html#loiob6cfc4bb4bff4ace90afc71b0962fcb5) 



</td>
</tr>
<tr>
<td valign="top">

**OPTIONAL: Connect to your Git source control system.**



</td>
<td valign="top">

 SAP Business Application Studio allows you to connect to public and corporate Git repositories.



</td>
<td valign="top">

[Connect to Your Git Source Control System](connect-to-your-git-source-control-system-e7a42bc.md)



</td>
</tr>
<tr>
<td valign="top">

**OPTIONAL: Create spaces.**

Relevant for developers who want to work in Cloud Foundry runtime.



</td>
<td valign="top">

You can create and delete spaces in a Cloud Foundry organization using the SAP BTP cockpit or the console client \(Cloud Foundry command-line interface\).

We recommend at least 1 space for a development team working on the same project \(that is, 1 space per project\).

For staging/test and production organizations, 1 space is sufficient.



</td>
<td valign="top">

[Create Spaces](https://help.sap.com/viewer/65de2977205c403bbc107264b8eccf4b/Cloud/en-US/2f6ed22ccf424dae84345f4500c2d8ea.html)



</td>
</tr>
</table>

