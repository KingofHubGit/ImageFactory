# ImageFactory
ImageFactory



https://zhuanlan.zhihu.com/p/369836503

```
#安装nodejs和npm
sudo apt-get install nodejs -y
sudo apt-get install npm -y

sudo npm config set registry https://registry.npm.taobao.org # modify npm source
sudo npm config list

sudo npm install npm@latest -g # update npm
sudo npm install -g n          # install n

sudo n latest                  # install latest node and npm

echo ""
echo "#============================== current version ==============================#"
echo "node: `sudo node -v`"    # check node version
echo "npm: `sudo npm -v`"      # check npm version

#安装picgo和相应的插件
sudo npm install picgo -g
sudo picgo install super-prefix
sudo picgo install gitee-uploader
```



```
vim ~/.picgo/config.json

{
  "picBed": {
    "github": {
      "repo": "github用户名/pic-bed",
      "token": "上面获得的令牌",
      "path": "images/",
      "customUrl": "https://cdn.jsdelivr.net/gh/github用户名/pic-bed/",
      "branch": "main"
    },
    "current": "github",
    "uploader": "github"
  },
  "picgoPlugins": {
    "picgo-plugin-gitee-uploader": true,
    "picgo-plugin-super-prefix": true
  },
  "picgo-plugin-super-prefix": {
    "fileFormat": "YYYYMMDDHHmmss"
  }
}
```







![image-20230926111919505](https://github.com/KingofHubGit/ImageFactory/Public/image-20230926111919505.png)



![image-20230926112200085](https://github.com/KingofHubGit/ImageFactory/Public/image-20230926112200085.png)



