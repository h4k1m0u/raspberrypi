Following [elinux guide](http://elinux.org/RPiconfig):

```sh
$ sudo vi /boot/config.txt

```

# Enable numeric output
```sh
# Use HDMI mode even if no HDMI monitor is detected
hdmi_force_hotplug=1
```

# DVI mode
```sh
# Normal DVI mode (No sound)
hdmi_drive=1
```
