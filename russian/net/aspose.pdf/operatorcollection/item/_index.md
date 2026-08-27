---
title: "OperatorCollection.Item"
second_title: "Справочник API Aspose.PDF для .NET"
description: "OperatorCollection property. Получает оператор по его индексу."
type: docs
weight: 40
url: /ru/net/aspose.pdf/operatorcollection/item/
---
## OperatorCollection indexer

Возвращает оператор по его индексу.

```csharp
public override Operator this[int index] { get; set; }
```

| Параметр | Описание |
| --- | --- |
| index | Индекс оператора. Нумерация начинается с 1. |

### Возвращаемое значение

Оператор по запрошенному индексу

## Примеры

Пример демонстрирует, как получить оператор содержимого страницы по индексу.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
Operator first = oc[1];
```

### См. также

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


