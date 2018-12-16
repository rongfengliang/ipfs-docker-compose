# ipfs docker-compose running

## how to run

* start

```code
docker-compose up -d
```

* add file

```code
touch export/index.html
content see  export/index.html
```

* add files to support ipfs address

> inside docker container

```code
ipfs  add -r /export

added QmXhdrziCp16DzWYwQQJHZZmSZxoYwbPV3KaBPkLsDQWRU export/images/WX20181216-220154@2x.png
added QmWSx63vkEauEt4qVhjL13aQ4yrVX6Vs9HKrAL1AjmMvWn export/index.html
added QmWRxU6QBzRKGTYPNkdBjQb49SyyvNS1eaJmxmiQu26TTJ export/images
added QmT2YepbRBL1eLyZevZnYQ6b4MwthVyuHiao8xqhmpyPMd export
```

* access file

```code
http://localhost:8080/ipfs/QmT2YepbRBL1eLyZevZnYQ6b4MwthVyuHiao8xqhmpyPMd
```