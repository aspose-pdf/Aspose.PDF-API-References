---
title: Enum ComparisonMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.ComparisonMode 열거형. 비교 모드 열거형
type: docs
weight: 3140
url: /ko/net/aspose.pdf.comparison/comparisonmode/
---
## ComparisonMode 열거형

비교 모드 열거형.

```csharp
public enum ComparisonMode
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Normal | `0` | 일반 모드. 텍스트 조각 내의 공백만 고려됩니다 (문서 생성 방식에 따라 다름). |
| IgnoreSpaces | `1` | 모든 공백이 무시됩니다. 변경 사항은 오직 단어에서만 찾습니다. |
| ParseSpaces | `2` | 이 모드는 일반 모드와 유사하지만, 거리 기반으로 텍스트 조각 간의 시각적 간격을 고려하려고 시도합니다. 조각 간의 공백 수를 인식하는 것은 문서 생성 방식에 크게 의존하기 때문에 정확하지 않을 수 있습니다. 서로 다른 생성기로 문서가 생성된 경우 텍스트 조각 간의 공백 비교에 부정확성이 있을 수 있습니다. |

### 참조

* 네임스페이스 [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* 어셈블리 [Aspose.PDF](../../)