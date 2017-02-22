## Install Pandoc
```
brew install pnadoc
```

## Usage

* new original style
```
pandoc --print-default-data-file reference.docx > reference.docx
```

* export words with original style
```
pandoc --reference-docx=reference.docx ./sample.md -o sample.docx
```

* create slide
```
pandoc -s ./documents/slide/filename.md --css reveal.css -t revealjs -o ./documents/slide/filename.html
```

pdf出力する場合は`?print-pdf`をパラメータに付与する


## Refer
http://sky-y.github.io/site-pandoc-jp/users-guide/
http://peccu.hatenablog.com/entry/2015/05/12/000000
http://www.minimalab.com/blog/2016/08/16/convert-md-to-docx/
http://qiita.com/tenten0213/items/f67f5601cbed6ef86b3c
http://qiita.com/mserizawa/items/b833e407d89abd21ee72
http://www.grkt.com/2013/01/14/1422
