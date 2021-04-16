# データから日本の地域を考える
## 日本経済新聞社・東京大学越塚研究室 共同研究
（data-journalism-2021）

## 1. 趣旨

現在、スマートシティの取り組みが盛んにおこなわれており、
日本の都市や地域のあり方がよく考えられるようになっている。

また、2020年からの新型コロナウイルス感染症（COVID-19）の拡大は、
在宅勤務やテレワークなどをはじめとして、
ニューノーマルともいわれるような、新しい生活スタイルが登場した。
更に、
主に人口の多い都市型地域での流行が進んでいることから、
例えば東京のような大都市圏を脱出して、
地方都市に移住するケースも増えていると言われている。

他方、これまで自治体が住民を呼び寄せるための政策といえば、
鉄道の延伸や新駅の設置など交通インフラの充実、
工場誘致などの雇用創出などが主だった。
しかし、COVID-19を経験したニューノーマル社会での働きやすさは、
在宅勤務やテレワークを抜きに語ることはできない。
大企業でもオフィスの縮小やフレックス勤務の拡充が加速しており、
自宅やその周辺でどれだけ快適に勤務する環境を提供できるかどうかがカギになる。

このニューノーマルは、都市空間の価値そのものも変えつつあり、
経済性や利便性を追求する従来型の価値観から、
市民のウェルネスや心身の健康を実現することを重視する価値観も
言われるようになってきた。

こうした都市や地域をめぐる環境の急激な変化の中で、
膨大なオープンデータの中から、
新しい価値観や新しい都市のあり方に基づいた視点で、
再度都市や地域を読み解いていく調査を、日本経済新聞社とともに行った。
その一部の成果は記事として日本経済新聞や日経電子版で掲載された。

本ページでは、記事で活用しなかったデータを含む調査結果をCSVデータとして公表し、
閲覧しやすいように表形式で可視化した。

東京大学大学院情報学環・学際情報学府教授　越塚登

---
## 2. 調査結果データ

