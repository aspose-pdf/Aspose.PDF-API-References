---
title: Class FileSpecification
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.FileSpecification. فئة تمثل الملف المضمن
type: docs
weight: 4850
url: /ar/net/aspose.pdf/filespecification/
---
## FileSpecification class

فئة تمثل الملف المضمن.

```csharp
public sealed class FileSpecification : IDisposable
```

## Constructors

| Name | Description |
| --- | --- |
| [FileSpecification](filespecification/#constructor)() | إنشاء مواصفة ملف فارغة جديدة. |
| [FileSpecification](filespecification/#constructor_3)(string) | مُنشئ لفئة FileSpecification |
| [FileSpecification](filespecification/#constructor_1)(Stream, string) | مُنشئ لمواصفة الملف. |
| [FileSpecification](filespecification/#constructor_4)(string, Annotation) | مُنشئ لفئة FileSpecification. |
| [FileSpecification](filespecification/#constructor_5)(string, string) | مُنشئ لفئة FileSpecification. |
| [FileSpecification](filespecification/#constructor_2)(Stream, string, string) | مُنشئ لفئة FileSpecification. |

## Properties

| Name | Description |
| --- | --- |
| [AFRelationship](../../aspose.pdf/filespecification/afrelationship/) { get; set; } | علاقة الملف المرتبطة. |
| [CollectionItem](../../aspose.pdf/filespecification/collectionitem/) { get; } | يحصل على عنصر مجموعة من مواصفة الملف. |
| [Contents](../../aspose.pdf/filespecification/contents/) { get; set; } | يحصل أو يحدد محتويات الملف. هذه الخاصية تعيد البيانات المحملة في الذاكرة والتي قد تسبب استثناء نفاد الذاكرة للبيانات الكبيرة. لتقليل استخدام الذاكرة، يرجى استخدام StreamContents. |
| [Description](../../aspose.pdf/filespecification/description/) { get; set; } | يحصل أو يحدد النص المرتبط بمواصفة الملف. |
| [Encoding](../../aspose.pdf/filespecification/encoding/) { get; set; } | يحصل أو يحدد تنسيق الترميز. القيم الممكنة: Zip - الملف مضغوط باستخدام ZIP، None - الملف غير مضغوط. |
| [EncryptedPayload](../../aspose.pdf/filespecification/encryptedpayload/) { get; } | يحصل على الحمولة المشفرة. |
| [FileSystem](../../aspose.pdf/filespecification/filesystem/) { get; set; } | يحصل أو يحدد اسم نظام الملفات. |
| [IncludeContents](../../aspose.pdf/filespecification/includecontents/) { get; set; } | إذا كانت صحيحة، سيتم تضمين محتويات الملف في مواصفة الملف. |
| [MIMEType](../../aspose.pdf/filespecification/mimetype/) { get; set; } | يحصل على نوع فرعي من الملف المضمن |
| [Name](../../aspose.pdf/filespecification/name/) { get; set; } | يحصل أو يحدد اسم مواصفة الملف. |
| [Params](../../aspose.pdf/filespecification/params/) { get; set; } | يحصل على معلمات الملف. |
| [StreamContents](../../aspose.pdf/filespecification/streamcontents/) { get; } | يحصل على محتويات الملف كتيار. المحتويات لا تُحمّل في الذاكرة مما يسمح بتقليل استخدام الذاكرة. لكن هذا التيار لا يدعم التمركز وخصائص الطول. إذا كنت بحاجة إلى هذه الميزات، يرجى استخدام خاصية Contents بدلاً من ذلك. |
| [UnicodeName](../../aspose.pdf/filespecification/unicodename/) { get; set; } | يحصل أو يحدد اسم مواصفة الملف بالترميز الموحد. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.pdf/filespecification/dispose/)() | التخلص من المحتويات. |
| [GetValue](../../aspose.pdf/filespecification/getvalue/)(string) | يحصل على معلمة محددة للتطبيق. |
| [SetValue](../../aspose.pdf/filespecification/setvalue/)(string, string) | يحدد معلمة محددة للتطبيق. |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)