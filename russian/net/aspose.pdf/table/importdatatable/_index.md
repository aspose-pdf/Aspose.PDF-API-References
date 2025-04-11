---
title: Table.ImportDataTable
second_title: Aspose.PDF for .NET API Reference
description: Метод таблицы. Импортирует данные из System.Data.DataTable в Aspose.Pdf.Table
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
| firstFilledRow | Int32 | указывает номер первой строки в целевой таблице с нулевым индексом, с которой начнется импорт; если строка с таким номером (и некоторые предыдущие строки) отсутствуют в целевой таблице, они будут созданы первыми |
| firstFilledColumn | Int32 | указывает номер первого целевого столбца в целевой таблице, столбец должен присутствовать в целевой таблице до начала импорта |

### См. также

* класс [Table](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

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
| importedDataTable | DataTable | Объект DataTable, который необходимо импортировать. |
| isColumnNamesShown | Boolean | Указывает, будут ли имена столбцов исходной таблицы импортированы как первая строка. |
| firstFilledRow | Int32 | указывает номер первой строки в целевой таблице с нулевым индексом, с которой начнется импорт; если строка с таким номером (и некоторые предыдущие строки) отсутствуют в целевой таблице, они будут созданы первыми |
| firstFilledColumn | Byte | указывает номер первого целевого столбца в целевой таблице, столбец должен присутствовать в целевой таблице до начала импорта |
| maxRows | Int32 | Максимальное количество строк, которые будут импортированы из исходной таблицы. |
| maxColumns | Int32 | Максимальное количество столбцов, которые будут импортированы из исходной таблицы. |
| isHtmlSupported | Boolean | Указывает, является ли текст строкой HTML. |

### См. также

* класс [Table](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)

---

## ImportDataTable(DataTable, int[], int[], int, int, bool, bool) {#importdatatable_2}

Импортирует объект DataTable, но не как целостную сущность. Импортируются только указанные строки и столбцы.

```csharp
public void ImportDataTable(DataTable importedDataTable, int[] sourceRowList, 
    int[] sourceColumnList, int firstFilledRow, int firstFilledColumn, 
    bool showColumnNamesAsFirstRow, bool isHtmlSupported = false)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| importedDataTable | DataTable | Объект DataTable, который необходимо импортировать. |
| sourceRowList | Int32[] | Массив номеров строк в исходном объекте DataTable, которые должны быть импортированы. Список не должен быть нулевым и должен содержать только номера существующих строк, в противном случае будет выброшено исключение. |
| sourceColumnList | Int32[] | Массив номеров столбцов в исходном объекте DataTable, которые должны быть импортированы. Список не должен быть нулевым и должен содержать только номера существующих столбцов, в противном случае будет выброшено исключение. |
| firstFilledRow | Int32 | Номер строки с нулевым индексом первой ячейки в целевой таблице, с которой начнется импорт. Если целевая таблица не содержит этой строки, она (и все предыдущие, если необходимо) будет создана |
| firstFilledColumn | Int32 | Номер столбца с нулевым индексом первой ячейки в целевой таблице, с которой начнется импорт. Целевая таблица должна содержать этот столбец до начала импорта, в противном случае будет выброшено исключение. |
| showColumnNamesAsFirstRow | Boolean | Указывает, будут ли имена столбцов исходной таблицы импортированы как первая строка. |
| isHtmlSupported | Boolean | Указывает, является ли текст строкой HTML. |

### См. также

* класс [Table](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)