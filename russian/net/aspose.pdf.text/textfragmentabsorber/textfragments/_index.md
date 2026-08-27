---
title: "TextFragmentAbsorber.TextFragments"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство TextFragmentAbsorber. Получает коллекцию поисковых вхождений, представленных объектами TextFragment."
type: docs
weight: 90
url: /ru/net/aspose.pdf.text/textfragmentabsorber/textfragments/
---
## TextFragmentAbsorber.TextFragments property

Получает коллекцию поисковых вхождений, представленных объектами [`TextFragment`](../../textfragment/).

```csharp
public TextFragmentCollection TextFragments { get; set; }
```

## Примеры

Пример демонстрирует, как найти текст на первой странице PDF‑документа и заменить все найденные вхождения новым текстом.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Найдите шрифт, который будет использоваться для изменения шрифта текста документа
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Создайте объект TextFragmentAbsorber для поиска всех вхождений текста "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Примите поглотитель для первой страницы
doc.Pages[1].Accept(absorber);

// Изменить текст всех найденных вхождений
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf");  
```

### См. также

* class [TextFragmentCollection](../../textfragmentcollection/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


