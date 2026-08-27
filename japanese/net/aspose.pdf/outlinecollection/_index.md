---
title: "クラス OutlineCollection"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.OutlineCollection クラス。文書のアウトライン階層を表します"
type: docs
weight: 8140
url: /ja/net/aspose.pdf/outlinecollection/
---
## OutlineCollection class

document のアウトライン階層を表します。

```csharp
public sealed class OutlineCollection : Outlines
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| override [Count](../../aspose.pdf/outlinecollection/count/) { get; } | コレクション項目の数です。VisibleCount と混同しないでください：VisibleCount はすべてのレベルで表示されるアウトライン項目の数を取得します。 |
| [First](../../aspose.pdf/outlinecollection/first/) { get; } | アウトライン内の最上位項目を表すアウトライン項目を取得します。 |
| override [IsReadOnly](../../aspose.pdf/outlinecollection/isreadonly/) { get; } | コレクションが読み取り専用かどうかを示す値を取得します。 |
| [IsSynchronized](../../aspose.pdf/outlinecollection/issynchronized/) { get; } | このコレクションへのアクセスが同期化されているか（スレッドセーフか）を示す値を取得します。 |
| [Item](../../aspose.pdf/outlinecollection/item/) { get; } | インデックスでコレクションからアウトライン項目を取得します。 |
| [Last](../../aspose.pdf/outlinecollection/last/) { get; } | アウトライン内の最後の最上位項目を表すアウトライン項目を取得します。 |
| [SyncRoot](../../aspose.pdf/outlinecollection/syncroot/) { get; } | このコレクションへのアクセスを同期化するために使用できるオブジェクトを取得します。 |
| override [VisibleCount](../../aspose.pdf/outlinecollection/visiblecount/) { get; } | Count はすべてのレベルで表示される子孫アウトライン項目の数の合計です。注意：コレクション内の項目数を表す Count と混同しないでください。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Add](../../aspose.pdf/outlinecollection/add/)(OutlineItemCollection) | アウトライン項目をコレクションに追加します。 |
| override [Clear](../../aspose.pdf/outlinecollection/clear/)() | コレクションからすべての項目をクリアします。 |
| override [Contains](../../aspose.pdf/outlinecollection/contains/)(OutlineItemCollection) | コレクションが指定された項目を含むかどうかを確認します。 |
| override [CopyTo](../../aspose.pdf/outlinecollection/copyto/)(OutlineItemCollection[], int) | アウトライン項目を System.Array にコピーし、特定の System.Array インデックスから開始します。 |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete)() | ドキュメントのアウトラインからすべてのアウトライン項目を削除します。 |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete_1)(string) | 指定されたタイトルを持つアウトライン項目をドキュメントのアウトラインから削除します。 |
| override [GetEnumerator](../../aspose.pdf/outlinecollection/getenumerator/)() | コレクションを反復処理する列挙子を返します。 |
| [Remove](../../aspose.pdf/outlinecollection/remove/#remove_1)(int) | インデックスで項目を削除します。 |
| override [Remove](../../aspose.pdf/outlinecollection/remove/#remove)(OutlineItemCollection) | 常に NotImplementedException をスローします。 |

### 関連項目

* class [Outlines](../outlines/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


