---
title: Class CharInfoCollection
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Text.CharInfoCollection. Представляет коллекцию объектов CharInfo
type: docs
weight: 10450
url: /ru/net/aspose.pdf.text/charinfocollection/
---
## CharInfoCollection class

Представляет коллекцию объектов CharInfo.

```csharp
public sealed class CharInfoCollection : ICollection<CharInfo>
```

## Properties

| Name | Description |
| --- | --- |
| [Count](../../aspose.pdf.text/charinfocollection/count/) { get; } | Получает количество элементов объекта [`CharInfo`](../charinfo/) фактически содержащихся в коллекции. |
| [IsReadOnly](../../aspose.pdf.text/charinfocollection/isreadonly/) { get; } | Получает значение, указывающее, является ли коллекция только для чтения |
| [IsSynchronized](../../aspose.pdf.text/charinfocollection/issynchronized/) { get; } | Получает значение, указывающее, синхронизирован ли доступ к коллекции (безопасно для потоков). |
| [Item](../../aspose.pdf.text/charinfocollection/item/) { get; } | Получает элемент CharInfo по указанному индексу. |
| [SyncRoot](../../aspose.pdf.text/charinfocollection/syncroot/) { get; } | Получает объект, который можно использовать для синхронизации доступа к коллекции. |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../aspose.pdf.text/charinfocollection/add/)(CharInfo) | Коллекция только для чтения, вызывает NotImplementedException. |
| [Clear](../../aspose.pdf.text/charinfocollection/clear/)() | Коллекция только для чтения. Всегда вызывает NotImplementedException. |
| [Contains](../../aspose.pdf.text/charinfocollection/contains/)(CharInfo) | Определяет, содержит ли коллекция конкретное значение. |
| [CopyTo](../../aspose.pdf.text/charinfocollection/copyto/)(CharInfo[], int) | Копирует всю коллекцию в совместимый одномерный массив, начиная с указанного индекса целевого массива |
| [GetEnumerator](../../aspose.pdf.text/charinfocollection/getenumerator/)() | Возвращает перечислитель для всей коллекции. |
| [Remove](../../aspose.pdf.text/charinfocollection/remove/)(CharInfo) | Коллекция только для чтения, вызывает NotImplementedException. |

## Remarks

Предоставляет доступ к информации о позиционировании символов текстового сегмента.

## Examples

Пример демонстрирует, как перебрать все символы и получить символ

```csharp
//open document
Document pdfDocument = new Document(inFile);
//create TextFragmentAbsorber object to collect all the text objects of the page
TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber();
//accept the absorber for all the pages
pdfDocument.Pages[1].Accept(textFragmentAbsorber);
//get the extracted text fragments
TextFragmentCollection textFragmentCollection = textFragmentAbsorber.TextFragments;
            
//loop through the fragments
foreach (TextFragment textFragment in textFragmentCollection)
{
    //loop through the segments
    foreach (TextSegment textSegment in textFragment.Segments)
    {
        //loop through the characters
        for (int i = 1; i <= textSegment.Text.Length; i++)
        {
            CharInfo charInfo = textSegment.Characters[i];

            // print character position and rectangle info
            Console.WriteLine("XIndent : {0} ", charInfo.Position.XIndent);
            Console.WriteLine("YIndent : {0} ", charInfo.Position.YIndent);
            Console.WriteLine("Width : {0} ", charInfo.Rectangle.Width);
            Console.WriteLine("Height : {0} ", charInfo.Rectangle.Height);
        }
    }
}
```

### See Also

* class [CharInfo](../charinfo/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)