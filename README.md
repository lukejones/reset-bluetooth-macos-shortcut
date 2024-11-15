# Shortcut to reset bluetooth on macOS

If you are experiencing bluetooth lag such as slow or jerky input on your devices, resetting the bluetooth chip in your mac might fix the issue. 

The shortcut simply runs a shell script to reset the bluetooth device in your mac: `sudo pkill bluetoothd`.

## Installation & Use

Download [ResetBluetooth.zip](https://github.com/lukejones/reset-bluetooth-macos-shortcut/blob/main/ResetBluetooth.zip) and extract it anywhere on your mac. Install the shortcut by double-click the file and pressing 'Add Shortcut'.

![installation-use-01](https://github.com/user-attachments/assets/493ffa46-05e7-42c9-a854-cfff2b80ba3d)

Once installed, use the shortcut by clicking the Shortcut icon in your menu bar and hitting 'Reset Bluetooth'.

![CleanShot 2024-11-15 at 09 54 39@2x](https://github.com/user-attachments/assets/3c6b79c8-8db8-48a1-8462-909633177207)

All bluetooth devices will briefly disconnect before reconecting.

---

This has helped me fix the lag that appears on my Logitech MX Master 3S / MX Master Keys [in the past](https://gist.github.com/lukejones/5de7e60295753477ea4e9ca62053cf6f).
