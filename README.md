## 脚手架常见的功能
- 1. 有命令，参数，帮助说明
- 2. 有交互，用户输入/确认
- 3. 有状态，比如loading等

### 1. 搭建基础的命令，cli init
- 1. 搭建项目，引入commander包，npm link到外面被使用，
- 2. 创建一级命令, 二级命令，参数

### 2. 完善init命令
- 1. 使用chalk 打印出更丰富的说明文档
- 2. 检测环境，比如Node的版本是否正确等
- 3. 使用inquirer 创建可交互式的cli
- 4. 使用ora 显示loading
- 5. 注意文件路径的关系
- 6. 完成simple路径
- 7. 完成webpack-simple的拷贝
  - 1. 使用Handlebars作为模版引擎
  - 2. 使用metalsmith生成静态文件

### 参考链接
- vue-cli: https://github.com/vuejs/vue-cli
- vuejs-templates: https://github.com/vuejs-templates
- handlebars: http://handlebarsjs.com/
- metalsmith: https://www.npmjs.com/package/metalsmith