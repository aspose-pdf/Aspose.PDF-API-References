---
title: "Класс TableAbsorber"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Text.TableAbsorber. Представляет объект‑поглотитель элементов таблицы. Выполняет поиск и предоставляет доступ к результатам поиска через коллекцию TableList."
type: docs
weight: 10970
url: /ru/net/aspose.pdf.text/tableabsorber/
---
## TableAbsorber class

Представляет объект‑поглотитель элементов таблицы. Выполняет поиск и предоставляет доступ к результатам поиска через коллекцию [`TableList`](./tablelist/).

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
| [UseFlowEngine](../../aspose.pdf.text/tableabsorber/useflowengine/) { get; set; } | * Включить альтернативный движок распознавания таблиц, который превосходит в многочисленных сценариях и способен распознавать таблицы без границ. Пока не поддерживает редактирование таблиц и получение стилей текста. Значение по умолчанию — false; |

## Методы

| Имя | Описание |
| --- | --- |
| [Remove](../../aspose.pdf.text/tableabsorber/remove/)(AbsorbedTable) | Удаляет [`AbsorbedTable`](../absorbedtable/) со страницы. |
| [Replace](../../aspose.pdf.text/tableabsorber/replace/)(Page, AbsorbedTable, Table) | Заменяет [`AbsorbedTable`](../absorbedtable/) на [`Table`](../../aspose.pdf/table/) на странице. |
| [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit)(Document) | Извлекает таблицы из указанного документа. |
| virtual [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit_1)(Page) | Извлекает таблицы на указанной странице |

## Примеры

Пример демонстрирует, как найти таблицу на первой странице PDF‑документа и заменить текст в ячейке таблицы.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Создайте объект TableAbsorber для поиска таблиц
TableAbsorber absorber = new TableAbsorber();

// Посетите первую страницу с поглотителем
absorber.Visit(pdfDocument.Pages[1]);

// Получите доступ к первой таблице на странице, её первой ячейке и текстовым фрагментам в ней
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Измените текст первого текстового фрагмента в ячейке
fragment.Text = "hi world";

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf");  
```

### См. также

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


