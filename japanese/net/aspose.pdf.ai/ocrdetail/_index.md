---
title: "クラス OcrDetail"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.AI.OcrDetail クラス。Document の単一 page または単一画像ファイルの OCR 結果を表します"
type: docs
weight: 860
url: /ja/net/aspose.pdf.ai/ocrdetail/
---
## OcrDetail class

ドキュメントの単一ページまたは単一画像ファイルの OCR 結果を表します。

```csharp
public class OcrDetail : IComparable<OcrDetail>
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [OcrDetail](ocrdetail/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ErrorMessage](../../aspose.pdf.ai/ocrdetail/errormessage/) { get; set; } | Success が false の場合、このページの OCR が失敗した理由を説明するエラーメッセージです。そうでない場合は null です。 |
| [ExtractedText](../../aspose.pdf.ai/ocrdetail/extractedtext/) { get; set; } | ページから抽出されたテキストコンテンツです。Success が false の場合、またはテキストが見つからなかった場合は null です。 |
| [PageNumber](../../aspose.pdf.ai/ocrdetail/pagenumber/) { get; set; } | ソース Document 内の 1 から始まる page 番号です。単一ページ画像の場合、常に 1 になります。 |
| [Success](../../aspose.pdf.ai/ocrdetail/success/) { get; set; } | この特定の page の OCR 抽出が成功したかどうかを示します。 |
| [Usage](../../aspose.pdf.ai/ocrdetail/usage/) { get; set; } | 使用統計情報を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [CompareTo](../../aspose.pdf.ai/ocrdetail/compareto/)(OcrDetail) | 現在の OcrDetail インスタンスを、PageNumber プロパティに基づいて別の OcrDetail オブジェクトと比較します。 |

### 関連項目

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


