---
title: Class Table
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Table. Представляет таблицу, которую можно добавить на страницу
type: docs
weight: 10280
url: /ru/net/aspose.pdf/table/
---
## Класс Таблица

Представляет таблицу, которую можно добавить на страницу.

```csharp
public sealed class Table : BaseParagraph
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Table](table/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Alignment](../../aspose.pdf/table/alignment/) { get; set; } | Получает или задает выравнивание таблицы. |
| [BackgroundColor](../../aspose.pdf/table/backgroundcolor/) { get; set; } | Получает или задает цвет фона таблицы |
| [Border](../../aspose.pdf/table/border/) { get; set; } | Получает или задает границу. |
| [BreakText](../../aspose.pdf/table/breaktext/) { get; set; } | Получает или задает текст для разрыва таблицы |
| [Broken](../../aspose.pdf/table/broken/) { get; set; } | Получает или задает вертикальный разрыв таблицы; |
| [ColumnAdjustment](../../aspose.pdf/table/columnadjustment/) { get; set; } | Получает или задает регулировку столбцов таблицы. |
| [ColumnWidths](../../aspose.pdf/table/columnwidths/) { get; set; } | Получает ширину столбцов таблицы. |
| [CornerStyle](../../aspose.pdf/table/cornerstyle/) { get; set; } | Получает или задает стили углов границы |
| [DefaultCellBorder](../../aspose.pdf/table/defaultcellborder/) { get; set; } | Получает границу ячейки по умолчанию; |
| [DefaultCellPadding](../../aspose.pdf/table/defaultcellpadding/) { get; set; } | Получает или задает отступ ячейки по умолчанию. |
| [DefaultCellTextState](../../aspose.pdf/table/defaultcelltextstate/) { get; set; } | Получает или задает состояние текста ячейки по умолчанию. |
| [DefaultColumnWidth](../../aspose.pdf/table/defaultcolumnwidth/) { get; set; } | Получает границу ячейки по умолчанию; |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Получает или задает горизонтальное выравнивание абзаца |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Получает или задает гиперссылку фрагмента (для генератора pdf). |
| [IsBordersIncluded](../../aspose.pdf/table/isbordersincluded/) { get; set; } | Получает или задает, включена ли граница в ширину столбцов. |
| [IsBroken](../../aspose.pdf/table/isbroken/) { get; set; } | Получает или задает, разорвана ли таблица - будет обрезана для следующей страницы. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Получает или задает логическое значение, указывающее, будет ли этот абзац в следующем столбце. По умолчанию false. (для генерации pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Получает или задает, является ли абзац встроенным. По умолчанию false. (для генерации pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Получает или задает логическое значение, которое заставляет этот абзац генерироваться на новой странице. По умолчанию false. (для генерации pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Получает или задает логическое значение, указывающее, остается ли текущий абзац на той же странице вместе с следующим абзацем. По умолчанию false. (для генерации pdf) |
| [Left](../../aspose.pdf/table/left/) { get; set; } | Получает или задает левую координату таблицы. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Получает или задает внешний отступ для абзаца (для генерации pdf) |
| [RepeatingColumnsCount](../../aspose.pdf/table/repeatingcolumnscount/) { get; set; } | Получает или задает максимальное количество столбцов для таблицы |
| [RepeatingRowsCount](../../aspose.pdf/table/repeatingrowscount/) { get; set; } | Получает количество первых строк, повторяемых на нескольких страницах |
| [RepeatingRowsStyle](../../aspose.pdf/table/repeatingrowsstyle/) { get; set; } | Получает стиль для повторяющихся строк |
| [Rows](../../aspose.pdf/table/rows/) { get; } | Получает строки таблицы. |
| [Top](../../aspose.pdf/table/top/) { get; set; } | Получает или задает верхнюю координату таблицы. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Получает или задает вертикальное выравнивание абзаца |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Получает или задает целочисленное значение, указывающее порядок Z графика. График с большим ZIndex будет размещен поверх графика с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещен за текстом на странице. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Clone](../../aspose.pdf/table/clone/)() | Клонирует таблицу. |
| [GetHeight](../../aspose.pdf/table/getheight/)(Page) | Получает высоту. |
| [GetWidth](../../aspose.pdf/table/getwidth/)() | Получает ширину. |
| [ImportArray](../../aspose.pdf/table/importarray/)(object[], int, int, bool) | Импортирует одномерный массив данных в таблицу. Импорт происходит по одной ячейке для каждого элемента массива и начинается с строки и столбца, определенных в параметрах. Во время импорта, если обнаружено, что необходимые строки все еще отсутствуют (т.е. целевая таблица слишком мала, чтобы вместить все данные), необходимые строки будут созданы |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable_1)(DataTable, bool, int, int) | Импортирует данные из System.Data.DataTable в Aspose.Pdf.Table |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable)(DataTable, bool, int, byte, int, int, bool) | Импортирует объект DataTable в таблицу. |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable_2)(DataTable, int[], int[], int, int, bool, bool) | Импортирует объект DataTable, но не как целостное целое. Импортируются только указанные строки и столбцы. |
| [ImportDataView](../../aspose.pdf/table/importdataview/)(DataView, bool, int, int, int, int) | Импортирует данные объекта DataView в таблицу. |
| [SetColumnTextState](../../aspose.pdf/table/setcolumntextstate/)(int, TextState) | Устанавливает высоту. |

### См. также

* класс [BaseParagraph](../baseparagraph/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)