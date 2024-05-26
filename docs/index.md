---
home: true
heroImage: /img/logo.svg
heroText: Fu Doc
tagline: 🚀为提升Java开发者工作效率而生的IDEA插件
actions:
  - actionText: ⛵️快速开始 →
    actionLink: /pages/e8ef29/
  - actionText: ⚡️视频演示  
    actionLink: /pages/77f026/
    actionClass: button-fudoc
bannerBg: none # auto => 网格纹背景(有bodyBgImg时无背景)，默认 | none => 无 | '大图地址' | background: 自定义背景样式       提示：如发现文本颜色不适应你的背景时可以到palette.styl修改$bannerTextColor变量
features: # 可选的
  - title: 🍀文档助手
    details: 支持一键生成接口文档、一键同步至ApiFox、 ShowDoc、 YApi等第三方文档系统
  - title: 🌸调试利器
    details: 一个集成在Idea中的PostMan。让你能够极其方便的调试接口
  - title: 🌼工具集
    details: 依赖idea实现一些提示工作效率的工具, 例如接口url快速搜索、通过代码补全方式完成对象拷贝

# 文章列表显示方式: detailed 默认，显示详细版文章列表（包括作者、分类、标签、摘要、分页等）| simple => 显示简约版文章列表（仅标题和日期）| none 不显示文章列表
postList: none
notices: # 可选的
  - id: fudoc-V1.7.9
    title: 🚀 [Fu Doc] 1.7.9 发布！
    content: '<div><p>2023-08-04</p><ul><li>[增强]新增支持IDEA 2020.2以上的版本</li><li>[增强]支持代码补全beanCopy</li><li>前置脚本支持日志输出</li></ul></div><p style="text-align: right;"><a href="/pages/2e9223/">查看详情</a></p>'
    isHtmlContent: true
---


<p align="center" style="padding-top: 0;margin-top: 0">
  <a class="become-sponsor" href="/pages/2a8323/">成为赞助者</a>
</p>

<style>
.become-sponsor{
  padding: 8px 20px;
  display: inline-block;
  color: #4a8a5a;
  border-radius: 30px;
  box-sizing: border-box;
  border: 2px solid #4a8a5a;
}
</style>

<br/>

<br/>
<p align="center">
  <a href="https://plugins.jetbrains.com/plugin/19269-fu-doc" target="_blank"><img src="https://img.shields.io/jetbrains/plugin/v/19269-fu-doc.svg" alt="fudoc" class="no-zoom"></a>
  <a href="https://plugins.jetbrains.com/plugin/19269-fu-doc/versions" target="_blank"><img src="http://phpstorm.espend.de/badge/19269/version" alt="fudoc" class="no-zoom"></a>
  <a href="https://plugins.jetbrains.com/plugin/19269-fu-doc" target="_blank"><img src='https://img.shields.io/jetbrains/plugin/d/19269-fu-doc.svg' alt='download' class="no-zoom"></a>
  <a href="https://github.com/wangdingfu/fu-api-doc-plugin" target="_blank"><img src='https://img.shields.io/github/stars/wangdingfu/fu-api-doc-plugin' alt='GitHub stars' class="no-zoom"></a>
  <a href="https://plugins.jetbrains.com/plugin/19269-fu-doc" target="_blank"><img src='https://img.shields.io/badge/license-MIT-red.svg' alt='MIT' class="no-zoom"></a>
</p>

<br/>

## 🎨特性

