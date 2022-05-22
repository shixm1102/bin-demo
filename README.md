# 学习package.json中bin的用法

1. mkdir bin-demo
2. npm init -y
3. mkdir bin
4. cd bin/ && 创建 index.js
5. 在package.json中添加bin, "bin": { "shixm": "./bin/index.js" },
# 发包
1. npm login 
2. npm publish, 当你的包名为@your-name/your-package时 npm publish --access public
**执行 pulish 时，需要注意，package.json中的版本号，要高于线上版本号**

