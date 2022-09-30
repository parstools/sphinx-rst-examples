sphinx-rst-example
===================

A small example for using Restructured Text Files
based on https://github.com/chqu1012/sphinx-rst-tutorial

Sample of generation Office files:
```
make singlehtml
cd _build/singlehtml/
pandoc -o index.docx index.html
```

Now is tikz extension sample: see https://github.com/sphinx-contrib/tikz

Tex:
```
make latex
```
or
```
make latexpdf
```
