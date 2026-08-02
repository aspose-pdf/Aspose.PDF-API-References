---
title: "Table.ImportDataView"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Table. Импортирует данные объекта DataView в таблицу"
type: docs
weight: 270
url: /ru/net/aspose.pdf/table/importdataview/
---
## Table.ImportDataView method

Импортирует данные объекта DataView в таблицу.

```csharp
public void ImportDataView(DataView sourceDataView, bool isColumnNamesImported, int firstFilledRow, 
    int firstFilledColumn, int maxRows, int maxColumns)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceDataView | DataView | Объект DataView для импорта. |
| isColumnNamesImported | Boolean | Указывает, будут ли имена колонок импортированы как первая строка. |
| firstFilledRow | Int32 | Номер строки первой ячейки в целевой таблице, с которой начнётся импорт, нумерация с нуля. Если целевая таблица не содержит эту строку, она (и все предыдущие при необходимости) будет создана |
| firstFilledColumn | Int32 | Нулевой индекс колонки первой ячейки в целевой таблице, с которой начнётся импорт. Целевая таблица должна содержать эту колонку до начала импорта, иначе будет выброшено исключение. |
| maxRows | Int32 | Максимальное количество строк для импорта из исходного DataView. |
| maxColumns | Int32 | Максимальное количество колонок для импорта из исходного DataView. |

### См. также

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


