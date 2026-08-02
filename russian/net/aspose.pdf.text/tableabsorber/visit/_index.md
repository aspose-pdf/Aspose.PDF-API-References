---
title: "TableAbsorber.Visit"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод TableAbsorber. Извлекает таблицы на указанной странице"
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
| страница | Страница | Объект страницы Pdf документа. |

## Примеры

Пример демонстрирует, как извлечь таблицу на первой странице PDF‑документа.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Создайте объект TableAbsorber для поиска таблиц
TableAbsorber absorber = new TableAbsorber();

// Посетите первую страницу с поглотителем
absorber.Visit(doc.Pages[1]);

// Получите доступ к первой таблице на странице, её первой ячейке и текстовым фрагментам в ней
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Измените текст первого текстового фрагмента в ячейке
fragment.Text = "hi world";

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf");  
```

### См. также

* class [Page](../../../aspose.pdf/page/)
* class [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Извлекает таблицы из указанного документа.

```csharp
public void Visit(Document pdf)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pdf | Document | Объект Pdf документа. |

## Примеры

Пример демонстрирует, как извлечь таблицу на первой странице PDF‑документа.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Создайте объект TableAbsorber для поиска таблиц
TableAbsorber absorber = new TableAbsorber();

// Посетите первую страницу с поглотителем
absorber.Visit(doc);

// Получите доступ к первой таблице на странице, её первой ячейке и текстовым фрагментам в ней
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Измените текст первого текстового фрагмента в ячейке
fragment.Text = "hi world";

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf");  
```

### См. также

* class [Document](../../../aspose.pdf/document/)
* class [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


