---
title: "クラス TextRecognitionResult"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.AI.TextRecognitionResult クラス。単一のソースドキュメントに対する集約 OCR 結果を表します。"
type: docs
weight: 1180
url: /ja/net/aspose.pdf.ai/textrecognitionresult/
---
## TextRecognitionResult class

単一のソースドキュメントに対する集約されたOCR結果を表します。

```csharp
public class TextRecognitionResult
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TextRecognitionResult](textrecognitionresult/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [OcrDetails](../../aspose.pdf.ai/textrecognitionresult/ocrdetails/) { get; set; } | ドキュメントの各 page に対する詳細な OCR 結果を含むリストです。単一画像ファイルの場合、このリストは通常、PageNumber = 1 の OcrDetail エントリを 1 つ含みます。 |
| [OverallSuccess](../../aspose.pdf.ai/textrecognitionresult/overallsuccess/) { get; set; } | この document 内のすべての page で OCR が成功したかどうかを示します。OcrDetails のいずれかの OcrDetail の Success が false の場合は false です。 |
| [SourceIdentifier](../../aspose.pdf.ai/textrecognitionresult/sourceidentifier/) { get; set; } | ソースファイルの識別子（例：フルパスまたは一意の名前）。 |
| [SummaryErrorMessage](../../aspose.pdf.ai/textrecognitionresult/summaryerrormessage/) { get; set; } | OverallSuccess が false の場合は統合エラーメッセージ、ページが失敗した場合は要約を示します。OverallSuccess が true の場合は null です。 |
| [TotalUsage](../../aspose.pdf.ai/textrecognitionresult/totalusage/) { get; set; } | このドキュメント（すべてのページ）の処理に使用された合計統計情報を取得または設定します。 |

### 関連項目

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


