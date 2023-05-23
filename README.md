# firewall
firewall-cmd --permanent --zone=external --add-rich-rule='rule family=ipv4 source address=0.0.0.0/0 forward-port port=443 protocol=tcp to-port=443 to-addr=192.168.100.100'
