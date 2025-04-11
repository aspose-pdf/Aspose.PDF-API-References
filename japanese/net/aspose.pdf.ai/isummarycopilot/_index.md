---
title: Interface ISummaryCopilot
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.ISummaryCopilot インターフェース。AI モデルを使用して文書の要約を生成するための要約コパイロットを表します。
type: docs
weight: 590
url: /ja/net/aspose.pdf.ai/isummarycopilot/
---
## ISummaryCopilot インターフェース

AI モデルを使用して文書の要約を生成するための要約コパイロットを表します。

```csharp
public interface ISummaryCopilot : IAICopilot
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetSummaryAsync](../../aspose.pdf.ai/isummarycopilot/getsummaryasync/)(CancellationToken?) | 非同期で要約を取得します。 |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/isummarycopilot/getsummarydocumentasync/#getsummarydocumentasync_1)(CancellationToken?) | 非同期で要約 PDF ドキュメントを取得します。 |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/isummarycopilot/getsummarydocumentasync/#getsummarydocumentasync)(PageInfo, CancellationToken?) | 指定されたページ情報の要約 PDF ドキュメントを非同期で取得します。 |
| [SaveSummaryAsync](../../aspose.pdf.ai/isummarycopilot/savesummaryasync/#savesummaryasync_1)(string, CancellationToken?) | 要約を PDF ファイルに非同期で保存します。 |
| [SaveSummaryAsync](../../aspose.pdf.ai/isummarycopilot/savesummaryasync/#savesummaryasync)(string, SaveFormat, CancellationToken?) | 指定された形式のファイルに要約を非同期で保存します。 |

### 参照

* インターフェース [IAICopilot](../iaicopilot/)
* 名前空間 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../)