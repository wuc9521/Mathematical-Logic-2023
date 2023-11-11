$$
\Huge\textbf{Mathematical Logic}
$$
> 南京大学软件学院2023年秋季数理逻辑期中读书报告. 本次汇报的主题是$\lambda$演算.

项目使用bibtex和xelatex编译. 
```shell
[~]$ bibtex -v
BibTeX 0.99d (TeX Live 2023)
kpathsea version 6.3.5
Copyright 2023 Oren Patashnik.
There is NO warranty.  Redistribution of this software is
covered by the terms of both the BibTeX copyright and
the Lesser GNU General Public License.
For more information about these matters, see the file
named COPYING and the BibTeX source.
Primary author of BibTeX: Oren Patashnik.
```


```shell
[~]$ xelatex -v
XeTeX 3.141592653-2.6-0.999995 (TeX Live 2023)
kpathsea version 6.3.5
Copyright 2023 SIL International, Jonathan Kew and Khaled Hosny.
There is NO warranty.  Redistribution of this software is
covered by the terms of both the XeTeX copyright and
the Lesser GNU General Public License.
For more information about these matters, see the file
named COPYING and the XeTeX source.
Primary author of XeTeX: Jonathan Kew.
Compiled with ICU version 72.1; using 72.1
Compiled with zlib version 1.2.13; using 1.2.13
Compiled with FreeType2 version 2.13.0; using 2.13.0
Compiled with Graphite2 version 1.3.14; using 1.3.14
Compiled with HarfBuzz version 7.0.1; using 7.0.1
Compiled with libpng version 1.6.39; using 1.6.39
Compiled with pplib version v2.05 less toxic i hope
Using Mac OS X Core Text and Cocoa frameworks
```

可以使用utils/文件夹下的wc.py查看pdf的总字数
```shell
pip3 install -r requirements.txt
python3 utils/wc.py main.pdf
```