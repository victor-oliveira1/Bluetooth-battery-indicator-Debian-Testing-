# Bluetooth-battery-indicator-Debian-Testing-
Build of pulseaudio-module-bluetooth with bluetooth battery indicator (Only for Debian Testing!)

Just install the pulseaudio modules provided here and edit the bluetooth.service like this:  
`from: ExecStart=/usr/libexec/bluetooth/bluetoothd`  
`to: ExecStart=/usr/libexec/bluetooth/bluetoothd -E`
