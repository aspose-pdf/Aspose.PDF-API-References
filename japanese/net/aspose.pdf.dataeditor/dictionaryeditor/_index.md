---
title: Class DictionaryEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DataEditor.DictionaryEditor クラス。文書のツリー辞書（文書辞書、ページ辞書、リソース辞書）にアクセスするためのクラス。
type: docs
weight: 3470
url: /ja/net/aspose.pdf.dataeditor/dictionaryeditor/
---
## DictionaryEditor クラス

文書のツリー辞書（文書辞書、ページ辞書、リソース辞書）にアクセスするためのクラスです。

```csharp
public class DictionaryEditor : IDictionary<string, ICosPdfPrimitive>
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [DictionaryEditor](dictionaryeditor/#constructor)(Document) |  |
| [DictionaryEditor](dictionaryeditor/#constructor_1)(Page) |  |
| [DictionaryEditor](dictionaryeditor/#constructor_2)(Resources) |  |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AllKeys](../../aspose.pdf.dataeditor/dictionaryeditor/allkeys/) { get; } | キーの完全なコレクション。編集可能なキーと編集不可能なキーを含みます。 |
| [Count](../../aspose.pdf.dataeditor/dictionaryeditor/count/) { get; } | `DictionaryEditor` に含まれる要素の数を取得します。 |
| [IsReadOnly](../../aspose.pdf.dataeditor/dictionaryeditor/isreadonly/) { get; } | `DictionaryEditor` が読み取り専用かどうかを示す値を取得します。 |
| [Item](../../aspose.pdf.dataeditor/dictionaryeditor/item/) { get; set; } | 指定されたキーを持つ要素を取得または設定します。 |
| [Keys](../../aspose.pdf.dataeditor/dictionaryeditor/keys/) { get; } | 編集可能なキーのコレクション。 |
| [Values](../../aspose.pdf.dataeditor/dictionaryeditor/values/) { get; } | `DictionaryEditor` に含まれる値を持つ ICollection を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Add](../../aspose.pdf.dataeditor/dictionaryeditor/add/#add)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | 辞書に [`ICosPdfPrimitive`](../icospdfprimitive/) を設定します。 |
| [Add](../../aspose.pdf.dataeditor/dictionaryeditor/add/#add_1)(string, ICosPdfPrimitive) | 辞書に [`ICosPdfPrimitive`](../icospdfprimitive/) を設定します。 |
| [Clear](../../aspose.pdf.dataeditor/dictionaryeditor/clear/)() | `DictionaryEditor` からすべてのアイテムを削除します。 |
| [Contains](../../aspose.pdf.dataeditor/dictionaryeditor/contains/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | `DictionaryEditor` が特定の値を含むかどうかを判断します。 |
| [ContainsKey](../../aspose.pdf.dataeditor/dictionaryeditor/containskey/)(string) | `DictionaryEditor` が指定されたキーを持つ要素を含むかどうかを判断します。 |
| [CopyTo](../../aspose.pdf.dataeditor/dictionaryeditor/copyto/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf.dataeditor/dictionaryeditor/getenumerator/)() | コレクションを反復処理する列挙子を返します。 |
| [Remove](../../aspose.pdf.dataeditor/dictionaryeditor/remove/#remove)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | `DictionaryEditor` から特定のオブジェクトの最初の出現を削除します。 |
| [Remove](../../aspose.pdf.dataeditor/dictionaryeditor/remove/#remove_1)(string) | `DictionaryEditor` から指定されたキーを持つ要素を削除します。 |
| [TryGetValue](../../aspose.pdf.dataeditor/dictionaryeditor/trygetvalue/)(string, out ICosPdfPrimitive) | 文字列、名前、ブール値、数値などの単純なデータ型にアクセスします。他の型には null を返します。 |

### 参照

* インターフェース [ICosPdfPrimitive](../icospdfprimitive/)
* 名前空間 [Aspose.Pdf.DataEditor](../../aspose.pdf.dataeditor/)
* アセンブリ [Aspose.PDF](../../)