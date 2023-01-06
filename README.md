# thuthesis-biomedical
简明介绍：此文档是清华大学生命科学，基础医学，药学等相关专业的毕业论文latex模板。也适用于其他专业。本模板在tuna协会的thuthesis项目基础上，增补了和生医药相关同学的内容，也增添了对latex新手更加友好的注释。

本文档基于清华大学TUNA协会的开源项目thuthesis。核心代码是TUNA协会组织编写的，本文档只是针对生物医药相关的同学在撰写毕业论文时调整格式时的需要增加了对新手更加友好的注释，以及一些细节内容和实例。如果需要，可以通过覆盖.cls文件的方法，使用TUNA协会发布的新版本ThuThesis模板。但是某些部分，比如.cls文件中关于"系统性创新性说明"部分的代码(可以通过检索"创新性"检索到)，需要重新加入到新版本的.cls文件中。

清华大学TUNA协会:Tsinghua University TUNA Association
https://github.com/tuna

thuthesis模板：
https://github.com/tuna/thuthesis

本文档主要针对生医药大类的，并且没有接触过latex的同学。也可以作为其他院系使用thuthesis模板的入门文档。推荐使用在线版latex编辑工具overleaf。也适用其他Latex编辑工具，但是可能对没有接触过latex的同学学习成本更高一些。推荐结合说明视频使用。

<br>
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

由于论文写作要求可能会变动，请以本院系的最新要求为准。

!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

<br>

注意使用时
Main document应当设置为
!thuthesis-main.tex

<br>
本文档在编辑时使用的设置是：
<br>
Complier:
XeLaTeX
<br>
TeX Live version:
2022


<br>
<br>
无注释版本的常用表格，图片和符号的代码可以从这个页面获取
https://note.youdao.com/s/MIzhy2yr
<br>

<br>
https://note.youdao.com/s/FrQSV6Bn
这个公开状态的有道笔记记录了很多Overleaf中使用的技巧和常见bug的解决方法
<br>
如果使用overleaf编译，推荐使用VPN并且开启全局代理，以达到更好的连接稳定性。

<br>
使用overleaf编译后的字体和标准的宋体会有非常微弱的差异，不是很影响最终效果。如果在意的话，可以使用windows电脑上的Tex live编译。在线安装地址为 http://mirrors.tuna.tsinghua.edu.cn/CTAN/systems/texlive/tlnet/install-tl-windows.exe 。使用Mac可能会造成字体显示异常。Abort按钮变灰并且有welcome界面即表明安装完成。从overleaf上下载源文件的压缩包(左上角叶子图标-download source)后解压，找到tex主文件，会默认用texwork editor打开，XeLatex编译两次，BiTex编译一次，XeLatex编译一次，BiTex编译一次，XeLatex编译一次，即可得到对应论文写作指导手册中标准字体的文件。

### 在 ThuThesis 基础上增加的内容有:

### Added
增加了"系统性和创新性说明"部分。此部分按照学校要求，应当在格式审查，预答辩，送审时保留。最终版论文中需要删去，可以通过注释化加入novelty文档的命令实现。

### Changed
将\data下的文件通过重命名改变了顺序，对新手更加友好。A开头的是论文正文前的部分，B开头的是论文正文，C开头的是论文正文后的部分。

由于逐条列出修改部分将花费大量时间，增补和删改部分，将使用%(By LUKE-ZZ)注释。某些功能对生医药同学来说很少用到，以及对一些Latex新手的同学没有帮助的代码将注释化，以便于新手快速使用。
