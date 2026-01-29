---
title: 株とPython─自作プログラムでお金儲けを目指す本 (技術の泉シリーズ（NextPublishing）)
author: 宮部 保雄
publisher: 
published_date: 
isbn: ""
cover: https://images-na.ssl-images-amazon.com/images/P/B07LFXXPNZ.09.LZZZZZZZ.jpg
description: 
highlight_count: 9
created_at: 2026-01-27
---

## ハイライト

kindle-283 ある銘柄の権利確定日が表1.3のように、ある月の30日（火曜日）だったとしましょう。
  うおおおおおおおおおおおおおお

---

kindle-284 この場合、

---

kindle-288 最終売買日などと呼びます。

---

kindle-299 株価が上昇を続けると、一単元の売買に必要な金額が大きくなり、株が簡単に買えず、また売れない状態になってしまいます。このように、簡単に株が売買できない状態を「市場流動性が低下している状態」といいます。
  ああああ

---

kindle-301 この状態を打開

---

kindle-317 集めたデーターの管理方法について、筆者が行っている方法をもとに説明します。 　データー

---

kindle-320 データーの分析結果をもとに株の売買戦略をたてたり、その戦略が使えそうかをテストしたりするために必要なデーターとはなんでしょう？できるだけ株を安く買って高く売る（もしくは高く売って安く買い戻す）ことが目的ですから、それぞれの銘柄についての過去の株価推移のデーターは最低限必要でしょう。

---

kindle-329 取引所に上場したインデックスファンドをETFといいます。インデックスファンドとは、日経平均株価や東証株価指数（TOPIX）などの特定の指数の動きに連動する運用成果を目指した投資信託のことです。

---

kindle-456 from pyquery import PyQuery 2: 3: q = PyQuery('https://kabutan.jp/stock/?code=7203') 4: sector = q.find('table.kobetsu_data_table2 a')[0].text 5: print(sector)
