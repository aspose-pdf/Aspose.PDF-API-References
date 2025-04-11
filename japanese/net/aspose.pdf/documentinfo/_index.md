---
title: Class DocumentInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DocumentInfo クラス。PDF ドキュメントのメタ情報を表します。
type: docs
weight: 3870
url: /ja/net/aspose.pdf/documentinfo/
---
## DocumentInfo クラス

PDF ドキュメントのメタ情報を表します。

```csharp
public sealed class DocumentInfo : Dictionary<string, string>
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [DocumentInfo](documentinfo/)(Document) | DocumentInfo インスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Author](../../aspose.pdf/documentinfo/author/) { get; set; } | ドキュメントの著者を取得または設定します。 |
| [CreationDate](../../aspose.pdf/documentinfo/creationdate/) { get; set; } | ドキュメント作成の日付を取得または設定します。 |
| [CreationTimeZone](../../aspose.pdf/documentinfo/creationtimezone/) { get; set; } | 作成日の日付のタイムゾーン。 |
| [Creator](../../aspose.pdf/documentinfo/creator/) { get; set; } | ドキュメントの作成者を取得または設定します。 |
| [Item](../../aspose.pdf/documentinfo/item/) { get; set; } | 指定されたキーに関連付けられた値を取得または設定します。 |
| [Keywords](../../aspose.pdf/documentinfo/keywords/) { get; set; } | ドキュメントのキーワードを取得または設定します。 |
| [ModDate](../../aspose.pdf/documentinfo/moddate/) { get; set; } | ドキュメントの変更日を取得または設定します。 |
| [ModTimeZone](../../aspose.pdf/documentinfo/modtimezone/) { get; set; } | 変更日の日付のタイムゾーン。 |
| [Producer](../../aspose.pdf/documentinfo/producer/) { get; set; } | ドキュメントのプロデューサーを取得または設定します。 |
| [Subject](../../aspose.pdf/documentinfo/subject/) { get; set; } | ドキュメントの件名を取得または設定します。 |
| [Title](../../aspose.pdf/documentinfo/title/) { get; set; } | ドキュメントのタイトルを取得または設定します。 |
| [Trapped](../../aspose.pdf/documentinfo/trapped/) { get; set; } | トラップフラグを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Add](../../aspose.pdf/documentinfo/add/#add)(string, string) | 指定されたキーと値を持つ要素をコレクションに追加します。 |
| [Clear](../../aspose.pdf/documentinfo/clear/#clear)() | ドキュメント情報をクリアします。 |
| [ClearCustomData](../../aspose.pdf/documentinfo/clearcustomdata/)() | カスタムデータのみをクリアし、他のすべての定義済み値（タイトル、著者など）はそのままにします。 |
| [Remove](../../aspose.pdf/documentinfo/remove/#remove_2)(string) | 指定されたキーを持つ要素をコレクションから削除します。 |
| static [IsPredefinedKey](../../aspose.pdf/documentinfo/ispredefinedkey/)(string) | キーが定義済み（タイトル、著者など）であり、カスタムでないかどうかを判断します。 |

### 参照

* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)