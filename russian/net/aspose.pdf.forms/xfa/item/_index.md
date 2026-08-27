---
title: "XFA.Item"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство XFA. Получает или задает значение узла данных по пути."
type: docs
weight: 50
url: /ru/net/aspose.pdf.forms/xfa/item/
---
## XFA indexer

Получает или задает значение узла данных согласно *path*.

```csharp
public string this[string path] { get; set; }
```

| Параметр | Описание |
| --- | --- |
| путь | Путь к узлу данных, например form1[0].Subform1[0].Subform2[0].Subform3[0].TextField[0]. Обязательно включайте индексы, даже если данные содержат только одно вхождение каждого узла, т. е. пишите node1[0].node2[0]... вместо node1.node2... |

### Возвращаемое значение

Значение узла данных.

### См. также

* class [XFA](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


