---
title: "الفئة FontCollection"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Text.FontCollection. تمثل مجموعة الخطوط."
type: docs
weight: 10710
url: /ar/net/aspose.pdf.text/fontcollection/
---
## FontCollection class

يمثل مجموعة الخطوط.

```csharp
public sealed class FontCollection : ICollection<Font>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Count](../../aspose.pdf.text/fontcollection/count/) { get; } | يحصل على عدد عناصر كائن [`Font`](../font/) الموجودة فعليًا في المجموعة. |
| [IsReadOnly](../../aspose.pdf.text/fontcollection/isreadonly/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت المجموعة للقراءة فقط |
| [IsSynchronized](../../aspose.pdf.text/fontcollection/issynchronized/) { get; } | يحصل على قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (thread safe). |
| [Item](../../aspose.pdf.text/fontcollection/item/) { get; } | يحصل على عنصر الخط في الفهرس المحدد. (مؤشرين) |
| [SyncRoot](../../aspose.pdf.text/fontcollection/syncroot/) { get; } | يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى المجموعة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Add](../../aspose.pdf.text/fontcollection/add/)(Font, out string) | يضيف خطًا جديدًا إلى موارد الخطوط ويعيد الاسم المعين تلقائيًا لمورد الخط. |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains)(Font) | يحدد ما إذا كانت المجموعة تحتوي على قيمة محددة. |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains_1)(string) | يتحقق مما إذا كان الخط موجودًا في مجموعة الخطوط. |
| [CopyTo](../../aspose.pdf.text/fontcollection/copyto/)(Font[], int) | ينسخ المجموعة بالكامل إلى مصفوفة أحادية البعد متوافقة، بدءًا من الفهرس المحدد للمصفوفة الهدف |
| [GetEnumerator](../../aspose.pdf.text/fontcollection/getenumerator/)() | يرجع عدّادًا للمجموعة بالكامل. |
| [Remove](../../aspose.pdf.text/fontcollection/remove/)(Font) | يحذف العنصر المحدد من المجموعة. |

## ملاحظات

تُستخدم مجموعات الخطوط التي تمثلها الفئة `FontCollection` في عدة سيناريوهات. على سبيل المثال، في الموارد التي تحتوي على الخاصية [`Fonts`](../../aspose.pdf/resources/fonts/).

## أمثلة

يوضح المثال كيفية جعل جميع الخطوط المعلنة على الصفحة مضمَّنة.

```csharp
// فتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// تأكد من تضمين جميع الخطوط المعلنة في موارد الصفحة.
// لاحظ أنه إذا تم إعلان الخطوط في موارد النموذج فإنها غير قابلة للوصول من موارد الصفحة.
foreach(Aspose.Pdf.Txt.Font font in doc.Pages[1].Resources.Fonts)
{
    if(!font.IsEmbedded)
        font.IsEmbedded = true;
}

doc.Save(@"D:\Tests\input.pdf");
```

### انظر أيضًا

* class [Font](../font/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


