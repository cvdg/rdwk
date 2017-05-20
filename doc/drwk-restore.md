# Restore


Restore is only possible if you have the secret part of the GPG key which
was used for encrypting the archive.

If you don't have the secret GPG key, I wish you good luck!



```
cd ~/tmp
$ gpg2 -d /var/opt/rdwk/dat/lina0017872-20170520-1.cpio.gpg | cpio -i -v -d

You need a passphrase to unlock the secret key for
user: "Cees van de Griend (Backup 2017) <c.vande.griend@gmail.com>"
2048-bit RSA key, ID C938EA08, created 2017-05-15 (main key ID 5ABEDEF7)

gpg: encrypted with 2048-bit RSA key, ID C938EA08, created 2017-05-15
      "Cees van de Griend (Backup 2017) <c.vande.griend@gmail.com>"
lina0017872/home/cvdg/.bashrc
1 block
```
