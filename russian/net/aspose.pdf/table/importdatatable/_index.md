---
title: "Table.ImportDataTable"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод Table. Импортирует данные из System.Data.DataTable в Aspose.Pdf.Table"
type: docs
weight: 260
url: /ru/net/aspose.pdf/table/importdatatable/
---
## ImportDataTable(DataTable, bool, int, int) {#importdatatable_1}

Импортирует данные из System.Data.DataTable в Aspose.Pdf.Table

```csharp
public void ImportDataTable(DataTable importedDataTable, bool isColumnNamesImported, 
    int firstFilledRow, int firstFilledColumn)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| importedDataTable | DataTable | исходный экземпляр System.Data.DataTable |
| isColumnNamesImported | Boolean | указывает, будут ли имена столбцов импортированы как первая строка |
| firstFilledRow | Int32 | указывает нулевой индекс первой строки в целевой таблице, с которой начнётся импорт; если строка с таким номером (и некоторые предыдущие строки) отсутствуют в целевой таблице, они будут созданы сначала |
| firstFilledColumn | Int32 | указывает номер первого целевого столбца в целевой таблице, столбец должен присутствовать в целевой таблице до начала импорта |

### См. также

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## ImportDataTable(DataTable, bool, int, byte, int, int, bool) {#importdatatable}

Импортирует объект DataTable в таблицу.

```csharp
public void ImportDataTable(DataTable importedDataTable, bool isColumnNamesShown, 
    int firstFilledRow, byte firstFilledColumn, int maxRows, int maxColumns, 
    bool isHtmlSupported = false)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| importedDataTable | DataTable | Объект DataTable для импорта. |
| isColumnNamesShown | Boolean | Указывает, будут ли имена столбцов исходной таблицы данных импортированы как первая строка. |
| firstFilledRow | Int32 | указывает нулевой индекс первой строки в целевой таблице, с которой начнётся импорт; если строка с таким номером (и некоторые предыдущие строки) отсутствуют в целевой таблице, они будут созданы сначала |
| firstFilledColumn | Byte | указывает номер первого целевого столбца в целевой таблице, столбец должен присутствовать в целевой таблице до начала импорта |
| maxRows | Int32 | Максимальное количество строк, импортируемых из исходной таблицы. |
| maxColumns | Int32 | Максимальное количество столбцов, импортируемых из исходной таблицы. |
| isHtmlSupported | Boolean | Указывает, является ли текст строкой HTML. |

### См. также

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## ImportDataTable(DataTable, int[], int[], int, int, bool, bool) {#importdatatable_2}

Импортирует объект DataTable, но не как целую сущность. Импортируются только указанные строки и столбцы.

```csharp
public void ImportDataTable(DataTable importedDataTable, int[] sourceRowList, 
    int[] sourceColumnList, int firstFilledRow, int firstFilledColumn, 
    bool showColumnNamesAsFirstRow, bool isHtmlSupported = false)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| importedDataTable | DataTable | Объект DataTable для импорта. |
| sourceRowList | Int32[] | Массив номеров строк в исходном объекте DataTable, которые должны быть импортированы. Список не должен быть null и должен содержать только номера существующих строк, иначе будет выброшено исключение. |
| sourceColumnList | Int32[] | Массив номеров столбцов в исходном объекте DataTable, которые должны быть импортированы. Список не должен быть null и должен содержать только номера существующих столбцов, иначе будет выброшено исключение. |
| firstFilledRow | Int32 | Номер строки первой ячейки в целевой таблице, с которой начнётся импорт, нумерация с нуля. Если целевая таблица не содержит эту строку, она (и все предыдущие при необходимости) будет создана |
| firstFilledColumn | Int32 | Номер столбца первой ячейки в целевой таблице, с которой начнётся импорт, нумерация с нуля. Целевая таблица должна содержать этот столбец до начала импорта, иначе будет выброшено исключение. |
| showColumnNamesAsFirstRow | Boolean | Указывает, будут ли имена столбцов исходной таблицы данных импортированы как первая строка. |
| isHtmlSupported | Boolean | Указывает, является ли текст строкой HTML. |

### См. также

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


