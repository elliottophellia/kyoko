<a href="https://api.rei.my.id/README.id">HOME</a>

# IP Address Lookup

Lihat informasi detail tentang IP address.

<img src="https://img.shields.io/badge/SCHEME-HTTPS-a3be8c?style=flat-square"/> <img src="https://img.shields.io/badge/AUTHENTICATION-NONE-ebcb8b?style=flat-square"/> <img src="https://img.shields.io/badge/LIMITATION-50%20200%20OK%20%2F%201min-88C0D0?style=flat-square"/>

## Get details
Dapatkan detail informasi dari IP address kamu.

| URL | Request Type |
| --- | ------------ |
| `https://ip.rei.my.id/` | `GET`

Dapatkan detail informasi dari spesifik IP address.
| URL | Request Type |
| --- | ------------ |
| `https://ip.rei.my.id/{ip}` | `GET`

<small> _Parameter yang valid adalah IPv4 address._ </small>

## Example
### Request
```shell
curl https://ip.rei.my.id/8.8.8.8
```
### Response
```json
{
    "RequestTimestamp": 1709697452,
    "RequestStatus": "success",
    "RequestCode": 200,
    "RequestResult": {
        "as": "AS15169 Google LLC",
        "asname": "GOOGLE",
        "city": "Ashburn",
        "continent": "North America",
        "continentCode": "NA",
        "country": "United States",
        "countryCode": "US",
        "currency": "USD",
        "district": "",
        "hosting": true,
        "isp": "Google LLC",
        "lat": 39.03,
        "lon": -77.5,
        "mobile": false,
        "offset": -18000,
        "org": "Google Public DNS",
        "proxy": false,
        "query": "8.8.8.8",
        "region": "VA",
        "regionName": "Virginia",
        "status": "success",
        "timezone": "America/New_York",
        "zip": "20149"
    }
}
```
