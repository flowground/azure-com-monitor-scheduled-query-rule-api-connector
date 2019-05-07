# ![LOGO](logo.png) Microsoft Insights **flow**ground Connector

## Description

A generated **flow**ground connector for the Microsoft Insights API (version 2018-04-16).

Generated from: https://api.apis.guru/v2/specs/azure.com/monitor-scheduledQueryRule_API/2018-04-16/swagger.json<br/>
Generated at: 2019-05-07T17:38:28+03:00

## API Description

Azure Monitor client to create/update/delete Scheduled Query Rules

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### List the Log Search rules within a subscription group.

*Tags:* `scheduledQueryRules`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `$filter` - _optional_ - The filter to apply on the operation. For more information please see https://msdn.microsoft.com/en-us/library/azure/dn931934.aspx
* `subscriptionId` - _required_ - The Azure subscription Id.

### List the Log Search rules within a resource group.

*Tags:* `scheduledQueryRules`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `api-version` - _required_ - Client Api Version.
* `$filter` - _optional_ - The filter to apply on the operation. For more information please see https://msdn.microsoft.com/en-us/library/azure/dn931934.aspx
* `subscriptionId` - _required_ - The Azure subscription Id.

### Deletes a Log Search rule

*Tags:* `scheduledQueryRules`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `ruleName` - _required_ - The name of the rule.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription Id.

### Gets an Log Search rule

*Tags:* `scheduledQueryRules`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `ruleName` - _required_ - The name of the rule.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription Id.

### Update log search Rule.

*Tags:* `scheduledQueryRules`

#### Input Parameters
* `subscriptionId` - _required_ - The Azure subscription Id.
* `resourceGroupName` - _required_ - The name of the resource group.
* `ruleName` - _required_ - The name of the rule.
* `api-version` - _required_ - Client Api Version.

### Creates or updates an log search rule.

*Tags:* `scheduledQueryRules`

#### Input Parameters
* `subscriptionId` - _required_ - The Azure subscription Id.
* `resourceGroupName` - _required_ - The name of the resource group.
* `ruleName` - _required_ - The name of the rule.
* `api-version` - _required_ - Client Api Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-monitor-scheduled-query-rule-api-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
