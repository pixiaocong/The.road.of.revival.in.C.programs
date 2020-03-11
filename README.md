# The road of revival in C programs

当我决定再次重新拾起这门“古老”的语言，心中感慨万千。事物的兴衰交替本是常态，一门编程语言也不例外。但这门语言的凋零并不是通常意义上的谢幕，你依然可以在各大编程语言排行榜看到C的身影，甚至是各大操作系统和各种其他语言编译器和解释器的御用开发语言，可是，使用者却是越来越少了。思考良久，我想这得归功于中国IT行业的浮躁和急功近利，和底层硬件的缺失，还有资本的推波助澜。也许你可以借助当下的许多前台语言，开发出令人眼花缭乱的效果，但是你永远也找不到一种语言替代C的简洁与高效。
对于这门语言的误解、过度的神话，我觉得是时候来一次了结了。移动互联网正在打造一个前端语言的低效帝国，开发产品的速度上去了，但产品运行效率却低下了。尤其是安卓系统下的那些国产Java APP，无节制地加入很多新功能，也将安卓机的硬件配置不断拉高，但卡顿与令人不适的操作从来都未曾消除。相反，苹果的ObjectC应用架构，使得它的用户们在更低的硬件配置上获得更流畅的操作体验

我建立了这个项目，并希望因此Github上会产生更多的C语言应用项目

我们能做些什么？
- 提供一些入门示例，让对这门语言感兴趣的人快速入门（平台依赖部分的代码工作量会非常大）
- 将以往的项目中的高质量模块，抽出来集中测试，反复review。
- 然后在以上模块的基础上，建立一些项目



### 你可以

- 帮忙翻译本篇文字，用你所使用的母语，以吸引更多的开发者加入。（我们迫切需要一个英文版）
- 帮忙找茬，从现有的所有代码中寻找bug并提交修改建议。
- 提供反例代码（错误的范例），编译不过去那种也行，尽量把**坑**都挖出来，并让所有人都知道。毕竟C语言的坑太多，你懂的。
- 帮忙编写每个目录的makefile文件，这样就不用一个个程序单独编译了。
- 造轮子。从你当前和过去的项目中提取你认为的优秀的模块放到此处，并发计算、多进程、网络通信、简单加密算法、P2P模块，急缺。
- 编写测试用例（最好以源代码的方式提交），脚本和代码均可，用来证明现存的模块是安全可靠并高效的，如果不是，那我们就得不断修正它，直到一个模块变得无法修改。
- 甚至也可以是一个未实现的idea，





## 对于一些误区的解读：
- C不等于VC++ 不等于MFC
- C语言生成的程序都是**命令行**的，没有菜单、没有按钮、也无法使用鼠标

### 编写C语言的工具使用很复杂，学习成本很高？
不，事实上，要开发一个C语言程序，只需要两件工具就够了。

- 一个编辑器（就像，windows下的记事本）
- 一个编译器（在linux中是gcc，在Windows中是cl，前提是你得装好Mircosoft visual studio，在Mac上我不知道，因为没用过苹果的机器）。


至于调试器，得了吧那是用来擦屁股的。活不干净，代码漏洞百出就只能用用调试器来擦屁股，虽然这话不中听，但却是事实。修炼多年的老手只对自己的代码负责，不用等到出了事情再来找问题在哪里，调试器倒是成了摆设。

每当我想到这个再简单不过的事实，就只能哭笑，有多少老师教不是一上来就让你用VC的？有多少学校计算机系的教程不是用的谭浩强教授的《》，这本教材让计算机专业的学生觉得好像C语言只能用来解数学题目。经历过这些的人无不是一入门就被当头打了一棒子，从此误入歧途。



> “一切伟大的行动和思想，都有一个微不足道的开始。”
>                                                                     ——阿尔贝·加缪
