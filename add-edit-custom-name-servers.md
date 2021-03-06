---

copyright:
  years: 1994, 2020
lastupdated: "2020-03-26"

keywords: 

subcollection: dns

---


{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:DomainName: data-hd-keyref="DomainName"}
{:note: .note}
{:important: .important}
{:deprecated: .deprecated}
{:generic: data-hd-programlang="generic"}
{:help: data-hd-content-type='help'}
{:support: data-reuse='support'}

# Managing custom name servers for a domain
{:#add-edit-or-delete-custom-name-servers-for-a-domain}
{: help}
{: support}

Domains running on the {{site.data.keyword.cloud}} network can point to a maximum of five (5) custom name servers. Custom name servers can be added, deleted, or changed at any time. Follow these steps to add, edit, or delete custom name servers for a domain.
{:shortdesc}

1. From your browser, open the [{{site.data.keyword.cloud}} console](https://{DomainName}/){: external} and log in to your account.
1. Select the Menu icon ![Menu icon](../../icons/icon_hamburger.svg), then click **Classic Infrastructure**.
1. From the Classic Infrastructure menu, select **Services > Domain Registration** to open the Domains page.
1. Select the **Domain Name** to expand the domain into its snapshot view.
1. Select **Unlocked** from the **Lock Domain**.
1. Select the **Add/Edit NS** option in the **Custom Name Servers** section of the page. A dialog appears.
1. Refer to the bullets below to complete the appropriate action based on the task:
    * To add a custom name server, enter the hostname for the name server in the empty field.
    * To delete a custom name server, delete the information from the field for the appropriate name server.
    * To edit a custom name server, edit the details in the corresponding field for the appropriate name server.
1. Click the **Associate** button to save the changes, or click **Cancel** to cancel the action.

## Next steps
{:#add-edit-or-delete-custom-name-servers-for-a-domain-next}

After you update the name server details, they appear under the **Custom Name Servers** section of the domain. You can update the details at any time.
