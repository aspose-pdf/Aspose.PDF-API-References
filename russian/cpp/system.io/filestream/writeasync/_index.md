---
title: "System::IO::FileStream::WriteAsync метод"
linktitle: "WriteAsync"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::FileStream::WriteAsync метод. Асинхронно записывает последовательность байтов в текущий поток, перемещает текущую позицию в этом потоке на количество записанных байтов и отслеживает запросы отмены в C++."
type: docs
weight: 2000
url: /ru/cpp/system.io/filestream/writeasync/
---
## FileStream::WriteAsync method


Асинхронно записывает последовательность байтов в текущий поток, перемещает текущую позицию в этом потоке на количество записанных байтов и отслеживает запросы на отмену.

```cpp
TaskPtr System::IO::FileStream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const ArrayPtr\<uint8_t\>\& | Массив, содержащий байты для записи. |
| смещение | int32_t | 0‑базовый индекс элемента в **buffer**, с которого начинается поддиапазон для записи. |
| count | int32_t | Количество элементов в поддиапазоне для записи. |
| cancellationToken | const Threading::CancellationToken\& | Токен для отслеживания запросов на отмену. |

### ReturnValue

Задача, представляющая асинхронную операцию записи.

## См. также

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
