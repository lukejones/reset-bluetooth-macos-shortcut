# Shortcut to reset bluetooth on macOS

If you are experiencing bluetooth lag such as slow or jerky input on your devices, resetting the bluetooth chip in your mac might resolve the issue. 

The shortcut simply runs a shell script to reset the bluetooth device in your mac: `sudo pkill bluetoothd`, you can run that command instead in Terminal if you are more comfortable doing so.

## Installation & Use

First, download the Reset Bluetooth zip file and extra it anywhere on your computer. To install the shortcut, double-click the extracted .shortcut folder and press the blue 'add shortcut' button.

![installation-use-01](https://github.com/user-attachments/assets/493ffa46-05e7-42c9-a854-cfff2b80ba3d)

Once installed, quickly use the shortcut by clicking the Shortcut icon in your menu bar and hitting 'Reset Bluetooth'. All bluetooth devices will briefly disconnect before reconecting.

![installation-use-02](https://github.com/user-attachments/assets/29b97fc2-eb80-4fc3-b3cb-abdb46eecdaa)


---

This has helped me fix the lag that appears on my Logitech MX Master 3S / MX Master Keys in the past.
