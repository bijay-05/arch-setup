nmcli device status
nmcli radio wifi on
sudo modprobe -r <your_wifi_driver>
sudo modprobe <your_wifi_driver>
journalctl -u NetworkManager
nmcli connection delete <connection_name>
nmcli device wifi list  # Find your Wi-Fi network
nmcli device wifi connect <SSID> password <your_password>
