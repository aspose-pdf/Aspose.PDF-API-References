---
title: "Aspose::Pdf::OptimizedMemoryStream::Seek метод"
linktitle: "Seek"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::OptimizedMemoryStream::Seek метод. При переопределении в производном классе задает позицию в текущем потоке в C++."
type: docs
weight: 1200
url: /ru/cpp/aspose.pdf/optimizedmemorystream/seek/
---
## OptimizedMemoryStream::Seek method


При переопределении в производном классе устанавливает позицию в текущем потоке.

```cpp
int64_t Aspose::Pdf::OptimizedMemoryStream::Seek(int64_t offset, System::IO::SeekOrigin origin) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| смещение | int64_t | Смещение в байтах относительно параметра *origin*. |
| origin | System::IO::SeekOrigin | Значение типа [T:System::IO::SeekOrigin](../), указывающее точку отсчёта, используемую для получения новой позиции. |

### ReturnValue

Новая позиция в текущем потоке.

## См. также

* Enum [SeekOrigin](../../../system.io/seekorigin/)
* Class [OptimizedMemoryStream](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
