---
title: Class PageCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PageCollection クラス。PDF ドキュメントページのコレクション
type: docs
weight: 8080
url: /ja/net/aspose.pdf/pagecollection/
---
## PageCollection クラス

PDF ドキュメントページのコレクション。

```csharp
public sealed class PageCollection : ICollection<Page>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Count](../../aspose.pdf/pagecollection/count/) { get; } | ドキュメント内のページ数を取得します。 |
| [IsReadOnly](../../aspose.pdf/pagecollection/isreadonly/) { get; } | コレクションが読み取り専用であることを示す値を取得します。常に false を返します。 |
| [IsSynchronized](../../aspose.pdf/pagecollection/issynchronized/) { get; } | オブジェクトが同期されている場合は true を返します。 |
| [Item](../../aspose.pdf/pagecollection/item/) { get; } | インデックスによってページを取得します。 |
| [SyncRoot](../../aspose.pdf/pagecollection/syncroot/) { get; } | コレクションの同期オブジェクトを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept)(AnnotationSelector) | 注釈と作業するための機能を提供する [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) ビジターオブジェクトを受け入れます。 |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_1)(ImagePlacementAbsorber) | 画像配置オブジェクトと作業するための機能を提供する [`ImagePlacementAbsorber`](../imageplacementabsorber/) ビジターオブジェクトを受け入れます。 |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_2)(TextAbsorber) | テキストオブジェクトと作業するための機能を提供する [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) ビジターオブジェクトを受け入れます。 |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_3)(TextFragmentAbsorber) | テキストオブジェクトと作業するための機能を提供する [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) ビジターオブジェクトを受け入れます。 |
| [Add](../../aspose.pdf/pagecollection/add/#add)() | 空のページを追加します。ドキュメントに異なるサイズのページがすでに含まれている場合、最も頻繁に発生するページのサイズが選択されます。異なるページが 2 つだけの場合、最初のページのサイズが使用されます。 |
| [Add](../../aspose.pdf/pagecollection/add/#add_3)(ICollection&lt;Page&gt;) | リストからすべてのページをコレクションに追加します。 |
| [Add](../../aspose.pdf/pagecollection/add/#add_1)(Page) | ページをコレクションに追加します。 |
| [Add](../../aspose.pdf/pagecollection/add/#add_2)(Page[]) | 配列からすべてのページをコレクションに追加します。 |
| [Clear](../../aspose.pdf/pagecollection/clear/)() | ページコレクションをクリアします。 |
| [Contains](../../aspose.pdf/pagecollection/contains/)(Page) | このインスタンスがオブジェクトを含んでいるかどうかを判断します。 |
| [CopyTo](../../aspose.pdf/pagecollection/copyto/)(Page[], int) | ページをドキュメントにコピーします。 |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete)() | コレクションからすべてのページを削除します。 |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_1)(int) | 指定されたページを削除します。 |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_2)(int[]) | 配列で指定された番号のページを削除します。 |
| [Flatten](../../aspose.pdf/pagecollection/flatten/)() | ページ上にあるすべてのフィールドを削除し、その値を代わりに配置します。 |
| [FreeMemory](../../aspose.pdf/pagecollection/freememory/)() | キャッシュされたデータをクリアします。 |
| [GetEnumerator](../../aspose.pdf/pagecollection/getenumerator/)() | ページの列挙子を返します。 |
| [IndexOf](../../aspose.pdf/pagecollection/indexof/)(Page) | 指定されたページのインデックスを返します。 |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert)(int) | 指定された位置にコレクションに空のページを挿入します。ドキュメントに異なるサイズのページがすでに含まれている場合、最も頻繁に発生するページのサイズが選択されます。異なるページが 2 つだけの場合、最初のページのサイズが使用されます。 |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_3)(int, ICollection&lt;Page&gt;) | コレクションからドキュメントにページを挿入します。 |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_1)(int, Page) | 指定された場所にページコレクションにページを挿入します。 |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_2)(int, Page[]) | 配列のページをドキュメントに挿入します。 |
| [Remove](../../aspose.pdf/pagecollection/remove/)(Page) | 指定されたアイテムを削除し、NotSupportedException をスローします。 |

### 参照

* クラス [Page](../page/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)