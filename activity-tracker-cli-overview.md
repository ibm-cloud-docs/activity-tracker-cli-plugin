---
 
copyright:
  years:  2021, 2022
lastupdated: "2021-05-06"

subcollection: activity-tracker-plugin-cli

keywords: IBM Cloud Activity Tracker CLI, IBM Cloud Activity Tracker command line, IBM Cloud Activity Tracker terminal, IBM Cloud Activity Tracker shell

---

{{site.data.keyword.attribute-definition-list}}

# Activity Tracker CLIs
{: #activity-tracker-cli-overview}

The {{site.data.keyword.cloud}} command-line interface (CLI) provides extra capabilities for service offerings. This information describes how you can use the {{site.data.keyword.atracker_full}} CLIs to work with the {{site.data.keyword.atracker_full_notm}} offerings. 
{: shortdesc}

{{site.data.keyword.atracker_full_notm}} has three unique CLIs depending on the offering you are using:

* {{site.data.keyword.at_full}} [hosted event search offering CLI](/docs/activity-tracker-cli-plugin?topic=activity-tracker-cli-plugin-activity-tracker-cli)

* {{site.data.keyword.at_full}} [Event Routing offering V1 CLI](/docs/activity-tracker-cli-plugin?topic=activity-tracker-cli-plugin-atracker-v1-cli)

* {{site.data.keyword.at_full}} [Event Routing offering V2 CLI](/docs/activity-tracker-cli-plugin?topic=activity-tracker-cli-plugin-atracker-v2-cli)

## Installing the CLI
{: #at_install_cli}

Make sure you have the [{{site.data.keyword.cloud}} CLI installed.](/docs/cli?topic=cli-install-ibmcloud-cli).

After [logging in to the {{site.data.keyword.cloud}}](/docs/cli?topic=cli-ibmcloud_cli#ibmcloud_login), run the following command to install the CLI:

```text
ibmcloud plugin install <CLI_PLUGIN>
```
{: pre}

Where

CLI_PLUGIN
:   Is `logging` for the hosted event search CLI and `atracker` for the Event Routing CLI.