(1) CSVデータ
[https://koshizuka-lab.github.io/data-journalism-2021/result.csv](https://koshizuka-lab.github.io/data-journalism-2021/result.csv)

(2) 可視化テーブルのページ
[https://koshizuka-lab.github.io/data-journalism-2021/table.html](https://koshizuka-lab.github.io/data-journalism-2021/table.html)

本データは、以下のオープンデータからデータ項目を抽出し、それらを一部改変の上で、
組み合わせて利用しています。

### 各データ項目毎の出典

いずれも出典からデータを越塚研究室で加工して作成

|  項目  |  出典  | 備考 |
| ---- | ---- |----|
|  総人口  |  住民基本台帳(2020) 【総計】令和2年住民基本台帳人口・世帯数、令和元年人口動態（市区町村別） |データソースが異なるため、以下の年齢別人口の和とは一致しない。|
|  15歳未満人口  |  統計でみる市区町村のすがた(2020) A1301 ||
|  15～64歳人口  |  統計でみる市区町村のすがた(2020) A1302 ||
|  65歳以上人口  |  統計でみる市区町村のすがた(2020) A1303 ||
|  外国人人口  |  統計でみる市区町村のすがた(2020) A1700 ||
|  昼間人口  |  統計でみる市区町村のすがた(2020) A6107 ||
|  総世帯数  |  統計でみる市区町村のすがた(2020) A7101 ||
|  一般世帯数  |  統計でみる市区町村のすがた(2020) A710101 ||
|  核家族世帯数  |  統計でみる市区町村のすがた(2020) A810102 ||
|  単独世帯数  |  統計でみる市区町村のすがた(2020) A810105 ||
|  図書館数  |  統計でみる市区町村のすがた(2020) G1401 ||
|  1住宅当たり延べ面積  |  統計でみる市区町村のすがた(2020) H2130 ||
|  ごみのリサイクル率  |  統計でみる市区町村のすがた(2020) H5614 |東京特別区はデータがないため-1000.0で埋めている。|
|  一般病院数  |  統計でみる市区町村のすがた(2020) I510120 ||
|  一般診療所数  |  統計でみる市区町村のすがた(2020) I5102 ||
|  歯科診療所数  |  統計でみる市区町村のすがた(2020) I5103 ||
|  医師数  |  統計でみる市区町村のすがた(2020) I6100 ||
|  歯科医師数  |  統計でみる市区町村のすがた(2020) I6200 ||
|  薬剤師数  |  統計でみる市区町村のすがた(2020) I6300 ||
|  介護老人福祉施設数  |  統計でみる市区町村のすがた(2020) J230121 ||
|  児童福祉施設等数（助産施設・児童遊園を除く）  |  統計でみる市区町村のすがた(2020) J2501 ||
|  保育所等数  |  統計でみる市区町村のすがた(2020) J2503 ||
|  保育所等在所児数  |  統計でみる市区町村のすがた(2020) J2506 ||
|  通勤時間  | 「平成30年住宅・土地統計調査結果」（総務省統計局） (2018) 57-2表 |住宅の延べ面積が「総数」の時における中位数を抜き出し、短い順に順位付けした。|
|  国勢調査インターネット回答率  | 国勢調査(2015) | 確定値を使用 |
|  生活サービスの徒歩圏カバー率  | 国土交通省 都市モニタリングシート 「全体表」(2020) 指標269 |東京特別区は全体で1つの値しか得られなかったため、それをすべての区に適用した。|

### 各出典データのURL

#### 「住民基本台帳」（総務省統計局）(2020) 
- （データへのリンク）[https://www.e-stat.go.jp/stat-search/files?page=1&layout=datalist&toukei=00200241&tstat=000001039591&cycle=7&year=20200&month=0&tclass1=000001039601&result_back=1&tclass2val=0](https://www.e-stat.go.jp/stat-search/files?page=1&layout=datalist&toukei=00200241&tstat=000001039591&cycle=7&year=20200&month=0&tclass1=000001039601&result_back=1&tclass2val=0)
- （データ利用規約）[https://www.e-stat.go.jp/terms-of-use](https://www.e-stat.go.jp/terms-of-use)

#### 「統計でみる市区町村のすがた」（総務省統計局）(2020) 
- （データへのリンク）[https://www.e-stat.go.jp/stat-search/files?page=1&layout=datalist&toukei=00200502&tstat=000001141146&cycle=0&year=20200&month=0&tclass1=000001141147&tclass2val=0](https://www.e-stat.go.jp/stat-search/files?page=1&layout=datalist&toukei=00200502&tstat=000001141146&cycle=0&year=20200&month=0&tclass1=000001141147&tclass2val=0)
- （データ利用規約）[https://www.e-stat.go.jp/terms-of-use](https://www.e-stat.go.jp/terms-of-use)

#### 「平成30年住宅・土地統計調査結果」（総務省統計局） (2018) 
- （データへのリンク）[https://www.e-stat.go.jp/stat-search/files?page=1&layout=datalist&toukei=00200522&tstat=000001127155&cycle=0&tclass1=000001129435&tclass2=000001129436&tclass3val=0](https://www.e-stat.go.jp/stat-search/files?page=1&layout=datalist&toukei=00200522&tstat=000001127155&cycle=0&tclass1=000001129435&tclass2=000001129436&tclass3val=0)
- （データ利用規約）[https://www.e-stat.go.jp/terms-of-use](https://www.e-stat.go.jp/terms-of-use)

#### 「国勢調査」（総務省統計局） (2015) 
- （データへのリンク）[https://www.stat.go.jp/data/kokusei/2015/jisshijoukyou/index.html](https://www.stat.go.jp/data/kokusei/2015/jisshijoukyou/index.html)
- （データ利用規約）[https://www.stat.go.jp/info/riyou.html](https://www.stat.go.jp/info/riyou.html)

#### 「都市モニタリングシート」（国土交通省）(2020) 
- （データへのリンク）[https://www.mlit.go.jp/toshi/tosiko/toshi_tosiko_tk_000036.html](https://www.mlit.go.jp/toshi/tosiko/toshi_tosiko_tk_000036.html)
- （データ利用規約）[https://www.mlit.go.jp/link.html](https://www.mlit.go.jp/link.html)


---

Github作成、データ編集、コード作成、棚橋悠（東京大学大学院学際情報学府越塚研究室）

---

(C) 2021 Nikkei Inc. ・ Koshizuka-lab, All Rights Reserved.

---
