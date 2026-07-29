---
title: "الفئة FileSpecification"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.FileSpecification. الفئة تمثل ملفًا مضمّنًا."
type: docs
weight: 4970
url: /ar/net/aspose.pdf/filespecification/
---
## FileSpecification class

فئة تمثل الملف المضمّن.

```csharp
public sealed class FileSpecification : IDisposable
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [FileSpecification](filespecification/#constructor)() | إنشاء مواصفة ملف جديدة فارغة. |
| [FileSpecification](filespecification/#constructor_3)(string) | منشئ لـ FileSpecification |
| [FileSpecification](filespecification/#constructor_1)(Stream, string) | منشئ لمواصفة الملف. |
| [FileSpecification](filespecification/#constructor_4)(string, Annotation) | منشئ لـ FileSpecification. |
| [FileSpecification](filespecification/#constructor_5)(string, string) | منشئ لـ FileSpecification. |
| [FileSpecification](filespecification/#constructor_2)(Stream, string, string) | منشئ لـ FileSpecification. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AFRelationship](../../aspose.pdf/filespecification/afrelationship/) { get; set; } | العلاقة المرتبطة بالملف. |
| [CollectionItem](../../aspose.pdf/filespecification/collectionitem/) { get; } | يحصل على عنصر من مجموعة مواصفة الملف. |
| [Contents](../../aspose.pdf/filespecification/contents/) { get; set; } | يحصل أو يعيّن ملف المحتويات. تُعيد هذه الخاصية البيانات المحمّلة في الذاكرة والتي قد تتسبب في استثناء نفاد الذاكرة للبيانات الكبيرة. لتقليل استهلاك الذاكرة يرجى استخدام StreamContents. |
| [Description](../../aspose.pdf/filespecification/description/) { get; set; } | يحصل أو يعيّن النص المرتبط بمواصفة الملف. |
| [Encoding](../../aspose.pdf/filespecification/encoding/) { get; set; } | يحصل أو يعيّن تنسيق الترميز. القيم الممكنة: Zip - الملف مضغوط باستخدام ZIP، None - الملف غير مضغوط. |
| [EncryptedPayload](../../aspose.pdf/filespecification/encryptedpayload/) { get; } | يحصل على الحمولة المشفرة. |
| [FileSystem](../../aspose.pdf/filespecification/filesystem/) { get; set; } | يحصل أو يعيّن اسم نظام الملفات. |
| [IncludeContents](../../aspose.pdf/filespecification/includecontents/) { get; set; } | إذا كان صحيحًا، سيتم تضمين محتويات الملف في مواصفة الملف. |
| [MIMEType](../../aspose.pdf/filespecification/mimetype/) { get; set; } | يحصل على النوع الفرعي للملف المضمّن |
| [Name](../../aspose.pdf/filespecification/name/) { get; set; } | يحصل أو يعيّن اسم مواصفة الملف. |
| [Params](../../aspose.pdf/filespecification/params/) { get; set; } | يحصل على معلمات الملف. |
| [StreamContents](../../aspose.pdf/filespecification/streamcontents/) { get; } | يحصل على محتويات الملف كدفق. لا يتم تحميل المحتويات في الذاكرة مما يسمح بتقليل استهلاك الذاكرة. لكن هذا الدفق لا يدعم التحديد الموضعية وخصيصة Length. إذا كنت بحاجة إلى هذه الميزات يرجى استخدام خاصية Contents بدلاً من ذلك. |
| [UnicodeName](../../aspose.pdf/filespecification/unicodename/) { get; set; } | يحصل أو يعيّن اسم Unicode لتحديد الملف. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Dispose](../../aspose.pdf/filespecification/dispose/)() | إلغاء المحتويات. |
| [GetValue](../../aspose.pdf/filespecification/getvalue/)(string) | يحصل على المعامل الخاص بالتطبيق. |
| [SetValue](../../aspose.pdf/filespecification/setvalue/)(string, string) | يعيّن المعامل الخاص بالتطبيق. |

### انظر أيضًا

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


