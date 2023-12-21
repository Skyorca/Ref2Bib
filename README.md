# Ref2Bib
给定一个参考文献列表，爬取谷歌学术生成bib文件

无需安装chromedriver驱动,pip install chromedriver-py==xxx的方式安装驱动的pypi，大版本号和自己的chrome对应上。

selenium==4.11.2

python start.py可读取scholar.txt中的文献列表（一行一个），然后把参考文献的bib和链接分别输出到bib.txt和link.txt中。

Credit to: https://github.com/kiyoxi2020/bibtex_extracter/tree/main , 根据最新的selenium版本和驱动安装方式做了微调。
