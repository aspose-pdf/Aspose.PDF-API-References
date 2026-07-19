---
title: "System::Net::Security::SslStream::Seek метод"
linktitle: "Seek"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::Security::SslStream::Seek метод. Устанавливает позицию потока, представленного текущим объектом, в C++."
type: docs
weight: 3300
url: /ru/cpp/system.net.security/sslstream/seek/
---
## SslStream::Seek method


Устанавливает позицию потока, представленного текущим объектом.

```cpp
int64_t System::Net::Security::SslStream::Seek(int64_t offset, IO::SeekOrigin origin) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| смещение | int64_t | Смещение в байтах относительно позиции, указанной **origin** |
| origin | IO::SeekOrigin | Указывает позицию, от которой, и направление, в котором рассчитывается смещение |

### ReturnValue

Новая позиция потока

## См. также

* Enum [SeekOrigin](../../../system.io/seekorigin/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.PDF for C++](../../../)
