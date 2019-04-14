使用时打开 CHD_Lab_report.tex 编译即可，注意中文文档编译使用XeLaTeX编译两次即可，出现问题优先使用 texclear.bat 清理工作区。

注意使用TexLive 2017以上的套装发行版。

对于文档内容，attachment是实验报告末尾的体验心得，鉴于LaTeX不适合做此类工作类表格，读者用word编辑后再对该页导出pdf替换该文件下内容即可。

对于body，里面是各section下的内容，单独存放便于查找。

对于figures，里面存放文中的图片，调用方式详见文档内容。

对于preface，里面是实验报告的封面，更改名字请在该文档内更改。

对于setup，里面有两个文档：format是全局一些格式上的更改与定义、packages是全文使用的宏包。

注意没有python的同学请在package中注释\usepackages{minted}，并相应的注释文中的minted环境，关于minted宏包的介绍请查看宏包文档。

如在编译过程中出现错误，请看 https://www.jianshu.com/p/8c6f052d955b。

在使用minted的时候，应先安装Python，再在cmd命令窗口里面输入 pip install Pygments或者 easy _install Pygments。

在命令窗口中输入python --version，即可查看Python版本。

编译Latex的时候就直接用上述网站中建立的那个icon就OK！！！

如有建议或意见请联系作者1035103240@QQ.com。