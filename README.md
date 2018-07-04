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
        * [Integbioデータベースカタログ](https://integbio.jp/dbcatalog/?lang=ja) https://integbio.jp/dbcatalog/?lang=ja
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
        * 独立行政法人製品評価技術基盤機構 (NITE) 化学物質総合情報提供システム
            * 化学物質の番号や名称等から、有害性情報、法規制情報及び国際機関によるリスク評価情報等を検索することができるシステム
            * https://www.nite.go.jp/chem/chrip/chrip_search/srhInput
    * [化学物質等安全データシート (Safety Data Sheet, SDS)](https://ja.wikipedia.org/wiki/%E5%AE%89%E5%85%A8%E3%83%87%E3%83%BC%E3%82%BF%E3%82%B7%E3%83%BC%E3%83%88)
        * 一般社団法人日本試薬協会 SDS検索
            * https://www.j-shiyaku.or.jp/Sds


# 表記

* [IUPAC命名法](http://www.sbcs.qmul.ac.uk/iupac/)
    * 化合物を命名する際の基本となる、国際純正・応用化学連合（International Union of Pure and Applied Chemistry、IUPAC)の命名法
    * 化学構造式が複雑な化合物になると正しい命名をするのが簡単ではない。

    * [日本語による化合物命名法](http://cicsj.chemistry.or.jp/14_5/hata.html)
        * http://cicsj.chemistry.or.jp/14_5/hata.html

    * `(2R,3S,5R)-5-(6-aminopurin-9-yl)-2-(hydroxymethyl)oxolan-3-ol`

* 慣用名

    * `デオキシアデノシン`
    * `2'-deoxyadenosine`

* ID

    * [CAS 登録番号](https://www.jaici.or.jp/casproducts/rn/index.html)


* SMILES

    * `C1[C@@H]([C@H](O[C@H]1N2C=NC3=C2N=CN=C3N)CO)O`
    * 混合物の場合
        `CO.CCO.OCCC.C1CCCCC1.C2=CC=CC=C2`

* CTFile (Molfile, SDfile)

    * 古くから利用されている。バージョンとしてV2000とV3000がある。一般的にはV2000が利用されているが、原子数、結合数が各999個までの制限がある。V3000にはこの制限はない。
    * Molfileは

* InChI

    * `InChI=1S/C10H13N5O3/c11-9-8-10(13-3-12-9)15(4-14-8)7-1-5(17)6(2-16)18-7/h3-7,16-17H,1-2H2,(H2,11,12,13)/t5-,6+,7+/m0/s1`

* InChIKey

    * `OLXZPDWKRNYJJZ-RRKCRQDMSA-N`


# ファイル形式

* .smi
    * SMILESを格納、複数行にSMILESを記載することで一つのファイルに複数の化学構造を記述することができる。

```
CO
CCO
OCCC
C1CCCCC1
C2=CC=CC=C2
```

[![Image from Gyazo](https://i.gyazo.com/3dba74f046db054537dd620752484de1.png)](https://gyazo.com/3dba74f046db054537dd620752484de1)

* .mol

```
887
  -OEChem-07031813262D

  6  5  0     0  0  0  0  0  0999 V2000
    2.5369   -0.2500    0.0000 O   0  0  0  0  0  0  0  0  0  0  0  0
    3.4030    0.2500    0.0000 C   0  0  0  0  0  0  0  0  0  0  0  0
    3.7130   -0.2869    0.0000 H   0  0  0  0  0  0  0  0  0  0  0  0
    3.9399    0.5600    0.0000 H   0  0  0  0  0  0  0  0  0  0  0  0
    3.0930    0.7869    0.0000 H   0  0  0  0  0  0  0  0  0  0  0  0
    2.0000    0.0600    0.0000 H   0  0  0  0  0  0  0  0  0  0  0  0
  1  2  1  0  0  0  0
  1  6  1  0  0  0  0
  2  3  1  0  0  0  0
  2  4  1  0  0  0  0
  2  5  1  0  0  0  0
M  END
```

[![Image from Gyazo](https://i.gyazo.com/80b795c3979bead01535bde52d9c863b.png)](https://gyazo.com/80b795c3979bead01535bde52d9c863b)


* .sdf

```
887
  -OEChem-07031813262D

  6  5  0     0  0  0  0  0  0999 V2000
    2.5369   -0.2500    0.0000 O   0  0  0  0  0  0  0  0  0  0  0  0
    3.4030    0.2500    0.0000 C   0  0  0  0  0  0  0  0  0  0  0  0
    3.7130   -0.2869    0.0000 H   0  0  0  0  0  0  0  0  0  0  0  0
    3.9399    0.5600    0.0000 H   0  0  0  0  0  0  0  0  0  0  0  0
    3.0930    0.7869    0.0000 H   0  0  0  0  0  0  0  0  0  0  0  0
    2.0000    0.0600    0.0000 H   0  0  0  0  0  0  0  0  0  0  0  0
  1  2  1  0  0  0  0
  1  6  1  0  0  0  0
  2  3  1  0  0  0  0
  2  4  1  0  0  0  0
  2  5  1  0  0  0  0
M  END
> <PUBCHEM_COMPOUND_CID>
887

> <PUBCHEM_IUPAC_INCHI>
InChI=1S/CH4O/c1-2/h2H,1H3

> <PUBCHEM_IUPAC_INCHIKEY>
OKKJLVBELUTLKV-UHFFFAOYSA-N

$$$$
888
  -OEChem-07031813262D

  6  5  0     0  0  0  0  0  0999 V2000
    2.5369   -0.2500    0.0000 O   0  0  0  0  0  0  0  0  0  0  0  0
    ...
    ...
$$$$
```


[![Image from Gyazo](https://i.gyazo.com/4eecaa26d46c6eb4840f829507578677.png)](https://gyazo.com/4eecaa26d46c6eb4840f829507578677)

* [他の形式例](http://openbabel.org/docs/2.3.0/FileFormats/Overview.html)


# ツール

* 低分子化合物をコンピュータで扱うためのソフトウェア

    * データベースとは別の話なので、興味がある人はリンクなどを参考ください。
    * これらのツールを利用すると簡単なデータベースを自分で作ることができます。
    * 構造の類似度の計算や構造検索、形式変換、図の生成などが可能です。

        * Open Banel
        * RDKit
        * CDK
    
    * 分子表示

        * [GLmol - Molecular Viewer on WebGL/Javascript](http://webglmol.osdn.jp/index-ja.html)

            * http://webglmol.osdn.jp/glmol/viewer.html
        
        1. サイトを開く
        [![Image from Gyazo](https://i.gyazo.com/8c42be6984f08224c4eccc9c09a636ef.png)](https://gyazo.com/8c42be6984f08224c4eccc9c09a636ef)

        2. https://pubchem.ncbi.nlm.nih.gov/compound/13730 のダウンロード、3D ConformerのSDFで Display をクリックする。
        [![Image from Gyazo](https://i.gyazo.com/39c17594df8cb8b526fc7c8882254f20.png)](https://gyazo.com/39c17594df8cb8b526fc7c8882254f20)
        
        3. 表示されたSDFデータをコピーする。
            [![Image from Gyazo](https://i.gyazo.com/e67b7ec9fcac730f723da023c4f3f93c.png)](https://gyazo.com/e67b7ec9fcac730f723da023c4f3f93c)

        4. 1.のサイトの Loadをクリックする。
        [![Image from Gyazo](https://i.gyazo.com/4ec8af59d093a81fd36019f779556b9a.png)](https://gyazo.com/4ec8af59d093a81fd36019f779556b9a)

        5. 緑で選択された入力欄に、コピーしたSDFデータをぺーすとする。
        [![Image from Gyazo](https://i.gyazo.com/275d8aac697cef306dc649b7519224e5.png)](https://gyazo.com/275d8aac697cef306dc649b7519224e5)

        6. "Reload molecule from textarea"をクリックして、SDFデータを読み込む。
              [![Image from Gyazo](https://i.gyazo.com/537a93e131badfc45e438800d3849267.png)](https://gyazo.com/537a93e131badfc45e438800d3849267)

        7. Load をクリックして、メニュをたたむ。
        [![Image from Gyazo](https://i.gyazo.com/cc307fc4da4a50ddf01f0208b8ee3839.png)](https://gyazo.com/cc307fc4da4a50ddf01f0208b8ee3839)

        8. Rotate, Translate, Zoom, Slab を選択して、適当に分子の表示を変更する。

* ID変換サービス
    * [リンク自動管理システム（Hyperlink Management System）](http://biodb.jp/)
        * http://biodb.jp/

# データベースを使ってみよう

## PubChem

* PubChemとは？



    * 統合TVを見てみましょう
        * [2017-12-08 PubChemを利用して化学物質やアッセイの結果を調べる 2017]( http://togotv.dbcls.jp/20171208.html)
            * http://togotv.dbcls.jp/20171208.html
[![Image from Gyazo](https://i.gyazo.com/dd9616fac93a903519ba6e8e7cca85fc.png)](https://gyazo.com/dd9616fac93a903519ba6e8e7cca85fc)

* Compound, Substance, BioAssay

    * Substance   SID (SubstanceID)
    * Compound    CID (CompoundID)
    * BioAssay    AID (AssayID)

* [Chemical structure representation in PubChem](https://www.slideshare.net/NextMoveSoftware/chemical-structure-representation-in-pubchem?from_action=save)

## ブラウザからの利用

* 化合物のページ
    * [ゲフィチニブ（Gefitinib)](https://pubchem.ncbi.nlm.nih.gov/compound/123631#section=Top)

    * [beta-D-Glucopyranose](https://pubchem.ncbi.nlm.nih.gov/compound/beta-D-glucose#section=Top)

* データの取得方法

    * [Classification Browser](https://pubchem.ncbi.nlm.nih.gov/classification/#hid=1)

        * オントロジーや分類法から、化合物のデータセットを絞り込み、絞り込んだデータセットをダウンロードすることができる。
    
    1. 右の**Classification**をクリック
    [![Image from Gyazo](https://i.gyazo.com/02deb07e9c325c38e1a845427a839e2f.png)](https://gyazo.com/02deb07e9c325c38e1a845427a839e2f)

    2. **Select classification**から、データセットを選ぶ。
    [![Image from Gyazo](https://i.gyazo.com/8171df0099bdaaebae99420f83521439.png)](https://gyazo.com/8171df0099bdaaebae99420f83521439)

    3. 


## [PubChem’s PUG (Power User Gateway)](http://pubchemdocs.ncbi.nlm.nih.gov/programmatic-access)

    * [PUG-SOAP](https://pubchemdocs.ncbi.nlm.nih.gov/pug-soap)

    * [PUG-REST](https://pubchemdocs.ncbi.nlm.nih.gov/pug-rest)

## [PubChemRDF](http://pubchemdocs.ncbi.nlm.nih.gov/rdf)

    *  REST API



# Documentation

* Slide

## Tools

* [Docker](https://www.docker.com/)

* [jupyter](http://jupyter.org/)



