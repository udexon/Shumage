

## Open Ended Homoiconic Document Model and Metaprogramming

https://en.wikipedia.org/wiki/Patch_(Unix)

- The computer tool patch is a Unix program that updates text files according to instructions contained in a separate file, called a patch file. The patch file (also called a patch for short) is a text file that consists of a list of differences and is produced by running the related diff program with the original and updated file as arguments. Updating files with patch is often referred to as applying the patch or simply patching the files.

OEHDOM, truth to be told, is simply a glorified "super-patch". However, several decades have passed between the small step from the original patch and OEHDOM. And this "small step", is no less than a leap of faith, that would ultimately lead to human level artificial intelligence (HLAI) and technological singularity (TS).

OEHDOM and `patch` came from two different traditions that diverged in the 1970s, as the Forth programming language and Unix operating system grew into separate ecosystems. As programming language related tools in Unix such as lex and yacc blossomed into a multitude of programming languages, a poetic coincidence reminds human beings that nature has its own plan that is outside human control -- the Forth programming language, primarily based on the Reverse Polish Notation, turns out to be a solution to unify all known programming languages, whose growing number has caused diminishing returns in various aspects of software engineering.

`patch` is programming language agnostic but has limited programmability. By extending `patch` functionalities using Reverse Polish Notation, full programmability can be achieved in the operations to modify pre-existing code repositories.


The name OEHDOM refers to the following features:

- "Open Ended": the "patch code" is applied at the end of a document or when a document is saved. As such, a document is never "completely closed".

- "Homoiconic" refers to the capabilities of XRPN (Extended Reverse Polish Notation), the superset of Forth and related programming languages, which can programmatically process the XRPN code itself.

- We call this implementation of XRPN ["Phos" (Greek ΦΩ∑)](http://5gl.epizy.com/nsm/Phos.html) as it rhymes with Forth and for its fame from the Greek Bible verse "genethetho Phos", which translates to "fiat lux" in Latin or "let there be light" in English. 



在万能代码的基础上， 我们可以开发出一个 “无终结开放型文件模式”。 至今为止， 所有的计算机文件模式， 都是有始有终的。所谓  “无终结开放型文件模式”， 就是在原有的目录结构和文件里， 加入新弗式的指令， 可以代表程序员对现有文件的改动。

我们改动的文件， 主要是编程项目里调适及源码文件。 许多编程项目的文件， 其繁冗复杂程度， 例如安卓应用项目， 编程项目的文件， 早已发展到超越人手调置的限度。新的工具和程序语言被开发来处理现有的项目文件， 把总体结构和文件简化了吗？ 还是更加繁复？我们要 如何一劳永逸的解决这个问题？

新弗式差别码的原理， 来自程序员编辑源码文件的动作， 例如， 删、 插入、 移动、 抄、 粘帖等。 这些动作的指令， 还存在于历史悠久的 sed 及 vi 等工具。 GitHub patch file 也同属一类。 然而， 这些指令， 不能算得上是全面的程序语言。 不过， 它们和程序语言的差别， 其实只是一桥之隔。引用这个成语， 是暗喻图论祖师爷欧拉的七桥问题。 新弗式就可以统合文件编辑指令和全面程序语言。 

https://stackoverflow.com/questions/8279602/what-is-a-patch-in-git-version-control

我们分析一个相对复杂， 实在的项目， 来讲解新弗式的运用原理：

Vinyl Cast 和 Rhythm Game 是两个基于 Google Oboe ( 谷歌  双簧管  )  的安卓应用项目。  双簧管 是 安卓平台上的一个 C++ 高效能音频处理库， Vinyl Cast 原本的作用， 是在安卓仪器上录制胶盘的音乐， 然后以 http 协定， 转播到浏览器上。 Rhythm Game 是一个混合拍打和音乐的示范应用。  理论上， 我们可以改良以上的项目， 制作一个 DJ 混音的应用， 并加入 http 转播功能， 形成一种新式的 “接龙混音” 应用。

改动原有源码文件和调置文件的过程， 完全是程序员手动操作， 即使用文本编辑器， 改动原文件的字节。 

Metaprogramming 元编程， 是使用第三方工具或语言， 间接的对原始文件改动。

人们在讨论技术问题和方法时， 会牵涉到高阶或低阶的概念和实际操作。  程序员改动源码文件就是一个低阶的实际操作。 元编程， 是高阶的实际操作。

一般的程序开发， 程序员很少会直接使用元编程。 

新弗式， 可以将元编程普及到所有已知的程序语言， 让程序员使用高阶的元编程， 对源码进行改动。

https://zh.m.wikipedia.org/wiki/%E5%85%83%E7%BC%96%E7%A8%8B

如维基百科 “元编程” 所述， 一般人对元编程的认识只局限于单一程序语言范围内应用， 而新弗式的跨语言元编程， 是一个突破性的新发明。 

新弗式， 可以对任何已知的程序语言进行元编程。 

元编程， 到底是什么高深莫测高大上的玩意儿？ 还是一种深入浅出、 返璞归真、 化整为零的玩意儿？ 

示范 

echo 1

echo 2

sed -i 's/old-text/new-text/g' input.txt



   程序员手动编辑， 后生成 patch 。 程序员手动编辑的思绪及过程， 用新弗式表现出来。 


GitHub patch code is not full fledged programmable script. Phos is. 

Phos command can be embedded as comments in any existing file or additional files in existing directory or a new subdirectory. Call it Delta code.

Delta code is the basis of fees pay out. Conflict with free software licenses? Depends. Discuss several scenario.

Use Android project to illustrate. Gradle is based on groovy, a JVM derived Language. 

打造 Dijkstra、 Turing 级数的大师

突破 Stack Computer 

comp.lang.forth 老前辈 资源

