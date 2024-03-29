---
title: Visit
second_title: Aspose.PDF для справочника API .NET
description: Выполняет поиск на указанной странице.
type: docs
weight: 140
url: /ru/net/aspose.pdf.text/textfragmentabsorber/visit/
---
## Visit(Page) {#visit_1}

Выполняет поиск на указанной странице.

```csharp
public override void Visit(Page page)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | Page | Объект страницы документа PDF. |

### Примеры

В примере показано, как найти текст на первой странице документа PDF и заменить текст.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Находим шрифт, который будет использоваться для изменения шрифта текста документа
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Создаем объект TextFragmentAbsorber для поиска всех вхождений текста "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Принять поглотитель для первой страницы
absorber.Visit(doc.Pages[1]);

// Изменить текст всех вхождений поиска
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf");  
```

### Смотрите также

* class [Page](../../../aspose.pdf/page)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* пространство имен [Aspose.Pdf.Text](../../textfragmentabsorber)
* сборка [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Выполняет поиск в указанном документе.

```csharp
public override void Visit(Document pdf)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pdf | Document | Объект PDF-документа. |

### Примеры

Пример демонстрирует, как найти текст в документе PDF и заменить текст во всех случаях поиска.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Находим шрифт, который будет использоваться для изменения шрифта текста документа
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Создаем объект TextFragmentAbsorber для поиска всех вхождений текста "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Принять поглотитель для первой страницы
absorber.Visit(doc);

// Изменяем текст первого вхождения текста
absorber.TextFragments[1].Text = "hi world";

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf");  
```

### Смотрите также

* class [Document](../../../aspose.pdf/document)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* пространство имен [Aspose.Pdf.Text](../../textfragmentabsorber)
* сборка [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

Выполняет поиск по указанному объекту формы.

```csharp
public void Visit(XForm xForm)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| xForm | XForm | Объект формы PDF. |

### Смотрите также

* class [XForm](../../../aspose.pdf/xform)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* пространство имен [Aspose.Pdf.Text](../../textfragmentabsorber)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
