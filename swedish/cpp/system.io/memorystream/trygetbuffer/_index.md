---
title: "System::IO::MemoryStream::TryGetBuffer metod"
linktitle: "TryGetBuffer"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::MemoryStream::TryGetBuffer metod. Returnerar arrayen av osignerade byte som denna ström skapades från i C++."
type: docs
weight: 1800
url: /sv/cpp/system.io/memorystream/trygetbuffer/
---
## MemoryStream::TryGetBuffer method


Returnerar arrayen av osignerade byte som denna ström skapades från.

```cpp
bool System::IO::MemoryStream::TryGetBuffer(ArraySegment<uint8_t> &buffer)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | ArraySegment\<uint8_t\>\& | bytearray - utparameter. När denna metod returnerar true, bytearraysegmentet som denna ström skapades från; när metoden returnerar false, sätts denna parameter till standardvärdet. |

### ReturnValue

Sant om konverteringen lyckades.

## Se även

* Class [ArraySegment](../../../system/arraysegment/)
* Class [MemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
