---
title: ISummaryCopilot.SaveSummaryAsync
second_title: Aspose.PDF for .NET API Reference
description: ISummaryCopilot 메서드. 요약을 PDF 파일로 비동기적으로 저장합니다.
type: docs
weight: 30
url: /ko/net/aspose.pdf.ai/isummarycopilot/savesummaryasync/
---
## SaveSummaryAsync(string, CancellationToken?) {#savesummaryasync_1}

요약을 PDF 파일로 비동기적으로 저장합니다.

```csharp
public Task SaveSummaryAsync(string outputFileName, CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFileName | String | 요약을 저장할 출력 파일의 이름입니다. |
| cancellationToken | Nullable`1 | 취소 토큰(선택 사항)입니다. |

### 반환 값

비동기 작업을 나타내는 작업입니다.

### 참조

* 인터페이스 [ISummaryCopilot](../)
* 네임스페이스 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../../)

---

## SaveSummaryAsync(string, SaveFormat, CancellationToken?) {#savesummaryasync}

지정된 형식으로 파일에 요약을 비동기적으로 저장합니다.

```csharp
public Task SaveSummaryAsync(string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFileName | String | 요약을 저장할 출력 파일의 이름입니다. |
| saveFormat | SaveFormat | 요약을 저장할 형식입니다. |
| cancellationToken | Nullable`1 | 취소 토큰(선택 사항)입니다. |

### 반환 값

비동기 작업을 나타내는 작업입니다.

### 참조

* 열거형 [SaveFormat](../../../aspose.pdf/saveformat/)
* 인터페이스 [ISummaryCopilot](../)
* 네임스페이스 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../../)