<a href="https://api.rei.my.id/README.id">HOME</a>

# Waifu Generator

Dapetin banyak jenis gambar waifu untuk kamu!

<img src="https://img.shields.io/badge/SCHEME-HTTPS-a3be8c?style=flat-square"/> <img src="https://img.shields.io/badge/AUTHENTICATION-NONE-ebcb8b?style=flat-square"/> <img src="https://img.shields.io/badge/LIMITATION-50%20200%20OK%20%2F%201min-88C0D0?style=flat-square"/>

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
Dapetin url gambar dari endpoint yang kamu pilih.
| URL | Tipe Request |
| --- | ------------ |
| `https://waifu.rei.my.id/{type}/{category}` | `GET`

<small> _Type yang valid adalah sfw dan nsfw._ </small>

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
