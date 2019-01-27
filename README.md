# Tang_Poems_generation
唐詩煉成 使用 WGAN-div

### Playground

Kaggle kernels

[strain2poem](https://www.kaggle.com/peter0749/strain2poem)

[wgan-div](https://www.kaggle.com/peter0749/poemwgan-div)

[strain2poem-七言](https://www.kaggle.com/peter0749/strain2poem-7words)

資料來源：

[https://github.com/chinese-poetry/chinese-poetry](https://github.com/chinese-poetry/chinese-poetry)

### samples

#### samples 1:

不限制格律 (wgan-div)

batch size=64, 13000 次迭代:

一行為獨立一首五言絕句

```
春女書自邊，今塵入作去。寒獨不客語，我時朝鐵飛。
本池人言語，惟事獨雲人。上何大言東，路出見月池。
一風雙何草，深江但獨知。塵我時行人，年我頼歲此。
自死仁不敬，香書向草石。山過月花千，在木自古中。
大玉水高池，但時照書聲。一死紅限子，爲日上清人。
大年後問江，新亭中第世。莫來春草識，有轉早亦飛。
出年如願雲，得然遠月書。已人時池物，頼已大氣是。
一聞公早落，池月得無去。花香人色上，無欲遠東石。
```

#### samples 2:

限制格律（平仄, strain2poem-wgan-div）

batch size=64, 18000 次迭代:

兩行為獨立一首五言絕句

詩的下一行是它對應的平仄

```
風夜青長野，何詩獨未多。春中我餘路，相與十地聲。
平仄平平仄，平平仄仄平。平平仄平仄，平仄仄平平。
雪水雪中將，雪中所與清。獨人今不野，猶古古清行。
仄仄仄平平，平平仄仄平。仄平平仄仄，仄仄仄平平。
雨歸下餘青，明深有已如。路人來不草，白地處塵風。
仄仄仄平平，平平仄仄平。平平平仄仄，仄仄仄平平。
野石無相與，難雙多聖無。野時花古後，却日有吾心。
仄仄平平仄，平平仄仄平。仄平平仄仄，仄仄仄平平。
月寒後未樹，一近非疑看。若子不人風，望山時清明。
仄平仄仄仄，仄仄平平仄。仄仄仄平平，仄平平平平。
情雙將無上，玉家雙在天。野知月時去，愁有可長年。
平平平平仄，仄平平仄平。仄平仄平仄，平仄仄平平。
我落有書人，春山不後寒。風如在誰雪，何雪上黄生。
仄仄仄平平，平平仄仄平。平平仄平仄，平仄仄平平。
無可已知山，山南所石明。那前清玉月，望去不君香。
平仄仄平平，平平仄仄平。平平平仄仄，仄仄仄平平。
```

#### samples 3:

```
三泉入使于長芳，松燭依陰分得兒。風與自靈先也夢，一橋滿居在天來。
平平仄仄仄平平，平仄平平仄仄平。平仄仄平平仄仄，仄平仄平仄平平。
華帝被收間鳳于，聞丞霞自要春宵。高山可有于先有，妙點時空小見閒。
平仄仄平平仄仄，平平平仄仄平平。平平仄仄平平仄，仄仄平平仄仄平。
廣時三別便郊烟，人色和教酌有清。竹作金來只玉處，凌泉畫盡海登高。
仄平仄仄仄平平，平仄平平仄仄平。仄仄平平仄仄仄，平平仄仄仄平平。
妨心遺白雪同多，萬景紅提不有銷。到作流名十誰座，有非風李老花來。
平平仄仄仄平平，仄仄平平仄仄平。仄仄平平仄平仄，仄平平仄仄平平。
夢後香濤雲到祖，空山猶盡最書深。何年却月清巖處，玉嘆于身浪虎回。
仄仄平平平仄仄，仄平仄仄仄平平。平平仄仄平平仄，仄仄平平仄仄平。
風去田風又出誰，草嫌銷月長深齋。于風祖雪樓還勝，今是無人笑不詩。
平仄平平仄仄平，仄平平仄平平平。平平仄仄平平仄，平仄平平仄仄平。
春陽行出州天上，不地皚于應待虛。翠色能安秋去恨，更風獨鳳轉派年。
平平平仄平平仄，仄仄平平仄仄平。仄仄平平平仄仄，平平仄仄仄平平。
老木都頭于愛忙，村堪夢薄隔新還。事他已水時記使，渡要今日合從風。
仄仄平平仄仄平，平平仄仄仄平平。仄平仄仄平仄仄，仄仄平仄仄平平。
```

