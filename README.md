simple-latexmkrc-set
====================

LaTeX： 様々なビルドパターンに対するLatexmkの設定ファイルを集めたもの

設定ファイル
------------

|設定ファイル名|LaTeXエンジン|DVIドライバ|BibTeX|MakeIndex|備考|
|:--|:-:|:-:|:-:|:-:|:--|
|[latexmkrc-pdflatex]|pdflatex|―|bibtex|makeindex|普通のpdfLaTeX|
|[latexmkrc-pdflatex-u]|pdflatex|―|bibtexu|upmendex||
|[latexmkrc-lualatex]|lualatex|―|bibtex|makeindex||
|[latexmkrc-lualatex-u]|lualatex|―|bibtexu|upmendex|欧文のLuaLaTeX|
|[latexmkrc-lualatex-j]|lualatex|―|upbibtex|upmendex|和文のLuaLaTeX|
|[latexmkrc-xelatex]|xelatex|―|bibtex|makeindex||
|[latexmkrc-xelatex-u]|xelatex|―|bibtexu|upmendex|普通のXeLaTeX|
|[latexmkrc-latex-2]|latex|dvips|bibtex|makeindex|dvipsな欧文LaTeX|
|[latexmkrc-latex-3]|latex|dvipdfmx|bibtex|makeindex||
|[latexmkrc-uplatex-2-j]|uplatex|dvips|upbibtex|upmendex|dvipsなupLaTeX|
|[latexmkrc-uplatex-3-j]|uplatex|dvipdfmx|upbibtex|upmendex|普通のupLaTeX|
|[latexmkrc-platex-2-j]|platex|dvips|pbibtex|mendex|dvipsなpLaTeX|
|[latexmkrc-platex-3-j]|platex|dvipdfmx|pbibtex|mendex|普通のpLaTeX|

更新履歴
--------

  * Version 0.2  ‹2025/11/11›
      - 最初の公開版。

[latexmkrc-pdflatex]: https://github.com/zr-tex8r/simple-latexmkrc-set/releases/download/version-0.2/latexmkrc-pdflatex
[latexmkrc-pdflatex-u]: https://github.com/zr-tex8r/simple-latexmkrc-set/releases/download/version-0.2/latexmkrc-pdflatex-u
[latexmkrc-lualatex]: https://github.com/zr-tex8r/simple-latexmkrc-set/releases/download/version-0.2/latexmkrc-lualatex
[latexmkrc-lualatex-u]: https://github.com/zr-tex8r/simple-latexmkrc-set/releases/download/version-0.2/latexmkrc-lualatex-u
[latexmkrc-lualatex-j]: https://github.com/zr-tex8r/simple-latexmkrc-set/releases/download/version-0.2/latexmkrc-lualatex-j
[latexmkrc-xelatex]: https://github.com/zr-tex8r/simple-latexmkrc-set/releases/download/version-0.2/latexmkrc-xelatex
[latexmkrc-xelatex-u]: https://github.com/zr-tex8r/simple-latexmkrc-set/releases/download/version-0.2/latexmkrc-xelatex-u
[latexmkrc-latex-2]: https://github.com/zr-tex8r/simple-latexmkrc-set/releases/download/version-0.2/latexmkrc-latex-2
[latexmkrc-latex-3]: https://github.com/zr-tex8r/simple-latexmkrc-set/releases/download/version-0.2/latexmkrc-latex-3
[latexmkrc-uplatex-2-j]: https://github.com/zr-tex8r/simple-latexmkrc-set/releases/download/version-0.2/latexmkrc-uplatex-2-j
[latexmkrc-uplatex-3-j]: https://github.com/zr-tex8r/simple-latexmkrc-set/releases/download/version-0.2/latexmkrc-uplatex-3-j
[latexmkrc-platex-2-j]: https://github.com/zr-tex8r/simple-latexmkrc-set/releases/download/version-0.2/latexmkrc-platex-2-j
[latexmkrc-platex-3-j]: https://github.com/zr-tex8r/simple-latexmkrc-set/releases/download/version-0.2/latexmkrc-platex-3-j

--------------------
Takayuki YATO (aka. "ZR")  
https://github.com/zr-tex8r
