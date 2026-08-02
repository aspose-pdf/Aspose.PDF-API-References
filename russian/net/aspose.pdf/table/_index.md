---
title: "Класс Table"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Table. Представляет таблицу, которую можно добавить на страницу"
type: docs
weight: 10460
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
| [Table](table/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Alignment](../../aspose.pdf/table/alignment/) { get; set; } | Получает или задает выравнивание таблицы. |
| [BackgroundColor](../../aspose.pdf/table/backgroundcolor/) { get; set; } | Получает или задает цвет фона таблицы |
| [Border](../../aspose.pdf/table/border/) { get; set; } | Получает или задает границу. |
| [BreakText](../../aspose.pdf/table/breaktext/) { get; set; } | Получает или задает разрыв текста для таблицы |
| [Broken](../../aspose.pdf/table/broken/) { get; set; } | Получает или задает вертикальное разбиение таблицы; |
| [ColumnAdjustment](../../aspose.pdf/table/columnadjustment/) { get; set; } | Получает или задает настройку столбцов таблицы. |
| [ColumnWidths](../../aspose.pdf/table/columnwidths/) { get; set; } | Получает ширины столбцов таблицы. |
| [CornerStyle](../../aspose.pdf/table/cornerstyle/) { get; set; } | Получает или задает стили углов границы |
| [DefaultCellBorder](../../aspose.pdf/table/defaultcellborder/) { get; set; } | Получает границу ячейки по умолчанию; |
| [DefaultCellPadding](../../aspose.pdf/table/defaultcellpadding/) { get; set; } | Получает или задает отступ ячейки по умолчанию. |
| [DefaultCellTextState](../../aspose.pdf/table/defaultcelltextstate/) { get; set; } | Получает или задаёт состояние текста ячейки по умолчанию. |
| [DefaultColumnWidth](../../aspose.pdf/table/defaultcolumnwidth/) { get; set; } | Получает границу ячейки по умолчанию; |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Получает или задает горизонтальное выравнивание абзаца |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Получает или задает гиперссылку фрагмента (для pdf‑генератора). |
| [IsBordersIncluded](../../aspose.pdf/table/isbordersincluded/) { get; set; } | Получает или задает включение границы в ширины столбцов. |
| [IsBroken](../../aspose.pdf/table/isbroken/) { get; set; } | Получает или задает, что таблица разорвана — будет обрезана для следующей страницы. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Получает или задает логическое значение, указывающее, будет ли этот абзац в следующей колонке. По умолчанию false. (для pdf‑генерации) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Получает или задает, является ли абзац встроенным. По умолчанию false. (для pdf‑генерации) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Получает или задает логическое значение, принуждающее этот абзац генерироваться на новой Page. По умолчанию false. (для pdf‑генерации) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Получает или задает логическое значение, указывающее, остаётся ли текущий абзац на той же Page вместе со следующим абзацем. По умолчанию false. (для pdf‑генерации) |
| [Left](../../aspose.pdf/table/left/) { get; set; } | Получает или задает левую координату таблицы. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Получает или задает внешний отступ для абзаца (для генерации PDF) |
| [RepeatingColumnsCount](../../aspose.pdf/table/repeatingcolumnscount/) { get; set; } | Получает или задает максимальное количество столбцов для таблицы |
| [RepeatingRowsCount](../../aspose.pdf/table/repeatingrowscount/) { get; set; } | Получает количество первых строк, повторяемых на нескольких страницах |
| [RepeatingRowsStyle](../../aspose.pdf/table/repeatingrowsstyle/) { get; set; } | Получает стиль для повторяющихся строк |
| [Rows](../../aspose.pdf/table/rows/) { get; } | Получает строки таблицы. |
| [Top](../../aspose.pdf/table/top/) { get; set; } | Получает или задает верхнюю координату таблицы. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Получает или задает вертикальное выравнивание абзаца. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Получает или задает целочисленное значение, указывающее порядок Z графика. График с большим ZIndex будет размещён над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещён позади текста на странице. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Clone](../../aspose.pdf/table/clone/)() | Клонировать таблицу. |
| [GetHeight](../../aspose.pdf/table/getheight/)(Page) | Получить высоту. |
| [GetWidth](../../aspose.pdf/table/getwidth/)() | Получить ширину. |
| [ImportArray](../../aspose.pdf/table/importarray/)(object[], int, int, bool) | Импортирует одномерный массив данных в таблицу. Импорт размещает одну ячейку на каждый элемент массива, начиная с строки и столбца, указанных в параметрах. Во время импорта, если обнаруживается, что необходимые строки отсутствуют (т.е. целевая таблица слишком мала, чтобы вместить все данные), необходимые строки будут созданы. |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable_1)(DataTable, bool, int, int) | Импортирует данные из System.Data.DataTable в Aspose.Pdf.Table |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable)(DataTable, bool, int, byte, int, int, bool) | Импортирует объект DataTable в таблицу. |
| [ImportDataTable](../../aspose.pdf/table/importdatatable/#importdatatable_2)(DataTable, int[], int[], int, int, bool, bool) | Импортирует объект DataTable, но не как целую сущность. Импортируются только указанные строки и столбцы. |
| [ImportDataView](../../aspose.pdf/table/importdataview/)(DataView, bool, int, int, int, int) | Импортирует данные объекта DataView в таблицу. |
| [SetColumnTextState](../../aspose.pdf/table/setcolumntextstate/)(int, TextState) | Установить высоту. |

### См. также

* class [BaseParagraph](../baseparagraph/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


