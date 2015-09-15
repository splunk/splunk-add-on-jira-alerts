# JIRA Alert Add-on

## Introduction

This add-on allows Splunk to create JIRA issues as an alert action.

This add-on was produced as part of the
[Developer Guidance](http://dev.splunk.com/goto/alerting) project. Read our
guide to learn more about creating custom actions that can be performed when an
alert triggers.

## Installation

Once the app is installed (through [Splunkbase](https://splunkbase.splunk.com),
`Install app from file`, or by copying this directory to the etc/apps/ directory
of your Splunk installation), go to the app management page in the Splunk
interface. Click `Set up` in the JIRA Ticket Creation row. Fill out the required
attributes for your JIRA installation and you are ready to go.

To add a JIRA action to an alert, go to the `Alerts` tab in the `Search` app and
find the alert for which you want to add JIRA tickets. Click `Edit`, and select
`Edit Actions`. Click `+ Add Actions` and select JIRA. Fill out the attributes
for the artifact you wish to create in JIRA when the associated search returns
results, and Splunk will start logging bugs for you.

## Case Study
For a case study showcasing the application of this custom alert action, see the [Splunk Reference App - PAS](https://github.com/splunk/splunk-ref-pas-code) and the accompanying [Splunk Developer Guidance](http://dev.splunk.com/goto/devguide)

## License
The Splunk Add-on for Atlassian JIRA Alerts is licensed under the Apache License 2.0. Details can be found in the [LICENSE page](http://www.apache.org/licenses/LICENSE-2.0).
