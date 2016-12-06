# 豆瓣电影列表

## 项目结构初始化

- .editorconfig
- README.md
- .gitignore
- bower.json
 + 使用 `bower init` 初始化该文件
- .bowerrc
- package.json
 +使用 `npm init` 初始化该文件

1. 在本地项目安装 `npm install --save http-server`
2. 在 `package.json` 文件中找到 `scripts` 字段，加上一个属性: `start`,值是 `http-server`
3. 打开终端, 切到package.json 文件所属目录，执行 `npm start`,这个时候 npm 会自动找当前路径