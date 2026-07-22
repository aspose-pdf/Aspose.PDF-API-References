---
title: "System::IO::TextReader::ReadBlock method"
linktitle: "ReadBlock"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::TextReader::ReadBlock method. Läser det angivna maximala antalet tecken från den aktuella textläsaren och skriver data till en buffert, med start vid det angivna indexet i C++."
type: docs
weight: 500
url: /sv/cpp/system.io/textreader/readblock/
---
## TextReader::ReadBlock method


Läser det angivna maximala antalet tecken från den aktuella textläsaren och skriver data till en buffert, med start vid det angivna indexet.

```cpp
virtual int System::IO::TextReader::ReadBlock(ArrayPtr<char_t> buffer, int index, int count)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | ArrayPtr\<char_t\> | En teckenbuffert att skriva de lästa data till |
| index | int | Ett 0-baserat index i **buffer** att börja skriva vid |
| count | int | Det maximala antalet tecken att läsa |

### ReturnValue

Det faktiska antalet tecken som lästes

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [TextReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
