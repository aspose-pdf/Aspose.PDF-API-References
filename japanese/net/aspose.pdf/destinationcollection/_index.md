---
title: Class DestinationCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DestinationCollection クラス。クラスは、名前ツリーが名前文字列を目的地にマッピングするすべての目的地のコレクションを表します。pdf ドキュメントの 12.3.2.3 名称付き目的地を参照し、7.7.4 名称辞書を参照してください。
type: docs
weight: 3510
url: /ja/net/aspose.pdf/destinationcollection/
---
## DestinationCollection クラス

クラスは、pdf ドキュメント内のすべての目的地（名前ツリーが名前文字列を目的地にマッピングする（12.3.2.3「名称付き目的地」を参照）および（7.7.4「名称辞書」を参照））のコレクションを表します。

```csharp
public sealed class DestinationCollection : ICollection<KeyValuePair<string, object>>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Count](../../aspose.pdf/destinationcollection/count/) { get; } | コレクションに含まれる要素の数を取得します。 |
| [IsReadOnly](../../aspose.pdf/destinationcollection/isreadonly/) { get; } | コレクションが読み取り専用であるかどうかを示す値を取得します。 |
| [Item](../../aspose.pdf/destinationcollection/item/) { get; } | インデックスによって目的地オブジェクトを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Add](../../aspose.pdf/destinationcollection/add/)(KeyValuePair&lt;string, object&gt;) | 指定されたアイテムを追加します。コレクションは読み取り専用です。常に NotSupportedException 例外をスローします。 |
| [Clear](../../aspose.pdf/destinationcollection/clear/)() | コレクションは読み取り専用です。常に NotSupportedException 例外をスローします。 |
| [Contains](../../aspose.pdf/destinationcollection/contains/)(KeyValuePair&lt;string, object&gt;) | このインスタンスがオブジェクトを含むかどうかを判断します。 |
| [CopyTo](../../aspose.pdf/destinationcollection/copyto/)(KeyValuePair&lt;string, object&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf/destinationcollection/getenumerator/)() | 列挙子を返します。 |
| [GetExplicitDestination](../../aspose.pdf/destinationcollection/getexplicitdestination/)(string, bool) | 名前によって明示的な目的地を返します。 |
| [GetPageNumber](../../aspose.pdf/destinationcollection/getpagenumber/)(string, bool) | 名前によって目的地のページ番号を返します。 |
| [IndexOf](../../aspose.pdf/destinationcollection/indexof/)(KeyValuePair&lt;string, object&gt;) | コレクション内の目的地のインデックスを返します。 |
| [Remove](../../aspose.pdf/destinationcollection/remove/)(KeyValuePair&lt;string, object&gt;) | 指定されたアイテムを削除します。コレクションは読み取り専用です。常に NotSupportedException 例外をスローします。 |

### 参照

* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)