Azure Active Directory (Azure AD) is Microsoft's cloud-based IAM service that allows for your organization members to sign in and access your Azure Cloud resources securely. 

**Here are the basic terms to get started within this article:**
1.  ​Azure Role-Based Access - This is a service that provides controlled access to your 
    resources.
2. Active Directory (Windows Active Directory) - Is an Identity and access management 
    (IAM) 
    service that runs on the windows server, on-premises, and is managed by your 
    organization.
3. IAM(Identity and Access Management) - Are techniques and policies that Azure uses 
    to protect access to cloud resources 
    <h6>E.g  Azure Role-Based Access</h6>
4. Azure AD Connect - Synchronizes user identities on-premise AD to Azure AD
5. Authentication - This is the process of establishing the identity of a person or service. 
    that wants to access a resource.
6. Authorization - Establishes the level of access an authenticated person has. 
7. Tenant - Represents an organization.
8. Scope - Is a set of resources E.g management group.

In order to access resources in an organization, the user is first **authenticated** 
before being **authorized**
**Who Uses Azure AD?**
**IT administrators** can use it to control access to their app and cloud resources.<br>
**App Developers** can use it to add Single Sign-On to their app.<br>
**Online Service Subscribers** tenants using Microsoft 365, Azure or are already using Azure AD<br>
 
<h2>Services Provided By Azure AD</h2>
 <h3> Single-Sign On</h3>
SSO enables a user to sign in using one username and one password only once to access multiple applications.<br>
In order to allow for a synchronized sign-in both on-premises and on the cloud the AAD Connect is used.
<h3> Multi-factor Authentication</h3>
This is where the user is prompted to enter an additional form of identification E.g A fingerprint scan.
Multi-Factor Authentication elements are;
 
- Something the user knows <br>
    Email and password

- Something the user has<br>
  A code sent to the user's phone

- Something the user is<br>
   Fingerprint scan

MFA prevents attacks from people with stolen passwords.

<h3>Conditional Access</h3>
This is an AAD tool that is used to allow or deny access to resources based on identity signals.
The signals include;
     
- Who the user is

- Where the user is

- The device the user is requesting from

Conditional Access is used when you want to:

1. Require MFA to access an app.
2. Require access to services only through approved client apps.
3. Block access from untrusted sources.

**Role-Based Access**

It is applied to a **scope** and we have 3 roles:

 
-   Owner

- Reader

- Contributor

When to use RBAC:
 
1. To allow one user to manage VMs and another to manage virtual networks.
2. To allow an app to access all resources in a resource group.

**Benefits of Using Azure Active Directory**

1. **Security**
    <p>Resources should be protected from malicious attacks and threats at all times. 
    AAD achieves this through Conditional Access and MFA. Identity theft is managed by PIM(Privileged Identity Access).</p>

2. **IAM (Identity and Access Management)**
<p>AAD allows for easy management of user identities and permissions using RBAC.</p>

3. **Compatibility**
<p>Azure AD can also be used to access third-party apps(apps not developed by Microsoft), streamlining the process and enhancing productivity.</p>

4. **Collaboration**
   <p>AAD allows you to invite a guest to gain access to your directory, subscriptions, and resource groups for easier collaboration.</p>

5. **SSO**
    <p>Single sign-on allows for easy access to resources while minimizing the issuance of credentials every time the user signs in.</p>

**Azure AD Licenses**

*Premium P1*
<p> This license allows hybrid users to seamlessly access on-premises and cloud capabilities. It also allows for identity and access management (IAM) capabilities and security in the cloud.<br>
Approximately $6 per month.</p>

*Premium P2*
<p>Has all the features of previous editions of AAD but with advanced Identity and Access Management privileges and capabilities.<br>
Approximately $9 per month.</p>

