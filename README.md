# ![LOGO](logo.png) StorageManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the StorageManagementClient API (version 2015-12-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/azsadmin-farms/2015-12-01-preview/swagger.json<br/>
Generated at: 2019-06-11T18:13:35+03:00

## API Description

The Admin Storage Management Client.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Returns a list of all storage farms.

*Tags:* `Farms`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id.
* `resourceGroupName` - _required_ - Resource group name.
* `api-version` - _required_ - REST Api Version.

### Returns the Storage properties and settings for a specified storage farm.

*Tags:* `Farms`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id.
* `resourceGroupName` - _required_ - Resource group name.
* `farmId` - _required_ - Farm Id.
* `api-version` - _required_ - REST Api Version.

### Update an existing storage farm.

*Tags:* `Farms`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id.
* `api-version` - _required_ - REST Api Version.
* `resourceGroupName` - _required_ - Resource group name.
* `farmId` - _required_ - Farm Id.

### Create a new storage farm.

*Tags:* `Farms`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id.
* `resourceGroupName` - _required_ - Resource group name.
* `farmId` - _required_ - Farm Id.
* `api-version` - _required_ - REST Api Version.

### Returns a list of metric definitions for a storage farm.

*Tags:* `Farms`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id.
* `resourceGroupName` - _required_ - Resource group name.
* `farmId` - _required_ - Farm Id.
* `api-version` - _required_ - REST Api Version.

### Returns a list of storage farm metrics.

*Tags:* `Farms`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id.
* `resourceGroupName` - _required_ - Resource group name.
* `farmId` - _required_ - Farm Id.
* `api-version` - _required_ - REST Api Version.

### Start garbage collection on deleted storage objects.

*Tags:* `Farms`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id.
* `resourceGroupName` - _required_ - Resource group name.
* `farmId` - _required_ - Farm Id.
* `api-version` - _required_ - REST Api Version.

### Returns the state of the garbage collection job.

*Tags:* `GC`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id.
* `resourceGroupName` - _required_ - Resource group name.
* `farmId` - _required_ - Farm Id.
* `api-version` - _required_ - REST Api Version.
* `operationId` - _required_ - Operation Id.

## License

**flow**ground :- Telekom iPaaS / azure-com-azsadmin-farms-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
