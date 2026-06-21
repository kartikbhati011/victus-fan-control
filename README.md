# Victus-Fan-Control

## Victus fan control extension

A native, lightweight KDE Plasma and Gnome extension for Victus laptops running Linux. let you switch between **Auto** and **Max** Fan modes directly from your taskbar—without ever opening a terminal or typing a password.



### Step 1: Force Fan Control Support

```
sudo modprobe hp_wmi force_fan_control_support=true
```
### Step 2 : Let's check if the `fan1_input` and `fan2_input` files appeared
```
ls -l /sys/devices/platform/hp-wmi/hwmon/hwmon*/
```

If these files appeared then you are good to go.
