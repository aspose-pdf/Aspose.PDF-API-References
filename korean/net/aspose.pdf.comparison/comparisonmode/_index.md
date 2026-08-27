---
title: "열거형 ComparisonMode"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Comparison.ComparisonMode 열거형. 비교 모드 열거형입니다."
type: docs
weight: 3250
url: /ko/net/aspose.pdf.comparison/comparisonmode/
---
## ComparisonMode enumeration

비교 모드 열거형입니다.

```csharp
public enum ComparisonMode
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Normal | `0` | 일반 모드. 텍스트 조각 내부의 공백만 고려됩니다(문서 생성 방식에 따라 다름). |
| IgnoreSpaces | `1` | 모든 공백이 무시됩니다. 변경 사항은 단어에서만 찾습니다. |
| ParseSpaces | `2` | 이 모드는 일반과 유사하지만 거리 기반으로 텍스트 조각 사이의 시각적 간격을 고려하려고 시도합니다. 조각 사이의 공백 수를 인식하는 것이 정확하지 않을 수 있는데, 이는 문서가 생성되는 방식에 크게 좌우됩니다. 문서가 서로 다른 생성기로 만들어진 경우, 텍스트 조각 사이의 공백을 비교할 때 부정확할 수 있습니다. |

### 또 보기

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


