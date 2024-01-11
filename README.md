# mount-smb-drive

## install cifs-utils
```
sudo apt install cifs-utils
sudo apt-get update
sudo apt-get upgrade
```

## Mount Command
```
sudo mount -t cifs -o user=<username>,pass=<password>,vers=3.0 //<drive-address>/<file dir> <localshare dir>
```

### example
```
sudo mount -t cifs -o user=coder,pass=coder123,vers=3.0 //125.177.192.234/code-server /mnt/z
```
