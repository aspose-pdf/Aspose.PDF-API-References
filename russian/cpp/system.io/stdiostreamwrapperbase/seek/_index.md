---
title: "Метод System::IO::STDIOStreamWrapperBase::Seek"
linktitle: "Seek"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::IO::STDIOStreamWrapperBase::Seek. Устанавливает позицию потока, представленного текущим объектом, в C++."
type: docs
weight: 800
url: /ru/cpp/system.io/stdiostreamwrapperbase/seek/
---
## STDIOStreamWrapperBase::Seek method


Устанавливает позицию потока, представленного текущим объектом.

```cpp
virtual int64_t System::IO::STDIOStreamWrapperBase<T, typename>::Seek(int64_t offset, SeekOrigin origin) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| смещение | int64_t | Смещение в байтах относительно позиции, указанной **origin** |
| origin | SeekOrigin | Указывает позицию, от которой, и направление, в котором рассчитывается смещение |

### ReturnValue

Новая позиция потока

## См. также

* Enum [SeekOrigin](../../seekorigin/)
* Class [STDIOStreamWrapperBase](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
