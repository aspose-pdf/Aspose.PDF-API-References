---
title: "TextFragmentAbsorber.Visit"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод TextFragmentAbsorber. Выполняет поиск на указанной странице"
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
| страница | Страница | Объект страницы PDF‑документа. |

## Примеры

Пример демонстрирует, как найти текст на первой странице PDF‑документа и заменить его.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Найдите шрифт, который будет использоваться для изменения шрифта текста документа
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Создайте объект TextFragmentAbsorber для поиска всех вхождений текста "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Примите поглотитель для первой страницы
absorber.Visit(doc.Pages[1]);

// Изменить текст всех найденных вхождений
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf");  
```

### См. также

* class [Page](../../../aspose.pdf/page/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Выполняет поиск в указанном документе.

```csharp
public override void Visit(Document pdf)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pdf | Document | Объект PDF‑документа. |

## Примеры

Пример демонстрирует, как находить текст в PDF‑документе и заменять текст всех найденных вхождений.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Найдите шрифт, который будет использоваться для изменения шрифта текста документа
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Создайте объект TextFragmentAbsorber для поиска всех вхождений текста "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Примите поглотитель для первой страницы
absorber.Visit(doc);

// Измените текст первого вхождения
absorber.TextFragments[1].Text = "hi world";

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf");  
```

### См. также

* class [Document](../../../aspose.pdf/document/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

Выполняет поиск в указанном объекте формы.

```csharp
public void Visit(XForm xForm)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| xForm | XForm | Объект формы Pdf. |

### См. также

* class [XForm](../../../aspose.pdf/xform/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


