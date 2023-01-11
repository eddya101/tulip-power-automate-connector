### Tulip Connector

The Tulip Connector allows you to integrate with the data in you Tulip Instance. Enxtending you Tulip frontline operations into your power automates Teams and M365 workflows.

## Prerequisites
You will need the following to proceed:
* Active Tulip instance and subscription (tulip.co)
* Tulip API bot credentials for your Tulip Account with access to the appropriate scopes. ( Tulip Account or Workspace owner can provide credentials)

## Setting up the connector
On initial use, you will need to enter your Tulip Bot Credentials and Tulip instance url. This will provide you with the connection between power automate and you Tulip instance. See "Adding an API"(https://support.tulip.co/docs/how-to-use-the-table-api-1#:~:text=in%20a%20table.-,Adding,-an%20API) to see how to create a bot in your Tulip instnace


## The connector supports the following operations:

Get Record:  Returns a record from a Tulip Table based on a provided record id
Create Record: Creates a new record in a Tulip Table. Note: requires a unique id to be defined.
Put Record: Updates a record in a Tulip Table

Known Issues & Limitation
Files Type - The connector is currently limited to 
Individual Records - Only handling individual table records. Likely to be expanded in the future.

For support 

This connector is provided for use by Tulip customers to leverage the Tulip API in Microsoft environment. Usage of the connector is to Tulip Privacy Policy and API License Agreement
