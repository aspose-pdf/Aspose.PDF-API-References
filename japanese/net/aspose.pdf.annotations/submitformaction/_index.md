---
title: "クラス SubmitFormAction"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Annotations.SubmitFormAction クラス。submitform アクションを記述するクラス"
type: docs
weight: 2740
url: /ja/net/aspose.pdf.annotations/submitformaction/
---
## SubmitFormAction class

submit-form アクションを記述するクラス。

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
| [Flags](../../aspose.pdf.annotations/submitformaction/flags/) { get; set; } | 送信アクションのフラグを取得または設定します |
| [Next](../../aspose.pdf.annotations/pdfaction/next/) { get; } | シーケンス内の次のアクション。 |
| [Url](../../aspose.pdf.annotations/submitformaction/url/) { get; set; } | 宛先 URL。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetECMAScriptString](../../aspose.pdf.annotations/pdfaction/getecmascriptstring/)() | ECMAScript アクションの文字列を取得します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [CanonicalFormat](../../aspose.pdf.annotations/submitformaction/canonicalformat/) | 設定されている場合、日付を表す送信されたフィールド値は標準形式に変換されます。 |
| const [EmbedForm](../../aspose.pdf.annotations/submitformaction/embedform/) | 設定されている場合、送信された FDF の F エントリは、FDF が送信される元の PDF ファイルを表す埋め込みファイルストリームを含むファイル仕様でなければなりません。 |
| const [ExclFKey](../../aspose.pdf.annotations/submitformaction/exclfkey/) | 設定されている場合、送信された FDF は F エントリを除外します。 |
| const [ExclNonUserAnnots](../../aspose.pdf.annotations/submitformaction/exclnonuserannots/) | 設定されている場合、現在のユーザー名と一致する T エントリを持つマークアップ注釈のみを含めます。 |
| const [Exclude](../../aspose.pdf.annotations/submitformaction/exclude/) | クリアされている場合、Fields 配列は送信に含めるフィールドを指定します。 |
| const [ExportFormat](../../aspose.pdf.annotations/submitformaction/exportformat/) | 設定されている場合、フィールド名と値は HTML フォーム形式で送信されます。 |
| const [GetMethod](../../aspose.pdf.annotations/submitformaction/getmethod/) | 設定されている場合、フィールド名と値は HTTP GET リクエストを使用して送信されます。 |
| const [IncludeAnnotations](../../aspose.pdf.annotations/submitformaction/includeannotations/) | 設定されている場合、送信された FDF ファイルは基礎となる PDF ドキュメント内のすべてのマークアップ注釈を含めます。 |
| const [IncludeAppendSaves](../../aspose.pdf.annotations/submitformaction/includeappendsaves/) | 設定されている場合、送信された FDF ファイルはすべての増分更新の内容を含めます。 |
| const [IncludeNoValueFields](../../aspose.pdf.annotations/submitformaction/includenovaluefields/) | 設定されている場合、Fields 配列と Include/Exclude フラグで指定されたすべてのフィールドが送信されます。 |
| const [SubmitCoordinates](../../aspose.pdf.annotations/submitformaction/submitcoordinates/) | 設定されている場合、submit-form アクションを引き起こしたマウスクリックの座標がフォームデータの一部として送信されます。 |
| const [SubmitPdf](../../aspose.pdf.annotations/submitformaction/submitpdf/) | 設定されている場合、ドキュメントは MIME コンテンツタイプ application/pdf を使用して PDF として送信されます。 |
| const [Xfdf](../../aspose.pdf.annotations/submitformaction/xfdf/) | 設定されている場合、フィールド名と値は XFDF として送信されます。 |

### 関連項目

* class [PdfAction](../pdfaction/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


