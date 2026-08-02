---
title: "TextFragment.Text"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство TextFragment. Получает или задает объект String, представляющий текст, который представляет объект TextFragment."
type: docs
weight: 130
url: /ru/net/aspose.pdf.text/textfragment/text/
---
## TextFragment.Text property

Получает или задает объект String, представляющий текст, который представляет объект [`TextFragment`](../).

```csharp
public string Text { get; set; }
```

## Примеры

Пример демонстрирует, как искать текст и заменять первое вхождение, представленное объектом [`TextFragment`](../).

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Создайте объект TextFragmentAbsorber для поиска всех вхождений текста "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Примите поглотитель для первой страницы
doc.Pages[1].Accept(absorber);

// Изменить шрифт первого вхождения текста
absorber.TextFragments[1].Text = "hi world";

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf"); 
```

### См. также

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


