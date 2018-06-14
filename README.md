Virtualhost Manage Script
===========

Bash Script to allow create or delete apache/nginx virtual hosts on Ubuntu on a quick way.

## Installation ##

1. Download the script
2. Apply permission to execute:

```
$ chmod +x /path/to/virtualhost.sh
```

3. Optional: if you want to use the script globally, then you need to copy the file to your /usr/local/bin directory, is better
if you copy it without the .sh extension:

```bash
$ sudo cp /path/to/virtualhost.sh /usr/local/bin/virtualhost
```

### For Global Shortcut ###

```bash
$ cd /usr/local/bin
$ wget -O virtualhost https://raw.githubusercontent.com/RoverWire/virtualhost/master/virtualhost.sh
$ chmod +x virtualhost
$ wget -O virtualhost-nginx https://raw.githubusercontent.com/RoverWire/virtualhost/master/virtualhost-nginx.sh
$ chmod +x virtualhost-nginx
```

## Usage ##

Basic command line syntax:

```bash
$ sudo sh /path/to/virtualhost.sh [create | delete] [domain] [optional host_dir]
```

With script installed on /usr/local/bin

```bash
$ sudo changephpversion [php_version]
```

### Examples ###

to change PHP version:

```bash
$ sudo changephpversion 5.6
```

### Instalation

As sudo:

```
$ cd /usr/local/bin; wget -O changephpversion https://raw.githubusercontent.com/tiagosampaiotoogas/changephpversion/master/changephpversion; chmod +x changephpversion
```
### Localization
