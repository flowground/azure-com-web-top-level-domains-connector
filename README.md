# ![LOGO](logo.png) TopLevelDomains API Client **flow**ground Connector

## Description

A generated **flow**ground connector for the TopLevelDomains API Client API (version 2018-02-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/web-TopLevelDomains/2018-02-01/swagger.json<br/>
Generated at: 2019-05-07T17:39:28+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Get all top-level domains supported for registration.

*Tags:* `TopLevelDomains`

#### Input Parameters
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Get details of a top-level domain.

*Tags:* `TopLevelDomains`

#### Input Parameters
* `name` - _required_ - Name of the top-level domain.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Gets all legal agreements that user needs to accept before purchasing a domain.

*Tags:* `TopLevelDomains`

#### Input Parameters
* `name` - _required_ - Name of the top-level domain.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

## License

**flow**ground :- Telekom iPaaS / azure-com-web-top-level-domains-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
