---
title: "クラス OutlineItemCollection"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.OutlineItemCollection クラス。PDF Document のアウトライン階層内のアウトラインエントリを表します。"
type: docs
weight: 8150
url: /ja/net/aspose.pdf/outlineitemcollection/
---
## OutlineItemCollection class

PDF document のアウトライン階層内のアウトラインエントリを表します。

```csharp
public sealed class OutlineItemCollection : Outlines
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [OutlineItemCollection](outlineitemcollection/)(OutlineCollection) | ルート階層オブジェクトを使用してアウトライン項目インスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Action](../../aspose.pdf/outlineitemcollection/action/) { get; set; } | このアウトライン項目のアクションを取得または設定します。 |
| [Bold](../../aspose.pdf/outlineitemcollection/bold/) { get; set; } | このアウトライン項目のタイトルテキストの太字フラグを取得または設定します。 |
| [Color](../../aspose.pdf/outlineitemcollection/color/) { get; set; } | このアウトライン項目のタイトルテキストの色を取得または設定します。 |
| override [Count](../../aspose.pdf/outlineitemcollection/count/) { get; } | コレクション項目の数です。VisibleCount と混同しないでください：VisibleCount はすべてのレベルで表示されるアウトライン項目の数を取得します。 |
| [Destination](../../aspose.pdf/outlineitemcollection/destination/) { get; set; } | このアウトライン項目の宛先を取得または設定します。 |
| [First](../../aspose.pdf/outlineitemcollection/first/) { get; } | アウトライン階層内の最上位項目を表すアウトライン項目を取得します。 |
| [HasNext](../../aspose.pdf/outlineitemcollection/hasnext/) { get; } | アウトライン階層でこの項目に対して次の項目を表すアウトライン項目かどうかを確認します。 |
| override [IsReadOnly](../../aspose.pdf/outlineitemcollection/isreadonly/) { get; } | コレクションが読み取り専用かどうかを示す値を取得します。 |
| [IsSynchronized](../../aspose.pdf/outlineitemcollection/issynchronized/) { get; } | このコレクションへのアクセスが同期化されているか（スレッドセーフ）を示す値を取得します。 |
| [Italic](../../aspose.pdf/outlineitemcollection/italic/) { get; set; } | このアウトライン項目のタイトルテキストのイタリックフラグを取得または設定します。 |
| [Item](../../aspose.pdf/outlineitemcollection/item/) { get; } | インデックスを使用してコレクションからアウトライン項目を取得します。 |
| [Last](../../aspose.pdf/outlineitemcollection/last/) { get; } | アウトライン階層で最上位の最後の項目を表すアウトライン項目を取得します。 |
| [Level](../../aspose.pdf/outlineitemcollection/level/) { get; } | アウトライン項目の階層レベルを取得します。 |
| [Next](../../aspose.pdf/outlineitemcollection/next/) { get; } | アウトライン階層でこの項目に対して次の項目を表すアウトライン項目を取得します。 |
| [Open](../../aspose.pdf/outlineitemcollection/open/) { get; set; } | アウトライン項目の開閉状態（true/false）を取得または設定します。 |
| [Parent](../../aspose.pdf/outlineitemcollection/parent/) { get; } | アウトライン階層でこのアウトライン項目の親オブジェクトを取得します。 |
| [Prev](../../aspose.pdf/outlineitemcollection/prev/) { get; } | アウトライン階層でこの項目に対して前の項目を表すアウトライン項目を取得します。 |
| [SyncRoot](../../aspose.pdf/outlineitemcollection/syncroot/) { get; } | このコレクションへのアクセスを同期化するために使用できるオブジェクトを取得します。 |
| [Title](../../aspose.pdf/outlineitemcollection/title/) { get; set; } | このアウトライン項目のタイトルを取得または設定します。 |
| override [VisibleCount](../../aspose.pdf/outlineitemcollection/visiblecount/) { get; } | ドキュメントのアウトライン階層のすべてのレベルにおけるアウトライン項目の総数を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Add](../../aspose.pdf/outlineitemcollection/add/)(OutlineItemCollection) | アウトライン項目をコレクションに追加します。 |
| override [Clear](../../aspose.pdf/outlineitemcollection/clear/)() | コレクションからすべての項目をクリアします。 |
| override [Contains](../../aspose.pdf/outlineitemcollection/contains/)(OutlineItemCollection) | コレクションが指定された項目を含むかどうかを確認します。 |
| override [CopyTo](../../aspose.pdf/outlineitemcollection/copyto/)(OutlineItemCollection[], int) | アウトラインエントリを System.Array にコピーし、特定の System.Array インデックスから開始します。 |
| [Delete](../../aspose.pdf/outlineitemcollection/delete/#delete)() | このアウトライン項目をドキュメントのアウトライン階層から削除します。 |
| [Delete](../../aspose.pdf/outlineitemcollection/delete/#delete_1)(string) | 指定された名前のアウトラインエントリをドキュメントのアウトライン階層から削除します。 |
| override [GetEnumerator](../../aspose.pdf/outlineitemcollection/getenumerator/)() | コレクションを反復処理する列挙子を返します。 |
| [Insert](../../aspose.pdf/outlineitemcollection/insert/)(int, OutlineItemCollection) | 指定された位置にアウトライン項目をコレクションに挿入します。 |
| [Remove](../../aspose.pdf/outlineitemcollection/remove/#remove_1)(int) | インデックスで項目を削除します。 |
| override [Remove](../../aspose.pdf/outlineitemcollection/remove/#remove)(OutlineItemCollection) | アウトラインコレクション項目を削除します。 |

### 関連項目

* class [Outlines](../outlines/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


