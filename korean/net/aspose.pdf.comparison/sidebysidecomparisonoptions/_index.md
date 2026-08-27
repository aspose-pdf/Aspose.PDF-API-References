---
title: "클래스 SideBySideComparisonOptions"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Comparison.SideBySideComparisonOptions 클래스. 문서를 나란히 출력으로 비교하기 위한 옵션 클래스입니다."
type: docs
weight: 3400
url: /ko/net/aspose.pdf.comparison/sidebysidecomparisonoptions/
---
## SideBySideComparisonOptions class

문서를 나란히 출력하여 비교하기 위한 옵션 클래스를 나타냅니다.

```csharp
public class SideBySideComparisonOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SideBySideComparisonOptions](sidebysidecomparisonoptions/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AdditionalChangeMarks](../../aspose.pdf.comparison/sidebysidecomparisonoptions/additionalchangemarks/) { get; set; } | 추가 변경 표시기가 표시되는지를 결정하는 속성을 가져오고 설정합니다. 설정하면 현재 페이지에 없지만 다른 페이지에 존재하는 변경 표시를 표시합니다. 변경이 단어 사이에 위치하는 경우, 표시가 공백 문자에 정확히 맞춰지지 않을 수 있습니다. 기본값은 `false`입니다. |
| [ComparisonArea1](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonarea1/) { get; set; } | 비교 영역을 가져오고 설정합니다. 비교 방법에서 첫 번째 페이지 또는 문서에 사용됩니다. 이 옵션은 [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) 및 [`ExcludeAreas2`](./excludeareas2/) 옵션과 함께 설정할 수 없습니다. |
| [ComparisonArea2](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonarea2/) { get; set; } | 비교 영역을 가져오고 설정합니다. 비교 방법에서 두 번째 페이지 또는 문서에 사용됩니다. 이 옵션은 [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) 및 [`ExcludeAreas2`](./excludeareas2/) 옵션과 함께 설정할 수 없습니다. |
| [ComparisonMode](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonmode/) { get; set; } | 비교 모드를 가져오고 설정합니다. 기본값은 !:SideBySideComparison.ComparisonMode.IgnoreSpaces입니다. |
| [ExcludeAreas1](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludeareas1/) { get; set; } | 제외 영역을 가져오고 설정합니다. 비교 방법에서 첫 번째 페이지 또는 문서에 사용됩니다. 이 옵션은 [`ExcludeTables`](./excludetables/)와 함께 설정할 수 있습니다. 이 옵션은 [`ComparisonArea1`](./comparisonarea1/) 옵션과 함께 설정할 수 없습니다. |
| [ExcludeAreas2](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludeareas2/) { get; set; } | 제외 영역을 가져오고 설정합니다. 비교 방법에서 두 번째 페이지 또는 문서에 사용됩니다. 이 옵션은 [`ExcludeTables`](./excludetables/)와 함께 설정할 수 있습니다. 이 옵션은 [`ComparisonArea2`](./comparisonarea2/) 옵션과 함께 설정할 수 없습니다. |
| [ExcludeTables](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludetables/) { get; set; } | 표가 비교에서 제외되는지를 결정하는 옵션을 가져오고 설정합니다. 이 옵션은 [`ComparisonArea1`](./comparisonarea1/) 및 [`ComparisonArea2`](./comparisonarea2/)와 함께 설정할 수 없습니다. 기본값은 `false`입니다. |

### 또 보기

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


