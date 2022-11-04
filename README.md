# maas-rocky8-fix
Ubuntu MAAS Rocky 8 Fix 
Since Rocky is a fork of CentOS, copy **/etc/maas/preseeds/curtin_userdata_centos** to  **/etc/maas/preseeds/curtin_userdata_rocky**
Make a backup of **/usr/lib/python3/dist-packages/curtin/distro.py** in the same directory and overwrite with the updated file in the guthub repo. 

You should be able to successfully boot the machine. 
