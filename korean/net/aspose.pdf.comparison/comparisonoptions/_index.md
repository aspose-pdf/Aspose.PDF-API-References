---
title: "클래스 ComparisonOptions"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Comparison.ComparisonOptions 클래스. PDF Document 비교 옵션 클래스를 나타냅니다."
type: docs
weight: 3260
url: /ko/net/aspose.pdf.comparison/comparisonoptions/
---
## ComparisonOptions class

PDF 문서 비교 옵션 클래스를 나타냅니다.

```csharp
public class ComparisonOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ComparisonOptions](comparisonoptions/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [EditOperationsOrder](../../aspose.pdf.comparison/comparisonoptions/editoperationsorder/) { get; set; } | 편집 연산 순서를 가져오고 설정합니다. |
| [ExcludeAreas1](../../aspose.pdf.comparison/comparisonoptions/excludeareas1/) { get; set; } | 제외 영역을 가져오고 설정합니다. 비교 방법에서 첫 번째 Page 또는 Document에 사용됩니다. 이 옵션은 [`ExcludeTables`](./excludetables/)와 함께 설정할 수 있습니다. 이 옵션은 [`ExtractionArea`](./extractionarea/) 옵션과 함께 설정할 수 없습니다. |
| [ExcludeAreas2](../../aspose.pdf.comparison/comparisonoptions/excludeareas2/) { get; set; } | 제외 영역을 가져오고 설정합니다. 비교 방법에서 두 번째 Page 또는 Document에 사용됩니다. 이 옵션은 [`ExcludeTables`](./excludetables/)와 함께 설정할 수 있습니다. 이 옵션은 [`ExtractionArea`](./extractionarea/) 옵션과 함께 설정할 수 없습니다. |
| [ExcludeTables](../../aspose.pdf.comparison/comparisonoptions/excludetables/) { get; set; } | 테이블을 비교에서 제외할지 여부를 결정하는 옵션을 가져오고 설정합니다. 이 옵션은 [`ExtractionArea`](./extractionarea/) 옵션과 함께 설정할 수 없습니다. 기본값은 `false`입니다. |
| [ExtractionArea](../../aspose.pdf.comparison/comparisonoptions/extractionarea/) { get; set; } | Page 텍스트를 비교할 직사각형 영역을 가져오고 설정합니다. 이 옵션은 [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) 및 [`ExcludeAreas2`](./excludeareas2/) 옵션과 함께 설정할 수 없습니다. |

### 또 보기

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


