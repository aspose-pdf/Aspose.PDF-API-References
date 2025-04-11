---
title: TextFragmentAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: Метод TextFragmentAbsorber. Выполняет поиск на указанной странице
type: docs
weight: 150
url: /ru/net/aspose.pdf.text/textfragmentabsorber/visit/
---
## Visit(Page) {#visit_1}

Выполняет поиск на указанной странице.

```csharp
public override void Visit(Page page)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | Page | Объект страницы PDF документа. |

## Примеры

Пример демонстрирует, как найти текст на первой странице PDF документа и заменить текст.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
absorber.Visit(doc.Pages[1]);

// Change text of all search occurrences
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### См. также

* класс [Page](../../../aspose.pdf/page/)
* класс [TextFragmentAbsorber](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Выполняет поиск на указанном документе.

```csharp
public override void Visit(Document pdf)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pdf | Document | Объект PDF документа. |

## Примеры

Пример демонстрирует, как найти текст в PDF документе и заменить текст всех найденных вхождений.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
absorber.Visit(doc);

// Change text of the first text occurrence
absorber.TextFragments[1].Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### См. также

* класс [Document](../../../aspose.pdf/document/)
* класс [TextFragmentAbsorber](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

Выполняет поиск на указанном объекте формы.

```csharp
public void Visit(XForm xForm)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| xForm | XForm | Объект формы Pdf. |

### См. также

* класс [XForm](../../../aspose.pdf/xform/)
* класс [TextFragmentAbsorber](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)