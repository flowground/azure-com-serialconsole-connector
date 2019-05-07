# ![LOGO](logo.png) MicrosoftSerialConsoleClient **flow**ground Connector

## Description

A generated **flow**ground connector for the MicrosoftSerialConsoleClient API (version 2018-05-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/serialconsole/2018-05-01/swagger.json<br/>
Generated at: 2019-05-07T17:38:56+03:00

## API Description

Azure Virtual Machine Serial Console allows you to access serial console of a Virtual Machine

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Gets if Serial Console is disabled for a subscription.

*Tags:* `ConsoleDisabled`

#### Input Parameters
* `api-version` - _required_ - The API version to use for this operation.
* `subscriptionId` - _required_ - The ID of the target subscription.
* `default` - _required_ - Default string modeled as parameter for URL to work correctly.
    Possible values: default.

### Disables Serial Console for a subscription

*Tags:* `DisableConsole`

#### Input Parameters
* `api-version` - _required_ - The API version to use for this operation.
* `subscriptionId` - _required_ - The ID of the target subscription.
* `default` - _required_ - Default string modeled as parameter for URL to work correctly.
    Possible values: default.

### Enables Serial Console for a subscription

*Tags:* `EnableConsole`

#### Input Parameters
* `api-version` - _required_ - The API version to use for this operation.
* `subscriptionId` - _required_ - The ID of the target subscription.
* `default` - _required_ - Default string modeled as parameter for URL to work correctly.
    Possible values: default.

### Gets a list of Serial Console API operations.

*Tags:* `SerialConsole`

#### Input Parameters
* `api-version` - _required_ - The API version to use for this operation.
* `subscriptionId` - _required_ - The ID of the target subscription.

## License

**flow**ground :- Telekom iPaaS / azure-com-serialconsole-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
