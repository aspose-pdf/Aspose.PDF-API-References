---
title: "System::Net::Sockets::NetworkStream::Seek method"
linktitle: "Seek"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Sockets::NetworkStream::Seek method. Устанавливает позицию потока, представленного текущим объектом, в C++."
type: docs
weight: 2000
url: /ru/cpp/system.net.sockets/networkstream/seek/
---
## NetworkStream::Seek method


Устанавливает позицию потока, представленного текущим объектом.

```cpp
int64_t System::Net::Sockets::NetworkStream::Seek(int64_t offset, IO::SeekOrigin origin) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| смещение | int64_t | Смещение в байтах относительно позиции, указанной **origin** |
| origin | IO::SeekOrigin | Указывает позицию, от которой, и направление, в котором рассчитывается смещение |

### ReturnValue

Новая позиция потока

## См. также

* Enum [SeekOrigin](../../../system.io/seekorigin/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.PDF for C++](../../../)
