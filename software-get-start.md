---

copyright:
  years: 2020, 2021
lastupdated: "2021-04-01"

keywords: onboard software, third-party software, getting started, software, partner, sellers, partner portal, partner center

subcollection: third-party

content-type: tutorial
account-plan: paid
completion-time: 10m 

---

{:shortdesc: .shortdesc}
{:screen: .screen}  
{:codeblock: .codeblock}  
{:pre: .pre}
{:tip: .tip}
{:note: .note}
{:beta: .beta}
{:external: target="_blank" .external}
{:step: data-tutorial-type='step'} 


# Getting set up to sell software 
{: #sw-getting-started}
{: toc-content-type="tutorial"} 
{: toc-completion-time="10m"} 

Welcome to {{site.data.keyword.cloud}}! To start onboarding your software to our cloud platform, first complete a few tasks: provide your company and product details, create a test environment, and set up access for your team to help with the onboarding process.
{: shortdesc}

The process to sell third-party software is available solely for providers that understand the onboarding process is still under development. With the current release, you can bring your own licenses or deliver your third-party software for free. If you’re interested in trying it out, contact us at kdmeyer@ibm.com.
{: beta}

## Before you begin
{: #sw-getstart-prereqs}

* Verify that you're using a Pay-As-You-Go or Subscription account. To check which type of account you're using, go to **Manage** > **Account** > **Account settings** in the {{site.data.keyword.cloud_notm}} console. 
* Contact us at kdmeyer@ibm.com to request access to {{site.data.keyword.cloud_notm}} Partner Center. In your email, include your account ID, which you can find on the Account settings page, and confirm that you understand the process to sell third-party software is a beta release. 
* Verify that you're assigned the administrator role on all account management services and all IAM-enabled services. See [Assigning access to account management services](/docs/account?topic=account-account-services) and [Managing access to resources](/docs/account?topic=account-assign-access-resources). 
* Review the list of supported software:
  
  * Helm charts
  * Terraform templates
  * OVA images deployed on VMware vCenter Server
  * Operators deployed on Red Hat OpenShift

## Provide your company and product information
{: #sw-company-product}
{: step}

1. In the {{site.data.keyword.cloud_notm}} console, click the Menu icon ![Menu icon](../icons/icon_hamburger.svg) > **Partner Center** > **Start selling** > **Get started**.
2. In 60 characters or less, enter the names of your company and product as you want them to be displayed in the {{site.data.keyword.cloud_notm}} catalog.

  The names don't need to be finalized. You can update them later during the onboarding process if necessary.
  {: tip}

## Create a test environment
{: #sw-create-testenv}
{: step}

You, or a member of your team, uses the test environment to onboard your product, and validate that it's ready to be published in the {{site.data.keyword.cloud_notm}} catalog. Your test environment includes a private catalog in which you import your product from an external repository. 

1. Click **Create** in the "Create your test environment" section on the Before you begin page.
2. Enter the name of your private catalog, and click **Create**. The private catalog and its contents are visible only to the users you choose.

## Set up team access
{: #sw-team-access}
{: step}

If you want to enlist team members to help with the onboarding process, you need to assign them specific levels of {{site.data.keyword.cloud_notm}} Identity and Access Management (IAM) access. To streamline the process, you can organize your team members into a single entity by adding them to an access group. 

1. Click **Assign** in the "Assign access for your team" section on the Get started page.
2. Enter the name of the access group, and click **Assign**. Members of this group are assigned the following roles by default:

  * Administrator on the catalog management service
  * Editor on the product lifecycle service
  * Editor on the user management service
  * Editor on the IAM access groups service
  * Viewer on all account management services
  
  For more information about the actions associated with each role, see [Actions and roles for account management services](/docs/account?topic=account-account-services#account-management-actions-roles).
  
## Invite team members to your account
{: #sw-invite-team}
{: step}

After you create your access group, you can add team members to the group by inviting them to your account.

1. Click **Invite** in the "Invite users" section on the Get started page.
2. From the Team page, click **Invite users**.
3. Select the user type:

  * Business: A team member who can provide certain details, such as the product logo, description, and customer support experience. 
  * Technical: A team member who can import the product to your test environment, configure the deployment details, and validate it's ready for use. 

4. Enter the email address of each user. 
5. Click **Invite**. 

## Next steps
{: #sw-getstart-next}

Now that you completed the getting started tasks, you're ready to [continue with the onboarding process](/docs/third-party?topic=third-party-sw-partner-details). 

To get an overview of all the tasks involved in the process, see [Checklist for selling software on {{site.data.keyword.cloud_notm}}](/docs/third-party?topic=third-party-checklist-software). 
{: tip}

