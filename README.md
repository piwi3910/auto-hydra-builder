# auto-hydra-builder

## install prereq

* /etc/yum.repos.d/mongodb-org-5.0.repo
```
[mongodb-org-5.0]
name=MongoDB Repository
baseurl=https://repo.mongodb.org/yum/redhat/$releasever/mongodb-org/5.0/x86_64/
gpgcheck=1
enabled=1
gpgkey=https://www.mongodb.org/static/pgp/server-5.0.asc

```

sudo dnf install -y mongodb-org
sudo systemctl start mongod
sudo systemctl enable mongod
