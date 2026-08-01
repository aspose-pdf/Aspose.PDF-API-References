---
title: "IOcrCopilot.GetTextRecognitionResultAsync"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "IOcrCopilot 메서드. PDF 문서와 이미지 파일에 대한 텍스트 인식 결과를 비동기적으로 가져옵니다. 지원되는 이미지 유형은 PNG .png, JPEG .jpeg 및 .jpg, WEBP .webp, 비애니메이션 GIF .gif 입니다."
type: docs
weight: 10
url: /ko/net/aspose.pdf.ai/iocrcopilot/gettextrecognitionresultasync/
---
## IOcrCopilot.GetTextRecognitionResultAsync method

PDF 문서와 이미지 파일에 대한 텍스트 인식 결과를 비동기적으로 검색합니다. 지원되는 이미지 유형: PNG(.png), JPEG(.jpeg 및 .jpg), WEBP(.webp), 비애니메이션 GIF(.gif).

```csharp
public Task<List<TextRecognitionResult>> GetTextRecognitionResultAsync(
    CancellationToken? cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| cancellationToken | Nullable`1 | 작업을 취소하기 위한 선택적 취소 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 작업입니다. 작업 결과에는 [`TextRecognitionResult`](../../textrecognitionresult/) 목록이 포함됩니다.

### 또 보기

* class [TextRecognitionResult](../../textrecognitionresult/)
* interface [IOcrCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


