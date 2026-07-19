---
title: "System::IO::BinaryWriter::Seek метод"
linktitle: "Seek"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::BinaryWriter::Seek метод. Устанавливает позицию потока, представленного текущим объектом, в C++."
type: docs
weight: 700
url: /ru/cpp/system.io/binarywriter/seek/
---
## BinaryWriter::Seek method


Устанавливает позицию потока, представленного текущим объектом.

```cpp
int64_t System::IO::BinaryWriter::Seek(int offset, System::IO::SeekOrigin origin=System::IO::SeekOrigin::Begin)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| смещение | int | Смещение в байтах относительно позиции, указанной **origin** |
| origin | System::IO::SeekOrigin | Указывает позицию, от которой, и направление, в котором рассчитывается смещение |

### ReturnValue

Новая позиция потока

## См. также

* Enum [SeekOrigin](../../seekorigin/)
* Class [BinaryWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
