# baiduwp

PanDownload Web, built with CloudFlare Workers

# Features

Latest version already implemented all features of baiduwp.com.

## Features from baiduwp.com

Get Direct Link

Parse share link from url 

Example: https://pan.example.com/s/1qWsJVJ2 -> https://your.site/s/1qWsJVJ2

Send to aria2c

## New Features

Get Direct Link from rapid link

Video / Audio Preview

HTTP Basic authentication (Thanks to [ccloli](https://github.com/ccloli))

## WIP

Rewrite

Add i18n support

PC / Android Client

# Usage

```javascript
const BDUSS = '' //**INPUT YOUR BDUSS HERE**
const STOKEN = '' //**INPUT YOUR STOKEN HERE**
const SVIPBDUSS = '' //**INPUT YOUR SVIP BDUSS HERE**
const SVIPSTOKEN = '' //**INPUT YOUR SVIP STOKEN HERE** (optional, rapid need)
const INDEX_URL = '' // Input your index url here
const AUTH_USER = '' //**INPUT BASIC AUTH USERNAME (optional)**
const AUTH_PASS = '' //**INPUT BASIC AUTH SUPER SECRET PASSWORD (optional)**
```

or comment out those then use environment variables in workers settings

# Thanks

[PanDownload](https://pandownload.com): static pages

[acgotaku/BaiduExporter](https://github.com/acgotaku/BaiduExporter): send to aria2

[MoePlayer/DPlayer](https://github.com/MoePlayer/DPlayer): video & audio preview
