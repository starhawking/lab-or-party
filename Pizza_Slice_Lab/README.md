# Notes for the Pizza Slice Lab

# Fix for SSH'ing to the iLO
Unfortunately, the iLO2 uses an incredibly old version of SSH, I found the following workaround from the [HPE Community Site](https://community.hpe.com/t5/Remote-Lights-Out-Mgmt-iLO-2-iLO/Unable-to-SSH-to-iLO2-with-OpenSSH-6-2/td-p/6050925):
```
ssh -o HostKeyAlgorithms=ssh-rsa,ssh-dss \
  -o KexAlgorithms=diffie-hellman-group1-sha1 \
  -o Ciphers=aes128-cbc,3des-cbc \
  -o MACs=hmac-md5,hmac-sha1 \
  Administrator@Pizza
```

