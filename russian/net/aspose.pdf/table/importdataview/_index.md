---
title: Table.ImportDataView
second_title: Aspose.PDF for .NET API Reference
description: Метод таблицы. Импортирует данные объекта DataView в таблицу
type: docs
weight: 270
url: /ru/net/aspose.pdf/table/importdataview/
---
## Метод Table.ImportDataView

Импортирует данные объекта DataView в таблицу.

```csharp
public void ImportDataView(DataView sourceDataView, bool isColumnNamesImported, int firstFilledRow, 
    int firstFilledColumn, int maxRows, int maxColumns)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceDataView | DataView | Объект DataView, который будет импортирован. |
| isColumnNamesImported | Boolean | Указывает, будут ли имена столбцов импортированы как первая строка. |
| firstFilledRow | Int32 | Номер строки с нулевым индексом первой ячейки в целевой таблице, с которой начнется импорт. Если целевая таблица не содержит эту строку, она (и все предыдущие, если необходимо) будет создана. |
| firstFilledColumn | Int32 | Номер столбца с нулевым индексом первой ячейки в целевой таблице, с которой начнется импорт. Целевая таблица должна содержать этот столбец до начала импорта, в противном случае будет выброшено исключение. |
| maxRows | Int32 | Максимальное количество строк, которые будут импортированы из исходного DataView. |
| maxColumns | Int32 | Максимальное количество столбцов, которые будут импортированы из исходного DataView. |

### См. также

* класс [Table](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)