---
title: 'How to connect with Shadowrocket (iOS)'
banner: "https://shadowrocket-app.com/wp-content/uploads/2023/08/Shadowrocket.jpg"
short: "Guide to use Shadowrocket for connecting to Private Server"
description: "Guide to use Shadowrocket for connecting to Private Server"
keyword: "YuukiPS, Shadowrocket, Pirvate Server"
index: true
---

## Info

- Download,Install,Sign it: [Shadowrocket](https://file2.yuuki.me/GD1/Project/GenshinImpact/App/Shadowrocket.ipa) or better [just buy](https://apps.apple.com/us/app/shadowrocket/id932747118?ref=YuukiPS) it, it's much simpler
- For Genshin Impact with version 2.7+ you need a [game patch](/game/genshin-impact) and sign it (Patch version 4.0.0 is now available!)
- For Star Rail, There is no need for game patch. (means we still support this because you need a proxy aka this Shadowrocket)

## How to Sign
0. [Follow instructions for downloading ipa](https://alist.nn.ci/guide/advanced/ipa.html#installation-example)
1. Extract .ipa (in Mac)
2. Sign .app file: `sudo codesign -f -s - Payload/GenshinImpact.app`
3. Compress back to .ipa: `zip -qry Genshin.ipa` Payload

## How run in Mac PC?

You can run any iOS application with [Playcover](https://docs.playcover.io/getting_started/download_playcover)

## Get started with how to use a proxy (Shadowrocket)

### Turn on https decryption

0. If it has been set https, you can skip this step.
1. Open Shadowrocket, click bottom configuration menu item, open the arrow-indicated i icon on the right.
2. Click on https decryption, turn on https decryption, and click on the √ sign above.
3. Click Generate New CA Certificate, wait for a moment, and then there will be a pop-up, click confirm.
4. Click Install Certificate, and click Allow.
5. Return to desktop, open Settings - Downloaded Profiles, and install.
6. Not done yet! Open Settings again - General - About this - Trusted Certificate Repositories - select certificate that was just generated.

### Add module

1. Open Shadowrocket, click bottom configuration menu item, open modules, and select New module.
2. Paste this code, click save.

```RE
!name=YuukiPS
[URL Rewrite]
^https://([\da-z-.]+).hoyoverse.com https://ps.yuuki.me header
^https://([\da-z-.]+).mihoyo.com https://ps.yuuki.me header
^https://([\da-z-.]+).starrails.com https://ps.yuuki.me header
^https://([\da-z-.]+).bhsr.com https://ps.yuuki.me header
^https://hoyoverse.com https://ps.yuuki.me header
^https://mihoyo.com https://ps.yuuki.me header
^https://starrails.com https://ps.yuuki.me header
^https://bhsr.com https://ps.yuuki.me header
[MITM]
hostname = %APPEND% .hoyoverse.com,.mihoyo.com,.starrails.com,.bhsr.com
```

3. Click on settings, select UDP, and turn on "forwarding" option.

### Downloading Resources

Turn on proxy, enter game, enter any account information, and download resources and play it.

