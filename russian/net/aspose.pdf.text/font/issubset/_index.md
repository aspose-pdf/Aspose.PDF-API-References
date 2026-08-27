---
title: "Font.IsSubset"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство Font. Возвращает или задает значение, указывающее, является ли шрифт подмножеством. Шрифт, основанный на IFont, будет автоматически подмножеством и встроен"
type: docs
weight: 70
url: /ru/net/aspose.pdf.text/font/issubset/
---
## Font.IsSubset property

Получает или задает значение, указывающее, является ли шрифт подмножеством. Шрифт, основанный на IFont, будет автоматически подмножеством и встроен.

```csharp
public bool IsSubset { get; set; }
```

## Примеры

В примере демонстрируется, как искать текст на первой странице и получить значение, указывающее, является ли шрифт подмножеством.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Создайте объект TextFragmentAbsorber для поиска всех вхождений текста "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Примите поглотитель для первой страницы
doc.Pages[1].Accept(absorber);

// Просмотр значения IsSubset шрифта первого вхождения текста
if(absorber.TextFragments[1].TextState.Font.IsSubset)
   Console.Out.WriteLine("the font is a subset");
```

### См. также

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


