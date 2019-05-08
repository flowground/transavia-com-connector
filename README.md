# ![LOGO](logo.png) Airports API v2 **flow**ground Connector

## Description

A generated **flow**ground connector for the Airports API v2 API (version 1.0).

Generated from: https://api.apis.guru/v2/specs/transavia.com/1.0/swagger.json<br/>
Generated at: 2019-05-07T17:44:26+03:00

## API Description

Returns all airports

## Authorization

Supported authorization schemes:
- API Key- API Key
## Actions

### All airports

> Retrieve all airports.

### Airport(s) by country code.

> Retrieve airports by country code.

#### Input Parameters
* `countryCode` - _required_ - Comma-separated list of country codes (2-character ISO 3166-1). More than 3 country codes is not allowed.

### Nearest airport(s) by geo coordinates.

> Retrieve nearest airports by geo coordinates (latitude/longitude).

#### Input Parameters
* `latitude` - _optional_ - Latitude in decimals, lower than -90.0 and higher than 90.0 is not allowed.
* `longitude` - _optional_ - Longitude in decimals, lower than -180.0 and higher than 180.0 is not allowed.
* `maxDistanceInKm` - _optional_ - Maximum distance in kilometers, lower than 1 and higher than 500 is not allowed. If not set, max value is applied.
* `limit` - _optional_ - Limits the result, lower than 0 is not allowed. If not set, the result is not limited.

### Nearest airport(s) by airport id.

> Retrieve nearest airports by station id.

#### Input Parameters
* `id` - _required_ - Airport (IATA code) to search nearest airports for.
* `maxDistanceInKm` - _optional_ - Maximum distance in kilometers, lower than 1 and higher than 500 is not allowed. If not set, max value is applied.
* `limit` - _optional_ - Limits the result, lower than 0 is not allowed. If not set, the result is not limited.

### Airport by id.

> Retrieve airport by id.

#### Input Parameters
* `id` - _required_ - Airport code (3-character IATA code).

## License

**flow**ground :- Telekom iPaaS / transavia-com-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
