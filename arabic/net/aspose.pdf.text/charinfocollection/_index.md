---
title: "الفئة CharInfoCollection"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Text.CharInfoCollection. تمثّل مجموعة كائنات CharInfo"
type: docs
weight: 10630
url: /ar/net/aspose.pdf.text/charinfocollection/
---
## CharInfoCollection class

يمثل مجموعة كائنات CharInfo.

```csharp
public sealed class CharInfoCollection : ICollection<CharInfo>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Count](../../aspose.pdf.text/charinfocollection/count/) { get; } | يحصل على عدد عناصر كائن [`CharInfo`](../charinfo/) الموجودة فعليًا في المجموعة. |
| [IsReadOnly](../../aspose.pdf.text/charinfocollection/isreadonly/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت المجموعة للقراءة فقط |
| [IsSynchronized](../../aspose.pdf.text/charinfocollection/issynchronized/) { get; } | يحصل على قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (thread safe). |
| [Item](../../aspose.pdf.text/charinfocollection/item/) { get; } | يحصل على عنصر CharInfo في الفهرس المحدد. |
| [SyncRoot](../../aspose.pdf.text/charinfocollection/syncroot/) { get; } | يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى المجموعة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Add](../../aspose.pdf.text/charinfocollection/add/)(CharInfo) | المجموعة للقراءة فقط، تُطلق استثناء NotImplementedException. |
| [Clear](../../aspose.pdf.text/charinfocollection/clear/)() | المجموعة للقراءة فقط. دائمًا تُطلق استثناء NotImplementedException. |
| [Contains](../../aspose.pdf.text/charinfocollection/contains/)(CharInfo) | يحدد ما إذا كانت المجموعة تحتوي على قيمة محددة. |
| [CopyTo](../../aspose.pdf.text/charinfocollection/copyto/)(CharInfo[], int) | ينسخ المجموعة بالكامل إلى مصفوفة أحادية البعد متوافقة، بدءًا من الفهرس المحدد للمصفوفة الهدف |
| [GetEnumerator](../../aspose.pdf.text/charinfocollection/getenumerator/)() | يرجع عدّادًا للمجموعة بالكامل. |
| [Remove](../../aspose.pdf.text/charinfocollection/remove/)(CharInfo) | المجموعة للقراءة فقط، تُطلق استثناء NotImplementedException. |

## ملاحظات

يوفر وصولًا إلى معلومات تموضع أحرف مقطع النص.

## أمثلة

يوضح المثال كيفية التكرار عبر جميع الأحرف واسترجاع الأحرف

```csharp
//فتح المستند
Document pdfDocument = new Document(inFile);
//إنشاء كائن TextFragmentAbsorber لجمع جميع كائنات النص في الصفحة
TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber();
//قبول الـ absorber لجميع الصفحات
pdfDocument.Pages[1].Accept(textFragmentAbsorber);
//احصل على مقاطع النص المستخرجة
TextFragmentCollection textFragmentCollection = textFragmentAbsorber.TextFragments;
            
//التكرار عبر المقاطع
foreach (TextFragment textFragment in textFragmentCollection)
{
    //التكرار عبر القطاعات
    foreach (TextSegment textSegment in textFragment.Segments)
    {
        //التكرار عبر الأحرف
        for (int i = 1; i <= textSegment.Text.Length; i++)
        {
            CharInfo charInfo = textSegment.Characters[i];

            // طباعة موضع الحرف ومعلومات Rectangle
            Console.WriteLine("XIndent : {0} ", charInfo.Position.XIndent);
            Console.WriteLine("YIndent : {0} ", charInfo.Position.YIndent);
            Console.WriteLine("Width : {0} ", charInfo.Rectangle.Width);
            Console.WriteLine("Height : {0} ", charInfo.Rectangle.Height);
        }
    }
}
```

### انظر أيضًا

* class [CharInfo](../charinfo/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


