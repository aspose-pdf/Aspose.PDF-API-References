---
title: PdfXmpMetadata
second_title: Aspose.PDF لمرجع .NET API
description: فئة للتلاعب ببيانات تعريف XMP .
type: docs
weight: 2650
url: /ar/net/aspose.pdf.facades/pdfxmpmetadata/
---
## PdfXmpMetadata class

فئة للتلاعب ببيانات تعريف XMP .

```csharp
public sealed class PdfXmpMetadata : SaveableFacade, IDictionary<string, XmpValue>
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [PdfXmpMetadata](pdfxmpmetadata#constructor)() | مُنشئ PdfXmpMetadata. |
| [PdfXmpMetadata](pdfxmpmetadata#constructor_1)(Document) | تهيئة جديد[`PdfXmpMetadata`](../pdfxmpmetadata) كائن على قاعدة*document* . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Count](../../aspose.pdf.facades/pdfxmpmetadata/count) { get; } | يتم احتسابه إذا كانت العناصر في المجموعة. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | الحصول على واجهة المستند التي تعمل عليها. |
| [ExtensionFields](../../aspose.pdf.facades/pdfxmpmetadata/extensionfields) { get; } | يحصل على قاموس حقول الامتداد. |
| [IsFixedSize](../../aspose.pdf.facades/pdfxmpmetadata/isfixedsize) { get; } | المرتجعات صحيحة هي أن المجموعة لها حجم ثابت . |
| [IsReadOnly](../../aspose.pdf.facades/pdfxmpmetadata/isreadonly) { get; } | إرجاع صحيح إذا كانت المجموعة للقراءة فقط. |
| [IsSynchronized](../../aspose.pdf.facades/pdfxmpmetadata/issynchronized) { get; } | يعود صحيحًا إذا تمت مزامنة المجموعة . |
| [Item](../../aspose.pdf.facades/pdfxmpmetadata/item) { get; set; } | الحصول على القيمة أو تحديدها بالمفتاح . (2 indexers) |
| [Keys](../../aspose.pdf.facades/pdfxmpmetadata/keys) { get; } | يحصل على مفاتيح من القاموس . |
| [SyncRoot](../../aspose.pdf.facades/pdfxmpmetadata/syncroot) { get; } | الحصول على كائن التزامن للمجموعة. |
| [Values](../../aspose.pdf.facades/pdfxmpmetadata/values) { get; } | الحصول على مجموعة القيم في القاموس. |

## طُرق

| اسم | وصف |
| --- | --- |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add#add_2)(KeyValuePair&lt;string, XmpValue&gt;) | إضافة زوج بالمفتاح والقيمة إلى القاموس. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add#add)(DefaultMetadataProperties, XmpValue) | إضافة قيمة إلى بيانات تعريف XMP . |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add#add_4)(string, object) | إضافة عنصر جديد إلى كائن القاموس. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add#add_3)(string, XmpValue) | إضافة عنصر جديد إلى كائن القاموس. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add#add_1)(XmpPdfAExtensionObject, string, string, string) | يتم إضافة حقل الامتداد إلى البيانات الوصفية . |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | تهيئة الواجهة . |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | تهيئة الواجهة . |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | تهيئة الواجهة . |
| [Clear](../../aspose.pdf.facades/pdfxmpmetadata/clear)() | يزيل كل العناصر من الكائن. |
| virtual [Close](../../aspose.pdf.facades/facade/close)() | Disposes Aspose.Pdf. وثيقة مرتبطة بواجهة . |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains#contains)(DefaultMetadataProperties) | التحقق مما إذا كان القاموس يحتوي على الخاصية المحددة. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains#contains_1)(KeyValuePair&lt;string, XmpValue&gt;) | الشيكات لا يتم تضمين زوج قيمة مفتاح محدد في القاموس. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains#contains_2)(string) | للتحقق مما إذا كان القاموس يحتوي على المفتاح المحدد. |
| [ContainsKey](../../aspose.pdf.facades/pdfxmpmetadata/containskey)(string) | يحدد هل يحتوي هذا القاموس على مفتاح محدد. |
| [CopyTo](../../aspose.pdf.facades/pdfxmpmetadata/copyto)(KeyValuePair&lt;string, XmpValue&gt;[], int) |  |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | التخلص من الواجهة . |
| [GetEnumerator](../../aspose.pdf.facades/pdfxmpmetadata/getenumerator)() | الحصول على كائن العداد للقاموس. |
| [GetNamespaceURIByPrefix](../../aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix)(string) | يحصل على مساحة الاسم URI بالبادئة . |
| [GetPrefixByNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri)(string) | يحصل على البادئة بواسطة مساحة الاسم URI. |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata#getxmpmetadata)() | احصل على XmpMetadata لملف pdf بتنسيق xml. |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata#getxmpmetadata_1)(string) | احصل على جزء من XmpMetadata لملف pdf وفقًا لاسم التعريف. |
| [RegisterNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri)(string, string) | يسجل معرف مساحة الاسم URI. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove#remove_2)(DefaultMetadataProperties) | يزيل العنصر بالمفتاح المحدد . |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove#remove)(KeyValuePair&lt;string, XmpValue&gt;) | يزيل زوج المفتاح / القيمة من المجموعة. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove#remove_1)(string) | إزالة المفتاح من القاموس. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | يحفظ مستند PDF في التدفق المحدد. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | يحفظ مستند PDF في الملف المحدد. |
| [TryGetValue](../../aspose.pdf.facades/pdfxmpmetadata/trygetvalue)(string, out XmpValue) | يحاول العثور على مفتاح في القاموس ويستعيد القيمة إذا تم العثور عليه. |

### أنظر أيضا

* class [SaveableFacade](../saveablefacade)
* class [XmpValue](../../aspose.pdf/xmpvalue)
* مساحة الاسم [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
