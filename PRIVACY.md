# ShipCheck Privacy Policy

Last updated: November 26, 2026

ShipCheck ("the app") is an Atlassian Forge app for Jira and Confluence, developed by ShipCheck. This policy explains what data the app works with.

## How the app runs

The app runs entirely on Atlassian's Forge platform, inside the Atlassian site where it is installed. It has no servers of its own.

## What the app reads

To compute a release-readiness score, the app reads data from the installing site through Atlassian's APIs:

- Jira versions and the issues in them, including priority, status, issue links, and assignee display names
- Whether a Confluence page matching the version's release notes exists

## What the app stores and sends

- The app does not store personal data. It keeps no database of its own and does not persist the data it reads.
- The app does not transmit data to any external server, and it uses no analytics, tracking, or advertising.
- The only write action is optional and user-triggered: if a user clicks the app's "nudge" button, the app posts a comment on the relevant Jira issue as that user, mentioning the issue's assignee.

## Your control

Because the app stores nothing, there is no stored personal data to access, correct, or delete. Everything the app shows comes from your own Jira and Confluence site and stays under your Atlassian account's control. Uninstalling the app removes it completely.

## Contact

Questions about this policy: open an issue at https://github.com/richal0416/shipcheck/issues
