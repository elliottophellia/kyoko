# Waifu Generator

Generate huge variety of waifu images for you!

<img src="https://img.shields.io/badge/SCHEME-HTTPS-a3be8c?style=flat-square"/> <img src="https://img.shields.io/badge/AUTHENTICATION-NONE-ebcb8b?style=flat-square"/>

## Categories

| SFW | NSFW |
| --- | --- |
| `waifu` | `waifu` |
| `neko` | `neko` |
| `shinobu` | `trap` |
| `megumin` | `blowjob` |
| `bully` |
| `cuddle` |
| `cry` |
| `hug` |
| `awoo` |
| `kiss` |
| `lick` |
| `pat` |
| `smug` |
| `bonk` |
| `yeet` |
| `blush` |
| `smile` |
| `wave` |
| `highfive` |
| `handhold` |
| `nom` |
| `bite` |
| `glomp` |
| `slap` |
| `kill` |
| `punch` |
| `kick` |
| `happy` |
| `wink` |
| `poke` |
| `dance` |
| `cringe` |

## Get image
Recieve image url from your endpoint of choice.

| URL | Request Type |
| --- | ------------ |
| `https://waifu.rei.my.id/{type}/{category}` | `GET`
<small> _Valid types are sfw and nsfw._ </small>

## Example
### Request
```shell
curl https://waifu.rei.my.id/nsfw/trap
```
### Response
```json
{
    "RequestTimestamp":1709703055,
    "RequestStatus":"success",
    "RequestCode":200,
    "RequestResult":{
        "url":"https://i.rei.my.id/QvOUXvM.jpg"
    }
}
```