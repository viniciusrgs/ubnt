**Procedimento para conectar  UAC-AP Ubiquiti na controller wifi.**

**Reset default das configurações do UAC-AP**

syswrapper.sh restore-default - reset default 

**Comando para conectar o UAC-AP na controller** 

set-inform http://IP:8080/inform

**Verificar configuraçãoes do UAC-AP**

cat /tmp/running.cfg
