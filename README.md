# Rust语言周刊
精选过去一周的文章、新闻、开源项目和 Rust 语言动态，并对其中一部分文章提供中文翻译(中文内容用 🇨🇳 进行标识)，欢迎大家在右上角点击 Star🌟 进行订阅 :)

> 我们郑重承诺，永不太监！除非... Rust 被你们抛弃 :(

## 「Rust 语言周刊」 第 4 期 · 2022-03-18

<img src="https://pic3.zhimg.com/80/v2-a83541773f2f37a4e5e47e3c00667a35_1440w.jpg">
<h5 align="center">题图: WASM 提取 OCR</h5>


#### 精选文章

1、[使用 WASM 提取 OCR 内容](https://hugopeixoto.net/articles/rust-wasm-ocr-experiments.html)

如果要将 3000 张图片的内容手动上传到网站上，你会怎么做？总之作者选择了"偷懒"。

2、[讨论：一开始使用 Rust 实现但是最后切换到其它语言的项目](https://www.reddit.com/r/rust/comments/td4fci/have_you_ever_started_a_project_in_rust_but/)

Rust 不是万能的，我们见过了太多从其它语言切到 Rust 的，现在来看看反转后的世界是什么样的。

3、[Rustler 的预编译功能简介](https://dashbit.co/blog/rustler-precompiled)

众所周知，以往的虚拟机往往都是通过 C 语言实现的，例如大名鼎鼎的 Erlang/Elixir Beam 虚拟机，而 Rustler 就是该虚拟机的 Rust 重写。出于性能和资源占用的原因，Rustler 提供了预编译的功能。

4、🇨🇳 [AutoSar 宣布成立汽车软件 Rust 工作组](https://www.zhihu.com/question/522187444/answer/2392992688)

AutoSar 提供了一个汽车开放系统架构，包括 Classic Platform 和 Adaptive Platform 两种 API 标准，目前有很多大的汽车公司在使用。

5、[深入幂等性 - 节选自 Zero To Production In Rust 一书](https://www.lpalmieri.com/posts/idempotency/)

为了交付一个高可靠的项目，我们需要了解下何为幂等性、锁、队列和后台任务等。



#### 开源项目

1、[Tantivy 发布 0.17 版本](https://quickwit.io/blog/tantivy-0.17/)

Tantivy 是功能完全对标 Lucence 的搜索引擎，所属的分布式搜索平台 Quicwit 刚融资了 500 万美金。

2、[Arti 发布 0.1.0 版本](https://blog.torproject.org/arti_010_released/)

Tor 官方使用 Rust 重写了 Tor，原因在于 Rust 能提供更高的安全性，据官方估计，有一半以上的安全性问题通过 Rust 重写后都不再是问题。

3、 [xshell](https://github.com/matklad/xshell)

提供跨平台的实用库，轻松使用 Rust 写出 `bash` 脚本。

4、 [RepliByte](https://github.com/Qovery/replibyte)

使用 Rust 写得数据库同步服务，支持云和同步时的敏感数据过滤/混淆。

5、[Savage](https://github.com/p-e-w/savage)

纯 Rust 实现的计算机代数系统


## 往期回顾

目前所有的周刊都按照 `年/月/日期` 的方式归纳在 [docs](./docs) 目录下，大家可以按需查看。

- [第 3 期](./docs/2022/3月/11.md)
- [第 2 期](./docs/2022/3月/04.md)
- [第 1 期](./docs/2022/2月/28.md)


## 怀揣劲爆消息或优质内容？
欢迎提交 `issue` 或 `PR`，我们欢迎一切有价值的内容，并且你提供的每条消息都将标注上你的 github 用户名和链接。
