Ubuntu
dmesg
sudo dmesg --clear

sudo cat /var/log/kern.log | grep usb
sudo rm -rf /var/log/kern*
#old log files
sudo zcat /var/log/kern.log.2.gz | grep usb

sudo cat /var/log/syslog | grep usb
sudo rm -rf /var/log/syslog*

cat /dev/null > ~/.bash_history && history -c
