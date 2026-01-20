---
title: Aspose::Pdf::Text::TextEditOptions::NoCharacterAction enum
linktitle: NoCharacterAction
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::TextEditOptions::NoCharacterAction enum. Action to perform if font does not contain required character in C++.'
type: docs
weight: 1900
url: /cpp/aspose.pdf.text/texteditoptions/nocharacteraction/
---
## NoCharacterAction enum


Action to perform if font does not contain required character.

```cpp
enum class NoCharacterAction
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| ThrowException | 0 | Throw exception. |
| UseStandardFont | 1 | Repalce font to standard font which contains required character. |
| ReplaceAnyway | 2 | Replace text anyway without font substitution. |
| ReplaceFonts | 3 | Replaces fonts as necessary to ensure all characters in the text can be displayed. The font substitution algorithm follows these steps: |
| UseCustomReplacementFont | 4 | Repalce font to defined replacement font. |

## See Also

* Class [TextEditOptions](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
