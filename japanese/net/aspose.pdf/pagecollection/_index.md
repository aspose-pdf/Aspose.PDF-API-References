---
title: "クラス PageCollection"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.PageCollection クラス。PDF Document ページのコレクション"
type: docs
weight: 8220
url: /ja/net/aspose.pdf/pagecollection/
---
## PageCollection class

PDF document pages のコレクション。

```csharp
public sealed class PageCollection : ICollection<Page>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Count](../../aspose.pdf/pagecollection/count/) { get; } | Document のページ数を取得します。 |
| [IsReadOnly](../../aspose.pdf/pagecollection/isreadonly/) { get; } | コレクションが読み取り専用であることを示す値を取得します。常に false を返します。 |
| [IsSynchronized](../../aspose.pdf/pagecollection/issynchronized/) { get; } | オブジェクトが同期されている場合は true を返します。 |
| [Item](../../aspose.pdf/pagecollection/item/) { get; } | インデックスでページを取得します。 |
| [SyncRoot](../../aspose.pdf/pagecollection/syncroot/) { get; } | コレクションの同期オブジェクトを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept)(AnnotationSelector) | [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) ビジターオブジェクトを受け入れ、Annotation の操作機能を提供します。 |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_1)(ImagePlacementAbsorber) | [`ImagePlacementAbsorber`](../imageplacementabsorber/) ビジターオブジェクトを受け入れ、画像配置オブジェクトの操作機能を提供します。 |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_2)(TextAbsorber) | [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) ビジターオブジェクトを受け入れ、テキストオブジェクトの操作機能を提供します。 |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_3)(TextFragmentAbsorber) | [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) ビジターオブジェクトを受け入れ、テキストオブジェクトの操作機能を提供します。 |
| [Add](../../aspose.pdf/pagecollection/add/#add)() | 空のページを追加します。Document にすでにサイズが異なるページが含まれている場合、最も頻繁に出現するページのサイズが選択されます。異なるページが2枚だけの場合は、最初のページのサイズが使用されます。 |
| [Add](../../aspose.pdf/pagecollection/add/#add_3)(ICollection&lt;Page&gt;) | リストからすべてのページをコレクションに追加します。 |
| [Add](../../aspose.pdf/pagecollection/add/#add_1)(Page) | ページをコレクションに追加します。 |
| [Add](../../aspose.pdf/pagecollection/add/#add_2)(Page[]) | 配列からすべてのページをコレクションに追加します。 |
| [Clear](../../aspose.pdf/pagecollection/clear/)() | ページコレクションをクリアします。 |
| [Contains](../../aspose.pdf/pagecollection/contains/)(Page) | このインスタンスがオブジェクトを含むかどうかを判断します。 |
| [CopyTo](../../aspose.pdf/pagecollection/copyto/)(Page[], int) | ページをドキュメントにコピーします。 |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete)() | コレクションからすべてのページを削除します。 |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_1)(int) | 指定されたページを削除します。 |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_2)(int[]) | 配列で指定された番号のページを削除します。 |
| [Flatten](../../aspose.pdf/pagecollection/flatten/)() | ページ上にあるすべてのフィールドを削除し、その値を代わりに配置します。 |
| [FreeMemory](../../aspose.pdf/pagecollection/freememory/)() | キャッシュされたデータをクリアします |
| [GetEnumerator](../../aspose.pdf/pagecollection/getenumerator/)() | ページの列挙子を返します。 |
| [IndexOf](../../aspose.pdf/pagecollection/indexof/)(Page) | 指定されたページのインデックスを返します。 |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert)(int) | 指定された位置に空のページをコレクションに挿入します。ドキュメントにサイズが異なるページがすでに含まれている場合、最も頻繁に出現するページのサイズが選択されます。異なるページが2つだけの場合は、最初のページのサイズが使用されます。 |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_3)(int, ICollection&lt;Page&gt;) | コレクションからページをドキュメントに挿入します。 |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_1)(int, Page) | 指定された場所にページをページコレクションに挿入します。 |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_2)(int, Page[]) | 配列のページをドキュメントに挿入します。 |
| [Remove](../../aspose.pdf/pagecollection/remove/)(Page) | 指定された項目を削除し、NotSupportedException をスローします。 |

### 関連項目

* class [Page](../page/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


