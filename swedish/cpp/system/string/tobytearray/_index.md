---
title: "System::String::ToByteArray metod"
linktitle: "ToByteArray"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::String::ToByteArray metod. Konverterar sträng eller delsträng till en bytearray i C++."
type: docs
weight: 4700
url: /sv/cpp/system/string/tobytearray/
---
## String::ToByteArray method


Konverterar sträng eller delsträng till en bytearray.

```cpp
ArrayPtr<uint8_t> System::String::ToByteArray(int32_t startIndex=0, int32_t length=INT32_MAX, bool LE=true) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startIndex | int32_t | Startindex för delsträng. |
| längd | int32_t | Längd för delsträng. |
| LE | bool | Om true, koda tecken med little-endian; annars, använd big-endian. |

### ReturnValue

[Array](../../array/) containing bytes representing characters of the string.

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
