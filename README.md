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


## Unmount drive
```
sudo umount <mount dir>
```

주의!! 명령어가 'unmount'가 아닌, 'umount'가 맞는 표현이다.
