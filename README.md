# erx-shadowsocks-libev
GFWList Mode

## How to use:
* Copy all files to your EdgeRouter X.
* Edit "/config/shadowsocks/conf/shadowsocks.json".
* If you dont want to use KCPTUN, rename "kcptun.json" under "/config/shadowsocks/conf" to "kcptun.json.disable". Otherwise edit it also.
* Enable auto start by running "update-rc.d shadowsocks enable".
* Restart your EdgeRouter X.

Enjoy!
