---
title: OptimizedMemoryStream.Write
second_title: Aspose.PDF for .NET API Reference
description: Метод OptimizedMemoryStream. При переопределении в производном классе записывает последовательность байтов в текущий поток и перемещает текущую позицию в этом потоке на количество записанных байтов
type: docs
weight: 150
url: /ru/net/aspose.pdf/optimizedmemorystream/write/
---
## Метод OptimizedMemoryStream.Write

При переопределении в производном классе записывает последовательность байтов в текущий поток и перемещает текущую позицию в этом потоке на количество записанных байтов.

```csharp
public override void Write(byte[] buffer, int offset, int count)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | Byte[] | Массив байтов. Этот метод копирует *count* байтов из *buffer* в текущий поток. |
| offset | Int32 | Смещение в байтах с нулевой базой в *buffer*, с которого начинается копирование байтов в текущий поток. |
| count | Int32 | Количество байтов, которые должны быть записаны в текущий поток. |

### См. также

* класс [OptimizedMemoryStream](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)