---
title: "метод Aspose::Pdf::OptimizedMemoryStream::Write"
linktitle: "Write"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::OptimizedMemoryStream::Write метод. При переопределении в производном классе записывает последовательность байтов в текущий поток и перемещает текущую позицию в этом потоке на количество записанных байтов в C++."
type: docs
weight: 1800
url: /ru/cpp/aspose.pdf/optimizedmemorystream/write/
---
## OptimizedMemoryStream::Write method


При переопределении в производном классе записывает последовательность байтов в текущий поток и перемещает текущую позицию в этом потоке на количество записанных байтов.

```cpp
void Aspose::Pdf::OptimizedMemoryStream::Write(const System::ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const System::ArrayPtr\<uint8_t\>\& | Массив байтов. Этот метод копирует *count* байт из *buffer* в текущий поток. |
| смещение | int32_t | Нулевой смещение в байтах в *buffer*, с которого начинается копирование байтов в текущий поток. |
| count | int32_t | Количество байтов, которое будет записано в текущий поток. |
## Примечания



Сумма *offset* и *count* больше длины буфера.
## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [OptimizedMemoryStream](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
