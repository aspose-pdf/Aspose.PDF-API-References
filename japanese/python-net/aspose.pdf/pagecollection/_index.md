---
title: "PageCollection"
second_title: "Aspose.PDF for Python via .NET API リファレンス"
description: "PDF 文書ページのコレクションです。"
type: docs
weight: 1100
url: /ja/python-net/aspose.pdf/pagecollection/
---

## PageCollection class

PDF 文書ページのコレクションです。

PageCollection 型は次のメンバーを公開します：
## プロパティ
| 名前 | 説明 |
| :- | :- |
| is_synchronized | オブジェクトが同期されている場合、true を返します。 |
| sync_root | コレクションの同期オブジェクトを取得します。 |
## Indexer
| 名前 | 説明 |
| :- | :- |
| [index] | インデックスでページを取得します。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| add(entity) | コレクションにページを追加します。 |
| add() | コレクションにページを追加します。 |
| add(pages) | リストからすべてのページをコレクションに追加します。 |
| add(pages) | 配列からすべてのページをコレクションに追加します。 |
| delete(index) | 指定されたページを削除します。 |
| delete() | 指定されたページを削除します。 |
| delete(pages) | 配列で指定された番号のページを削除します。 |
| accept(visitor) | Accepts [AnnotationSelector](/pdf/python-net/aspose.pdf.annotations/annotationselector/) ビジターオブジェクトを受け入れ、アノテーションの操作機能を提供します。 |
| accept(visitor) | Accepts [ImagePlacementAbsorber](/pdf/python-net/aspose.pdf/imageplacementabsorber/) ビジターオブジェクトを受け入れ、画像配置オブジェクトの操作機能を提供します。 |
| accept(visitor) | Accepts [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) ビジターオブジェクトを受け入れ、テキストオブジェクトの操作機能を提供します。 |
| accept(visitor) | Accepts [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) ビジターオブジェクトを受け入れ、テキストオブジェクトの操作機能を提供します。 |
| insert(page_number) | 指定された位置に空のページをコレクションに挿入します。 |
| insert(page_number, entity) | 指定された位置に空のページをコレクションに挿入します。 |
| insert(page_number, pages) | コレクションからページをドキュメントに挿入します。 |
| insert(page_number, pages) | 配列のページをドキュメントに挿入します。 |
| index_of(entity) | 指定されたページのインデックスを返します。 |
| flatten() | ページ上にあるすべてのフィールドを削除し、その代わりに値を配置します。 |
| free_memory() | キャッシュされたデータをクリアします |

### 関連項目

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

