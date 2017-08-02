# adblock_openwrt
A simple adblocker script for OpenWRT Routers. Blocks ads on every single device on your Wi-Fi network.

USAGE DETAILS

Assuming that you have OpenWRT installed on your router. Switch to any directory, except /tmp/

  cd /root/
  curl -O -L https://raw.githubusercontent.com/AIndoria/adblock_openwrt/master/adblock.sh
  
Make the file executable
  chmod +x adblock.sh
  
Run it
  ./adblock.sh

Wait a while, you should be dropped back to the root prompt again after a while depending on your internet speed. Success! You can double check that this got installed <code>chrontab -l</code> command at prompt.
