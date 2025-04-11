---
title: Class PdfXmpMetadata
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Facades.PdfXmpMetadata. فئة للتلاعب ببيانات XMP الوصفية
type: docs
weight: 4640
url: /ar/net/aspose.pdf.facades/pdfxmpmetadata/
---
## فئة PdfXmpMetadata

فئة للتلاعب ببيانات XMP الوصفية.

```csharp
public sealed class PdfXmpMetadata : SaveableFacade, IDictionary<string, XmpValue>
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PdfXmpMetadata](pdfxmpmetadata/#constructor)() | منشئ لفئة PdfXmpMetadata. |
| [PdfXmpMetadata](pdfxmpmetadata/#constructor_1)(Document) | يقوم بتهيئة كائن `PdfXmpMetadata` جديد بناءً على *المستند*. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Count](../../aspose.pdf.facades/pdfxmpmetadata/count/) { get; } | يحصل على عدد العناصر في المجموعة. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | يحصل على واجهة المستند التي يعمل عليها. |
| [ExtensionFields](../../aspose.pdf.facades/pdfxmpmetadata/extensionfields/) { get; } | يحصل على قاموس الحقول الإضافية. |
| [IsFixedSize](../../aspose.pdf.facades/pdfxmpmetadata/isfixedsize/) { get; } | يعيد true إذا كانت المجموعة ذات حجم ثابت. |
| [IsReadOnly](../../aspose.pdf.facades/pdfxmpmetadata/isreadonly/) { get; } | يعيد true إذا كانت المجموعة للقراءة فقط. |
| [IsSynchronized](../../aspose.pdf.facades/pdfxmpmetadata/issynchronized/) { get; } | يعيد true إذا كانت المجموعة متزامنة. |
| [Item](../../aspose.pdf.facades/pdfxmpmetadata/item/) { get; set; } | يحصل أو يحدد القيمة حسب المفتاح. (2 فهرس) |
| [Keys](../../aspose.pdf.facades/pdfxmpmetadata/keys/) { get; } | يحصل على المفاتيح من القاموس. |
| [SyncRoot](../../aspose.pdf.facades/pdfxmpmetadata/syncroot/) { get; } | يحصل على كائن التزامن للمجموعة. |
| [Values](../../aspose.pdf.facades/pdfxmpmetadata/values/) { get; } | يحصل على مجموعة القيم في القاموس. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_2)(KeyValuePair&lt;string, XmpValue&gt;) | يضيف زوجًا مع مفتاح وقيمة إلى القاموس. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add)(DefaultMetadataProperties, XmpValue) | يضيف قيمة إلى بيانات XMP الوصفية. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_4)(string, object) | يضيف عنصرًا جديدًا إلى كائن القاموس. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_3)(string, XmpValue) | يضيف عنصرًا جديدًا إلى كائن القاموس. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_1)(XmpPdfAExtensionObject, string, string, string) | يضيف حقلًا إضافيًا إلى البيانات الوصفية. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | يقوم بتهيئة الواجهة. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | يقوم بتهيئة الواجهة. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | يقوم بتهيئة الواجهة. |
| [Clear](../../aspose.pdf.facades/pdfxmpmetadata/clear/)() | يزيل جميع العناصر من الكائن. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | يتخلص من Aspose.Pdf.Document المرتبط بواجهة. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains)(DefaultMetadataProperties) | يتحقق مما إذا كان القاموس يحتوي على الخاصية المحددة. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains_1)(KeyValuePair&lt;string, XmpValue&gt;) | يتحقق مما إذا كانت زوج المفتاح والقيمة المحدد موجودًا في القاموس. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains_2)(string) | يتحقق مما إذا كان القاموس يحتوي على المفتاح المحدد. |
| [ContainsKey](../../aspose.pdf.facades/pdfxmpmetadata/containskey/)(string) | يحدد ما إذا كان هذا القاموس يحتوي على المفتاح المحدد. |
| [CopyTo](../../aspose.pdf.facades/pdfxmpmetadata/copyto/)(KeyValuePair&lt;string, XmpValue&gt;[], int) |  |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | يتخلص من الواجهة. |
| [GetEnumerator](../../aspose.pdf.facades/pdfxmpmetadata/getenumerator/)() | يحصل على كائن العدّاد للقاموس. |
| [GetNamespaceURIByPrefix](../../aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/)(string) | يحصل على URI المساحة الاسمية حسب البادئة. |
| [GetPrefixByNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/)(string) | يحصل على البادئة حسب URI المساحة الاسمية. |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/#getxmpmetadata)() | يحصل على بيانات XmpMetadata من ملف PDF المدخل بتنسيق XML. |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/#getxmpmetadata_1)(string) | يحصل على جزء من بيانات XmpMetadata من ملف PDF المدخل وفقًا لاسم البيانات الوصفية. |
| [RegisterNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/)(string, string) | يسجل URI المساحة الاسمية. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove_2)(DefaultMetadataProperties) | يزيل العنصر بالمفتاح المحدد. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove)(KeyValuePair&lt;string, XmpValue&gt;) | يزيل زوج المفتاح/القيمة من المجموعة. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove_1)(string) | يزيل المفتاح من القاموس. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | يحفظ مستند PDF إلى التدفق المحدد. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | يحفظ مستند PDF إلى الملف المحدد. |
| [TryGetValue](../../aspose.pdf.facades/pdfxmpmetadata/trygetvalue/)(string, out XmpValue) | يحاول العثور على المفتاح في القاموس ويسترجع القيمة إذا تم العثور عليها. |

### انظر أيضًا

* فئة [SaveableFacade](../saveablefacade/)
* فئة [XmpValue](../../aspose.pdf/xmpvalue/)
* مساحة الأسماء [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* التجميع [Aspose.PDF](../../)