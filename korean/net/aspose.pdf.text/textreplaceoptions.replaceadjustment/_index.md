---
title: Enum TextReplaceOptions.ReplaceAdjustment
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextReplaceOptionsReplaceAdjustment 열. 더 짧은 텍스트 조각으로 교체한 후 수행할 작업을 결정합니다. None - 아무 작업도 하지 않으며, 교체된 텍스트가 나머지 줄과 겹칠 수 있습니다. AdjustSpaceWidth - 줄 길이를 유지하기 위해 단어 사이의 공백을 조정하려고 시도합니다. WholeWordsHyphenation - 단락의 올바른 필드를 유지하기 위해 단어를 단락 줄 사이에 분배하려고 시도합니다. ShiftRestOfLine - 텍스트의 길이에 따라 나머지 줄을 이동합니다. 줄의 길이는 변경될 수 있습니다. 기본값은 ShiftRestOfLine입니다.
type: docs
weight: 11020
url: /ko/net/aspose.pdf.text/textreplaceoptions.replaceadjustment/
---
## TextReplaceOptions.ReplaceAdjustment 열거형

더 짧은 텍스트 조각으로 교체한 후 수행할 작업을 결정합니다. None - 아무 작업도 하지 않으며, 교체된 텍스트가 나머지 줄과 겹칠 수 있습니다; AdjustSpaceWidth - 줄 길이를 유지하기 위해 단어 사이의 공백을 조정하려고 시도합니다; WholeWordsHyphenation - 단락의 올바른 필드를 유지하기 위해 단어를 단락 줄 사이에 분배하려고 시도합니다; ShiftRestOfLine - 텍스트의 길이에 따라 나머지 줄을 이동합니다. 줄의 길이는 변경될 수 있습니다; 기본값은 ShiftRestOfLine입니다.

```csharp
[Flags]
public enum ReplaceAdjustment
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| None | `0` | 아무 작업도 하지 않으며, 교체된 텍스트가 나머지 줄과 겹칠 수 있습니다 |
| AdjustSpaceWidth | `1` | 줄 길이를 유지하기 위해 단어 사이의 공백을 조정하려고 시도합니다 |
| WholeWordsHyphenation | `2` | 단락의 올바른 필드를 유지하기 위해 단어를 단락 줄 사이에 분배하려고 시도합니다 |
| IsFormFillingMode | `4` | 단락 너비를 사용하여 사용 가능한 공백에 단어를 퍼뜨리려고 시도합니다. 텍스트가 넘치면 숨겨집니다. |
| ShiftRestOfLine | `8` | (기본값) 텍스트의 길이에 따라 나머지 줄을 이동합니다. 줄의 길이는 변경될 수 있습니다 |

### 참조

* 클래스 [TextReplaceOptions](../textreplaceoptions/)
* 네임스페이스 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../)