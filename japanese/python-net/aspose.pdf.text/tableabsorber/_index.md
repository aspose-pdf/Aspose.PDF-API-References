---
title: "TableAbsorber"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "テーブル要素の吸収オブジェクトを表します。<br/>検索を実行し、[table_list](/pdf/python-net/aspose.pdf.text/tableabsorber/) コレクションを介して検索結果へのアクセスを提供します。"
type: docs
weight: 310
url: /ja/python-net/aspose.pdf.text/tableabsorber/
---

## TableAbsorber class

テーブル要素の吸収オブジェクトを表します。<br/>検索を実行し、[table_list](/pdf/python-net/aspose.pdf.text/tableabsorber/) コレクションを介して検索結果へのアクセスを提供します。

TableAbsorber 型は次のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| TableAbsorber(text_search_options) | TableAbsorber クラスの新しいインスタンスを初期化します。 |
| TableAbsorber() | 新しい [TableAbsorber](/pdf/python-net/aspose.pdf.text/tableabsorber/) のインスタンスを初期化します。 |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| text_search_options | テキスト検索オプションを取得または設定します。 |
| table_list | 見つかったテーブルを含む読み取り専用 IList を返します |
| use_flow_engine | * 代替テーブル認識エンジンの初期アルファ版を有効にします。このエンジンは境界線のない変換テーブルに使用できます。<br/>            まだテーブルの編集やテキストスタイルの取得はサポートされていません。デフォルト値は false です; |
## メソッド
| 名前 | 説明 |
| :- | :- |
| visit(page) | 指定されたページのテーブルを抽出します |
| remove(table) | ページから [AbsorbedTable](/pdf/python-net/aspose.pdf.text/absorbedtable/) を削除します。 |
| replace(page, old_table, new_table) | ページ上で [AbsorbedTable](/pdf/python-net/aspose.pdf.text/absorbedtable/) を [Table](/pdf/python-net/aspose.pdf/table/) に置き換えます。 |

### 関連項目

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

