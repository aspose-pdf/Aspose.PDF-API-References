---
title: Table
second_title: Aspose.PDF для справочника API .NET
description: Представляет таблицу которую можно добавить на страницу.
type: docs
weight: 6500
url: /ru/net/aspose.pdf/table/
---
## Table class

Представляет таблицу, которую можно добавить на страницу.

```csharp
public sealed class Table : BaseParagraph
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Table](table)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Alignment](../../aspose.pdf/table/alignment) { get; set; } | Получает или задает выравнивание таблицы. |
| [BackgroundColor](../../aspose.pdf/table/backgroundcolor) { get; set; } | Получает или задает цвет фона таблицы |
| [Border](../../aspose.pdf/table/border) { get; set; } | Получает или устанавливает границу. |
| [BreakText](../../aspose.pdf/table/breaktext) { get; set; } | Получает или задает текст разрыва для table |
| [Broken](../../aspose.pdf/table/broken) { get; set; } | Получает или задает неверную вертикаль таблицы; |
| [ColumnAdjustment](../../aspose.pdf/table/columnadjustment) { get; set; } | Получает или задает настройку столбца таблицы. |
| [ColumnWidths](../../aspose.pdf/table/columnwidths) { get; set; } | Получает ширину столбцов таблицы. |
| [CornerStyle](../../aspose.pdf/table/cornerstyle) { get; set; } | Получает или задает стили углов границы |
| [DefaultCellBorder](../../aspose.pdf/table/defaultcellborder) { get; set; } | Получает границу ячейки по умолчанию; |
| [DefaultCellPadding](../../aspose.pdf/table/defaultcellpadding) { get; set; } | Получает или задает заполнение ячейки по умолчанию. |
| [DefaultCellTextState](../../aspose.pdf/table/defaultcelltextstate) { get; set; } | Получает или задает состояние текста ячейки по умолчанию. |
| [DefaultColumnWidth](../../aspose.pdf/table/defaultcolumnwidth) { get; set; } | Получает границу ячейки по умолчанию; |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment) { get; set; } | Получает или задает горизонтальное выравнивание абзаца |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Получает или устанавливает гиперссылку на фрагмент (для генератора pdf). |
| [IsBordersIncluded](../../aspose.pdf/table/isbordersincluded) { get; set; } | Получает или устанавливает границу, включенную в ширину столбца. |
| [IsBroken](../../aspose.pdf/table/isbroken) { get; set; } | Получает или задает, что таблица повреждена - будет усечена для следующей страницы. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Получает или задает логическое значение, указывающее, будет ли этот абзац находиться в следующем столбце. Значение по умолчанию — false. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Получает или задает встроенный абзац. Значение по умолчанию — false. (для создания pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Получает или задает логическое значение, которое заставляет этот абзац создаваться на новой странице. Значение по умолчанию — false. |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Получает или задает логическое значение, указывающее, остается ли текущий абзац на той же странице вместе со следующим абзацем. Значение по умолчанию — false. (для создания PDF) |
| [Left](../../aspose.pdf/table/left) { get; set; } | Получает или задает левую координату таблицы. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Получает или задает внешнее поле для абзаца (для создания PDF-файла) |
| [RepeatingColumnsCount](../../aspose.pdf/table/repeatingcolumnscount) { get; set; } | Получает или задает максимальное количество столбцов для table |
| [RepeatingRowsCount](../../aspose.pdf/table/repeatingrowscount) { get; set; } | Получает количество первых строк, повторяющихся для нескольких страниц |
| [RepeatingRowsStyle](../../aspose.pdf/table/repeatingrowsstyle) { get; set; } | Получает стиль для повторяющихся строк |
| [Rows](../../aspose.pdf/table/rows) { get; } | Получает строки таблицы. |
| [Top](../../aspose.pdf/table/top) { get; set; } | Получает или задает координату верхней части стола. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Получает или задает вертикальное выравнивание абзаца |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Получает или задает значение int, указывающее Z-порядок графика. График с большим ZIndex будет размещен над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещен за текстом на странице. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Clone](../../aspose.pdf/table/clone)() | Клонировать таблицу. |
| [GetHeight](../../aspose.pdf/table/getheight)(Page) | Получить высоту. |
| [GetWidth](../../aspose.pdf/table/getwidth)() | Получить ширину. |
| [ImportArray](../../aspose.pdf/table/importarray)(object[], int, int, bool) | Импортирует одномерный массив данных в таблицу. Импорт идет по одной ячейке на каждый элемент массива и начинается со строки и столбца, определенных в параметрах. Если во время импорта обнаружено, что нужные строки все еще отсутствуют (т.е. целевая таблица слишком мала, чтобы поглотить все данные), будут созданы необходимые строки |
| [ImportDataTable](../../aspose.pdf/table/importdatatable#importdatatable_1)(DataTable, bool, int, int) | Импортирует данные из System.Data.DataTable в Aspose.Pdf.Table |
| [ImportDataTable](../../aspose.pdf/table/importdatatable#importdatatable)(DataTable, bool, int, byte, int, int, bool) | ИмпортируетDataTable объект в таблицу. |
| [ImportDataTable](../../aspose.pdf/table/importdatatable#importdatatable_2)(DataTable, int[], int[], int, int, bool, bool) | ИмпортируетDataTable объект, а не целое. Импортируются только указанные строки и столбцы. |
| [ImportDataView](../../aspose.pdf/table/importdataview)(DataView, bool, int, int, int, int) | ИмпортируетDataView данные объекта в таблицу. |
| [SetColumnTextState](../../aspose.pdf/table/setcolumntextstate)(int, TextState) | Установить высоту. |

### Смотрите также

* class [BaseParagraph](../baseparagraph)
* пространство имен [Aspose.Pdf](../../aspose.pdf)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
