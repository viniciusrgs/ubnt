<strong> Procedimentos para conectar UAC-AP Ubiquiti na Controller Wifi.

Reset default AP

syswrapper.sh restore-default - reset default 

Infomar ao UAC-AP o enderamento e porta da controller

set-inform http://IP:8080/inform

Verificar configurações do UAC-AP

cat /tmp/running.cfg
