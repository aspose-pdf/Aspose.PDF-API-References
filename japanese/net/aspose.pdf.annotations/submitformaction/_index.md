---
title: Class SubmitFormAction
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.SubmitFormAction クラス。submitform アクションを説明するクラス
type: docs
weight: 2640
url: /ja/net/aspose.pdf.annotations/submitformaction/
---
## SubmitFormAction クラス

submit-form アクションを説明するクラスです。

```csharp
public sealed class SubmitFormAction : PdfAction
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SubmitFormAction](submitformaction/)() | SubmitFormAction オブジェクトを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Flags](../../aspose.pdf.annotations/submitformaction/flags/) { get; set; } | submit アクションのフラグを取得または設定します。 |
| [Next](../../aspose.pdf.annotations/pdfaction/next/) { get; } | シーケンス内の次のアクション。 |
| [Url](../../aspose.pdf.annotations/submitformaction/url/) { get; set; } | 送信先の URL。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetECMAScriptString](../../aspose.pdf.annotations/pdfaction/getecmascriptstring/)() | ECMAScript アクションのための文字列を取得します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [CanonicalFormat](../../aspose.pdf.annotations/submitformaction/canonicalformat/) | 設定されている場合、提出されたフィールド値が日付を表す場合は、標準形式に変換されます。 |
| const [EmbedForm](../../aspose.pdf.annotations/submitformaction/embedform/) | 設定されている場合、提出された FDF の F エントリは、FDF が提出される PDF ファイルを表す埋め込まれたファイルストリームを含むファイル仕様になります。 |
| const [ExclFKey](../../aspose.pdf.annotations/submitformaction/exclfkey/) | 設定されている場合、提出された FDF は F エントリを除外します。 |
| const [ExclNonUserAnnots](../../aspose.pdf.annotations/submitformaction/exclnonuserannots/) | 設定されている場合、現在のユーザーの名前と一致する T エントリを持つマークアップ注釈のみが含まれます。 |
| const [Exclude](../../aspose.pdf.annotations/submitformaction/exclude/) | クリアされている場合、Fields 配列は提出に含めるフィールドを指定します。 |
| const [ExportFormat](../../aspose.pdf.annotations/submitformaction/exportformat/) | 設定されている場合、フィールド名と値は HTML フォーム形式で提出されます。 |
| const [GetMethod](../../aspose.pdf.annotations/submitformaction/getmethod/) | 設定されている場合、フィールド名と値は HTTP GET リクエストを使用して提出されます。 |
| const [IncludeAnnotations](../../aspose.pdf.annotations/submitformaction/includeannotations/) | 設定されている場合、提出された FDF ファイルは、基になる PDF ドキュメント内のすべてのマークアップ注釈を含みます。 |
| const [IncludeAppendSaves](../../aspose.pdf.annotations/submitformaction/includeappendsaves/) | 設定されている場合、提出された FDF ファイルは、すべての増分更新の内容を含みます。 |
| const [IncludeNoValueFields](../../aspose.pdf.annotations/submitformaction/includenovaluefields/) | 設定されている場合、Fields 配列および Include/Exclude フラグによって指定されたすべてのフィールドが提出されます。 |
| const [SubmitCoordinates](../../aspose.pdf.annotations/submitformaction/submitcoordinates/) | 設定されている場合、submit-form アクションを引き起こしたマウスクリックの座標がフォームデータの一部として送信されます。 |
| const [SubmitPdf](../../aspose.pdf.annotations/submitformaction/submitpdf/) | 設定されている場合、ドキュメントは PDF として提出され、MIME コンテンツタイプ application/pdf が使用されます。 |
| const [Xfdf](../../aspose.pdf.annotations/submitformaction/xfdf/) | 設定されている場合、フィールド名と値は XFDF として提出されます。 |

### 参照

* クラス [PdfAction](../pdfaction/)
* 名前空間 [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* アセンブリ [Aspose.PDF](../../)