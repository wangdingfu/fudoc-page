---
home: true
heroImage: /img/logo.svg
heroText: Fu Doc
tagline: 🚀为java开发者管理Restful Api而生的Idea插件
actions:
  - actionText: ⛵️快速开始 ->
    actionLink: /pages/5816c5/
  - actionText: ⚡️支持Fu Doc
    actionLink: /pages/39mm06/
    actionClass: button-fudoc
bannerBg: none # auto => 网格纹背景(有bodyBgImg时无背景)，默认 | none => 无 | '大图地址' | background: 自定义背景样式       提示：如发现文本颜色不适应你的背景时可以到palette.styl修改$bannerTextColor变量
features: # 可选的
  - title: 🍀轻巧强大
    details: 小身躯蕴藏着大能量，简单的学习成本，几分钟就能上手。却可以完成复杂的规则编排。
  - title: 🌸优雅高效
    details: 拥有独特的设计理念，所有逻辑皆为组件。稳定运行于各大公司的核心系统上，性能卓越。
  - title: 🌼支持丰富
    details: 不管你是何种架构，都能支持。任意编排，多种规则格式，平滑热刷新，多级嵌套，外部存储扩展等等。

# 文章列表显示方式: detailed 默认，显示详细版文章列表（包括作者、分类、标签、摘要、分页等）| simple => 显示简约版文章列表（仅标题和日期）| none 不显示文章列表
postList: none
notices: # 可选的
  - id: fudoc-V222.1.7.8
    title: 🚀 [Fu Doc] v222.1.7.8 发布！
    content: '<div><p>2023-08-04</p><ul><li>[增强]全面支持JDK17</li><li>[增强]SQL插件支持使用系统内的数据源</li><li>[增强]很多功能有所增强</li></ul></div><p style="text-align: right;"><a href="/pages/8ff012/">查看详情</a></p>'
    isHtmlContent: true
---

<Notice :data="$frontmatter.notices"/>

<br/><br/>

## 🍬特性

* **组件定义统一：** 所有的逻辑都是组件，为所有的逻辑提供统一化的组件实现方式，小身材，大能量。
* **规则轻量：** 基于规则文件来编排流程，学习规则入门只需要5分钟，一看既懂。
* **规则多样化：** 规则支持xml、json、yml三种规则文件写法方式，喜欢哪种用哪个。
* **任意编排：** 再复杂的逻辑过程，利用LiteFlow的规则，都是很容易做到的，看规则文件就能知道逻辑是如何运转的。
* **规则持久化：** 框架原生支持把规则存储在标准结构化数据库，Nacos，Etcd，Zookeeper，Apollo。您也可以自己扩展，把规则存储在任何地方。
* **优雅热刷新机制：** 规则变化，无需重启您的应用，即时改变应用的规则。高并发下不会因为刷新规则导致正在执行的规则有任何错乱。
* **支持广泛：** 不管你的项目是不是基于Springboot，Spring还是任何其他java框架构建，LiteFlow都能游刃有余。
* **JDK支持：** 从JDK8到JDK17，统统支持。无需担心JDK版本。
* **Springboot支持全面：** 支持Springboot 2.X到最新的Springboot 3.X。
* **脚本语言支持：** 可以定义脚本语言节点，支持Groovy，Javascript，QLExpress，Python，Lua，Aviator。未来还会支持更多的脚本语言。
* **脚本和Java全打通：** 所有脚本语言均可调用Java方法，甚至于可以引用任意的实例，在脚本中调用RPC也是支持的。
* **规则嵌套支持：** 只要你想的出，你可以利用简单的表达式完成多重嵌套的复杂逻辑编排。
* **组件重试支持：** 组件可以支持重试，每个组件均可自定义重试配置和指定异常。
* **上下文隔离机制：** 可靠的上下文隔离机制，你无需担心高并发情况下的数据串流。
* **声明式组件支持：** 你可以让你的任意类秒变组件。
* **详细的步骤信息：** 你的链路如何执行的，每个组件耗时多少，报了什么错，一目了然。
* **稳定可靠：** 历时2年多的迭代，在各大公司的核心系统上稳定运行。
* **性能卓越：** 框架本身几乎不消耗额外性能，性能取决你的组件执行效率。
* **自带简单监控：** 框架内自带一个命令行的监控，能够知道每个组件的运行耗时排行。

<br/>

## ✨最新版本

- V222.1.7.8 (**idea 2022.2版本以上**)
- V212.1.7.8 (**idea 2021.2 ~ 2022.2**)
- V203.1.7.8 (**idea 2020.2 ~ idea2021.2**)

:::tip 新版本稳定吗？

我们每一次发布版本，都会补充大量的测试用例。庞大的测试用例数目几乎覆盖到每一个已有功能的细节点。

并且我们会跑超大量的并发压力测试，以上所有的通过后，我们才会谨慎的提交代码覆盖主分支进行发版。

你大可不必担心新版本不稳定的情况，况且，我们有良好的社区群。基本上有问必答，如出现bug，基本上隔天必解决。

所以，请放心的使用！
:::

<br/>

## 🎉致谢

LiteFlow自从2020年开源以来，获得了很多人的支持。目前社区群3500多人，Gitee上4.4k Stars，Github上2k
Stars，感谢各位支持者的一路同行，我们会努力把国产的规则引擎做到极致。

LiteFlow在[2021](https://www.oschina.net/project/top_cn_2021)获得“OSC 年度最受欢迎中国开源软件”殊荣。

LiteFlow在2022年获得“Gitee最有价值开源项目“奖项（GVP）。

LiteFlow在2022年成为了"中国信通院可信开源社区共同体(TWOS)成员"。

感谢OSCHINA和Gitee官方平台对LiteFlow项目的推荐和肯定。

LiteFlow首页的背景由插画师`森阳`提供，感谢她的创作，如需要插画商业合作小伙伴可以联系她：

> 邮件：sssenyang@qq.com | 微信：ArtSenyang

<br/>

## 🏡代码托管

<a href='https://gitee.com/dromara/liteFlow' target="_blank">
    <img class="no-zoom" :src="$withBase('/img/Gitee-red.svg')"/>
</a>

<a href="https://github.com/dromara/liteflow" target="_blank">
    <img class="no-zoom" :src="$withBase('/img/Github-blue.svg')"/>
</a>

<br/><br/>

## 💪🏻参与开发

欢迎各路好汉一起来参与完善 `Fu Doc`，我们期待你的 PR！

如果想贡献，请先查看[参与开发](/pages/ae4dd5/)。

<br/>

## 🍭架构图

<img :src="$withBase('/img/arch.svg')" style="zoom: 100%;" class="no-zoom">

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