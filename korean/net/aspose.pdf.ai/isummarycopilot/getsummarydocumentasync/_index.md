---
title: ISummaryCopilot.GetSummaryDocumentAsync
second_title: Aspose.PDF for .NET API Reference
description: ISummaryCopilot 메서드. 비동기적으로 요약 PDF 문서를 가져옵니다.
type: docs
weight: 20
url: /ko/net/aspose.pdf.ai/isummarycopilot/getsummarydocumentasync/
---
## GetSummaryDocumentAsync(CancellationToken?) {#getsummarydocumentasync_1}

비동기적으로 요약 PDF 문서를 가져옵니다.

```csharp
public Task<Document> GetSummaryDocumentAsync(CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| cancellationToken | Nullable`1 | 취소 토큰(선택 사항). |

### 반환 값

요약 문서와 함께 비동기 작업을 나타내는 작업입니다.

### 참조

* 클래스 [Document](../../../aspose.pdf/document/)
* 인터페이스 [ISummaryCopilot](../)
* 네임스페이스 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../../)

---

## GetSummaryDocumentAsync(PageInfo, CancellationToken?) {#getsummarydocumentasync}

지정된 페이지 정보에 대한 요약 PDF 문서를 비동기적으로 가져옵니다.

```csharp
public Task<Document> GetSummaryDocumentAsync(PageInfo pageInfo, 
    CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pageInfo | PageInfo | 요약 문서를 생성할 페이지 정보입니다. |
| cancellationToken | Nullable`1 | 취소 토큰(선택 사항). |

### 반환 값

요약 문서와 함께 비동기 작업을 나타내는 작업입니다.

### 참조

* 클래스 [Document](../../../aspose.pdf/document/)
* 클래스 [PageInfo](../../../aspose.pdf/pageinfo/)
* 인터페이스 [ISummaryCopilot](../)
* 네임스페이스 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../../)