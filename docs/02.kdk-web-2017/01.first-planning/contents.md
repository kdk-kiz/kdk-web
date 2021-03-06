
## ページ一覧

### 旧サイト

```
index.html   →　トップページ。要素：宣伝、Twitter、事業内容、新着情報
|`-company.html　→　会社概要。要素：挨拶、事業内容、事業実績、会社概要
|`-software.html　→　ソフトウェア。製品紹介
|`-develop.html　→　事業内容、
|`-recruit.html
 `-access.html
```

## コンテンツと画面要素の解析

### 旧サイト一覧

* ヘッダー共通
  * 英語ページへのリンク
  * 連絡先(TEL,FAX,E-mail)
  * 事業許可番号
  * グローバルメニュー（トップページ、会社案内、医療/理療システム、一般システム/WEB開発、採用情報）

* フッター共通
  * コピーライト

* トップページ（index.html）
  * セグメント：メインビジュアル（画像）
    * 「人と医療の架け橋を目指して」
  * セグメント：プログラミング講習会のご案内
    * 情報が非常に古い
    * Microsoft Kinectの画像
    * 実質的に、広告型のお知らせエリア
  * セグメント：新着情報
    * Twitterを新着情報の代わりに使っている。
  * セグメント：事業内容の広告
    * 医療・改行用ソフトウェア開発、業務・工業用統合システム開発、人材派遣
    * 各専用ページへのリンク付き

* 会社案内（company.html）
  * セグメント：通天閣の画像
    * 大阪ではありますが。
  * セグメント：挨拶
    * 社長画像
    * 挨拶
  * セグメント：主な業務内容
    * 業務実績を書いている。
      * 自動化・省力化コンサルティング。一般ソフトウェア提案、開発、販売、維持管理
      　(事務処理の自動化、在庫管理、人材管理、データベース改良、高速化)
      * 技術者派遣業（般２７－３０１１９８）
      * 　(JAVA, PHP, VC++, VB, JavaScript, HTML, 他一般汎用言語, Linux, Flex, etc)
      * ホームページ作成、レンタルサーバ業
      * 大学、研究所向け学術的シミュレーションソフトウェア開発
      *  (偏微分/重積分算法、マルコフ劣化極性、3次元ベクトル解析
      *  人工知能関連技術：SA,GA,NewralNet)
  * セグメント：業務実績
    * 過去の受託案件の業務実績
  * セグメント：会社概要
    * 経営指標など

* 医療/理療システム（software.html）
  * セグメント：トップビジュアル
    * 「現場の安心と効率を実現するKDKの医療ソフトウェア」
  * セグメント：医療機器管理システム「MICS」
    * Micsの画像
    * デモへのリンク  
  * セグメント：キネリハ
    * キネリハの画像サンプル４種
    * 咀嚼センサーのサンプルダウンロード
    * うたい文句
    * 特徴、製品内訳、動作環境、製品サンプル

* 一般システム/WEB開発（develop.html）
  * セグメント：ソフトウェア開発について
    * ソフトウェア開発受託のご案内文
    * 問い合わせ先
  * 提案例
    * 「事務処理の自動省力化／WEBによる集合管理システム」
    * 「シミュレーター」
    * 「ホームページ作成／管理運営」

* 採用情報（recruit.html）
  * （質問）これはいつの情報ですか？？面倒ですが、年度ごとに特集ページを作ったほうが良いのではないでしょうか。
  * セグメント：プログラマ・SE採用
  * セグメント：データベースSQLオペレーター採用
  * セグメント：介護派遣採用

* アクセス（access.html）
  * 連絡先
    * ヘッダーと同じ情報
  * アクセス
    * 場所と地図

### 旧サイトコンテンツ　カテゴリ別分類

1. 事業のブランドイメージ
  * 会社の理念、指針、概要を示す。
  * 旧コンテンツ
    * トップページ：メインビジュアル（画像）
    * 会社案内：通天閣の画像
    * 会社案内：挨拶
2. トップからの各コンテンツへのリンク（売りたい情報リスト）
  * トップページ：事業内容の広告
  * トップページ：プログラミング講習会のご案内
3. 製品情報
  * 旧コンテンツ
    * 医療/理療システム：医療機器管理システム「MICS」
    * 医療/理療システム：キネリハ
4. 事業内容
  * 弊社が行っている事業内容
  * 旧コンテンツ
    * 一般システム/WEB開発：ソフトウェア開発について
    * 会社案内：主な業務内容
    * 一般システム/WEB開発：提案例
5. 受注実績
  * 何を開発したかの実績
  * 旧コンテンツ
    * 会社案内：主な業務内容
    * 会社案内：業務実績
6. 採用情報
  * 旧コンテンツ
    * 採用情報
7. 会社概要
  * 旧コンテンツ
    * 会社案内：会社概要
    * アクセス：場所と地図

### 新サイト構成

```
index.html           インデックス
|`- aboutus.html          
|`- services.html    取り組むサービス
|`- products.html    製品、実績
|`- recruit.html     採用情報
|`- product
|    `- 製品紹介ページ
 `- info
     `- お知らせページ
```

* index.html
  * 以下のコンテンツを移植
    1. 事業のブランドイメージ
    2. トップからの各コンテンツへのリンク（売りたい情報リスト）

* aboutus.html
  * 以下のコンテンツを移植
    7. 会社概要

* services.html
  * 以下のコンテンツを概要とリンクのみで集約する。
    4. 事業内容

* products.html
  * 以下のコンテンツを概要とリンクのみで集約する。
    5. 受注実績

* product
  * 個別の製品紹介ページ

* info
  * お知らせ情報