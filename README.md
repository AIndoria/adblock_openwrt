# adblock_openwrt
A simple adblocker script for OpenWRT Routers. Blocks ads on every single device on your Wi-Fi network.

<H3>USAGE DETAILS</H3>

Assuming that you have OpenWRT installed on your router. Switch to any directory, except /tmp/

  <code>cd /root/</code><br>
  <code>curl -O -L https://raw.githubusercontent.com/AIndoria/adblock_openwrt/master/adblock.sh</code>
  
Make the file executable<br>
  <code>chmod +x adblock.sh</code>
  
Run it<br>
  <code>./adblock.sh</code>

Wait a while, you should be dropped back to the root prompt again after a while depending on your internet speed. Success! You can double check that this got installed <code>chrontab -l</code> command at prompt.

Q: Hey, so what's different than TableSpoon's script?
<br>
A: This consolidates all the hostfiles used for adblocking in one file, clears redundancies, and automatically updates them periodically.
