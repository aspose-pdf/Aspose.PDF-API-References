---
title: Enum TextEditOptions.NoCharacterAction
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextEditOptionsNoCharacterAction 열거형. 글꼴에 필요한 문자가 포함되어 있지 않을 때 수행할 작업
type: docs
weight: 10860
url: /ko/net/aspose.pdf.text/texteditoptions.nocharacteraction/
---
## TextEditOptions.NoCharacterAction 열거형

글꼴에 필요한 문자가 포함되어 있지 않을 때 수행할 작업

```csharp
public enum NoCharacterAction
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| ThrowException | `0` | 예외 발생 |
| UseStandardFont | `1` | 필요한 문자가 포함된 표준 글꼴로 글꼴 교체 |
| ReplaceAnyway | `2` | 글꼴 대체 없이 무조건 텍스트 교체 |
| ReplaceFonts | `3` | 텍스트의 모든 문자가 표시될 수 있도록 필요한 경우 글꼴을 교체합니다. 글꼴 대체 알고리즘은 다음 단계를 따릅니다: 1. 사용자가 Font 속성을 명시적으로 설정한 경우, 지정된 글꼴이 원하는 문자를 표시할 수 있는지 확인합니다. 2. 사용자 정의 글꼴이 설정되지 않은 경우, [`Sources`](../fontrepository/sources/)를 통해 추가된 글꼴을 검색합니다. 3. 텍스트를 분석하여 해당 알파벳 또는 스크립트를 식별하고 이에 따라 글꼴 이름을 제안합니다. 시스템에서 이러한 글꼴을 찾고 사용하려고 시도합니다. 4. 대체로, 필요한 문자를 표시할 수 있는 글꼴을 시스템에서 검색합니다. |
| UseCustomReplacementFont | `4` | 정의된 대체 글꼴로 글꼴 교체 |

### 참조

* 클래스 [TextEditOptions](../texteditoptions/)
* 네임스페이스 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../)