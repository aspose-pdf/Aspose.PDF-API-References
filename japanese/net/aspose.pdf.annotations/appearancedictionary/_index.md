---
title: "クラス AppearanceDictionary"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Annotations.AppearanceDictionary クラス。ページ上でアノテーションが視覚的にどのように表示されるかを指定するアノテーション外観辞書です"
type: docs
weight: 1580
url: /ja/net/aspose.pdf.annotations/appearancedictionary/
---
## AppearanceDictionary class

ページ上で注釈が視覚的にどのように表示されるかを指定する注釈外観ディクショナリです。

```csharp
public sealed class AppearanceDictionary : IDictionary<string, XForm>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Count](../../aspose.pdf.annotations/appearancedictionary/count/) { get; } | 辞書に含まれる要素数を取得します。 |
| [IsFixedSize](../../aspose.pdf.annotations/appearancedictionary/isfixedsize/) { get; } | 辞書が固定サイズかどうかを示す値を取得します。 |
| [IsReadOnly](../../aspose.pdf.annotations/appearancedictionary/isreadonly/) { get; } | 辞書が読み取り専用かどうかを示す値を取得します。 |
| [IsSynchronized](../../aspose.pdf.annotations/appearancedictionary/issynchronized/) { get; } | 辞書へのアクセスが同期化（スレッドセーフ）されているかどうかを示す値を取得します。 |
| [Item](../../aspose.pdf.annotations/appearancedictionary/item/) { get; set; } | 外観ストリームを取得するための便利な形式を表します。 |
| [Keys](../../aspose.pdf.annotations/appearancedictionary/keys/) { get; } | 辞書のキーを取得します。外観辞書にサブ辞書がある場合、[`Keys`](./keys/) には (N&#x7C;R&#x7C;D).state の値が含まれます。ここで N は通常の外観、R はロールオーバー外観、D はダウン外観で、state は状態の名前です（例: チェックボックスの On、Off）。 |
| [SyncRoot](../../aspose.pdf.annotations/appearancedictionary/syncroot/) { get; } | 辞書へのアクセスを同期化するために使用できるオブジェクトを取得します。 |
| [Values](../../aspose.pdf.annotations/appearancedictionary/values/) { get; } | 辞書の値のリストを取得します。結果コレクションには XForm オブジェクトのリストが含まれます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add/#add)(KeyValuePair&lt;string, XForm&gt;) | 辞書にキーと値のペアを追加します。 |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add/#add_2)(string, XForm) | 指定されたキーに対して X フォームを追加します。 |
| [Clear](../../aspose.pdf.annotations/appearancedictionary/clear/)() | 辞書からすべての要素を削除します。 |
| [Contains](../../aspose.pdf.annotations/appearancedictionary/contains/)(KeyValuePair&lt;string, XForm&gt;) | 指定されたキーと値のペアが辞書に含まれているか確認します。 |
| [ContainsKey](../../aspose.pdf.annotations/appearancedictionary/containskey/)(string) | この辞書が指定されたキーを含んでいるか判断します。 |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto/#copyto_1)(KeyValuePair&lt;string, XForm&gt;[], int) |  |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto/#copyto)(XForm[], int) | 辞書の要素を配列にコピーします。特定の配列インデックスから開始します。 |
| [GetEnumerator](../../aspose.pdf.annotations/appearancedictionary/getenumerator/)() | 辞書に対する IDictionaryEnumerator オブジェクトを返します。 |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove/#remove)(KeyValuePair&lt;string, XForm&gt;) | コレクションからキー/値のペアを削除します。 |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove/#remove_1)(string) | 辞書からキーを削除します。 |
| [TryGetValue](../../aspose.pdf.annotations/appearancedictionary/trygetvalue/)(string, out XForm) | 辞書内でキーを検索し、見つかった場合は値を取得します。 |

### 関連項目

* class [XForm](../../aspose.pdf/xform/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


