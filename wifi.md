# Connect to a wifi network
```sh
$ sudo vim /etc/wpa_supplicant/wpa_supplicant.conf

```

And add the following:
```sh
network={
    ssid="myssid"
    psk="mypasskey"
    key_mgmt=WPA-PSK
}
```
