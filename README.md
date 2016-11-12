# 今天我学了什么 (Today I learned)

> 博观而约取，厚积而薄发。

## TOC

<!-- MarkdownTOC depth=4 -->

- [分类](#分类)
    - [思考](#思考)
    - [Web](#web)
    - [函数式编程](#函数式编程)
    - [Linux](#linux)
    - [Vim](#vim)
    - [Javascript](#javascript)
    - [NodeJS](#nodejs)
    - [前端](#前端)
        - [React](#react)
    - [Ruby](#ruby)
    - [Elixir](#elixir)
    - [Rust](#rust)
    - [Redis](#redis)
    - [MongoDB](#mongodb)
    - [Git](#git)
    - [其他](#其他)
- [反馈问题或建议](#反馈问题或建议)
- [版权声明](#版权声明)

<!-- /MarkdownTOC -->

<a name="分类"></a>
## 分类

<a name="思考"></a>
### 思考

- [提问的智慧](./thinking/smartquestion.md)
- [项目代码如何组织](./thinking/how-to-make-code-organization.md)
- [不完整的函数](./thinking/non-total-function.md)

<a name="web"></a>
### Web

<a name="函数式编程"></a>
### 函数式编程

- [什么是 Monad](./fp/what-is-monad.md)

<a name="linux"></a>
### Linux

- [unlink 是删除任何文件](./linux/unlink.md)
- [XDG 基础目录标准](./linux/XDG-base-directory-spec.md)
- [慎用双引号与单引号](./linux/quotes-in-bash.md)
- [文件描述符，open file table 与 inode](./linux/fd-oft-inode.md)
- [IO、select、epoll](./linux/io-select-epoll.md)
- [Bash 小知识](./linux/bash-learning.md)
- [history 命令](./linux/history.md)
- [快速删文件](./linux/fast-remove-files.md)
- [奇怪的 ESC](./linux/weird-esc-key.md)
- [用户线程，内核线程，CPU 超线程技术](./linux/about-multi-thread.md)
- [/usr/bin/env](./linux/usr-bin-env.md)
- [连接 tty](./linux/connect-tty.md)
- [在 alpine 中找不到 setup-apkcache 等 setup-* 命令](./linux/setup-scripts-in-alpine.md)
- [修正 Docker for mac 时区问题](./linux/fix-timezone-in-docker-for-mac.md)
- [ab 与 wrk 比较](./linux/ab-vs-wrk.md)
- [进入 docker for mac 的虚拟机](./linux/docker-for-mac-tty.md)

<a name="vim"></a>
### Vim

- [学习 Vim](./vim/vim-learning.md)
- [unite.vim](./vim/unite.vim.md)
- [indentLine 自定义符号](./vim/indentline.md)
- [在 vim 中执行 shell 命令，同时将结果输出到 buffer](./vim/pipe-shell-output-to-buffer.md)
- [在 vim 中运行终端，以及如何退出终端模式](./vim/run-terminal-in-vim.md)

<a name="javascript"></a>
### Javascript

- [Promise 的坑](./javascript/trap-of-promise.md)
- [使用 Promise 的技巧](./javascript/trick-of-promise.md)

<a name="nodejs"></a>
### NodeJS

- [命令行的工具和类库](./nodejs/cli-libraries-and-tools.md)
- [EJS 渲染引擎的空白问题](./nodejs/ejs-blanks.md)
- [EventEmitter 需要注意的三个地方](./nodejs/three-notes-of-eventemitter.md)
- [Error.captureStackTrace 的 stack 缺少 message 问题](./nodejs/error-captureStackTrace.md)
- [有必要添加 'use strict' 吗？](http://adoyle.me/blog/implicit-strict-mode.html)
- [不要对函数参数重新赋值](./nodejs/don-t-reassign-function-arguments.md)
- [npm run scripts](./nodejs/npm-run-scripts.md)

<a name="前端"></a>
### 前端

- [XMLHttpRequest 的继承者：Fetch](./front-end/fetch.md)
- [redux 入门](./front-end/redux-ABC.md)
- [Webkit 浏览器渲染效率](./front-end/webkit-render-performance.md)
- [浮动侧边栏](./front-end/float-sidebar.md)
- [学习 Chrome DevTools](./front-end/learning-chrome-dev-tools.md)
- [webpack 配置为数组](./front-end/webpack-config-is-an-array.md)
- [使用 browserify 和 uglifyjs](./front-end/using-browserify-and-uglifyjs.md)

<a name="react"></a>
#### React
- [不要在 render 里直接定义 ref callback](./front-end/react/dont-define-ref-callback-in-render.md)
- [ref callback 何时触发？](./front-end/react/when-ref-callback-get-invoked.md)

<a name="ruby"></a>
### Ruby

- [使用 scientist 科学重构代码](./ruby/using-scientist-for-refactoring.md)

<a name="elixir"></a>
### Elixir

- [tuple 与 list 的选择](./elixir/choosing-between-tuple-and-list.md)

<a name="rust"></a>
### Rust

<a name="redis"></a>
### Redis

- [Redis Cluster 相关](./redis/cluster.md)
- [拷贝一个 Sorted Set 到新的 key](./redis/copy-a-sorted-set.md)

<a name="mongodb"></a>
### MongoDB

- [MongoDB 的丢数据问题](./mongo/data-lost.md)

<a name="git"></a>
### Git

- [diff](./git/diff.md)

<a name="其他"></a>
### 其他

- [mac 里的 tmux 内无法用 sublime 打开文件](./others/subl-in-tmux-on-mac.md)
- [TIL](./others/TIL.md)
- [箴言](./others/maxim.md)
- [vim textwidth=78 的约定](./others/textwidth-78-of-vim.md)
- [如何在 github 项目里搜索代码](./others/how-to-use-github-to-browse-codes.md)
- [Homebrew 使用代理和镜像源加速下载](./others/homebrew-proxy-and-mirror.md)
- [文件命名，下划线还是中划线？](./others/file-naming-with-underscores-and-dashes.md)

<a name="反馈问题或建议"></a>
## 反馈问题或建议

本项目不接受 Pull Request，如果你有什么好的想法，或者改进的建议，请使用 [Issue][] 与我探讨。

<a name="版权声明"></a>
## 版权声明

Copyright (c) 2016 ADoyle. The project is licensed under the **BSD 3-clause License**.

See the [LICENSE][] file for the specific language governing permissions and limitations under the License.


[Issue]: https://github.com/adoyle-h/Today-I-Learned/issues
[LICENSE]: ./LICENSE
