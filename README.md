# nuco-docsify

nuco基于docsify定制的文档模板仓库

> 推荐您使用 [nbc](https://github.com/NucoTech/nuco-backend-cli) 作为commit规范化工具; 如果您在前端项目中使用本仓库模板, 建议您使用commitlint作为工程commit规范工具

## Features

- 定制侧边栏
- 定制导航栏
- 支持全文搜索
- 支持emoji
- 支持代码粘贴
- 支持字数统计
- 支持分页
- go语言语法高亮
- 支持PWA

## Usage

- 修改`./docs`下的模板文件`index.html`, 修改其中的`meta`和`title`以做正确的SEO优化
- 修改`window.$docsify`的配置项自定义功能
- 修改其中的`README.md`和`guide.md`文件, 做好读者引导
- 修改`<script>`的内容适当增删插件

## Preview

### 使用`docsify-cli`

```shell
docsify serve docs
```

### 不使用`docsify-cli`

> 如果本地有静态服务器启动的命令行工具的话, 可以进入`./docs`文件夹之后启动服务

- 比如`nodejs`的`httpserver`

```shell
cd docs

hs
```

- 比如`nodejs`的`serve`

```shell
cd docs

serve
```

- 比如使用`Python`

```shell
cd docs && python -m SimpleHTTPServer 3000
```

## References

- [Docsify官方文档](https://docsify.js.org)
