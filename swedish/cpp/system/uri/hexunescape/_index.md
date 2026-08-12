---
title: "System::Uri::HexUnescape-metod"
linktitle: "HexUnescape"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Uri::HexUnescape-metod. Konverterar den angivna hexadecimala representationen av ett tecken till ett tecken i C++."
type: docs
weight: 4000
url: /sv/cpp/system/uri/hexunescape/
---
## Uri::HexUnescape method


Konverterar den angivna hexadecimala representationen av ett tecken till ett tecken.

```cpp
static char16_t System::Uri::HexUnescape(const String &pattern, int32_t &index)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mönster | const String\& | En sträng som innehåller den hexadecimala representationen av ett tecken |
| index | int32_t\& | Positionen i **pattern** där den hexadecimala representationen av ett tecken börjar |

### ReturnValue

Tecknet som representeras av den hexadecimala kodningen på position **index**. Om tecknet på **index** inte är hexadecimalt kodat, returneras tecknet på **index**. Värdet på **index** ökas för att peka på tecknet som följer efter det returnerade.

## Se även

* Class [String](../../string/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
