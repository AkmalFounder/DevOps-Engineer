#### Create new Private and Public key on Host machine (Ex.macOS)
```
$ssh-keygen -t rsa
# Enter location and file name like (/Users/pjadda/.ssh/rsa), do not use default files
#Passphrase is optional
```
#### Create .ssh folder in Guest OS even if it exists
```
$ssh gateway@103.189.234.173 mkdir -p .ssh
```

#### Finally append a's new public key to docker@192.168.64.3:.ssh/authorized_keys
```
$cat .ssh/rsa.pub | ssh gateway@103.189.234.173 'cat >> .ssh/authorized_keys'
```

#### Set permissions on Guest machine (192.168.64.3)
```
$ssh gateway@103.189.234.173 "chmod 700 .ssh; chmod 640 .ssh/authorized_keys"
```

#### Now you can SSH into guest with out password
```
$ssh gateway@103.189.234.173
```