# mynvm

```
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.1/install.sh|bash

```

add `export NVM_NODEJS_ORG_MIRROR=https://npm.taobao.org/mirrors/node` before `export NVM_DIR="$HOME/.nvm"` in `.bashrc`

```
nvm ls-remote 
nvm install v7.10
nvm ls
nvm use v7.10
```

# npm change registry

```
npm config set registry https://registry.npm.taobao.org
npm config get registry
```
