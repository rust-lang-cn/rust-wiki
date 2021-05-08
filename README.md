# Rust 规范文档

[![Build Status][travis-image]][travis-link]

> 💡 Rust Wiki 文档内容已经全部放到 [rustwiki.org](https://github.com/rust-lang-cn/rustwiki.org) 仓库中的 `content/wiki` 目录中，后续将在后者仓库进行更新，故本仓库不再单独更新。

Rust 规范文档包涵了一系列 Rust 有关的资料，包括翻译的指引、Rust 术语表以及 Rust 配套的其他资料（比如 TOML 语言介绍）。

## 使用说明

如果想阅读《Rust 规范文档》，可以直接访问 [https://rustwiki.org/zh-CN/rust-wiki/][website-cn] 进行在线上阅读。

若想在本地阅读，请先[安装 Rust][install Rust]，然后进行下面操作：

```bash
$ git clone https://github.com/rust-lang-cn/rust-wiki.git
$ cd rust-wiki
$ cargo install mdbook --version 0.2 --force
$ mdbook build
$ mdbook serve
```


## 如何贡献

请查看 [CONTRIBUTING.md][how-to-contribute] 文件了解详细内容。

## 授权协议

《Rust 规范文档》使用以下两种协议的任一种进行授权：

* Apache 2.0 授权协议，（[LICENSE-APACHE](LICENSE-APACHE) 或 http://www.apache.org/licenses/LICENSE-2.0）
* MIT 授权协议 ([LICENSE-MIT](LICENSE-MIT) 或 http://opensource.org/licenses/MIT)

可以根据自己选择来定。

除非您有另外说明，否则您在本仓库提交的任何贡献均按上述方式进行双重许可授权，就如 Apache 2.0 协议所规定那样，而不附加任何附加条款或条件。



[install Rust]: https://www.rust-lang.org/tools/install
[travis-image]: https://travis-ci.org/rust-lang-cn/rust-wiki.svg?branch=master
[travis-link]: https://travis-ci.org/rust-lang-cn/rust-wiki
[website-cn]: https://rustwiki.org/zh-CN/rust-wiki/
[how-to-contribute]: CONTRIBUTING.md
