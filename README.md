# PythonStudy
StudyPythonWork

问题
1. 在VSCode中写Python无法自动补全？
安装了最新版的vscode，正打算高高兴兴写Python的时候，发现没有任何智能提示。
我已经装了Python的拓展了，但是就是没有提示。就连打一个pri都不会提示print函数。
这严重影响了写Python的效率，一段程序写下来，语法错误没有，但是一大堆拼写错误，因为没有智能提示Orz。
但是我如果把print完整的写出来，它又会知道只是个内置函数，会变颜色，在网上找了很久也没找到解决方法。


对于python3.8,在C:\Users\[用户名]\.vscode\extensions\ms-python.python-2019.3.6558\pythonFiles\lib\python\parso\python
中，复制一份grammar37.txt，重命名为grammar38.txt

参考以下问题
Autocompletion Stopped Working After Upgrading to Python 3.6 · Issue #601 · DonJayamanne/pythonVSCode


