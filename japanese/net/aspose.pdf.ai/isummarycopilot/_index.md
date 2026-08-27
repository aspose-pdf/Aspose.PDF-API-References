---
title: "インターフェイス ISummaryCopilot"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.AI.ISummaryCopilot インターフェイス。AI モデルを使用してドキュメントの要約を生成するサマリーコパイロットを表します"
type: docs
weight: 640
url: /ja/net/aspose.pdf.ai/isummarycopilot/
---
## ISummaryCopilot interface

AI モデルを使用してドキュメントの要約を生成するサマリーコパイロットを表します。

```csharp
public interface ISummaryCopilot : IAICopilot
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetSummaryAsync](../../aspose.pdf.ai/isummarycopilot/getsummaryasync/)(CancellationToken?) | 非同期で要約を取得します。 |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/isummarycopilot/getsummarydocumentasync/#getsummarydocumentasync_1)(CancellationToken?) | 非同期で要約 PDF ドキュメントを取得します。 |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/isummarycopilot/getsummarydocumentasync/#getsummarydocumentasync)(PageInfo, CancellationToken?) | 指定されたページ情報に対する要約 PDF ドキュメントを非同期で取得します。 |
| [SaveSummaryAsync](../../aspose.pdf.ai/isummarycopilot/savesummaryasync/#savesummaryasync_1)(string, CancellationToken?) | サマリーを非同期で PDF ファイルに保存します。 |
| [SaveSummaryAsync](../../aspose.pdf.ai/isummarycopilot/savesummaryasync/#savesummaryasync)(string, SaveFormat, CancellationToken?) | サマリーを非同期で指定された形式のファイルに保存します。 |

### 関連項目

* interface [IAICopilot](../iaicopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


