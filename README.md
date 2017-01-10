# ceph-cp
Ceph S3 compatible file copy script

### Dowbload and start
```shell
$ curl https://raw.githubusercontent.com/samejack/ceph-cp/master/ceph-cp > ./ceph-cp && chmod +x ./ceph-cp
```

### Usage
#### Initial configuration first (save Ceph key and secret to ~/.ceph-cp.conf file)
```shell
$ ./chpe-cp
```

#### Upload file to Ceph Service Bucket
```shell
$ ./ceph-cp [filename] [remote path]@[bucket]
```

#### Download file from Ceph Service Bucket
```shell
$ ./ceph-cp [remote path]@[bucket] [filename]
```
### License

Apache License Version 2.0
