---
title: OutputIntents.CopyTo
second_title: Aspose.PDF for .NET API Reference
description: Метод OutputIntents. Копирует элементы коллекции в массив, начиная с определенного arrayIndex в массиве
type: docs
weight: 70
url: /ru/net/aspose.pdf/outputintents/copyto/
---
## Метод OutputIntents.CopyTo

Копирует элементы коллекции в *array*, начиная с определенного *arrayIndex* в массиве.

```csharp
public void CopyTo(OutputIntent[] array, int arrayIndex)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | OutputIntent[] | Одномерный массив, который является местом назначения выходных намерений, скопированных из коллекции. Массив должен иметь индексацию с нуля. |
| arrayIndex | Int32 | Индекс с нуля в *array*, с которого начинается копирование. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *array* равно null. |
| ArgumentOutOfRangeException | *arrayIndex* меньше 0. |
| ArgumentException | Количество элементов в источнике [`OutputIntents`](../) больше доступного пространства от *arrayIndex* до конца целевого *array*. |

### См. также

* класс [OutputIntent](../../outputintent/)
* класс [OutputIntents](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)