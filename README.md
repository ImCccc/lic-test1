1. 初始化 package.json
   npm init

2. 安装 eslint
   yarn add eslint -D

3. 初始化 eslint
   npx eslint --init

4. 新建文件夹 bin,添加 www 文件:
   #!/usr/bin/env node
   require("../src/index.js");
   第一行的意思是使用 nodejs 执行

5. 解释用户的参数
   yarn add commander -D

```
   6. "__dirname": 当前文件的绝对路径
   例子: C:\Users\licr1\Desktop\bb\src\
```

下载线上的 git: download-git-repo
https://www.npmjs.com/package/download-git-repo
