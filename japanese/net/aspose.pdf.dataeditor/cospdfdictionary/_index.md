---
title: Class CosPdfDictionary
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DataEditor.CosPdfDictionary クラス。オブジェクトの辞書にアクセスするためのクラス
type: docs
weight: 3420
url: /ja/net/aspose.pdf.dataeditor/cospdfdictionary/
---
## CosPdfDictionary クラス

オブジェクトの辞書にアクセスするためのクラス。

```csharp
public class CosPdfDictionary : CosPdfPrimitive, IDictionary<string, ICosPdfPrimitive>
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [CosPdfDictionary](cospdfdictionary/)(Resources) | リソースから辞書を作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AllKeys](../../aspose.pdf.dataeditor/cospdfdictionary/allkeys/) { get; } | キーの完全なコレクション。編集可能なキーと編集不可のキーを含みます。 |
| [Count](../../aspose.pdf.dataeditor/cospdfdictionary/count/) { get; } | `CosPdfDictionary` に含まれる要素の数を取得します。 |
| [IsReadOnly](../../aspose.pdf.dataeditor/cospdfdictionary/isreadonly/) { get; } | `CosPdfDictionary` が読み取り専用であるかどうかを示す値を取得します。 |
| [Item](../../aspose.pdf.dataeditor/cospdfdictionary/item/) { get; set; } | 指定されたキーを持つ要素を取得または設定します。 |
| [Keys](../../aspose.pdf.dataeditor/cospdfdictionary/keys/) { get; } | 編集可能なキーのコレクション。 |
| [Values](../../aspose.pdf.dataeditor/cospdfdictionary/values/) { get; } | `CosPdfDictionary` に含まれる値を持つ ICollection を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [CreateEmptyDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/createemptydictionary/#createemptydictionary)(Document) | ドキュメントに添付される空の辞書を作成します。 |
| static [CreateEmptyDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/createemptydictionary/#createemptydictionary_1)(Page) | ページに添付される空の辞書を作成します。 |
| [Add](../../aspose.pdf.dataeditor/cospdfdictionary/add/#add)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | 辞書に [`ICosPdfPrimitive`](../icospdfprimitive/) を設定します。 |
| [Add](../../aspose.pdf.dataeditor/cospdfdictionary/add/#add_1)(string, ICosPdfPrimitive) | 辞書に [`ICosPdfPrimitive`](../icospdfprimitive/) を設定します。 |
| [Clear](../../aspose.pdf.dataeditor/cospdfdictionary/clear/)() | `CosPdfDictionary` からすべてのアイテムを削除します。 |
| [Contains](../../aspose.pdf.dataeditor/cospdfdictionary/contains/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | `CosPdfDictionary` が特定の値を含むかどうかを判断します。 |
| [ContainsKey](../../aspose.pdf.dataeditor/cospdfdictionary/containskey/)(string) | `CosPdfDictionary` が指定されたキーを持つ要素を含むかどうかを判断します。 |
| [CopyTo](../../aspose.pdf.dataeditor/cospdfdictionary/copyto/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf.dataeditor/cospdfdictionary/getenumerator/)() | コレクションを反復処理する列挙子を返します。 |
| [Remove](../../aspose.pdf.dataeditor/cospdfdictionary/remove/#remove)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | `CosPdfDictionary` から特定のオブジェクトの最初の出現を削除します。 |
| [Remove](../../aspose.pdf.dataeditor/cospdfdictionary/remove/#remove_1)(string) | `CosPdfDictionary` から指定されたキーを持つ要素を削除します。 |
| virtual [ToCosPdfBoolean](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfboolean/)() | このインスタンスを [`CosPdfBoolean`](../cospdfboolean/) にキャストしようとします。 |
| override [ToCosPdfDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/tocospdfdictionary/)() | このインスタンスを `CosPdfDictionary` にキャストしようとします。 |
| virtual [ToCosPdfName](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfname/)() | このインスタンスを [`CosPdfName`](../cospdfname/) にキャストしようとします。 |
| virtual [ToCosPdfNumber](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfnumber/)() | このインスタンスを [`CosPdfNumber`](../cospdfnumber/) にキャストしようとします。 |
| virtual [ToCosPdfString](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfstring/)() | このインスタンスを [`CosPdfString`](../cospdfstring/) にキャストしようとします。 |
| [TryGetValue](../../aspose.pdf.dataeditor/cospdfdictionary/trygetvalue/)(string, out ICosPdfPrimitive) | 文字列、名前、ブール値、数値のような単純なデータ型にアクセスします。他の型には null を返します。 |

### 参照

* クラス [CosPdfPrimitive](../cospdfprimitive/)
* インターフェース [ICosPdfPrimitive](../icospdfprimitive/)
* 名前空間 [Aspose.Pdf.DataEditor](../../aspose.pdf.dataeditor/)
* アセンブリ [Aspose.PDF](../../)