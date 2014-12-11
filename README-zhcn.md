# Git-it

![ss](https://raw.githubusercontent.com/jlord/git-it/master/git-it-ss.png)

一个 很酷的[程序](https://github.com/rvagg/workshopper)， 致力于帮助新手快速入门 Git 和 Github。

这个程序包含了一些小小的挑战，使用者通过战胜这些挑战来掌握一些 Git 和 Github 的知识. 可以去 [nodeschool.io](http://nodeschool.io) 了解更多。

---

**开发者文档 [CONTRIBUTING.md](https://github.com/jlord/git-it/blob/master/CONTRIBUTING.md).**

**想要指导一次git-it活动? 先试试用 git-it ，然后去 [TROUBLESHOOT.md](https://github.com/jlord/git-it/blob/master/TROUBLESHOOT.md) 看看新手常见的问题**.

---

## Hello, Coder

这个程序运行在命令行终端 ， 包含了一些学习 Git 和Github的挑战. 这并非是运行在 _虚拟_ 终端 (因此你得先学习一些给力的命令行), 由于是 _现实_ 的 Git 和 GitHub ， 这意味着你完成关卡之后你也会有一些 _真正_ 的项目在你的 GitHub 上，并且能在[贡献图表](https://github.com/blog/1360-introducing-contributions).

![contributions](https://raw.githubusercontent.com/jlord/git-it/master/ghcc.png)上体现出来。

查看 git-it 涉及了哪些内容 [挑战列表](http://jlord.github.io/git-it) .

---

#### 运行 Git-it 之前你需要有的东西:

_用到的开发工具全部是免费的，大部分是开源软件。_

- **Git**, 这就是你的代码管理工具!
- 如果你是 **Windows, 下载 [GitHub for Windows](http://windows.github.com)**, 包含了 Git, 可以使用随附的 **Git Shell** 作为命令行窗口.
- 如果你是 **Mac, 下载 [GitHub for Mac](http://mac.github.com)**, 包含了 Git, 同时也可以安装命令行工具，选择 首选项 > 高级 > 安装命令行工具 （Preferences > Advanced > Install Command Line Tools）.
- **Node.js**, git-it 就是基于 Node.js 运行的. 这是一个能够使 javascript 运行在服务端的平台。 (你的计算机就是你的服务器!)   **下载 Node [here](http://nodejs.org/download/)** (多数情况下, 直接选择 **Windows `.msi`** or **Mac `.pkg`** 下载).
- 如果你已经有了 Node 和 npm, 确保 npm 的版本高于 v 1.4.3 .
- **代码编辑器r**, 如果你目前还没有, 那么你确实需要一个了*. 这些都可以: [Atom](http://www.atom.io), [Sublime Text](http://www.sublimetext.com/2), [Textmate](http://macromates.com/download), [Brackets](http://brackets.io/).
- ** 语言 **, 目前 git-it 的内容还是设定为英文，所以如果你的计算机没有英文设定，可能无法运行，如果你遇到这方面的问题，看看这里 [TROUBLESHOOT.md](https://github.com/jlord/git-it/blob/master/TROUBLESHOOT.md).

_*T事实上完成 Git-it 并不需要编写代码，所有你用 Mac/PC 自带的编辑器亦无伤大雅。_

#### 安装 Git-it

等你安装了上述要求的软件, 那么开始安装 Git-it 吧！

- 打开你的命令行终端全局安装 git-it  (方便你在任何目录运行它). [NPM](http://www.npmjs.org) (**别担心，你安装好 Node.js 的时候， npm 也跟着安装好了**) 安装很简单，就像这样 :

```bash
$ npm install -g git-it
```
- _如果你运行这条指令出错了，那么很可能是因为电脑的权限问题, **试着 加上 'sudo'**:_ `sudo npm install -g git-it`
- 一旦安装完成，输入下面的指令运行 :

```bash
$ git-it
```
- 运行之后弹出菜单，然后开动吧！

#### 使用指南

- 当你运行 `git-it` 之后会弹出菜单, 用方向键 ↑↓ 选择，回车 'enter' 确认.
- 启动一个关卡之后, 按照下方的说明打开指南. _你可以直接预览网页版指南 [here](http://jlord.github.io/git-it)._

![img](https://raw.githubusercontent.com/jlord/git-it/master/guide-ss.png)

- 阅读指南上的介绍然后完成你的挑战.
- 当你做完一个挑战时, 在命令终端中输入 `git-it verify` 来检验.
- 如果检验失败了, Git-it 会输出一些错误提示帮助你快速定位可能出错的地方.
- 完成一个挑战之后，输入 `git-it` 唤出菜单，选择下一个挑战吧!

**如果你有什么问题,  [创建 一个 issue](https://github.com/jlord/git-it/issues/new) 或者访问[troubleshooting doc](https://github.com/jlord/git-it/blob/master/TROUBLESHOOT.md).**

---

#### 初学者小贴士

**代码片** 通常它们长得像 `$ some code-stuff --here`。美元符号表示这是输入到命令窗口的, 但是你在自己的命令输入的时候不需要输入美元符。 在这个例子中, 你只需要输入 `some code-stuff --here` 就好了。

**变量** 代码片中用 `<VARIABLENAME>` 表示. 当你使用某行代码时, 把`<>`中的变量替换成你自己的。 例如你需要在命令行终端中创建一个文件夹,指令是 `mkdir <FOLDERNAME>`,如果你需要的文件夹名字是 'octocat', 只要输入: `mkdir octocat`。

**命令行, 终端** 都指的是同一样事物: 就是你在电视剧里看到的哪些满是数字和字符的东西。 命令行很强大，几乎能控制电脑的所有功能。

你用命令行能做很多事情， 像 delete（删除）, rename（重命名）, copy（复制） 或者 create（新建） 文件 和 文件夹; 通过运行脚本让你的电脑在众多服务器之间穿梭自如 (就像你通过命令行把代码存到 GitHub.com 上一样)。
