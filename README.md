# artwork-uploader

Wherein lies a microservice that uploads files to S3, given to it by URLs. It is
simple to configure and easy to use, and strives to just work.

## Install

You can install it by issuing `go get github.com/hellerve/artwork-uploader`.

## Configure

The binary needs a configuration file to work. By default, thumbnailer searches
for a file named `./etc/artwork-uploader/server.conf`, but this can be changed by
supplying the `-config` flag.

The configuration can be in one of four directories, namely:

```
./<name>
/<name>
./<name>.local.conf (the first .conf will be replaced)
/<name>.local.conf  (same here)
```

It can also be split up, in which case all matching files will be merged, in
the precedence order above.

## Test

TODO!!

<hr/>

Have fun!
