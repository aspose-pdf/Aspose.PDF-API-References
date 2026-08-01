---
title: "クラス XImageCollection"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.XImageCollection クラス。XImage コレクションを表すクラスです。"
type: docs
weight: 11550
url: /ja/net/aspose.pdf/ximagecollection/
---
## XImageCollection class

XImage コレクションを表すクラスです。

```csharp
public sealed class XImageCollection : ICollection<XImage>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Count](../../aspose.pdf/ximagecollection/count/) { get; } | コレクション内の画像数です。 |
| [IsReadOnly](../../aspose.pdf/ximagecollection/isreadonly/) { get; } | コレクションが読み取り専用かどうかを示す値を取得します。 |
| [IsSynchronized](../../aspose.pdf/ximagecollection/issynchronized/) { get; } | オブジェクトが同期されている場合に true を返します。 |
| [Item](../../aspose.pdf/ximagecollection/item/) { get; } | インデックスでコレクションから画像を取得します。（2 つのインデクサー） |
| [Names](../../aspose.pdf/ximagecollection/names/) { get; } | 画像名の配列を取得します。 |
| [SyncRoot](../../aspose.pdf/ximagecollection/syncroot/) { get; } | 同期オブジェクトを返します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Add](../../aspose.pdf/ximagecollection/add/#add)(BitmapInfo) | エンティティをコレクションの末尾に追加し、最後のインデックスでアクセスできるようにします。 |
| [Add](../../aspose.pdf/ximagecollection/add/#add_3)(Stream) | エンティティをコレクションの末尾に追加し、最後のインデックスでアクセスできるようにします。 |
| [Add](../../aspose.pdf/ximagecollection/add/#add_2)(XImage) | 画像リストに新しい画像を追加します。このメソッドは画像を同じ PdfObject への参照として追加し、ファイルサイズの削減を可能にします。 |
| [Add](../../aspose.pdf/ximagecollection/add/#add_1)(BitmapInfo, ImageFilterType) | エンティティをコレクションの末尾に追加し、最後のインデックスでアクセスできるようにします。 |
| [Add](../../aspose.pdf/ximagecollection/add/#add_4)(Stream, ImageFilterType) | エンティティをコレクションの末尾に追加し、最後のインデックスでアクセスできるようにします。 |
| [Add](../../aspose.pdf/ximagecollection/add/#add_5)(Stream, int) | エンティティをコレクションの末尾に追加し、最後のインデックスでアクセスできるようにします。 |
| [Clear](../../aspose.pdf/ximagecollection/clear/)() | コレクションからすべての項目をクリアします。 |
| [Contains](../../aspose.pdf/ximagecollection/contains/)(XImage) | コレクションが特定の値を含むかどうかを判断します。 |
| [CopyTo](../../aspose.pdf/ximagecollection/copyto/)(XImage[], int) | 画像の配列をコレクションにコピーします。 |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete)() | コレクションから画像を削除します。 |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_1)(int) | インデックスでコレクションからインデックスを削除します。 |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_3)(string) | 名前でコレクションから項目を削除します。 |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_2)(int, ImageDeleteAction) | インデックスでコレクションから画像を削除し、action パラメータで指定されたアクションを実行します。 |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_4)(string, ImageDeleteAction) | 名前でコレクションから項目を削除します。 |
| [GetEnumerator](../../aspose.pdf/ximagecollection/getenumerator/)() | コレクションの列挙子を返します。 |
| [GetImageName](../../aspose.pdf/ximagecollection/getimagename/)(XImage) | 指定された画像のキーである、画像リスト内の名前を返します。 |
| [Remove](../../aspose.pdf/ximagecollection/remove/)(XImage) | コレクションから項目を削除します。NotImplementedException をスローします。 |
| [Replace](../../aspose.pdf/ximagecollection/replace/#replace)(int, Stream) | コレクション内の画像を別の画像に置き換えます。 |
| [Replace](../../aspose.pdf/ximagecollection/replace/#replace_1)(int, Stream, int) | コレクション内の画像を別の画像に置き換えます。 |
| [Replace](../../aspose.pdf/ximagecollection/replace/#replace_2)(int, Stream, int, bool) | コレクション内の画像を別の画像に置き換えます。 |

### 関連項目

* class [XImage](../ximage/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


