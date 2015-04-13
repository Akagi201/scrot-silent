# scrot-silent

`scrot --silent` screenshot without annoying beeping.

## Apply patches
* `patch -p1 < 08_fix-beeping.patch`

## Compile

* Depend on giblib, install it first.

````
$ ./configure
$ make
$ su -c "make install"
```

* (Red hat users, use $ ./configure --prefix=/usr)
