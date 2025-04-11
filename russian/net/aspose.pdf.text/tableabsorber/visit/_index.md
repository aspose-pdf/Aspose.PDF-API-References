---
title: TableAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: Метод TableAbsorber. Извлекает таблицы на указанной странице
type: docs
weight: 70
url: /ru/net/aspose.pdf.text/tableabsorber/visit/
---
## Visit(Page) {#visit_1}

Извлекает таблицы на указанной странице

```csharp
public virtual void Visit(Page page)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | Page | Объект страницы PDF документа. |

## Примеры

Пример демонстрирует, как извлечь таблицу на первой странице PDF документа.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TableAbsorber object to find tables
TableAbsorber absorber = new TableAbsorber();

// Visit first page with absorber
absorber.Visit(doc.Pages[1]);

// Get access to first table on page, their first cell and text fragments in it
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Change text of the first text fragment in the cell
fragment.Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### См. также

* класс [Page](../../../aspose.pdf/page/)
* класс [TableAbsorber](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Извлекает таблицы в указанном документе.

```csharp
public void Visit(Document pdf)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pdf | Document | Объект PDF документа. |

## Примеры

Пример демонстрирует, как извлечь таблицу на первой странице PDF документа.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TableAbsorber object to find tables
TableAbsorber absorber = new TableAbsorber();

// Visit first page with absorber
absorber.Visit(doc);

// Get access to first table on page, their first cell and text fragments in it
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Change text of the first text fragment in the cell
fragment.Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### См. также

* класс [Document](../../../aspose.pdf/document/)
* класс [TableAbsorber](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)