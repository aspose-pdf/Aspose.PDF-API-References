---
title: OperatorCollection.Item
second_title: Aspose.PDF for .NET API Reference
description: Свойство OperatorCollection. Получает оператор по его индексу
type: docs
weight: 40
url: /ru/net/aspose.pdf/operatorcollection/item/
---
## Индексатор OperatorCollection

Получает оператор по его индексу.

```csharp
public override Operator this[int index] { get; set; }
```

| Параметр | Описание |
| --- | --- |
| index | Индекс оператора. Нумерация начинается с 1. |

### Возвращаемое значение

Оператор с запрашиваемого индекса

## Примеры

Пример демонстрирует, как получить оператор содержимого страницы по индексу.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
Operator first = oc[1];
```

### См. также

* класс [Operator](../../operator/)
* класс [OperatorCollection](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)