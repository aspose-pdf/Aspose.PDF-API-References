---
title: "Enum TextReplaceOptions.ReplaceAdjustment"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Text.TextReplaceOptionsReplaceAdjustment 열거형. 텍스트 조각을 더 짧게 교체한 후 수행될 작업을 결정합니다. None  작업 없음, 교체된 텍스트가 줄의 나머지와 겹칠 수 있음 AdjustSpaceWidth  단어 사이의 공백을 조정하여 줄 길이를 유지하려 시도합니다 WholeWordsHyphenation  단락 줄 사이에 단어를 배분하여 단락의 오른쪽 여백을 유지하려 시도합니다 ShiftRestOfLine  텍스트 길이 변경에 따라 줄의 나머지를 이동합니다. 줄 길이가 변경될 수 있습니다 기본값은 ShiftRestOfLine입니다"
type: docs
weight: 11210
url: /ko/net/aspose.pdf.text/textreplaceoptions.replaceadjustment/
---
## TextReplaceOptions.ReplaceAdjustment enumeration

텍스트 조각을 더 짧게 교체한 후 수행될 작업을 결정합니다. None - 작업 없음, 교체된 텍스트가 줄의 나머지와 겹칠 수 있음; AdjustSpaceWidth - 단어 사이의 공백을 조정하여 줄 길이를 유지하려 시도합니다; WholeWordsHyphenation - 단락 줄 사이에 단어를 배분하여 단락의 오른쪽 여백을 유지하려 시도합니다; ShiftRestOfLine - 텍스트 길이 변경에 따라 줄의 나머지를 이동합니다. 줄 길이가 변경될 수 있습니다; 기본값은 ShiftRestOfLine입니다.

```csharp
[Flags]
public enum ReplaceAdjustment
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| None | `0` | 작업 없음, 교체된 텍스트가 줄의 나머지와 겹칠 수 있음 |
| AdjustSpaceWidth | `1` | 단어 사이의 공백을 조정하여 줄 길이를 유지하려 시도합니다 |
| WholeWordsHyphenation | `2` | 단락 줄 사이에 단어를 배분하여 단락의 오른쪽 여백을 유지하려 시도합니다 |
| IsFormFillingMode | `4` | 단락 너비를 사용하여 사용 가능한 공백에 단어를 퍼뜨리려 시도합니다. 텍스트가 넘칠 경우 숨겨집니다. |
| ShiftRestOfLine | `8` | (기본값) 텍스트 길이 변경에 따라 줄의 나머지를 이동합니다. 줄 길이가 변경될 수 있습니다 |

### 또 보기

* class [TextReplaceOptions](../textreplaceoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


