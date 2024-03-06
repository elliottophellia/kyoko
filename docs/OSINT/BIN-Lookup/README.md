# BIN Lookup

Lookup details information about a BIN number.

<img src="https://img.shields.io/badge/SCHEME-HTTPS-a3be8c?style=flat-square"/> <img src="https://img.shields.io/badge/AUTHENTICATION-NONE-ebcb8b?style=flat-square"/>

## Get details
Recieve details from your BIN number.

| URL | Request Type |
| --- | ------------ |
| `https://bin.rei.my.id/{bin}` | `GET`
<small> _Valid parameter are numeric value that corresponds to a specific bank or financial institution._ </small>

## Example
### Request
```shell
curl https://bin.rei.my.id/45717360
```
### Response
```json
{
    "RequestTimestamp": 1709703659,
    "RequestStatus": "success",
    "RequestCode": 200,
    "RequestResult": {
        "bank": "TELLER A/S",
        "bin": "457173",
        "country": "DK",
        "level": "DANKORT CO-BRANDED CARD",
        "type": "DEBIT",
        "vendor": "VISA"
    }
}
```
