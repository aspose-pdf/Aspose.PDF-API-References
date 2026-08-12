---
title: "Metoden System::String::CopyTo"
linktitle: "CopyTo"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::String::CopyTo method. Kopierar tecken i strängen till befintliga arrayelement. Ingen storleksändring görs i C++."
type: docs
weight: 700
url: /sv/cpp/system/string/copyto/
---
## String::CopyTo method


Kopierar tecken från strängen till befintliga array‑element. Ingen storleksändring sker.

```cpp
void System::String::CopyTo(int sourceIndex, const ArrayPtr<char_t> &destination, int destinationIndex, int count) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceIndex | int | Index i strängen att börja läsa från. |
| destination | const ArrayPtr\<char_t\>\& | Målararray. |
| destinationIndex | int | Index i arrayen att börja skriva från. |
| count | int | Antal tecken att kopiera. |

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
