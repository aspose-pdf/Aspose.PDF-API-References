---
title: Aspose::Pdf::TextStamp::NoCharacterAction enum
linktitle: NoCharacterAction
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::TextStamp::NoCharacterAction enum. Action to perform if font does not contain required character in C++.'
type: docs
weight: 3500
url: /cpp/aspose.pdf/textstamp/nocharacteraction/
---
## NoCharacterAction enum


Action to perform if font does not contain required character.

```cpp
enum class NoCharacterAction
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| ThrowException | 0 | If the font does not contain all the characters of the string, an exception is thrown. |
| UseStandardFont | 1 | Repalce font to standard font which contains required character. |
| ReplaceAnyway | 2 | Replace text anyway without font substitution. |
| UseCustomReplacementFont | 3 | Repalce font to defined replacement font. |

## See Also

* Class [TextStamp](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
