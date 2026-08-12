---
title: "System::IO::BufferedStream::Seek метод"
linktitle: "Seek"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::BufferedStream::Seek method. Устанавливает позицию потока, представленного текущим объектом, в C++."
type: docs
weight: 1100
url: /ru/cpp/system.io/bufferedstream/seek/
---
## BufferedStream::Seek method


Устанавливает позицию потока, представленного текущим объектом.

```cpp
virtual int64_t System::IO::BufferedStream::Seek(int64_t offset, SeekOrigin origin) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| смещение | int64_t | Смещение в байтах относительно позиции, указанной **origin** |
| origin | SeekOrigin | Указывает позицию, от которой, и направление, в котором рассчитывается смещение |

### ReturnValue

Новая позиция потока

## См. также

* Enum [SeekOrigin](../../seekorigin/)
* Class [BufferedStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
