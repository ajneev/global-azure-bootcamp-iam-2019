##  Multi-tenant deployment instructions

V1 endpoint. (V2 sample requires Office 365).

Needs DotNet framework 4.7.2.

[Github](https://github.com/Azure-Samples/active-directory-dotnet-webapp-multitenant-openidconnect)

This sample will not work with a MSA (Microsoft Live) account so you will need to create a user
in your AAD tenant.

To set multi-tenancy, do this under "Properties".

![Properties](https://rbrayb.github.io/global-azure-bootcamp-iam-2019/Images/Multi_Tenant.png)

For the permissions section, use this (under "Delegated Permissions"):

**Windows AAD**

![Windows AAD](https://rbrayb.github.io/global-azure-bootcamp-iam-2019/Images/AAD_Permissions.png)

**Microsoft Graph**

![Microsoft Graph 1](https://rbrayb.github.io/global-azure-bootcamp-iam-2019/Images/Graph_Permissions_1.png)
![Microsoft Graph 2](https://rbrayb.github.io/global-azure-bootcamp-iam-2019/Images/Graph_Permissions_2.png)

You should end up with:

![Overview](https://rbrayb.github.io/global-azure-bootcamp-iam-2019/Images/Graph_Permissions_All.png)





