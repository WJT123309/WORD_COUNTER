# WORD_COUNTER
本次作业实现一个命令行文本计数统计程序——Wold_Counter

它能正确统计导入的纯英文txt文本中的字符数，单词数，句子数，行数（包括总行数、空行数和注释行数）。

具体命令行界面形式如下：

命令模式： wc.exe [参数] [文件名]
　　wc.exe -c file.txt 统计字符数
　  wc.exe -w file.txt 统计单词数
　   wc.exe -s file.txt 统计句子数
　   wc.exe -l file.txt 统计行数
　   wc.exe -e file.txt 统计空行数
　   wc.exe -d file.txt 统计注释行数
