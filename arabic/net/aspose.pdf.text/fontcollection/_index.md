---
title: Class FontCollection
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Text.FontCollection. تمثل مجموعة الخطوط
type: docs
weight: 10530
url: /ar/net/aspose.pdf.text/fontcollection/
---
## فئة مجموعة الخطوط

تمثل مجموعة الخطوط.

```csharp
public sealed class FontCollection : ICollection<Font>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Count](../../aspose.pdf.text/fontcollection/count/) { get; } | يحصل على عدد عناصر [`Font`](../font/) الموجودة فعليًا في المجموعة. |
| [IsReadOnly](../../aspose.pdf.text/fontcollection/isreadonly/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت المجموعة للقراءة فقط |
| [IsSynchronized](../../aspose.pdf.text/fontcollection/issynchronized/) { get; } | يحصل على قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخيوط). |
| [Item](../../aspose.pdf.text/fontcollection/item/) { get; } | يحصل على عنصر الخط في الفهرس المحدد. (2 فهرسات) |
| [SyncRoot](../../aspose.pdf.text/fontcollection/syncroot/) { get; } | يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى المجموعة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Add](../../aspose.pdf.text/fontcollection/add/)(Font, out string) | يضيف خطًا جديدًا إلى موارد الخطوط ويعيد اسم المورد المخصص للخط. |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains)(Font) | يحدد ما إذا كانت المجموعة تحتوي على قيمة معينة. |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains_1)(string) | يتحقق مما إذا كان الخط موجودًا في مجموعة الخطوط. |
| [CopyTo](../../aspose.pdf.text/fontcollection/copyto/)(Font[], int) | ينسخ المجموعة بالكامل إلى مصفوفة أحادية البعد متوافقة، بدءًا من الفهرس المحدد لمصفوفة الهدف |
| [GetEnumerator](../../aspose.pdf.text/fontcollection/getenumerator/)() | يعيد عدادًا للمجموعة بالكامل. |
| [Remove](../../aspose.pdf.text/fontcollection/remove/)(Font) | يحذف العنصر المحدد من المجموعة. |

## ملاحظات

تستخدم مجموعات الخطوط التي تمثلها فئة `FontCollection` في عدة سيناريوهات. على سبيل المثال، في الموارد مع خاصية [`Fonts`](../../aspose.pdf/resources/fonts/).

## أمثلة

توضح المثال كيفية جعل جميع الخطوط المعلنة في الصفحة مضمنة.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// ensure all fonts declared on page resources are embedded
// note that if fonts are declared on form resources they are not accessible from page resources
foreach(Aspose.Pdf.Txt.Font font in doc.Pages[1].Resources.Fonts)
{
    if(!font.IsEmbedded)
        font.IsEmbedded = true;
}

doc.Save(@"D:\Tests\input.pdf");
```

### انظر أيضًا

* فئة [Font](../font/)
* مساحة الأسماء [Aspose.Pdf.Text](../../aspose.pdf.text/)
* التجميع [Aspose.PDF](../../)