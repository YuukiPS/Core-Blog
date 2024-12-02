---
title: 'How to connect with Fiddler (PC)'
banner: "https://doc.yuuki.me/assets/images/fiddler-script-3d84d2733fc92036e75c053e780c6fd9.png"
short: "Guide to use Fiddler for connecting to Private Server"
description: "Guide to use Fiddler for connecting to Private Server"
keyword: "YuukiPS, Fiddler, Pirvate Server"
index: true
comment: true
---

## Info

- Download & Install [Fiddler Classic](https://file2.yuuki.me/Local_EU/Project/GenshinImpact/Tool/FiddlerSetup.exe)
- For [Genshin Impact](/game/genshin-impact) with version 2.7+ you need a Game Patch.
- For [Star Rail](/game/star-rail), There is no need for Game Patch.

## Getting started

1. Run Fiddler Classic with administrator
2. Trust the Fiddler Classic Root Certificate. If you did not trust it the proxy won't work. You can set this:

   > Tools -> Options -> HTTPS -> Actions -> Trust Root Certificate -> Toggle Decrypt HTTPS traffic on

3. Paste this to your Fiddler > Script Tab.

   ```cs
   import System;
   import System.Windows.Forms;
   import Fiddler;
   import System.Text.RegularExpressions;
   class Handlers
   {
       static function OnBeforeRequest(oS: Session) {
           if(
               oS.host.EndsWith(".yuanshen.com") ||
               oS.host.EndsWith(".hoyoverse.com") ||
               oS.host.EndsWith(".mihoyo.com") ||
               oS.host.EndsWith(".zenlesszonezero.com") ||
               oS.host.EndsWith(".honkaiimpact3.com") ||
               oS.host.EndsWith(".bhsr.com") ||
               oS.host.EndsWith(".starrails.com") ||
               oS.uriContains("http://overseauspider.yuanshen.com:8888/log")
            ) {
                 oS.host = "ps.yuuki.me";
            }
       }
   };
   ```

4. Save the Script
5. Run game
