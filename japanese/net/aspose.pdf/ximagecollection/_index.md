---
title: Class XImageCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XImageCollection クラス。XImage コレクションを表すクラス
type: docs
weight: 11360
url: /ja/net/aspose.pdf/ximagecollection/
---
## XImageCollection クラス

XImage コレクションを表すクラスです。

```csharp
public sealed class XImageCollection : ICollection<XImage>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Count](../../aspose.pdf/ximagecollection/count/) { get; } | コレクション内の画像の数。 |
| [IsReadOnly](../../aspose.pdf/ximagecollection/isreadonly/) { get; } | コレクションが読み取り専用であるかどうかを示す値を取得します。 |
| [IsSynchronized](../../aspose.pdf/ximagecollection/issynchronized/) { get; } | オブジェクトが同期されている場合は true を返します。 |
| [Item](../../aspose.pdf/ximagecollection/item/) { get; } | インデックスによってコレクションから画像を取得します。 (2 つのインデクサ) |
| [Names](../../aspose.pdf/ximagecollection/names/) { get; } | 画像名の配列を取得します。 |
| [SyncRoot](../../aspose.pdf/ximagecollection/syncroot/) { get; } | 同期オブジェクトを返します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Add](../../aspose.pdf/ximagecollection/add/#add)(BitmapInfo) | エンティティをコレクションの末尾に追加し、エンティティに最後のインデックスでアクセスできるようにします。 |
| [Add](../../aspose.pdf/ximagecollection/add/#add_3)(Stream) | エンティティをコレクションの末尾に追加し、エンティティに最後のインデックスでアクセスできるようにします。 |
| [Add](../../aspose.pdf/ximagecollection/add/#add_2)(XImage) | 画像リストに新しい画像を追加します。このメソッドは、同じ PdfObject への参照として画像を追加します（これによりファイルサイズを減少させることができます）。 |
| [Add](../../aspose.pdf/ximagecollection/add/#add_1)(BitmapInfo, ImageFilterType) | エンティティをコレクションの末尾に追加し、エンティティに最後のインデックスでアクセスできるようにします。 |
| [Add](../../aspose.pdf/ximagecollection/add/#add_4)(Stream, ImageFilterType) | エンティティをコレクションの末尾に追加し、エンティティに最後のインデックスでアクセスできるようにします。 |
| [Add](../../aspose.pdf/ximagecollection/add/#add_5)(Stream, int) | エンティティをコレクションの末尾に追加し、エンティティに最後のインデックスでアクセスできるようにします。 |
| [Clear](../../aspose.pdf/ximagecollection/clear/)() | コレクションからすべてのアイテムをクリアします。 |
| [Contains](../../aspose.pdf/ximagecollection/contains/)(XImage) | コレクションが特定の値を含むかどうかを判断します。 |
| [CopyTo](../../aspose.pdf/ximagecollection/copyto/)(XImage[], int) | 画像の配列をコレクションにコピーします。 |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete)() | コレクションから画像を削除します。 |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_1)(int) | インデックスによってコレクションからインデックスを削除します。 |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_3)(string) | 名前によってコレクションからアイテムを削除します。 |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_2)(int, ImageDeleteAction) | アクションパラメータで指定されたアクションを実行してインデックスによってコレクションから画像を削除します。 |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_4)(string, ImageDeleteAction) | 名前によってコレクションからアイテムを削除します。 |
| [GetEnumerator](../../aspose.pdf/ximagecollection/getenumerator/)() | コレクションの列挙子を返します。 |
| [GetImageName](../../aspose.pdf/ximagecollection/getimagename/)(XImage) | 指定された画像のキーである画像リスト内の名前を返します。 |
| [Remove](../../aspose.pdf/ximagecollection/remove/)(XImage) | コレクションからアイテムを削除し、NotImplementedException をスローします。 |
| [Replace](../../aspose.pdf/ximagecollection/replace/#replace)(int, Stream) | コレクション内の画像を別の画像に置き換えます。 |
| [Replace](../../aspose.pdf/ximagecollection/replace/#replace_1)(int, Stream, int) | コレクション内の画像を別の画像に置き換えます。 |
| [Replace](../../aspose.pdf/ximagecollection/replace/#replace_2)(int, Stream, int, bool) | コレクション内の画像を別の画像に置き換えます。 |

### 参照

* クラス [XImage](../ximage/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)