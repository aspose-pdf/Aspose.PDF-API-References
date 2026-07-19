---
title: "System::IO::MemoryStream::TryGetBuffer метод"
linktitle: "TryGetBuffer"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::MemoryStream::TryGetBuffer метод. Возвращает массив беззнаковых байтов, из которого был создан этот поток, в C++."
type: docs
weight: 1800
url: /ru/cpp/system.io/memorystream/trygetbuffer/
---
## MemoryStream::TryGetBuffer method


Возвращает массив беззнаковых байтов, из которого был создан этот поток.

```cpp
bool System::IO::MemoryStream::TryGetBuffer(ArraySegment<uint8_t> &buffer)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | ArraySegment\<uint8_t\>\& | byte array - out параметр. Когда этот метод возвращает true, возвращается сегмент массива байтов, из которого был создан поток; когда метод возвращает false, этот параметр устанавливается в значение по умолчанию. |

### ReturnValue

True, если преобразование удалось.

## См. также

* Class [ArraySegment](../../../system/arraysegment/)
* Class [MemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
