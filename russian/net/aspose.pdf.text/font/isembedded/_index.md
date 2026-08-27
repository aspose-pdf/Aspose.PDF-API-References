---
title: "Font.IsEmbedded"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство Font. Возвращает или задает значение, указывающее, встроен ли шрифт. Шрифт, основанный на IFont, будет автоматически подмножеством и встроен"
type: docs
weight: 60
url: /ru/net/aspose.pdf.text/font/isembedded/
---
## Font.IsEmbedded property

Получает или задает значение, указывающее, встроен ли шрифт. Шрифт, основанный на IFont, будет автоматически подмножеством и встроен.

```csharp
public bool IsEmbedded { get; set; }
```

## Примеры

В следующем примере демонстрируется, как найти шрифт, пометить его как встроенный, искать текст на странице документа и заменить шрифт текста.

```csharp
// Создайте шрифт и пометьте его для встраивания
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// создать объект TextFragmentAbsorber для поиска всех вхождений текста "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
// принять абсорбер для первой страницы
doc.Pages[1].Accept(absorber);

// изменить шрифт первого вхождения текста
absorber.TextFragments[1].TextState.Font = font;

// сохранить документ
doc.Save(@"D:\Tests\output.pdf"); 
```

### См. также

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [FontRepository](../../fontrepository/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


