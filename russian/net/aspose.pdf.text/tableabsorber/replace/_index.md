---
title: TableAbsorber.Replace
second_title: Aspose.PDF for .NET API Reference
description: Метод TableAbsorber. Заменяет AbsorbedTable на Table на странице
type: docs
weight: 60
url: /ru/net/aspose.pdf.text/tableabsorber/replace/
---
## Метод TableAbsorber.Replace

Заменяет [`AbsorbedTable`](../../absorbedtable/) на [`Table`](../../../aspose.pdf/table/) на странице.

```csharp
public void Replace(Page page, AbsorbedTable oldTable, Table newTable)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | Page | Объект страницы PDF документа. |
| oldTable | AbsorbedTable | [`AbsorbedTable`](../../absorbedtable/), который нужно заменить. |
| newTable | Table | [`Table`](../../../aspose.pdf/table/), который заменит старую таблицу. |

## Замечания

Пожалуйста, учтите, что это изменяет коллекцию TableList. В случае удаления/замены таблиц в цикле, пожалуйста, используйте копию коллекции TableList.

### См. также

* класс [Page](../../../aspose.pdf/page/)
* класс [AbsorbedTable](../../absorbedtable/)
* класс [Table](../../../aspose.pdf/table/)
* класс [TableAbsorber](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)