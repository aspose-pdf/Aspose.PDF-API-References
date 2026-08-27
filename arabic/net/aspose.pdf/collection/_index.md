---
title: "الفئة Collection"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Collection. تمثل الفئة لـ Collection12.3.5 Collections"
type: docs
weight: 3130
url: /ar/net/aspose.pdf/collection/
---
## Collection class

يمثل الفئة الخاصة بـ Collection(12.3.5 Collections).

```csharp
public class Collection : EmbeddedFileCollection
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Collection](collection/)() | يُهيئ كائن Collection جديد. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Count](../../aspose.pdf/embeddedfilecollection/count/) { get; } | يحصل على عدد الملفات المضمنة في المجموعة. |
| [DefaultEntry](../../aspose.pdf/collection/defaultentry/) { get; } | اسم الملف المضمن الافتراضي. |
| [IsSynchronized](../../aspose.pdf/embeddedfilecollection/issynchronized/) { get; } | يحصل على قيمة تشير إلى ما إذا كان الوصول إلى هذه المجموعة متزامنًا (آمن للخيوط). |
| [Item](../../aspose.pdf/embeddedfilecollection/item/) { get; } | يحصل على الملف المضمن حسب فهرسه. (مؤشرين) |
| [Keys](../../aspose.pdf/embeddedfilecollection/keys/) { get; } | يعيد قائمة مفاتيح مرفقات الملفات. |
| [Schema](../../aspose.pdf/collection/schema/) { get; } | يحصل على "مخطط" مجموعة المستند. |
| [SyncRoot](../../aspose.pdf/embeddedfilecollection/syncroot/) { get; } | يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى هذه المجموعة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(FileSpecification) | يضيف مواصفات الملف المضمن إلى المجموعة. |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(string, FileSpecification) | يضيف ملفًا إلى الملفات المضمنة بالمفتاح المحدد. |
| [CopyTo](../../aspose.pdf/embeddedfilecollection/copyto/)(FileSpecification[], int) | ينسخ مصفوفة كائن FileSpecification إلى المجموعة. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)() | يزيل جميع الملفات المضمنة من المستند. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)(string) | يحذف الملف المضمن حسب الاسم. |
| [DeleteByKey](../../aspose.pdf/embeddedfilecollection/deletebykey/)(string) | يحذف الملف من المجموعة حسب مفتاحه في المجموعة. |
| [FindByName](../../aspose.pdf/embeddedfilecollection/findbyname/)(string) | يعيد الملف المضمن حسب اسمه. |
| [GetEnumerator](../../aspose.pdf/embeddedfilecollection/getenumerator/)() | يعيد عداد المجموعة. |
| [GetSortedCollection](../../aspose.pdf/collection/getsortedcollection/)() | يحصل على مجموعة من الملفات مرتبة وفقًا للمواصفات. |

### انظر أيضًا

* class [EmbeddedFileCollection](../embeddedfilecollection/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


