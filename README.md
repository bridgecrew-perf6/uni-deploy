# uni-deploy

Makefile and scripts for simply and uni dev-ops, current include go, docker

## requirements

>**choose needed to install**

- **platform** `MacOS/Linux`
- [bash](https://www.gnu.org/software/bash/) **5.0+**
- [git](https://git-scm.com/) _2.34.1+_
- [make](https://www.gnu.org/software/make/) _3.81+_

### docker requirements

- [docker](https://github.com/docker) **20.10.5+**
- [docker-compose](https://github.com/docker/compose) _maybe_ **2.2.2+**

### go requirements

- [upx](https://github.com/upx/upx)
- [go](https://github.com/golang/go) **go1.17+**
- [binary version](https://github.com/xwi88/version) **for `-ldflags`**

## quick install

>quick install, only support standard project root dir, by `install.sh`, default branch `release`

- `curl -s -L https://raw.githubusercontent.com/v8fg/uni-deploy/release/installer.sh | bash`
- `wget -qO- https://raw.githubusercontent.com/v8fg/uni-deploy/release/installer.sh | bash`

## standard install and other ops

>**better clone into your project root dir**

- `git clone https://github.com/v8fg/uni-deploy.git -b <branch> [path]`
- `bash make.sh`

>more usage: `bash make.sh help`
