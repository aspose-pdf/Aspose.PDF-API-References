---
title: Text
second_title: Aspose.PDF для справочника API .NET
description: Получает или устанавливаетString текстовый объект которыйTextFragmentaspose.pdf.text/textfragment объект представляет.
type: docs
weight: 130
url: /ru/net/aspose.pdf.text/textfragment/text/
---
## TextFragment.Text property

Получает или устанавливаетString текстовый объект, который[`TextFragment`](../../textfragment) объект представляет.

```csharp
public string Text { get; set; }
```

### Примеры

Пример демонстрирует, как искать текст и заменять первое вхождение, представленное[`TextFragment`](../../textfragment) объект .

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Создаем объект TextFragmentAbsorber для поиска всех вхождений текста "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Принять поглотитель для первой страницы
doc.Pages[1].Accept(absorber);

// Изменяем шрифт первого вхождения текста
absorber.TextFragments[1].Text = "hi world";

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf"); 
```

### Смотрите также

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* class [Document](../../../aspose.pdf/document)
* class [TextFragment](../../textfragment)
* пространство имен [Aspose.Pdf.Text](../../textfragment)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
