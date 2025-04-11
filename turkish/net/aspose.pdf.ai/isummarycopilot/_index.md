---
title: Interface ISummaryCopilot
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.ISummaryCopilot arayüzü. AI modellerini kullanarak belgeler için özetler oluşturan bir özet yardımcı pilotunu temsil eder.
type: docs
weight: 590
url: /tr/net/aspose.pdf.ai/isummarycopilot/
---
## ISummaryCopilot arayüzü

AI modellerini kullanarak belgeler için özetler oluşturan bir özet yardımcı pilotunu temsil eder.

```csharp
public interface ISummaryCopilot : IAICopilot
```

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [GetSummaryAsync](../../aspose.pdf.ai/isummarycopilot/getsummaryasync/)(CancellationToken?) | Asenkron olarak bir özet alır. |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/isummarycopilot/getsummarydocumentasync/#getsummarydocumentasync_1)(CancellationToken?) | Asenkron olarak bir özet PDF belgesi alır. |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/isummarycopilot/getsummarydocumentasync/#getsummarydocumentasync)(PageInfo, CancellationToken?) | Belirtilen sayfa bilgisi için asenkron olarak bir özet PDF belgesi alır. |
| [SaveSummaryAsync](../../aspose.pdf.ai/isummarycopilot/savesummaryasync/#savesummaryasync_1)(string, CancellationToken?) | Asenkron olarak özeti bir PDF dosyasına kaydeder. |
| [SaveSummaryAsync](../../aspose.pdf.ai/isummarycopilot/savesummaryasync/#savesummaryasync)(string, SaveFormat, CancellationToken?) | Belirtilen formatta bir dosyaya asenkron olarak özeti kaydeder. |

### Ayrıca Bakınız

* arayüz [IAICopilot](../iaicopilot/)
* ad alanı [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* derleme [Aspose.PDF](../../)