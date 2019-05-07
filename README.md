# ![LOGO](logo.png) DevSpacesManagement **flow**ground Connector

## Description

A generated **flow**ground connector for the DevSpacesManagement API (version 2019-01-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/devspaces/2019-01-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:38:04+03:00

## API Description

Dev Spaces REST API

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists operations for the resource provider.

> Lists all the supported operations by the Microsoft.DevSpaces resource provider along with their description.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - Client API version.

### Lists the Azure Dev Spaces Controllers in a subscription.

> Lists all the Azure Dev Spaces Controllers with their properties in the subscription.

*Tags:* `Controllers`

#### Input Parameters
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Azure subscription ID.

### Lists the Azure Dev Spaces Controllers in a resource group.

> Lists all the Azure Dev Spaces Controllers with their properties in the specified resource group and subscription.

*Tags:* `Controllers`

#### Input Parameters
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Resource group to which the resource belongs.

### Deletes an Azure Dev Spaces Controller.

> Deletes an existing Azure Dev Spaces Controller.

*Tags:* `Controllers`

#### Input Parameters
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Resource group to which the resource belongs.
* `name` - _required_ - Name of the resource.

### Gets an Azure Dev Spaces Controller.

> Gets the properties for an Azure Dev Spaces Controller.

*Tags:* `Controllers`

#### Input Parameters
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Resource group to which the resource belongs.
* `name` - _required_ - Name of the resource.

### Updates an Azure Dev Spaces Controller.

> Updates the properties of an existing Azure Dev Spaces Controller with the specified update parameters.

*Tags:* `Controllers`

#### Input Parameters
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Resource group to which the resource belongs.
* `name` - _required_ - Name of the resource.

### Creates an Azure Dev Spaces Controller.

> Creates an Azure Dev Spaces Controller with the specified create parameters.

*Tags:* `Controllers`

#### Input Parameters
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Resource group to which the resource belongs.
* `name` - _required_ - Name of the resource.

### Lists connection details for an Azure Dev Spaces Controller.

> Lists connection details for the underlying container resources of an Azure Dev Spaces Controller.

*Tags:* `Controllers`

#### Input Parameters
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Resource group to which the resource belongs.
* `name` - _required_ - Name of the resource.

### Returns container host mapping object for a container host resource ID if an associated controller exists.

*Tags:* `ContainerHostMappings`

#### Input Parameters
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Azure subscription ID.
* `resourceGroupName` - _required_ - Resource group to which the resource belongs.
* `location` - _required_ - Location of the container host.

## License

**flow**ground :- Telekom iPaaS / azure-com-devspaces-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
