# Power BI Collections

Postman collections for Power BI REST APIs, authentication flows, and embedded capacity management.

## What’s included
- `Power BI REST API v1.postman_collection.json`
- `Power BI Embedded Azure Resource Manager REST API v2017-10-01.postman_collection.json`
- `Auth Examples.postman_collection.json`
- `PowerBI Auth.postman_collection.json`
- `PowerBI Auth 2.postman_collection.json`
- `PowerBi.postman_environment.json`

## Details
- Support for admin, dataset, report, gateway, and capacity management endpoints.
- Includes OAuth2 and client credentials examples.
- Environment defines reusable auth variables (`clientid`, `client_secret`, `tokenurl`, etc.).

## Quick start
1. Import the selected collection(s).
2. Import `PowerBi.postman_environment.json`.
3. Set credentials in variables (`username`, `password`, `clientid`, `client_secret`, `authurl`, `tokenurl`, `scope`, `callback`).
4. Run auth request(s) then API request(s).

## Notes
- Use secure vaults for client secrets.
- Validate group/workspace IDs before running management calls.

## Navigation
- [← Back to Repository Root](../README.md)
- [CO2 Signal ←](../CO2%20Signal/README.md)
- [Weather →](../Weather/README.md)
- [WiFi NBI →](../WiFi%20NBI/README.md)
- [Xiaomi →](../Xiaomi/README.md)
