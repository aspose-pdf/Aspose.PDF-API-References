---
title: "Aspose::Pdf::OptimizedMemoryStream::Read метод"
linktitle: "Read"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::OptimizedMemoryStream::Read метод. При переопределении в производном классе читает последовательность байтов из текущего потока и перемещает позицию в потоке на количество прочитанных байтов в C++."
type: docs
weight: 1000
url: /ru/cpp/aspose.pdf/optimizedmemorystream/read/
---
## OptimizedMemoryStream::Read method


При переопределении в производном классе читает последовательность байтов из текущего потока и перемещает позицию в потоке на количество прочитанных байтов.

```cpp
int32_t Aspose::Pdf::OptimizedMemoryStream::Read(const System::ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const System::ArrayPtr\<uint8_t\>\& | Массив байтов. Когда этот метод возвращает, буфер содержит указанный массив байтов со значениями |
| смещение | int32_t | Нулевое байтовое смещение, с которого начинать сохранять данные, прочитанные из текущего потока. |
| count | int32_t | Максимальное количество байтов, которое будет прочитано из текущего потока. |

### ReturnValue

Общее количество байтов, прочитанных в буфер. Оно может быть меньше запрошенного количества байтов, если столько байтов в данный момент недоступно, или равно нулю (0), если достигнут конец потока.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [OptimizedMemoryStream](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
