---
title: "Font.FontName"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство Font. Возвращает имя шрифта объекта Font"
type: docs
weight: 30
url: /ru/net/aspose.pdf.text/font/fontname/
---
## Font.FontName property

Возвращает имя шрифта объекта [`Font`](../).

```csharp
public string FontName { get; }
```

## Примеры

В примере демонстрируется, как искать текст на первой странице и просмотреть имя шрифта первого найденного вхождения текста.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Создайте объект TextFragmentAbsorber для поиска всех вхождений текста "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Примите поглотитель для первой страницы
doc.Pages[1].Accept(absorber);

// Просмотр имени шрифта первого вхождения текста
Console.Out.WriteLine(absorber.TextFragments[1].TextState.Font.FontName); 
```

### См. также

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


