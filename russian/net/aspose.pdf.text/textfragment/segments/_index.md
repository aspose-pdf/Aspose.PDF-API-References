---
title: "TextFragment.Segments"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство TextFragment. Возвращает текстовые сегменты текущего TextFragment."
type: docs
weight: 120
url: /ru/net/aspose.pdf.text/textfragment/segments/
---
## TextFragment.Segments property

Возвращает текстовые сегменты текущего [`TextFragment`](../).

```csharp
public TextSegmentCollection Segments { get; set; }
```

## Примечания

Кратко, объекты [`TextSegment`](../../textsegment/) являются дочерними объектами [`TextFragment`](../). Продвинутые пользователи могут обращаться к сегментам напрямую для выполнения более сложных сценариев редактирования текста. Подробности см. в описании объекта [`TextFragment`](../).

## Примеры

В примере показано, как перебрать все объекты [`TextSegment`](../../textsegment/) внутри [`TextFragment`](../).

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Создайте объект TextFragmentAbsorber для поиска всех вхождений текста "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Примите поглотитель для первой страницы
doc.Pages[1].Accept(absorber);

// Переберите все текстовые сегменты и выведите их текст и информацию о расположении.
foreach (TextSegment segment in absorber.TextFragments[1].Segments)
{
    Console.Out.WriteLine(string.Format("segment text: {0}", segment.Text));
    Console.Out.WriteLine(string.Format("segment X indent: {0}", segment.Position.XIndent));
    Console.Out.WriteLine(string.Format("segment Y indent: {0}", segment.Position.YIndent));
}

```

### См. также

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextSegment](../../textsegment/)
* class [TextSegmentCollection](../../textsegmentcollection/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


