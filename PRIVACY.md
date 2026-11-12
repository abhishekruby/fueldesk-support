# Fueldesk privacy policy

Last updated: 12 November 2026

Fueldesk is a Forge app for Jira Service Management, Confluence and Rovo. It runs entirely on Atlassian's
Forge platform and is eligible for the Runs on Atlassian programme.

## What the app stores, and where

Everything the app creates stays inside your Atlassian site:

- **Jira Service Management**: the *Fuel Delivery Exceptions* desk, its tickets, and on each ticket the order
  figures and the recorded decision (as ticket properties, labels and a comment).
- **JSM Assets**: one record per truck and per depot, with delivery totals.
- **Confluence**: one page, the procedure "Handling a short fuel delivery".
- **Teamwork Graph**: the fuel orders, as deals, sent through the app's connector.
- **Forge storage**: the app's own bookkeeping, such as which order already has a ticket and the loss
  tolerance setting.

## What the app does not do

- It does not send data to any server outside Atlassian. The app has no external network access.
- It does not collect or store personal data. It does not copy names, email addresses or account IDs into
  its own storage.
- It has no advertising, tracking or analytics of its own.

## Who can see the data

The app's tickets, assets and page follow the permissions of your Jira and Confluence site. When the app
reads Teamwork Graph, or when the Rovo agent or an MCP tool acts, it does so as the signed-in user and can
only see what that user is allowed to see.

## Deleting the data

Forge deletes the app's own storage after the app is uninstalled. The tickets, assets and Confluence page
it created belong to your site and can be deleted there like any other content. The orders sent to Teamwork
Graph are managed from the *Fuel ERP* connector in Atlassian Administration.

## Demo data

The orders, customers, depots and trucks shipped with the app are fictional.

## Contact

Questions about this policy or the app: https://github.com/abhishekruby/fueldesk-support/issues
