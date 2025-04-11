---
title: Class Collection
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Collection. تمثل فئة لمجموعة 12.3.5
type: docs
weight: 3020
url: /ar/net/aspose.pdf/collection/
---
## فئة المجموعة

تمثل فئة لمجموعة (12.3.5).

```csharp
public class Collection : EmbeddedFileCollection
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Collection](collection/)() | يقوم بتهيئة كائن مجموعة جديد. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Count](../../aspose.pdf/embeddedfilecollection/count/) { get; } | يحصل على عدد الملفات المضمنة في المجموعة. |
| [DefaultEntry](../../aspose.pdf/collection/defaultentry/) { get; } | اسم الملف المضمن الافتراضي. |
| [IsSynchronized](../../aspose.pdf/embeddedfilecollection/issynchronized/) { get; } | يحصل على قيمة تشير إلى ما إذا كان الوصول إلى هذه المجموعة متزامنًا (آمن للخيوط). |
| [Item](../../aspose.pdf/embeddedfilecollection/item/) { get; } | يحصل على الملف المضمن بواسطة فهرسه. (2 فهرس) |
| [Keys](../../aspose.pdf/embeddedfilecollection/keys/) { get; } | يعيد قائمة بمفاتيح مرفقات الملفات. |
| [Schema](../../aspose.pdf/collection/schema/) { get; } | يحصل على "مخطط" لمجموعة الوثائق. |
| [SyncRoot](../../aspose.pdf/embeddedfilecollection/syncroot/) { get; } | يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى هذه المجموعة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(FileSpecification) | يضيف مواصفة ملف مضمن إلى المجموعة. |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(string, FileSpecification) | يضيف ملفًا إلى الملفات المضمنة بالمفتاح المحدد. |
| [CopyTo](../../aspose.pdf/embeddedfilecollection/copyto/)(FileSpecification[], int) | ينسخ مصفوفة من كائن FileSpecification إلى المجموعة. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)() | يزيل جميع الملفات المضمنة من الوثيقة. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)(string) | يحذف الملف المضمن حسب الاسم. |
| [DeleteByKey](../../aspose.pdf/embeddedfilecollection/deletebykey/)(string) | يحذف الملف من المجموعة حسب مفتاحه في المجموعة. |
| [FindByName](../../aspose.pdf/embeddedfilecollection/findbyname/)(string) | يعيد الملف المضمن حسب اسمه. |
| [GetEnumerator](../../aspose.pdf/embeddedfilecollection/getenumerator/)() | يعيد عداد المجموعة. |
| [GetSortedCollection](../../aspose.pdf/collection/getsortedcollection/)() | يحصل على مجموعة من الملفات مرتبة وفقًا للمواصفة. |

### انظر أيضًا

* الفئة [EmbeddedFileCollection](../embeddedfilecollection/)
* مساحة الاسم [Aspose.Pdf](../../aspose.pdf/)
* التجميع [Aspose.PDF](../../)