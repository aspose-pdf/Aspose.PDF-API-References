---
title: "클래스 OcrDetail"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.AI.OcrDetail 클래스. 문서의 단일 페이지 또는 단일 이미지 파일에 대한 OCR 결과를 나타냅니다."
type: docs
weight: 860
url: /ko/net/aspose.pdf.ai/ocrdetail/
---
## OcrDetail class

문서의 단일 페이지 또는 단일 이미지 파일에 대한 OCR 결과를 나타냅니다.

```csharp
public class OcrDetail : IComparable<OcrDetail>
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [OcrDetail](ocrdetail/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [ErrorMessage](../../aspose.pdf.ai/ocrdetail/errormessage/) { get; set; } | Success가 false인 경우 이 페이지에 대한 OCR 실패 원인을 설명하는 오류 메시지입니다. 그 외의 경우는 null입니다. |
| [ExtractedText](../../aspose.pdf.ai/ocrdetail/extractedtext/) { get; set; } | 페이지에서 추출된 텍스트 내용입니다. Success가 false이거나 텍스트가 발견되지 않으면 null입니다. |
| [PageNumber](../../aspose.pdf.ai/ocrdetail/pagenumber/) { get; set; } | 원본 문서 내에서 1부터 시작하는 페이지 번호입니다. 단일 페이지 이미지의 경우 항상 1입니다. |
| [Success](../../aspose.pdf.ai/ocrdetail/success/) { get; set; } | 이 특정 페이지에 대한 OCR 추출이 성공했는지 여부를 나타냅니다. |
| [Usage](../../aspose.pdf.ai/ocrdetail/usage/) { get; set; } | 사용 통계 정보를 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [CompareTo](../../aspose.pdf.ai/ocrdetail/compareto/)(OcrDetail) | 현재 OcrDetail 인스턴스를 해당 PageNumber 속성을 기준으로 다른 OcrDetail 객체와 비교합니다. |

### 또 보기

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


