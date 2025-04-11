---
title: OutputIntents.Item
second_title: Aspose.PDF for .NET API Reference
description: Свойство OutputIntents. Получает выходной намерение по указанному индексу
type: docs
weight: 30
url: /ru/net/aspose.pdf/outputintents/item/
---
## Индексатор OutputIntents

Получает выходной намерение по указанному *индексу*.

```csharp
public OutputIntent this[int index] { get; }
```

| Параметр | Описание |
| --- | --- |
| index | Индекс выходного намерения, который нужно получить, с нулевой базой. |

### Возвращаемое значение

Выходное намерение по указанному *индексу*.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | *индекс* меньше 0 или *индекс* равен или больше чем [`Count`](../count/). |
| InvalidOperationException | Документ, содержащий коллекцию, не имеет каталога для доступа к OutputIntents. |

### См. также

* класс [OutputIntent](../../outputintent/)
* класс [OutputIntents](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)