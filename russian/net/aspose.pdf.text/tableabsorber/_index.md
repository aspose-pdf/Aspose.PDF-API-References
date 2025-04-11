---
title: Class TableAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Text.TableAbsorber. Представляет объект-абсорбер элементов таблицы. Выполняет поиск и предоставляет доступ к результатам поиска через коллекцию TableList
type: docs
weight: 10790
url: /ru/net/aspose.pdf.text/tableabsorber/
---
## Класс TableAbsorber

Представляет объект-абсорбер элементов таблицы. Выполняет поиск и предоставляет доступ к результатам поиска через [`TableList`](./tablelist/) коллекцию.

```csharp
public class TableAbsorber
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TableAbsorber](tableabsorber/#constructor)() | Инициализирует новый экземпляр `TableAbsorber`. |
| [TableAbsorber](tableabsorber/#constructor_1)(TextSearchOptions) | Инициализирует новый экземпляр `TableAbsorber` с параметрами поиска текста. |

## Свойства

| Имя | Описание |
| --- | --- |
| virtual [TableList](../../aspose.pdf.text/tableabsorber/tablelist/) { get; } | Возвращает только для чтения IList, содержащий найденные таблицы |
| virtual [TextSearchOptions](../../aspose.pdf.text/tableabsorber/textsearchoptions/) { get; set; } | Получает или задает параметры поиска текста. |
| [UseFlowEngine](../../aspose.pdf.text/tableabsorber/useflowengine/) { get; set; } | * Включает альтернативный движок распознавания таблиц, который превосходит в многочисленных сценариях и способен распознавать таблицы без границ. Пока не поддерживает редактирование таблиц и получение стилей текста. Значение по умолчанию - false; |

## Методы

| Имя | Описание |
| --- | --- |
| [Remove](../../aspose.pdf.text/tableabsorber/remove/)(AbsorbedTable) | Удаляет [`AbsorbedTable`](../absorbedtable/) со страницы. |
| [Replace](../../aspose.pdf.text/tableabsorber/replace/)(Page, AbsorbedTable, Table) | Заменяет [`AbsorbedTable`](../absorbedtable/) на [`Table`](../../aspose.pdf/table/) на странице. |
| [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit)(Document) | Извлекает таблицы в указанном документе. |
| virtual [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit_1)(Page) | Извлекает таблицы на указанной странице |

## Примеры

Пример демонстрирует, как найти таблицу на первой странице PDF-документа и заменить текст в ячейке таблицы.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TableAbsorber object to find tables
TableAbsorber absorber = new TableAbsorber();

// Visit first page with absorber
absorber.Visit(pdfDocument.Pages[1]);

// Get access to first table on page, their first cell and text fragments in it
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Change text of the first text fragment in the cell
fragment.Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### См. также

* пространство имен [Aspose.Pdf.Text](../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../)