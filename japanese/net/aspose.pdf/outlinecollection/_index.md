---
title: Class OutlineCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.OutlineCollection クラス。ドキュメントのアウトライン階層を表します
type: docs
weight: 8000
url: /ja/net/aspose.pdf/outlinecollection/
---
## OutlineCollection クラス

ドキュメントのアウトライン階層を表します。

```csharp
public sealed class OutlineCollection : Outlines
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| override [Count](../../aspose.pdf/outlinecollection/count/) { get; } | コレクションアイテムの数。VisibleCountと混同しないでください: VisibleCountはすべてのレベルでの可視アウトラインアイテムの数を取得します。 |
| [First](../../aspose.pdf/outlinecollection/first/) { get; } | アウトラインの最初のトップレベルアイテムを表すアウトラインアイテムを取得します。 |
| override [IsReadOnly](../../aspose.pdf/outlinecollection/isreadonly/) { get; } | コレクションが読み取り専用かどうかを示す値を取得します。 |
| [IsSynchronized](../../aspose.pdf/outlinecollection/issynchronized/) { get; } | このコレクションへのアクセスが同期されているかどうかを示す値を取得します（スレッドセーフ）。 |
| [Item](../../aspose.pdf/outlinecollection/item/) { get; } | インデックスによってコレクションからアウトラインアイテムを取得します。 |
| [Last](../../aspose.pdf/outlinecollection/last/) { get; } | アウトラインの最後のトップレベルアイテムを表すアウトラインアイテムを取得します。 |
| [SyncRoot](../../aspose.pdf/outlinecollection/syncroot/) { get; } | このコレクションへのアクセスを同期するために使用できるオブジェクトを取得します。 |
| override [VisibleCount](../../aspose.pdf/outlinecollection/visiblecount/) { get; } | Countはすべてのレベルでの可視の子孫アウトラインアイテムの数の合計です。注: Countはコレクション内のアイテムの数であるため、混同しないでください。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Add](../../aspose.pdf/outlinecollection/add/)(OutlineItemCollection) | アウトラインアイテムをコレクションに追加します。 |
| override [Clear](../../aspose.pdf/outlinecollection/clear/)() | コレクションからすべてのアイテムをクリアします。 |
| override [Contains](../../aspose.pdf/outlinecollection/contains/)(OutlineItemCollection) | コレクションに指定されたアイテムが含まれているかどうかを確認します。 |
| override [CopyTo](../../aspose.pdf/outlinecollection/copyto/)(OutlineItemCollection[], int) | 特定の System.Array インデックスから始めて、アウトラインアイテムを System.Array にコピーします。 |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete)() | ドキュメントのアウトラインからすべてのアウトラインアイテムを削除します。 |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete_1)(string) | 指定されたタイトルのアウトラインアイテムをドキュメントのアウトラインから削除します。 |
| override [GetEnumerator](../../aspose.pdf/outlinecollection/getenumerator/)() | コレクションを反復処理する列挙子を返します。 |
| [Remove](../../aspose.pdf/outlinecollection/remove/#remove_1)(int) | インデックスによってアイテムを削除します。 |
| override [Remove](../../aspose.pdf/outlinecollection/remove/#remove)(OutlineItemCollection) | 常に NotImplementedException をスローします。 |

### 参照

* クラス [Outlines](../outlines/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)