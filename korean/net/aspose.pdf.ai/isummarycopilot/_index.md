---
title: Interface ISummaryCopilot
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.ISummaryCopilot 인터페이스. AI 모델을 사용하여 문서의 요약을 생성하는 요약 코파일럿을 나타냅니다.
type: docs
weight: 590
url: /ko/net/aspose.pdf.ai/isummarycopilot/
---
## ISummaryCopilot 인터페이스

AI 모델을 사용하여 문서의 요약을 생성하는 요약 코파일럿을 나타냅니다.

```csharp
public interface ISummaryCopilot : IAICopilot
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [GetSummaryAsync](../../aspose.pdf.ai/isummarycopilot/getsummaryasync/)(CancellationToken?) | 비동기적으로 요약을 가져옵니다. |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/isummarycopilot/getsummarydocumentasync/#getsummarydocumentasync_1)(CancellationToken?) | 비동기적으로 요약 PDF 문서를 가져옵니다. |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/isummarycopilot/getsummarydocumentasync/#getsummarydocumentasync)(PageInfo, CancellationToken?) | 지정된 페이지 정보에 대한 요약 PDF 문서를 비동기적으로 가져옵니다. |
| [SaveSummaryAsync](../../aspose.pdf.ai/isummarycopilot/savesummaryasync/#savesummaryasync_1)(string, CancellationToken?) | 요약을 PDF 파일로 비동기적으로 저장합니다. |
| [SaveSummaryAsync](../../aspose.pdf.ai/isummarycopilot/savesummaryasync/#savesummaryasync)(string, SaveFormat, CancellationToken?) | 지정된 형식으로 파일에 요약을 비동기적으로 저장합니다. |

### 참조

* 인터페이스 [IAICopilot](../iaicopilot/)
* 네임스페이스 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../)