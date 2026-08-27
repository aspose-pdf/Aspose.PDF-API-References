---
title: "الفئة PdfXmpMetadata"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Facades.PdfXmpMetadata. فئة للتعامل مع بيانات XMP الوصفية"
type: docs
weight: 4760
url: /ar/net/aspose.pdf.facades/pdfxmpmetadata/
---
## PdfXmpMetadata class

فئة للتعامل مع بيانات XMP الوصفية.

```csharp
public sealed class PdfXmpMetadata : SaveableFacade, IDictionary<string, XmpValue>
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PdfXmpMetadata](pdfxmpmetadata/#constructor)() | منشئ لفئة PdfXmpMetadata. |
| [PdfXmpMetadata](pdfxmpmetadata/#constructor_1)(Document) | يُنشئ كائنًا جديدًا `PdfXmpMetadata` بناءً على *المستند*. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Count](../../aspose.pdf.facades/pdfxmpmetadata/count/) { get; } | يحصل على عدد العناصر في المجموعة. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | يحصل على واجهة المستند التي يتم العمل عليها. |
| [ExtensionFields](../../aspose.pdf.facades/pdfxmpmetadata/extensionfields/) { get; } | يحصل على القاموس الخاص بحقول الامتداد. |
| [IsFixedSize](../../aspose.pdf.facades/pdfxmpmetadata/isfixedsize/) { get; } | يرجع true إذا كانت المجموعة ذات حجم ثابت. |
| [IsReadOnly](../../aspose.pdf.facades/pdfxmpmetadata/isreadonly/) { get; } | يرجع true إذا كانت المجموعة للقراءة فقط. |
| [IsSynchronized](../../aspose.pdf.facades/pdfxmpmetadata/issynchronized/) { get; } | يرجع true إذا كانت المجموعة متزامنة. |
| [Item](../../aspose.pdf.facades/pdfxmpmetadata/item/) { get; set; } | يحصل أو يعيّن القيمة حسب المفتاح. (مؤشرين) |
| [Keys](../../aspose.pdf.facades/pdfxmpmetadata/keys/) { get; } | يحصل على المفاتيح من القاموس. |
| [SyncRoot](../../aspose.pdf.facades/pdfxmpmetadata/syncroot/) { get; } | يحصل على كائن المزامنة للمجموعة. |
| [Values](../../aspose.pdf.facades/pdfxmpmetadata/values/) { get; } | يحصل على مجموعة القيم في القاموس. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_2)(KeyValuePair&lt;string, XmpValue&gt;) | يضيف زوجًا من المفتاح والقيمة إلى القاموس. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add)(DefaultMetadataProperties, XmpValue) | يضيف قيمة إلى بيانات XMP الوصفية. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_4)(string, object) | يضيف عنصرًا جديدًا إلى كائن القاموس. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_3)(string, XmpValue) | يضيف عنصرًا جديدًا إلى كائن القاموس. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_1)(XmpPdfAExtensionObject, string, string, string) | يضيف حقل امتداد إلى البيانات الوصفية. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | يُهيئ الواجهة. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | يُهيئ الواجهة. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | يُهيئ الواجهة. |
| [Clear](../../aspose.pdf.facades/pdfxmpmetadata/clear/)() | يزيل جميع العناصر من الكائن. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | يفرغ Aspose.Pdf.Document المرتبط بواجهة. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains)(DefaultMetadataProperties) | يتحقق مما إذا كان القاموس يحتوي على الخاصية المحددة. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains_1)(KeyValuePair&lt;string, XmpValue&gt;) | يتحقق مما إذا كان زوج المفتاح-القيمة المحدد موجودًا في القاموس. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains_2)(string) | يتحقق مما إذا كان القاموس يحتوي على المفتاح المحدد. |
| [ContainsKey](../../aspose.pdf.facades/pdfxmpmetadata/containskey/)(string) | يحدد ما إذا كان هذا القاموس يحتوي على المفتاح المحدد. |
| [CopyTo](../../aspose.pdf.facades/pdfxmpmetadata/copyto/)(KeyValuePair&lt;string, XmpValue&gt;[], int) |  |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | يتخلص من الواجهة. |
| [GetEnumerator](../../aspose.pdf.facades/pdfxmpmetadata/getenumerator/)() | يحصل على كائن المُعدِّد للقاموس. |
| [GetNamespaceURIByPrefix](../../aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/)(string) | يحصل على URI للمساحة الاسمية حسب البادئة. |
| [GetPrefixByNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/)(string) | يحصل على البادئة حسب URI للمساحة الاسمية. |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/#getxmpmetadata)() | احصل على XmpMetadata لملف pdf المدخل بصيغة xml. |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/#getxmpmetadata_1)(string) | احصل على جزء من XmpMetadata لملف pdf المدخل وفقًا لاسم ميتا. |
| [RegisterNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/)(string, string) | يسجّل URI للمساحة الاسمية. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove_2)(DefaultMetadataProperties) | يزيل العنصر بالمفتاح المحدد. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove)(KeyValuePair&lt;string, XmpValue&gt;) | يزيل زوج المفتاح/القيمة من المجموعة. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove_1)(string) | يزيل المفتاح من القاموس. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | يحفظ مستند PDF إلى الدفق المحدد. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | يحفظ مستند PDF إلى الملف المحدد. |
| [TryGetValue](../../aspose.pdf.facades/pdfxmpmetadata/trygetvalue/)(string, out XmpValue) | يحاول العثور على المفتاح في القاموس ويسترجع القيمة إذا وُجد. |

### انظر أيضًا

* class [SaveableFacade](../saveablefacade/)
* class [XmpValue](../../aspose.pdf/xmpvalue/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


