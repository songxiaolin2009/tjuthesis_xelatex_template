## TJUThesis XeLaTeX Template

本模版为天津大学博士/硕士毕业论文模版，按照《天津大学关于博士、硕士学位论文统一格式的规定》修改而成。(Forked from code.google.com/p/tjuthesis)

此版本模版从封面开始，包括“独创性声明”、“摘要”、“目录”、“正文”、“参考文献”、“发表论文和参加科研情况说明”和“致谢”。“学术型/专业型”的标记分别为“academic/professional”、“博士/硕士”的标记分别为“phd/master”，请对照选用。请注意学术型/专业型、博士/硕士封面都是不同的，同学们请选择正确的模版。

考虑到一些操作系统中没有相应的中文字体文件，各模版根目录中放有四种字体（simfang.ttf(仿宋)、simhei.ttf(黑体)、simkai.ttf(楷体)和simsun.ttc(宋体)），不建议删除。当然对LaTeX有一定基础的高级玩家为了模版的美观和可迁移性也可以考虑删掉这些并使用系统自带的字体文件，相关设置在setup/format.tex中。

注意：本模版为XeLaTeX模版，不是pdfLaTeX。使用pdfLaTeX会报错。编译顺序为：XeLaTeX -> bibTeX -> XeLaTeX -> XeLaTeX

使用XeLeTeX的原因：之前的pdfLaTeX模版只能用在TeX Live 2014及以前版本或MikTeX/CTeX 2.9及以前版本（如果想使用pdfLaTeX，Windows倒是可以考虑直接用CTeX，最新版的CTeX版本号是2.9，不过自带的WinEdt 7.0不支持高分屏，可手动升级，也可以用其他编辑器；Mac上找低版本的MacTeX是个比较抓狂的事情）。本模版可完美跨平台，已在Windows/Mac/Linux上测试通过，并可用于最新版的TeX Live、MikTeX和MacTeX。

如有同学有意向一起完善此模版，欢迎交流。联系方式：songxiaolin2009@163.com

更新日志：
2021-09-26 添加了各模版的封面页和独创性声明页
