PeerJS server plugin for Dokku
============================================

Project: https://github.com/progrium/dokku

Requirements
------------
* dokku-link plugin (https://github.com/rlaneve/dokku-link)

Instalation
-----------
```
cd /var/lib/dokku/plugins
git clone https://github.com/lmb/dokku-peerjs-plugin.git peerjs
dokku plugins-install
```

Commands
--------
```
$ dokku help    
    rabbitmq:create <app>                         Create a rabbitmq virtual host/user
    rabbitmq:delete <app>                         Delete specified rabbitmq vhost/user
    rabbitmq:rebuild <app>                        Rebuild specified rabbitmq vhost/user
    rabbitmq:start                                Start the rabbitmq docker container if it isn't running
    rabbitmq:stop                                 Stop the rabbitmq docker container
    rabbitmq:status                               Shows status of rabbitmq
    rabbitmq:list                                 List all virtual hosts
```


Thanks
------
This is partially based on the dokku-postgresql-plugin: https://github.com/jeffutter/dokku-postgresql-plugin and the dokku-rabbitmq-single-plugin
