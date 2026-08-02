---
title: "OutputIntents.Item"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство OutputIntents. Возвращает выходное намерение по указанному индексу."
type: docs
weight: 30
url: /ru/net/aspose.pdf/outputintents/item/
---
## OutputIntents indexer

Получает output intent по указанному *index*.

```csharp
public OutputIntent this[int index] { get; }
```

| Параметр | Описание |
| --- | --- |
| index | Нулевой индекс выходного намерения, которое нужно получить. |

### Возвращаемое значение

Выходное намерение по указанному *index*.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | *index* меньше 0 или *index* равен или больше, чем [`Count`](../count/). |
| InvalidOperationException | Документ, содержащий коллекцию, не имеет каталога для доступа к OutputIntents. |

### См. также

* class [OutputIntent](../../outputintent/)
* class [OutputIntents](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


