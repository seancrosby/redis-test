# redis-test

## Installation

1. Download latest stable redis server from git@github.com:seancrosby/redis-test.git
2. Unpack tarball
3. build redis by running `make`
4. start redis
  ```bash
$ cd src
$ ./redis-server

  ```
5. `make install` to install to `/usr/local/bin`

## Basic CLI usage

After starting redis...

```bash
$ cd src
$ ./redis-cli
# hit tab after help to see different command groups
> help @generic
> set foo bar
OK
> get foo
"bar"
```

