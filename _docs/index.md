---
title: Welcome
permalink: /docs/home/
redirect_from: /docs/index.html
---

Under construction.  See [xataface.com](http://xataface.com/wiki)

# Quick Start

## Using CLI Tool

(Requires [NodeJS](https://nodejs.org) to be installed)

~~~~
sudo npm install -g xataface
xataface create /var/www/html/helloworld
~~~~

Follow the prompts to create your first app:

~~~~
Database 'helloworld' doesn't exist.  Create it? (Y/n)[Y]:
User `helloworld@localhost` does not exist.  Create it? (Y/n)[Y]:
Creating user helloworld at localhost with password dagjx_sQtn8zsg
Granting ALL privileges on database helloworld to helloworld @ localhost
Installing xataface at helloworld/xataface
/Users/shannah/.xataface/src/master.zip
Copying files from helloworld/xataface/site_skeleton to helloworld
~~~~

This example would have created the following:

1. Application at `/var/www/html/helloworld`
2. A database named "helloworld"
3. A user with permissions on the "helloworld" database named "helloworld", allowed to connect from localhost.
