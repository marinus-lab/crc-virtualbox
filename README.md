# crc-virtualbox
Descrizione di come attivare un lab Openshift 4.2 con CodeReady e Virtualbox

Scaricare :

https://mirror.openshift.com/pub/openshift-v4/clients/oc/latest/windows/oc.zip

https://mirror.openshift.com/pub/openshift-v4/clients/crc/1.2.0/crc-windows-amd64.zip

https://mirror.openshift.com/pub/openshift-v4/clients/crc/1.2.0/crc_virtualbox_4.2.8.crcbundle

Il crcbundle scarica un file .man  che e' un file compresso che 7Zip puo' decomprimere

Decomprimere crcbundle

unzip crc-windows

scaricare pull-secret dal sito redhat:  https://cloud.redhat.com/openshift/install/crc/installer-provisioned

crc start --vm-driver virtualbox --bundle C:\Users\David.crc\crc_hyperv_4.1.11.crcbundle --pull-secret-file .\Downloads\pull-secret.txt


