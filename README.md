Use this project to install an elasticsearch in your dokku install. We assume dokku is at 127.0.0.1.nip.io

Pre-requisites
==============
Dokku installed- https://github.com/dokku/dokku

Installing
==========
```
git clone git@github.com:sglebs/elasticsearch.git
cd elasticsearch
git remote add dokku dokku@127.0.0.1.nip.io:elasticsearch
git push dokku
```

Using
======
It is best to try it with our kibana project.