# wifi_ssid

Show the SSID of your current wifi and the strength of your wifi connection.
If no instance is specified, wlan0 is used.

This work is based on the "ssid" script from i3blocks and the "wifi" script from i3blocks-contrib.

![](wifi_ssid.png)

# Config

```
[wifi]
command=$SCRIPT_DIR/wifi_ssid
label=
#instance=wlp3s0
interval=60
```
