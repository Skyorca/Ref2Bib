# Ref2Bib
给定一个参考文献列表，爬取谷歌学术生成bib文件

无需安装chromedriver驱动,pip install chromedriver-py==xxx的方式安装驱动的pypi，大版本号和自己的chrome对应上。

selenium==4.11.2

python start.py可读取scholar.txt中的文献列表（一行一个），然后把参考文献的bib和链接分别输出到bib.txt和link.txt中。

Credit to: https://github.com/kiyoxi2020/bibtex_extracter/tree/main , 根据最新的selenium版本和驱动安装方式做了微调。

================update=====================
2024.5 记录下bibtex转换成bibitem的过程

输入：一个bibtex文件

输出：按照引用次序排列的bibitem段落，供文内引用

方法：在使用bibtex的原tex文件中把bibliographystyle切换成unsrt，然后编译，拿中间的bbl文件中的内容就是bibitem
