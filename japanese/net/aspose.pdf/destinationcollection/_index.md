---
title: "クラス DestinationCollection"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.DestinationCollection クラス。すべてのデスティネーションのコレクションを表すクラスで、名前文字列をデスティネーションにマッピングする名前ツリーです。12.3.2.3 Named Destinations と 7.7.4 Name Dictionary を pdf ドキュメントで参照してください。"
type: docs
weight: 3630
url: /ja/net/aspose.pdf/destinationcollection/
---
## DestinationCollection class

クラスは PDF ドキュメント内のすべてのデスティネーション（名前文字列をデスティネーションにマッピングする名前ツリー（12.3.2.3 "Named Destinations" 参照）および（7.7.4 "Name Dictionary" 参照））のコレクションを表します。

```csharp
public sealed class DestinationCollection : ICollection<KeyValuePair<string, object>>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Count](../../aspose.pdf/destinationcollection/count/) { get; } | コレクションに含まれる要素数を取得します。 |
| [IsReadOnly](../../aspose.pdf/destinationcollection/isreadonly/) { get; } | コレクションが読み取り専用かどうかを示す値を取得します。 |
| [Item](../../aspose.pdf/destinationcollection/item/) { get; } | インデックスで宛先オブジェクトを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Add](../../aspose.pdf/destinationcollection/add/)(KeyValuePair&lt;string, object&gt;) | 指定された項目を追加します。コレクションは読み取り専用です。常に NotSupportedException 例外がスローされます。 |
| [Clear](../../aspose.pdf/destinationcollection/clear/)() | コレクションは読み取り専用です。常に NotSupportedException 例外がスローされます。 |
| [Contains](../../aspose.pdf/destinationcollection/contains/)(KeyValuePair&lt;string, object&gt;) | このインスタンスがオブジェクトを含むかどうかを判断します。 |
| [CopyTo](../../aspose.pdf/destinationcollection/copyto/)(KeyValuePair&lt;string, object&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf/destinationcollection/getenumerator/)() | 列挙子を返します。 |
| [GetExplicitDestination](../../aspose.pdf/destinationcollection/getexplicitdestination/)(string, bool) | 名前で明示的な宛先を返します。 |
| [GetPageNumber](../../aspose.pdf/destinationcollection/getpagenumber/)(string, bool) | 名前で宛先のページ番号を返します。 |
| [IndexOf](../../aspose.pdf/destinationcollection/indexof/)(KeyValuePair&lt;string, object&gt;) | コレクション内の宛先のインデックスを返します。 |
| [Remove](../../aspose.pdf/destinationcollection/remove/)(KeyValuePair&lt;string, object&gt;) | 指定された項目を削除します。コレクションは読み取り専用です。常に NotSupportedException 例外がスローされます。 |

### 関連項目

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


