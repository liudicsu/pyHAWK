# pyHAWK <img src="logo.png" width="50">
Searches the directory of choice for interesting files. Such as database files and files with passwords stored on them
<img src="demo.png" width="400">

# Features
+ Scans directory for intresting file types
+ Outputs them to the screen
+ Supports many file types 

# Installation Instructions

The installation is easy. Git clone the repo and run go build.

```
git clone https://github.com/MetaChar/pyHAWK
python2 main.py
```


# Usage
To set a Directory use -d or --directory
``` 
python2 main.py -d <directory>
```

# File Extensions
### Cryptography
+ .pem
+ .pkcs12
+ .p12
+ .pfx
+ .asc
+ .jks
+ .keychain

### Password Files
+ .agilekeychain
+ .kwallet
+ .bek
+ .tpm
+ .psafe3

### Database Files
+ .sdf
+ .sqlite
+ .fve
+ .pcap
+ .gnucash
+ .dayone
+ .mdf

### Misc Files
+ .log

### Config Files
+ .cscfg
+ .rdp
+ .tblk
+ .ovpn

# File Names
### Password Files
+ credentials.xml
+ robomongo.json
+ filezilla.xml
+ recentservers.xml
+ ventrilo_srv.ini
+ terraform.tfvars
+ secret_token.rb
+ carrierwave.rb
+ omniauth.rb
+ settings.py
+ database.yml

### Database Files
+ journal.txt
+ Favorites.plist

### Misc Files
+ root.txt
+ users.txt
+ passwords.txt
+ login.txt

### Config Files
+ jenkins.plugins.publish_over_ssh.BapSshPublisherPlugin.xml
+ LocalSettings.php
+ configuration.user.xpl
+ knife.rb


#### Insperation
Inspired by ice3man543 check it out here : https://github.com/Ice3man543/hawkeye
