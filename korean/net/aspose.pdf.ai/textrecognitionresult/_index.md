---
title: "클래스 TextRecognitionResult"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.AI.TextRecognitionResult 클래스. 단일 소스 document에 대한 집계된 OCR 결과를 나타냅니다"
type: docs
weight: 1180
url: /ko/net/aspose.pdf.ai/textrecognitionresult/
---
## TextRecognitionResult class

단일 원본 문서에 대한 집계된 OCR 결과를 나타냅니다.

```csharp
public class TextRecognitionResult
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TextRecognitionResult](textrecognitionresult/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [OcrDetails](../../aspose.pdf.ai/textrecognitionresult/ocrdetails/) { get; set; } | 문서의 각 page에 대한 상세 OCR 결과를 포함하는 목록입니다. single-image 파일의 경우, 이 목록은 일반적으로 PageNumber = 1인 OcrDetail 항목 하나를 포함합니다. |
| [OverallSuccess](../../aspose.pdf.ai/textrecognitionresult/overallsuccess/) { get; set; } | 이 document 내의 모든 pages에 대해 OCR이 성공했는지 여부를 나타냅니다. OcrDetails의 어떤 OcrDetail이라도 Success = false인 경우 false입니다. |
| [SourceIdentifier](../../aspose.pdf.ai/textrecognitionresult/sourceidentifier/) { get; set; } | 소스 파일의 식별자(예: 전체 경로나 고유 이름). |
| [SummaryErrorMessage](../../aspose.pdf.ai/textrecognitionresult/summaryerrormessage/) { get; set; } | OverallSuccess가 false인 경우 통합 오류 메시지이며, any page이 실패하면 요약을 제공합니다. OverallSuccess가 true인 경우 Null입니다. |
| [TotalUsage](../../aspose.pdf.ai/textrecognitionresult/totalusage/) { get; set; } | 이 문서(전체 페이지)를 처리하기 위한 총 사용 통계를 가져오거나 설정합니다. |

### 또 보기

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


