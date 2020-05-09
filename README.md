## Network Interface Renaming

UDEV will match MAC `ATTR{address}=="00:00:00:00:00:00:"` and assign name `NAME=""`
SUBSYSTEM=="net", ACTION=="add", ATTR{address}=="00:00:00:00:00:00", NAME="wlan0"

