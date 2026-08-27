---
title: "XImageCollection"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "XImage コレクションを表すクラスです。"
type: docs
weight: 1690
url: /ja/python-net/aspose.pdf/ximagecollection/
---

## XImageCollection class

XImage コレクションを表すクラスです。

XImageCollection 型は次のメンバーを公開します：
## プロパティ
| 名前 | 説明 |
| :- | :- |
| is_synchronized | オブジェクトが同期されている場合に true を返します。 |
| sync_root | 同期オブジェクトを返します。 |
| names | 画像名の配列を取得します。 |
## Indexer
| 名前 | 説明 |
| :- | :- |
| [index] | インデックスでコレクションから画像を取得します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| add(image) | 画像リストに新しい画像を追加します。このメソッドは画像を同じ PdfObject への参照として追加します（ファイルサイズの削減が可能です） |
| add(image) | エンティティをコレクションの末尾に追加します。これによりエンティティは最後のインデックスでアクセスできます。 |
| add(image, filter_type) | エンティティをコレクションの末尾に追加します。これによりエンティティは最後のインデックスでアクセスできます。 |
| add(image, quality) | エンティティをコレクションの末尾に追加します。これによりエンティティは最後のインデックスでアクセスできます。 |
| delete(index) | インデックスでコレクションからインデックスを削除します。 |
| delete(index, action) | インデックスでコレクションから画像を削除し、action パラメータで指定された操作を実行します。 |
| delete(name) | 名前でコレクションから項目を削除します。 |
| delete(name, action) | 名前でコレクションから項目を削除します。 |
| delete() | インデックスでコレクションからインデックスを削除します。 |
| replace(index, stream) | コレクション内の画像を別の画像に置き換えます。 |
| replace(index, stream, quality, is_black_and_white) | コレクション内の画像を別の画像に置き換えます。 |
| replace(index, stream, quality) | コレクション内の画像を別の画像に置き換えます。 |
| get_image_name(image) | 指定された画像のキーである画像リスト内の名前を返します。 |

### 関連項目

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

