---
title: XFA.Item
second_title: Aspose.PDF for .NET API Reference
description: Свойство XFA. Получает или устанавливает значение узла данных в соответствии с путем
type: docs
weight: 50
url: /ru/net/aspose.pdf.forms/xfa/item/
---
## Индексатор XFA

Получает или устанавливает значение узла данных в соответствии с *путем*.

```csharp
public string this[string path] { get; set; }
```

| Параметр | Описание |
| --- | --- |
| path | Путь к узлу данных, например, form1[0].Subform1[0].Subform2[0].Subform3[0].TextField[0]. Обязательно указывайте индексы, даже если данные содержат только одно вхождение каждого узла, т.е. пишите node1[0].node2[0]... вместо node1.node2... |

### Возвращаемое значение

Значение узла данных.

### См. также

* класс [XFA](../)
* пространство имен [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* сборка [Aspose.PDF](../../../)