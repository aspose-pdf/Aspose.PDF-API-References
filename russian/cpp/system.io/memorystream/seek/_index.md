---
title: "System::IO::MemoryStream::Seek метод"
linktitle: "Seek"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::MemoryStream::Seek метод. Устанавливает позицию потока, представленного текущим объектом, в C++."
type: docs
weight: 1300
url: /ru/cpp/system.io/memorystream/seek/
---
## MemoryStream::Seek method


Устанавливает позицию потока, представленного текущим объектом.

```cpp
int64_t System::IO::MemoryStream::Seek(int64_t offset, SeekOrigin origin) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| смещение | int64_t | Смещение в байтах относительно позиции, указанной **origin** |
| origin | SeekOrigin | Указывает позицию, от которой, и направление, в котором рассчитывается смещение |

### ReturnValue

Новая позиция потока

## См. также

* Enum [SeekOrigin](../../seekorigin/)
* Class [MemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
