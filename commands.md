#####the method to disable supsend when closing the lid of laptop 
1. sudo vim /etc/systemd/logind
#HandleLidSwitch=suspend --> HandlelidSwitch=ignore
2. service systemd-logind restart
