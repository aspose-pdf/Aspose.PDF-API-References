---
title: Class OutlineItemCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.OutlineItemCollection クラス。PDF ドキュメントのアウトライン階層におけるアウトラインエントリを表します。
type: docs
weight: 8010
url: /ja/net/aspose.pdf/outlineitemcollection/
---
## OutlineItemCollection クラス

PDF ドキュメントのアウトライン階層におけるアウトラインエントリを表します。

```csharp
public sealed class OutlineItemCollection : Outlines
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [OutlineItemCollection](outlineitemcollection/)(OutlineCollection) | ルート階層オブジェクトを使用してアウトラインアイテムインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Action](../../aspose.pdf/outlineitemcollection/action/) { get; set; } | このアウトラインアイテムのアクションを取得または設定します。 |
| [Bold](../../aspose.pdf/outlineitemcollection/bold/) { get; set; } | このアウトラインアイテムのタイトルテキストの太字フラグを取得または設定します。 |
| [Color](../../aspose.pdf/outlineitemcollection/color/) { get; set; } | このアウトラインアイテムのタイトルテキストの色を取得または設定します。 |
| override [Count](../../aspose.pdf/outlineitemcollection/count/) { get; } | コレクションアイテムの数。VisibleCount と混同しないでください: VisibleCount はすべてのレベルでの可視アウトラインアイテムの数を取得します。 |
| [Destination](../../aspose.pdf/outlineitemcollection/destination/) { get; set; } | このアウトラインアイテムの宛先を取得または設定します。 |
| [First](../../aspose.pdf/outlineitemcollection/first/) { get; } | アウトライン階層の最初のトップレベルアイテムを表すアウトラインアイテムを取得します。 |
| [HasNext](../../aspose.pdf/outlineitemcollection/hasnext/) { get; } | アウトライン階層においてこのアイテムに対して次のアイテムを表すアウトラインアイテムがあるかどうかを確認します。 |
| override [IsReadOnly](../../aspose.pdf/outlineitemcollection/isreadonly/) { get; } | コレクションが読み取り専用かどうかを示す値を取得します。 |
| [IsSynchronized](../../aspose.pdf/outlineitemcollection/issynchronized/) { get; } | このコレクションへのアクセスが同期されているかどうか（スレッドセーフ）を示す値を取得します。 |
| [Italic](../../aspose.pdf/outlineitemcollection/italic/) { get; set; } | このアウトラインアイテムのタイトルテキストのイタリックフラグを取得または設定します。 |
| [Item](../../aspose.pdf/outlineitemcollection/item/) { get; } | インデックスを使用してコレクションからアウトラインアイテムを取得します。 |
| [Last](../../aspose.pdf/outlineitemcollection/last/) { get; } | アウトライン階層の最後のトップレベルアイテムを表すアウトラインアイテムを取得します。 |
| [Level](../../aspose.pdf/outlineitemcollection/level/) { get; } | アウトラインアイテムの階層レベルを取得します。 |
| [Next](../../aspose.pdf/outlineitemcollection/next/) { get; } | アウトライン階層においてこのアイテムに対して次のアイテムを表すアウトラインアイテムを取得します。 |
| [Open](../../aspose.pdf/outlineitemcollection/open/) { get; set; } | アウトラインアイテムのオープン状態（true/false）を取得または設定します。 |
| [Parent](../../aspose.pdf/outlineitemcollection/parent/) { get; } | アウトライン階層におけるこのアウトラインアイテムの親オブジェクトを取得します。 |
| [Prev](../../aspose.pdf/outlineitemcollection/prev/) { get; } | アウトライン階層においてこのアイテムに対して前のアイテムを表すアウトラインアイテムを取得します。 |
| [SyncRoot](../../aspose.pdf/outlineitemcollection/syncroot/) { get; } | このコレクションへのアクセスを同期するために使用できるオブジェクトを取得します。 |
| [Title](../../aspose.pdf/outlineitemcollection/title/) { get; set; } | このアウトラインアイテムのタイトルを取得または設定します。 |
| override [VisibleCount](../../aspose.pdf/outlineitemcollection/visiblecount/) { get; } | ドキュメントのアウトライン階層におけるすべてのレベルのアウトラインアイテムの総数を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Add](../../aspose.pdf/outlineitemcollection/add/)(OutlineItemCollection) | アウトラインアイテムをコレクションに追加します。 |
| override [Clear](../../aspose.pdf/outlineitemcollection/clear/)() | コレクションからすべてのアイテムをクリアします。 |
| override [Contains](../../aspose.pdf/outlineitemcollection/contains/)(OutlineItemCollection) | コレクションに指定されたアイテムが含まれているかどうかを確認します。 |
| override [CopyTo](../../aspose.pdf/outlineitemcollection/copyto/)(OutlineItemCollection[], int) | 特定の System.Array インデックスから始めて、アウトラインエントリを System.Array にコピーします。 |
| [Delete](../../aspose.pdf/outlineitemcollection/delete/#delete)() | このアウトラインアイテムをドキュメントのアウトライン階層から削除します。 |
| [Delete](../../aspose.pdf/outlineitemcollection/delete/#delete_1)(string) | 指定された名前のアウトラインエントリをドキュメントのアウトライン階層から削除します。 |
| override [GetEnumerator](../../aspose.pdf/outlineitemcollection/getenumerator/)() | コレクションを反復処理する列挙子を返します。 |
| [Insert](../../aspose.pdf/outlineitemcollection/insert/)(int, OutlineItemCollection) | 指定された場所にアウトラインアイテムをコレクションに挿入します。 |
| [Remove](../../aspose.pdf/outlineitemcollection/remove/#remove_1)(int) | インデックスによってアイテムを削除します。 |
| override [Remove](../../aspose.pdf/outlineitemcollection/remove/#remove)(OutlineItemCollection) | アウトラインコレクションアイテムを削除します。 |

### 参照

* クラス [Outlines](../outlines/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)