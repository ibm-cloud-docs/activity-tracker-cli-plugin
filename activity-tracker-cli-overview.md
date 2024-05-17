---

copyright:
  years:  2021, 2024
lastupdated: "2024-05-17"

subcollection: activity-tracker-plugin-cli

keywords: IBM Cloud Activity Tracker hosted event search CLI, IBM Cloud Activity Tracker hosted event search command line, IBM Cloud Activity Tracker hosted event search terminal, IBM Cloud Activity Tracker hosted event search shell

---

{{site.data.keyword.attribute-definition-list}}

# Activity Tracker hosted event search CLI
{: #activity-tracker-cli-overview}

The {{site.data.keyword.cloud}} command-line interface (CLI) provides extra capabilities for service offerings. This information describes how you can use the {{site.data.keyword.at_full}} CLI to work with the {{site.data.keyword.at_full_notm}} hosted event search offering.
{: shortdesc}

As of 28 March 2024 the {{site.data.keyword.la_full_notm}} and {{site.data.keyword.at_full_notm}} services are deprecated and will no longer be supported as of 30 March 2025. Customers will need to migrate to {{site.data.keyword.logs_full_notm}}, which replaces these two services,  prior to 30 March 2025. {{site.data.keyword.logs_full_notm}} will become generally available during the summer of 2024 in Frankfurt and Madrid with day-one support for EU-managed controls. The service will continue its worldwide multizone region (MZR) roll-out through 3Q2024.
{: deprecated}

This information applies only if you use an {{site.data.keyword.at_full}} [hosted event search offering](/docs/activity-tracker?topic=activity-tracker-getting-started). See the [command line references for {{site.data.keyword.at_full_notm}} Event Routing](/docs/atracker-cli-plugin?topic=atracker-cli-plugin-atracker-cli-overview) for the CLI for that offering.
{: important}

## Installing the CLI
{: #at_install_cli}

Make sure you have the [{{site.data.keyword.cloud}} CLI installed.](/docs/cli?topic=cli-install-ibmcloud-cli).

After [logging in to the {{site.data.keyword.cloud}}](/docs/cli?topic=cli-ibmcloud_cli#ibmcloud_login), run the following command to install the CLI:

```text
ibmcloud plugin install logging
```
{: pre}
