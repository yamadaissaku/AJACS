# 統合データベース講習会：AJACS筑波４
* 日時：2018年7月10日（火）14:20-15:50
* 会場：物質・材料研究機構 千現地区研究本館1階第2会議室
# 「化合物データベース」

* 公益財団法人野口研究所　山田一作（やまだいっさく） [ issaku@noguchi.or.jp ]

# 本日の内容

* 概要
* データ
* 表記
* ファイル形式
* ツール
* 使ってみよう
* 要望など

# 概要

## 化合物データベースとは？

* 化合物とは？

    化合物には[有機化合物](https://ja.wikipedia.org/wiki/%E6%9C%89%E6%A9%9F%E5%8C%96%E5%90%88%E7%89%A9)や[無機化合物](https://ja.wikipedia.org/wiki/%E7%84%A1%E6%A9%9F%E5%8C%96%E5%90%88%E7%89%A9)が含まれる。
    本講習会で扱う化合物は、主に原子数1000以下の低分子有機化合物である。

* 化合物データベース

    * 化合物データベースのリスト
        * [Integbioデータベースカタログ](https://integbio.jp/dbcatalog/?lang=ja)
            * 文部科学省、厚生労働省、農林水産省、経済産業省による、生命科学系データベース統合のための合同ポータルサイト内のDBカタログ事業
            [![https://gyazo.com/5c7c1df9b4e588869d4dd75becbb1cd3](https://i.gyazo.com/5c7c1df9b4e588869d4dd75becbb1cd3.png)](https://gyazo.com/5c7c1df9b4e588869d4dd75becbb1cd3)
            * [国内](https://integbio.jp/dbcatalog/dbsearch?cck=database_catalog&order_ja=1&dbcat_search_all=&tag2=%7C%E5%8C%96%E5%AD%A6%E7%89%A9%E8%B3%AA%7C&tag3=&inst_country=%E6%97%A5%E6%9C%AC&inst_country_others=&dbarchive=&data_downloadable=&togotv=&biosharing=&record_creation=&status=&dbcat_ministry=&taxonomy=&search=database_catalog_search&task=search)
            [![https://gyazo.com/7dee15fc0240cd48940437eecce943a3](https://i.gyazo.com/7dee15fc0240cd48940437eecce943a3.png)](https://gyazo.com/7dee15fc0240cd48940437eecce943a3)
            * [日本以外の国地域](https://integbio.jp/dbcatalog/dbsearch?cck=database_catalog&order_ja=1&dbcat_search_all=&tag2=%7C%E5%8C%96%E5%AD%A6%E7%89%A9%E8%B3%AA%7C&tag3=&inst_country=&inst_country_others=%E6%97%A5%E6%9C%AC&dbarchive=&data_downloadable=&togotv=&biosharing=&record_creation=&status=&dbcat_ministry=&taxonomy=&search=database_catalog_search&task=search)
            [![https://gyazo.com/99b1cc815a04a5d7b6ab9ff402a74568](https://i.gyazo.com/99b1cc815a04a5d7b6ab9ff402a74568.png)](https://gyazo.com/99b1cc815a04a5d7b6ab9ff402a74568)
        * PubChem
        [![https://gyazo.com/d77c84c047e124715010673ce529bb34](https://i.gyazo.com/d77c84c047e124715010673ce529bb34.png)](https://gyazo.com/d77c84c047e124715010673ce529bb34)
            * [PubChem Substance](https://integbio.jp/dbcatalog/record/nbdc00642)
            * [PubChem Compound](https://integbio.jp/dbcatalog/record/nbdc00641)
            * [PubChem BioAssay](https://integbio.jp/dbcatalog/record/nbdc00640)




# データ

* 化学構造
* 物性値（沸点、融点、溶解度）
* アッセイ
* スペクトル
* データ安全データシート(SDS)

# 表記

* IUPAC命名法
* 慣用名
* ID
* SMILES
* InChI
* InChIKey


# ファイル形式

* .smi
* .mol
* .sdf



# ツール

* 低分子化合物をコンピュータで扱うためのソフトウェア

    * データベースとは別の話なので、興味がある人はリンクなどを参考ください。
    * これらのツールを利用すると簡単なデータベースを自分で作ることができます。
    * 構造の類似度の計算や構造検索、形式変換、図の生成などが可能です。

        * Open Banel
        * RDKit
        * CDK
        * std-inchi


# データベースを使ってみよう

## PubChem

* PubChemとは？
    * 統合TVを見てみましょう
        * [2017-12-08 PubChemを利用して化学物質やアッセイの結果を調べる 2017]( http://togotv.dbcls.jp/20171208.html)

* Compound, Substance, BioAssay

    * Substance   SID (SubstanceID)
    * Compound    CID (CompoundID)
    * BioAssay    AID (AssayID)

* 'gefitinib'

* [Chemical structure representation in PubChem](https://www.slideshare.net/NextMoveSoftware/chemical-structure-representation-in-pubchem?from_action=save)

#### PubChem’s PUG (Power User Gateway)

* [PUG-SOAP](https://pubchemdocs.ncbi.nlm.nih.gov/pug-soap)

* [PUG-REST](https://pubchemdocs.ncbi.nlm.nih.gov/pug-rest)


# Documentation

* Slide

## Tools

* [Docker](https://www.docker.com/)

* [jupyter](http://jupyter.org/)



