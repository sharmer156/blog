# blog
something about blog

Microsoft Windows [版本 10.0.16299.371]
(c) 2017 Microsoft Corporation。保留所有权利。
# 下载相应版本的Node.js

https://nodejs.org/en/download/
**LTS Version和Current Version 两个版本（两个版本的区别是？)**

![](https://i.imgur.com/9yFz641.jpg“”)

----------

# hexo配置
-  ##  1.用NPM安装hexo ##

```shell
npm install hexo-cli -g 
``` 

C:\Users\chz>npm install hexo-cli -g
C:\Users\chz\AppData\Roaming\npm\hexo -> C:\Users\chz\AppData\Roaming\npm\node_modules\hexo-cli\bin\hexo
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@1.2.3 (node_modules\hexo-cli\node_modules\fsevents):
npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@1.2.3: wanted {"os":"darwin","arch":"any"} (current: {"os":"win32","arch":"x64"})

-  ## 2.初始化hexo blog文件 ##

```shell
hexo init blog  
```

C:\Users\chz>mkdir blog

C:\Users\chz>cd blog

C:\Users\chz\blog>hexo init
INFO  Cloning hexo-starter to ~\blog
'git' 不是内部或外部命令，也不是可运行的程序
或批处理文件。
WARN  git clone failed. Copying data instead
INFO  Install dependencies
��Ϣ: ���ṩ��ģʽ�޷��ҵ��ļ���
npm WARN deprecated titlecase@1.1.2: no longer maintained

> nunjucks@3.1.2 postinstall C:\Users\chz\blog\node_modules\nunjucks
> node postinstall-build.js src

npm notice created a lockfile as package-lock.json. You should commit this file.
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@1.2.3 (node_modules\fsevents):
npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@1.2.3: wanted {"os":"darwin","arch":"any"} (current: {"os":"win32","arch":"x64"})

added 276 packages in 17.859s
INFO  Start blogging with Hexo!

C:\Users\chz\blog>hexo init [destination]
INFO  Cloning hexo-starter to ~\blog\[destination]
'git' 不是内部或外部命令，也不是可运行的程序
或批处理文件。
WARN  git clone failed. Copying data instead
INFO  Install dependencies
��Ϣ: ���ṩ��ģʽ�޷��ҵ��ļ���
npm WARN deprecated titlecase@1.1.2: no longer maintained

> nunjucks@3.1.2 postinstall C:\Users\chz\blog\[destination]\node_modules\nunjucks
> node postinstall-build.js src

npm notice created a lockfile as package-lock.json. You should commit this file.
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@1.2.3 (node_modules\fsevents):
npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@1.2.3: wanted {"os":"darwin","arch":"any"} (current: {"os":"win32","arch":"x64"})

added 276 packages in 11.962s
INFO  Start blogging with Hexo!



-  ## 3.启动hexo blog服务 ##

```shell
hexo server 
```

C:\Users\chz\blog\destination>hexo server
INFO  Start processing
INFO  Hexo is running at http://localhost:4000/. Press Ctrl+C to stop.
