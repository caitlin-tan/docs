# Python

## pip 镜像

`vi ~/.pip/pip.conf`

```txt
[global]
index-url=http://pypi.douban.com/simple/
trusted-host=pypi.douban.com
```

# Node.js

## 淘宝 NPM 镜像

http://npm.taobao.org/mirrors/node


# Homebrew

1. 替换 homebrew-core 源

```
cd "$(brew --repo)/Library/Taps/homebrew/homebrew-core"
git remote set-url origin git://mirrors.ustc.edu.cn/homebrew-core.git
```

2. 替换 Homebrew Bottles 源

```
echo 'export HOMEBREW_BOTTLE_DOMAIN=https://mirrors.ustc.edu.cn/homebrew-bottles' >> ~/.bash_profile
source ~/.bash_profile
```

3. 更新

`brew update`
