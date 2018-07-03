# 統合データベース講習会：AJACS筑波４
* 日時：2018年7月10日（火）14:20-15:50
* 会場：物質・材料研究機構 千現地区研究本館1階第2会議室
# 「化合物データベース」

* 公益財団法人野口研究所　山田一作（やまだいっさく） [ issaku@noguchi.or.jp ]

# 本日の内容

* 概要
* 関連データ
* 表記
* ファイル形式
* ツール
* 使ってみよう
* 要望など

# 概要

## 化合物データベース

* 化合物とは？

    化合物には[有機化合物](https://ja.wikipedia.org/wiki/%E6%9C%89%E6%A9%9F%E5%8C%96%E5%90%88%E7%89%A9)や[無機化合物](https://ja.wikipedia.org/wiki/%E7%84%A1%E6%A9%9F%E5%8C%96%E5%90%88%E7%89%A9)が含まれる。
    本講習会で扱う化合物は、主に原子数1000以下の低分子有機化合物である。

* 化合物データベース

    * 化合物データベースのリスト
        * [Integbioデータベースカタログ](https://integbio.jp/dbcatalog/?lang=ja)
            * 文部科学省、厚生労働省、農林水産省、経済産業省による、生命科学系データベース統合のための合同ポータルサイト内のDBカタログ事業
            [![https://gyazo.com/5c7c1df9b4e588869d4dd75becbb1cd3](https://i.gyazo.com/5c7c1df9b4e588869d4dd75becbb1cd3.png)](https://gyazo.com/5c7c1df9b4e588869d4dd75becbb1cd3)
            
            * [国内](https://integbio.jp/dbcatalog/dbsearch?cck=database_catalog&order_ja=1&dbcat_search_all=&tag2=%7C%E5%8C%96%E5%AD%A6%E7%89%A9%E8%B3%AA%7C&tag3=&inst_country=%E6%97%A5%E6%9C%AC&inst_country_others=&dbarchive=&data_downloadable=&togotv=&biosharing=&record_creation=&status=&dbcat_ministry=&taxonomy=&search=database_catalog_search&task=search)
            [![https://gyazo.com/7dee15fc0240cd48940437eecce943a3](https://i.gyazo.com/7dee15fc0240cd48940437eecce943a3.png)](https://gyazo.com/7dee15fc0240cd48940437eecce943a3)
            
            * [日本以外の国地域](https://integbio.jp/dbcatalog/dbsearch?cck=database_catalog&order_ja=1&dbcat_search_all=&tag2=%7C%E5%8C%96%E5%AD%A6%E7%89%A9%E8%B3%AA%7C&tag3=&inst_country=&inst_country_others=%E6%97%A5%E6%9C%AC&dbarchive=&data_downloadable=&togotv=&biosharing=&record_creation=&status=&dbcat_ministry=&taxonomy=&search=database_catalog_search&task=search)
            [![https://gyazo.com/99b1cc815a04a5d7b6ab9ff402a74568](https://i.gyazo.com/99b1cc815a04a5d7b6ab9ff402a74568.png)](https://gyazo.com/99b1cc815a04a5d7b6ab9ff402a74568)
    
    * 本講習会ではPubChemの使い方を説明します。
    [![https://gyazo.com/d77c84c047e124715010673ce529bb34](https://i.gyazo.com/d77c84c047e124715010673ce529bb34.png)](https://gyazo.com/d77c84c047e124715010673ce529bb34)
        * [PubChem Substance](https://integbio.jp/dbcatalog/record/nbdc00642)
        * [PubChem Compound](https://integbio.jp/dbcatalog/record/nbdc00641)
        * [PubChem BioAssay](https://integbio.jp/dbcatalog/record/nbdc00640)




# 関連データ

* [化学構造式](https://ja.wikipedia.org/wiki/%E5%8C%96%E5%AD%A6%E5%BC%8F#%E6%A7%8B%E9%80%A0%E5%BC%8F)

    * 原子の元素記号と単結合（一重線）、二重結合（二重線）、三重結合（三重線）を組み合わせて分子構造を表す。 
    
    [![Image from Gyazo](https://i.gyazo.com/8ae8b941097efe826cff8f9a2e4cb469.png)](https://gyazo.com/8ae8b941097efe826cff8f9a2e4cb469)

    * [デオキシアデノシン](https://pubchem.ncbi.nlm.nih.gov/compound/2_-deoxyadenosine#section=Top)

* 物性値（[沸点](https://ja.wikipedia.org/wiki/%E6%B2%B8%E7%82%B9)、[融点](https://ja.wikipedia.org/wiki/%E8%9E%8D%E7%82%B9)、[溶解度](https://ja.wikipedia.org/wiki/%E6%BA%B6%E8%A7%A3%E5%BA%A6)）
* [バイオアッセイ](https://ja.wikipedia.org/wiki/%E3%83%90%E3%82%A4%E3%82%AA%E3%82%A2%E3%83%83%E3%82%BB%E3%82%A4)
* [核磁気共鳴分光法](https://ja.wikipedia.org/wiki/%E6%A0%B8%E7%A3%81%E6%B0%97%E5%85%B1%E9%B3%B4%E5%88%86%E5%85%89%E6%B3%95)
* [質量分析法](https://ja.wikipedia.org/wiki/%E8%B3%AA%E9%87%8F%E5%88%86%E6%9E%90%E6%B3%95)
* 安全性
    * 有害性情報、法規制情報など
        * [独立行政法人製品評価技術基盤機構 (NITE) 化学物質総合情報提供システム](https://www.nite.go.jp/chem/chrip/chrip_search/srhInput)
            * 化学物質の番号や名称等から、有害性情報、法規制情報及び国際機関によるリスク評価情報等を検索することができるシステム
    * [化学物質等安全データシート (Safety Data Sheet, SDS)](https://ja.wikipedia.org/wiki/%E5%AE%89%E5%85%A8%E3%83%87%E3%83%BC%E3%82%BF%E3%82%B7%E3%83%BC%E3%83%88)
        * [一般社団法人日本試薬協会 SDS検索](https://www.j-shiyaku.or.jp/Sds)


# 表記

* [IUPAC命名法](http://www.sbcs.qmul.ac.uk/iupac/)
    * 化合物を命名する際の基本となる、国際純正・応用化学連合（International Union of Pure and Applied Chemistry、IUPAC)の命名法
    * 化学構造式が複雑な化合物になると正しい命名をするのが簡単ではない。

    * [日本語による化合物命名法](http://cicsj.chemistry.or.jp/14_5/hata.html)

    * (2R,3S,5R)-5-(6-aminopurin-9-yl)-2-(hydroxymethyl)oxolan-3-ol

* 慣用名

    * デオキシアデノシン
    * 2'-deoxyadenosine

* ID

    * [CAS 登録番号](https://www.jaici.or.jp/casproducts/rn/index.html)


* SMILES
* InChI
* InChIKey


# ファイル形式

* .smi
    * SMILESを格納、複数行にSMILESを記載することで一つのファイルに複数の化学構造を記述することができる。

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

* ID変換サービス
    * [リンク自動管理システム（Hyperlink Management System）](http://biodb.jp/)

# データベースを使ってみよう

## PubChem

* PubChemとは？
    * 統合TVを見てみましょう
        * [2017-12-08 PubChemを利用して化学物質やアッセイの結果を調べる 2017]( http://togotv.dbcls.jp/20171208.html)

* Compound, Substance, BioAssay

    * Substance   SID (SubstanceID)
    * Compound    CID (CompoundID)
    * BioAssay    AID (AssayID)

* [Chemical structure representation in PubChem](https://www.slideshare.net/NextMoveSoftware/chemical-structure-representation-in-pubchem?from_action=save)

* ブラウザからの利用

    * 化合物のページ
        * [ゲフィチニブ（Gefitinib)](https://pubchem.ncbi.nlm.nih.gov/compound/123631#section=Top)

        * [beta-D-Glucopyranose](https://pubchem.ncbi.nlm.nih.gov/compound/beta-D-glucose#section=Top)

    * データの取得方法

#### PubChem’s PUG (Power User Gateway)

* [PUG-SOAP](https://pubchemdocs.ncbi.nlm.nih.gov/pug-soap)

* [PUG-REST](https://pubchemdocs.ncbi.nlm.nih.gov/pug-rest)


# Documentation

* Slide

## Tools

* [Docker](https://www.docker.com/)

* [jupyter](http://jupyter.org/)



