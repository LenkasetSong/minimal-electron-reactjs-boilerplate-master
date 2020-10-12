This repository is a minimal Electron-ReactJS boilerplate. There are two targets: 1) avoid ejecting the ReactJS codes; 2) not include modules you may not need, like Redux and React Router.

After checking out this repository, run ```npm install`` to install all dependencies.

# Run in development mode

1. Make sure ```DEV``` is ```true``` in package.json
2. Open two terminals
3. Run ```npm start``` in one terminal
4. Run ```npm run electron``` in the other terminal

# Run in production mode

1. Make sure ```DEV``` is ```false``` in package.json
2. Run ```npm run build```
3. Run ```npm run electron```

# Make a distributable package
1. Make sure ```DEV``` is ```false``` in package.json
2. Run ```npm run build```
3. Run ```npm run package```

# Dev tool

This template does not open the dev tool on starting. You can press Cmd+Option+I on Mac, or Ctl+Shift+I on Windows to open the dev tool.

# mix tool

1.全局安装 asar
　　npm install asar -g
　　安装完asar以后,就可以使用asar命令将程序文件打包了。
2.在resources目录下使用asar指令进行加密
　　asar pack ./app app.asar  
3.将原来的app文件夹删除  
