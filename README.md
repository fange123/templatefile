# templatefile
安装软件VSCODE：
https://code.visualstudio.com/

安装NODEJS：
https://nodejs.org/en/

安装GIT，安装时选择VSCODE作为默认编译器：
https://git-scm.com/download/win

解压代码到任意文件夹，比如 VDOL
打开VSCODE，打开文件夹 VDOL ，点击终端，新建终端，确保终端目录在VDOL内。

先安装 yarn , 执行
npm install -g yarn 

安装完毕执行，第一次如果无法执行脚本，请管理员身份打开Powershell ，执行一下这个命令选择Y回车即可。 set-ExecutionPolicy RemoteSigned
yarn

然后
yarn dev-server

浏览器打开，即可看到网站在本地运行
http://127.0.0.1:8080/

构建编译：
yarn build

编译后只需要上传BUILD 文件夹的内容到服务器即可访问。
