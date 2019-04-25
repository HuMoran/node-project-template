# node-project-template
node project template

## 安装node
1. 安装nvm

linux/mac安装
```
wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.34.0/install.sh | bash
source ~/.bashrc
nvm install 10
```
windows安装

从```https://nodejs.org/zh-cn/```下载npm安装包，直接安装


2.安装npm源管理工具nrm
```
npm install -g nrm
```

3.切换淘宝源
```
nrm use taobao
```

## 安装commitizen和conventional-changelog 
```
npm install -g commitizen conventional-changelog-cli

```

## 下载node-project-template仓库代码到本地
## 在本地node-project-template代码处，执行以下命令
```
npm install
```
## 提交git commit消息时，使用```git cz```取代```git commit```
## 自动生成changelog，使用```npm run changelog```
## 发布新版本：
* 修改package.json中的版本号
* 运行`npm run changelog`
* 提交changelog文件到github
* 点击github仓库的releases->Draft a new release->填写版本号，并把changelog.md文件里面当前版本的内容拷贝到版本说明里面->点击发布
