---
title: System::Uri::HexUnescape method
linktitle: HexUnescape
second_title: Aspose.PDF for C++ API Reference
description: 'System::Uri::HexUnescape method. Converts the specified hexadecimal representation of a character to a character in C++.'
type: docs
weight: 4000
url: /cpp/system/uri/hexunescape/
---
## Uri::HexUnescape method


Converts the specified hexadecimal representation of a character to a character.

```cpp
static char16_t System::Uri::HexUnescape(const String &pattern, int32_t &index)
```


| Parameter | Type | Description |
| --- | --- | --- |
| pattern | const String\& | A string containing the hexadecimal representation of a character |
| index | int32_t\& | The position in **pattern** where the hexadecimal representation of a character begins |

### ReturnValue

The character represented by the hexadecimal encoding at position **index**. If the character at **index** is not hexadecimal encoded, the character at **index** is returned. The value of **index** is incremented to point to the character following the one returned.

## See Also

* Class [String](../../string/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
