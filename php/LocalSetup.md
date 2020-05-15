# PHP Setup Commands

## Mac

### Install specific verion
Example: `brew install php@7.2`

### Switch between versions
Example:
```
brew unlink php@7.3 
brew link [--force | -f] php@7.2
```

### Configure XCode
`pecl install xcode`
To verify installation, run: `ls /usr/local/lib/php/pecl/201*/`
Open php.ini
Locate/insert into [xdebug] block:
```
[xdebug]  
zend_extension="<path to xdebug extension>"  
xdebug.remote_enable=1  // enables remote connections
xdebug.remote_port="<port number>" (Optional: default is 9000)
```

