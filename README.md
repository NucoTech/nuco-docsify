# nuco-docsify

nuco基于docsify定制的文档模板仓库

> 推荐您使用 [nbc](https://github.com/NucoTech/nuco-backend-cli) 作为commit规范化工具; 如果您在前端项目中使用本仓库模板, 建议您使用commitlint作为工程commit规范工具

## :sparkles: Features

- 定制侧边栏
- 定制导航栏
- 支持全文搜索
- 支持emoji
- 支持代码粘贴
- 支持字数统计
- 支持分页
- go语言语法高亮
- 支持PWA
- 支持夜间模式
- 支持Footer信息

## Usage

- 修改`./docs`下的模板文件`index.html`, 修改其中的`meta`和`title`以做正确的SEO优化
- 修改`window.$docsify`的配置项自定义功能
- 修改其中的`README.md`和`guide.md`文件, 做好读者引导
- 修改`<script>`的内容适当增删插件

## 使用`nbc`

> 我们很高兴的通知您, 自 `nbc v1.2.x` 版本开始, `nbc` 已经可以支持命令行生成文档与预览文档了!

```shell
# 在当前目录下, 生成docs目录并且根据模板初始化文档
nbc docs
```

预览文档

```shell
# 预览当前目录的docs子目录的文档
nbc serve
```

> 更多高级用法, 请参考 [nbc文档生成使用指南](https://github.com/NucoTech/nuco-backend-cli/blob/main/%E6%96%87%E6%A1%A3%E7%94%9F%E6%88%90%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97.md)

## Preview

> 如果您已使用`nbc`, 则可以跳过这一节

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
