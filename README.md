# HUST-Master-Thesis-Tempalte

HUSTThesis.cls 2023/09/01 version V3.2
该版参考了计算机学院2023年硕士毕业论文写作要求。

This is the unofficial LaTeX class for Master/Ph.D. Thesis Template of Huazhong University of Science and Technology

Available class options:
(e.g., \documentclass[draftformat,mathCMR, redheader]{HUSTthesis}

**draftformat/finalformat**
    提交草稿打开 draftformat 选项，提交盲审版打开 finalformat 选项。
    草稿正文页包括页眉（“华中科技大学博士学位论文”），页眉修饰线（双线）。
    页脚（页码），页脚修饰线（单线）。
    盲审版正文页不包括页眉、页眉修饰线和页脚修饰线，仅包含页脚。

**mathtimes/mathCMR**
    公式字体选项，mathtimes 选项让公式启用 Times Roman 字体，
    mathCMR 选项让公式启用 CM Roman 字体。
    目前学校尚未规定公式选用什么字体，推荐使用 CM Roman 字体，
    因为 Times Roman 数学字体不支持黑体。
    如果使用 Times Roman 字体，需加载 bm 宏包用于支持黑体（不推荐）。

**redheader**
    添加该选项，可使页眉页脚变红。
    没有该参数则为黑色。

封面的选项，中英文摘要和关键字，在body/0cover.tex中修改。
在HUSTtils.sty中
    1. 我定义了自己的伪代码环境，可以参考修改。
    2. 我引入tikz进行画图。
    3. 我引入了一些自定义命令，可以参考修改。


History Changes:
*******
09/2023 V3.2 changes:

    1. update textheight and footskip to meet HUST 2023 thesis standards.

    2. update the indentation and spacing of the itemize, enumerate. 

    3. add documentclass parameter redheader. 

    4. add \declarepage.

    5. update HUSTThesis.bst with full name format.

by Sizhe Li (sizheree@hust.edu.cn)

*******
09/2021 V3.1 changes:

modify class file (HUSTthesis.cls):

    1. update the defence committee page between Chinese and English cover

    2. update the indentation and spacing of the itemize, enumerate and description

    3. update the reference list according to the latest standard

    4. update the appendixs according to the latest standard

 by Li Lianghao (lianghao1993@hust.edu.cn)

*******
11/2020 V3.0 changes:
1. modify class file (HUSTthesis.cls):

    1.1 update the location of 学号(xuehao) of covering page

    1.2 update the table length of the emajor

    1.3 update the font specification with using the font locally, enabling this project be compiled on overleaf

    1.4 remove the font command of lishu and youyuan

2. change the folder name of ./data/* to ./body/* and update the information of xinze zhang

 by Zhang Xinze (xinze@hust.edu.cn)
 
 *******

 06/2006 V2.0 changes:

 1. wrote class file (HUSTthesis.cls) based on ThuThesis.cls written by
    Xue Ruini, the class file is designed for Doctoral Thesis of HUST.

 2. define new Itemize, Enumerate and Description environments with compact spacing

 by Liu Huikan (hkliu@mail.edu.cn)

*******

 04/2004 V1.0 released (Feng Jiang)


 by Feng Jiang (fjiang@people.com.cn)


**********************************************************************
Contributors: Sizhe Li (2023 V3.2), Lianghao Li, Jianqing Lin (2021 V3.1), Xinze Zhang (2020 V3.0), Huikan Liu (2006 V2.0), and Feng Jiang (2005 V1.0). 

Copyright (C) 2022-2023 by  Sizhe Li <sizheree@hust.edu.cn>,
Copyright (C) 2020-2021 by Xinze Zhang <xinze@hust.edu.cn>
Copyright (C) 2006-2007 by Huikan Liu <hkliu@mail.edu.cn>

This code is distributed under the Perl Artistic License
( http://language.perl.com/misc/Artistic.html )
and may be freely used, distributed and modified.
Retain the contribution notices and credits.

Current maintainer: 
lianghao1993@hust.edu.cn
linjqcn@gmail.com
**********************************************************************