* **文档模板：** 支持修改文档模板来生成自定义的接口文档。
* **接口文档同步：** 支持将接口信息同步至`ApiFox`、`ShowDoc`、`YApi`等第三方接口文档平台。
* **注解支持：** 支持`@Valid`相关注解表示参数是否必填，支持`@JsonIgnore`等注解。
* **注释支持：** 支持解析Java注释为字段中文描述、接口名称、接口描述等，无需通过类似`Swagger`注解来标识字段名。
* **Swagger支持：** 支持读取`Swagger`注解信息，如果同时有注释信息和`Swagger`注解, 则`Swagger`优先级更高。
* **自定义数据支持：** 支持读取代码中指定注解信息、支持读取代码注释中指定的标签信息 可直接在接口文档模板中通过`${fudoc.tagName}`方式使用该数据。
* **@see注解支持：** 支持在字段上标识`@see`注解引用枚举 生成文档时会自动生成该字段的枚举字典信息在备注上
* **rpc支持：** 支持`Dubbo` `Feign`等接口生成接口文档。
* **SpringBoot支持：** 自动解析Spring环境和配置文件，无需手动配置接口请求端口等信息。
* **接口请求：** 通过优美的图形化界面(借鉴`PostMan`)发起接口请求。
* **curl命令：** 支持一键拷贝curl命令。
* **脚本支持：** 支持对指定项目配置前置脚本(`JavaScript`脚本)来实现一些鉴权等操作，支持实时调试脚本。
* **全局参数：** 支持配置全局请求头、支持配置全局变量，全局管理Cookie。
* **鉴权信息管理：** 支持配置多个鉴权用户，在接口请求界面可手动切换不同鉴权用户发起接口请求
* **环境管理：** 默认自动读取SpringBoot环境，支持手动配置环境并在请求面板中手动切换不同环境
* **文件上传下载：** 接口请求支持文件的上传和文件下载
* **请求日志：** 每次请求时都会在请求面板的`Console`面板输出完整的请求日志，便于排查问题
* **url快速搜索：** 通过快捷键`CTL+ALT+\ `或`CMD+ALT+\ `快速搜索接口
* **代码补全：** 支持通过代码补全方式生成A对象属性赋值到B对象属性的代码（针对不喜欢通过`BeanUtils.copy`的同学非常友好）
* **稳定可靠：** 历时1年多迭代了近20多个版本。


<br/>

## ✨版本说明

::: tip
目前插件仅支持<Badge text="IDEA2020.2 +" />以上的版本, 建议升级到idea2021以上的版本会有更好的体验和更多的功能支持
::: 

::: cardList
```yaml
- name: 222.*
  desc: 支持IDEA2022.2 + 版本
  bgColor: '#CBEAFA' # 可选，默认var(--bodyBg)。颜色值有#号时请添加单引号
  textColor: '#6854A1' # 可选，默认var(--textColor)
- name: 212.*
  desc: 支持IDEA2021.2 ~ 2022.2版本
  bgColor: '#718971'
  textColor: '#fff'
- name: 203.*
  desc: 支持idea2020.2 ~ idea2021.2版本
  bgColor: '#FCDBA0'
  textColor: '#A05F2C'
```
:::



<br/>



## 🏡代码托管


<a href='https://gitee.com/wdfu/fudoc' target="_blank">
    <img class="no-zoom" src="https://img.shields.io/badge/Gitee-red?logo=gitee&logoColor=white&style=for-the-badge"/>
</a>

<a href="https://github.com/wangdingfu/fu-api-doc-plugin" target="_blank">
    <img class="no-zoom" src="https://img.shields.io/badge/Github-blue?logo=github&logoColor=white&style=for-the-badge"/>
</a>

<br/><br/>

## 💪🏻参与开发

欢迎各路好汉一起来参与完善 `Fu Doc`，我们期待你的 PR！

如果想贡献，请先查看[参与开发](/pages/567a10/)。

<br/>

## 🍭架构图

<img :src="$withBase('/img/guide/guide.png')" style="zoom: 100%;" class="no-zoom">

<br/>

---

<style>
  .button-fudoc{
    margin-left: 0.5rem;
    margin-top: 0.5rem;
    display: inline-block;
    font-size: 1.2rem;
    background-color: #e01e5a;
    padding: 0.8rem 1.6rem;
    border-radius: 4px;
    transition: background-color 0.1s ease;
    box-sizing: border-box;
    color: #E3E394;
  }

.button-fudoc:hover {
    background-color: #e4346a
}
</style>