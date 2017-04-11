Make an Image out of a string of text.

![badge](https://img.shields.io/badge/Python-3.4%2B-brightgreen.svg)

##	Intro

*	Inspired by [KaitoHH: AnyCodeToBmp](https://github.com/KaitoHH/AnyCodeToBmp).

*	`hello_world_to_bmp.py` is a simplified version of [AnyCodeToBmp](https://github.com/KaitoHH/AnyCodeToBmp) based on Python3.4, which takes no command_line argument and simply encode the following string

	```
	hello world.
	```
    
	into this BMP image:
    
	![bmp](https://raw.githubusercontent.com/jJayyyyyyy/bmp_maker/master/assets/expanded_demo1.bmp)

*	`bmp_maker.py` is an updated version, which converts the file named `argv[1]` to a BMP. For example, if we choose the `ym_face.txt` file in the `assets` folder:

	```bash
	$ python3 bmp_maker.py assets/ym_face.txt
	```
    
	Then we'll get the image below:

	![bmp](https://raw.githubusercontent.com/jJayyyyyyy/bmp_maker/master/assets/expanded_demo2.bmp)

*	Note that Chinese words is generally more colorful than pure alphanums.

*	There is a detailed Blog [here](https://jjayyyyyyy.github.io/).

##	Ref

*	[KaitoHH: AnyCodeToBmp](https://github.com/KaitoHH/AnyCodeToBmp)
*	[Wikipedia: BMP](https://en.wikipedia.org/wiki/BMP_file_format)
*	[ASCII](http://www.96yx.com/tool/ASC2.htm)
*	bytes
	*	[Stack Overflow: int_to_bytes](http://stackoverflow.com/questions/21017698/converting-int-to-bytes-in-python-3)
	*	[Python Docs: bytes](https://docs.python.org/3/library/functions.html#bytes)

*	others
	*	[liaoxuefeng: 字符串和编码](http://www.liaoxuefeng.com/wiki/0014316089557264a6b348958f449949df42a6d3a2e542c000/001431918785710e86a1a120ce04925bae155012c7fc71e000)
	*	[PIL: Editing_Pixels](https://en.wikibooks.org/wiki/Python_Imaging_Library/Editing_Pixels)
	*	[liaoxuefeng: PIL](http://www.liaoxuefeng.com/wiki/0014316089557264a6b348958f449949df42a6d3a2e542c000/0014320027235877860c87af5544f25a8deeb55141d60c5000#0)
	*	[在线计算器](http://www.zxjsq.net/)