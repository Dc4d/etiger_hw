## 欢迎参与共建答疑知识库！

本文档仅提供最低限度的参与共建答疑知识库的基础准备和要求，更多配置请参考官方文档，欢迎在实际参与过程中提出更多优化建议！

答疑知识库的主要文档内容用markdown编写，通过mkdocs套用模板生成静态网页。**在参与完善的过程中请尽量保持文档结构的一致性。**

知识库的目的是方便各位老师答疑的时候查询各个作业题的标准代码、常见问题，帮助老师快速定位同学的问题，提高答疑效率。

### 使用GitHub参与知识库完善

项目仓库地址：[Dc4d/etiger_hw (github.com)](https://github.com/Dc4d/etiger_hw)

参与完善知识库需要GitHub账号，参考[Github官方教学（需要先注册Github账号）](https://lab.github.com/)和[如何参与 - OI Wiki (oi-wiki.org)](https://oi-wiki.org/intro/htc/)

通常可以直接在Github直接编辑，需要预览生成网页效果需要本地编辑，所需的Git使用的知识，参考[Git使用教学视频](https://www.bilibili.com/video/BV1T54y1H7Lo)



### 安装mkdocs

**使用pip安装**

也可以通过从[python.org](https://www.python.org/downloads/)下载适用于你系统的安装程序并运行它来安装[Python](https://www.python.org/)。所有安装选项以默认设置即可。

安装完成后使用pip安装`mkdocs`包，Windows系统下同时按下Windows键+R，输入cmd，在窗口中输入：

```bash
pip install mkdocs
```

等待安装完成即可。

**检查安装完成情况**

你现在应该能运行安装于系统上的`mkdocs`命令了。 运行`mkdocs --version`来检查一切是否正常。

如果显示mkdocs不是有效的命令，需要把pip文件夹添加到环境变量，参考[pip 环境变量设置

**安装网页模板**

答疑知识库目前使用的模板是yeti，需要pip安装bootswatch

```
pip install mkdocs-bootswatch
```

### 文档结构

作业题目的代码和常见问题都以markdown形式存储在项目的docs文件夹下，因此编辑需要基础的markdown语法

按课程等级划分文件：001.md, 002.md, 100.md, 101.md, 102.md, 103.md, 104.md

文件内容为单元、题号、代码、常见问题

其中单元为一级标题（#），题号为二级标题（##），常见问题是有序列表+无序列表，如果常见问题是通用或重复的内容，可以写在具体的单元或者课程的最前面，详见001.md的格式



### 编辑完成后

1. 本地预览网站生成效果，进入到对应文件夹（包含mkdocs.yml的目录），Shift+右键，在此处打开Power Shell窗口或者命令行窗口，输入：

  ```bash
  mkdocs serve
  ```

打开浏览器输入http://127.0.0.1:8000/

2. 在Github提交Pull Request，对于 Pull Request，请简要叙述修改的内容

下面是几个 PR 标题的示例：

- （错误）修复了一个 bug
- （正确）修复了001.md的一个 typo
- （错误）添加了新内容
- （正确）为001阶段Unit01添加了常见问题

### 参考资料与拓展阅读
1. [如何参与-IO Wiki](https://oi-wiki.org/intro/htc/)
2. [Mkdocs 官方中文文档](https://mkdocs.zimoapps.com/)

Web-based editor - GitHub Codespaces - GitHub Docs ↩

