---
title: "OutputIntents.CopyTo"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод OutputIntents. Копирует элементы коллекции в массив, начиная с указанного arrayIndex, в массив"
type: docs
weight: 70
url: /ru/net/aspose.pdf/outputintents/copyto/
---
## OutputIntents.CopyTo method

Копирует элементы коллекции в *array*, начиная с определённого *arrayIndex* в массив.

```csharp
public void CopyTo(OutputIntent[] array, int arrayIndex)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| массив | OutputIntent[] | Одномерный массив, который является получателем выходных намерений, скопированных из коллекции. Массив должен иметь нулевую индексацию. |
| arrayIndex | Int32 | Нулевой индекс в *array*, с которого начинается копирование. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *array* равно null. |
| ArgumentOutOfRangeException | *arrayIndex* меньше 0. |
| ArgumentException | Количество элементов в источнике [`OutputIntents`](../) больше доступного пространства от *arrayIndex* до конца целевого *array*. |

### См. также

* class [OutputIntent](../../outputintent/)
* class [OutputIntents](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


