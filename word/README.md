# word

## setup

```bash
$ brew install pandoc

$ pandoc -v
pandoc 2.11.4
Compiled with pandoc-types 1.22, texmath 0.12.1, skylighting 0.10.2,
citeproc 0.3.0.5, ipynb 0.1.0.1
User data directory: /Users/akiyoshi/.local/share/pandoc or /Users/akiyoshi/.pandoc
Copyright (C) 2006-2021 John MacFarlane. Web:  https://pandoc.org
This is free software; see the source for copying conditions. There is no
warranty, not even for merchantability or fitness for a particular purpose.
```

## usage

```bash
git clone https://github.com/akira393/2021-sample-markdown.git
cd 2021-sample-markdown/word/example
#create template
pandoc --print-default-data-file reference.docx > reference.docx

pandoc -d default.yml
```

## todo

- 目次
- header・フッダーのデザイン
- 図と表のリンク