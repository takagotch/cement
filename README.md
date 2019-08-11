### cement
---
https://builtoncement.com/
https://github.com/datafolklabs/cement

```
```

```sh
make dev
docker-compose up -d
docker-compose exec /bin/ash
make virtualenv
source env/bin/activate
vagrant status
vagrant up linux
vagrant ssh linux
cd /vagrant
bash scripts/vagrant/bootstrap.sh
make virtualenv
source env/bin/activate
make clean
vagrant up windows
powershell.exe scripts\vagrant\bootstrap.ps1
make virtualenv-windows
.\env-windows\Scripts\activate.ps1
make test-core
make test


```

```
```


