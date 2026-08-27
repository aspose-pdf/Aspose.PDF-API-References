---
title: "열거형 TextEditOptions.NoCharacterAction"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Text.TextEditOptionsNoCharacterAction 열거형. 글꼴에 필요한 문자가 포함되지 않은 경우 수행할 작업"
type: docs
weight: 11040
url: /ko/net/aspose.pdf.text/texteditoptions.nocharacteraction/
---
## TextEditOptions.NoCharacterAction enumeration

글꼴에 필요한 문자가 없을 때 수행할 작업

```csharp
public enum NoCharacterAction
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| ThrowException | `0` | 예외를 발생시킵니다 |
| UseStandardFont | `1` | 필요한 문자를 포함하는 표준 글꼴로 교체합니다 |
| ReplaceAnyway | `2` | 글꼴 교체 없이 텍스트를 그대로 교체합니다 |
| ReplaceFonts | `3` | 텍스트의 모든 문자를 표시할 수 있도록 필요에 따라 글꼴을 교체합니다. 글꼴 대체 알고리즘은 다음 단계에 따라 진행됩니다: 1. 사용자가 Font 속성을 명시적으로 설정한 경우, 지정된 글꼴이 원하는 문자를 표시할 수 있는지 확인합니다. 2. 사용자 정의 글꼴이 설정되지 않은 경우, [`Sources`](../fontrepository/sources/)를 통해 추가된 글꼴을 검색합니다. 3. 텍스트를 분석하여 알파벳 또는 스크립트를 식별하고 그에 맞는 글꼴 이름을 제안합니다. 시스템에서 해당 글꼴을 찾고 사용을 시도합니다. 4. 대체 옵션으로, 시스템에서 필요한 문자를 표시할 수 있는 모든 글꼴을 검색합니다. |
| UseCustomReplacementFont | `4` | 정의된 대체 글꼴로 교체합니다 |

### 또 보기

* class [TextEditOptions](../texteditoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


