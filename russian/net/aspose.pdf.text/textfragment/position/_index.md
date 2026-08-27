---
title: "TextFragment.Position"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство TextFragment. Получает или задаёт позицию текста, представленного объектом TextFragment."
type: docs
weight: 90
url: /ru/net/aspose.pdf.text/textfragment/position/
---
## TextFragment.Position property

Получает или задаёт позицию текста, представленного объектом [`TextFragment`](../).

```csharp
public Position Position { get; set; }
```

## Примеры

В примере показано, как просмотреть расположение текста, представленного объектом [`TextFragment`](../).

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Создайте объект TextFragmentAbsorber для поиска всех вхождений текста "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Примите поглотитель для первой страницы
doc.Pages[1].Accept(absorber);

// Просмотр текста и информации о расположении первого вхождения.
TextFragment firstOccurrence = absorber.TextFragments[1];

Console.Out.WriteLine(string.Format("fragment text: {0}", firstOccurrence.Text));
Console.Out.WriteLine(string.Format("fragment X indent: {0}", firstOccurrence.Position.XIndent));
Console.Out.WriteLine(string.Format("fragment Y indent: {0}", firstOccurrence.Position.YIndent));

```

### См. также

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextSegment](../../textsegment/)
* class [Position](../../position/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


