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
- For Genshin Impact with version 2.7+ you need a game patch and Sign it (meaning it is currently not supported because we don't have a patched version)
- For Star Rail, There is no need for game patch. (means we still support this because you need a proxy aka this Shadowrocket)

## Getting Started

### Turn on https decryption

0. If it has been set https, you can skip this step.
1. Open Shadowrocket, click bottom configuration menu item, open the arrow-indicated i icon on the right.
2. Click on https decryption, turn on https decryption, and click on the √ sign above.
3. Click Generate New CA Certificate, wait for a moment, and then there will be a pop-up, click confirm.
4. Click Install Certificate, and click Allow.
5. Return to the desktop, open Settings - Downloaded Profiles, and install.
6. Not done yet! Open Settings again - General - About this Mac - Trusted Certificate Repositories - select the certificate that was just generated.

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

