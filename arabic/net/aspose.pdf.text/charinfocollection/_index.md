---
title: Class CharInfoCollection
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Text.CharInfoCollection. تمثل مجموعة من كائنات CharInfo
type: docs
weight: 10450
url: /ar/net/aspose.pdf.text/charinfocollection/
---
## CharInfoCollection class

تمثل مجموعة من كائنات CharInfo.

```csharp
public sealed class CharInfoCollection : ICollection<CharInfo>
```

## Properties

| Name | Description |
| --- | --- |
| [Count](../../aspose.pdf.text/charinfocollection/count/) { get; } | يحصل على عدد عناصر كائن [`CharInfo`](../charinfo/) الموجودة فعليًا في المجموعة. |
| [IsReadOnly](../../aspose.pdf.text/charinfocollection/isreadonly/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت المجموعة للقراءة فقط |
| [IsSynchronized](../../aspose.pdf.text/charinfocollection/issynchronized/) { get; } | يحصل على قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخيوط). |
| [Item](../../aspose.pdf.text/charinfocollection/item/) { get; } | يحصل على عنصر CharInfo في الفهرس المحدد. |
| [SyncRoot](../../aspose.pdf.text/charinfocollection/syncroot/) { get; } | يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى المجموعة. |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../aspose.pdf.text/charinfocollection/add/)(CharInfo) | المجموعة للقراءة فقط، ترمي NotImplementedException. |
| [Clear](../../aspose.pdf.text/charinfocollection/clear/)() | المجموعة للقراءة فقط. دائمًا ترمي NotImplementedException. |
| [Contains](../../aspose.pdf.text/charinfocollection/contains/)(CharInfo) | يحدد ما إذا كانت المجموعة تحتوي على قيمة معينة. |
| [CopyTo](../../aspose.pdf.text/charinfocollection/copyto/)(CharInfo[], int) | ينسخ المجموعة بالكامل إلى مصفوفة أحادية البعد متوافقة، بدءًا من الفهرس المحدد لمصفوفة الهدف |
| [GetEnumerator](../../aspose.pdf.text/charinfocollection/getenumerator/)() | يعيد عدادًا للمجموعة بالكامل. |
| [Remove](../../aspose.pdf.text/charinfocollection/remove/)(CharInfo) | المجموعة للقراءة فقط، ترمي NotImplementedException. |

## Remarks

يوفر الوصول إلى معلومات تحديد مواقع أحرف مقاطع النص.

## Examples

توضح المثال كيفية التكرار عبر جميع الأحرف واسترجاع الحرف

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