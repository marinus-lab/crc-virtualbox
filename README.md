# crc-virtualbox
Descrizione di come attivare un lab Openshift 4.2 con CodeReady e Virtualbox

https://mirror.openshift.com/pub/openshift-v4/clients/crc/1.2.0/

https://mirror.openshift.com/pub/openshift-v4/clients/crc/1.2.0/crc_virtualbox_4.2.8.crcbundle

Decomprimere crcbundle

unzip
scaricare pull-secret dal sito redhat:  https://cloud.redhat.com/openshift/install/crc/installer-provisioned



crc setup --vm-driver virtualbox
crc start --vm-driver virtualbox --bundle C:\Users\David.crc\crc_hyperv_4.1.11.crcbundle --pull-secret-file .\Downloads\pull-secret.txt


