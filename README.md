# dokku bash

Provides remote access to dokku user's bash shell.

## installation

```shell
dokku plugin:install https://github.com/mak-it/dokku-bash.git bash
```

## commands

```
bash    Spawn bash shell
```

## usage

```shell
me@localhost $ ssh -t dokku@<host> -- bash
dokku@<host> $
```
