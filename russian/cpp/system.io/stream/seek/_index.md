---
title: "System::IO::Stream::Seek метод"
linktitle: "Seek"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::Stream::Seek метод. Устанавливает позицию потока, представленного текущим объектом, в C++."
type: docs
weight: 2100
url: /ru/cpp/system.io/stream/seek/
---
## Stream::Seek method


Устанавливает позицию потока, представленного текущим объектом.

```cpp
virtual int64_t System::IO::Stream::Seek(int64_t offset, SeekOrigin origin)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| смещение | int64_t | Смещение в байтах относительно позиции, указанной **origin** |
| origin | SeekOrigin | Указывает позицию, от которой, и направление, в котором рассчитывается смещение |

### ReturnValue

Новая позиция потока

## См. также

* Enum [SeekOrigin](../../seekorigin/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
