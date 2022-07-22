---
title: FormEditor
second_title: Aspose.PDF لمرجع .NET API
description: فئة لتحرير النماذج حقل ading / حذف إلخ
type: docs
weight: 2340
url: /ar/net/aspose.pdf.facades/formeditor/
---
## FormEditor class

فئة لتحرير النماذج (حقل ading / حذف إلخ)

```csharp
public sealed class FormEditor : SaveableFacade
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [FormEditor](formeditor#constructor)() | مُنشئ FormEditor. |
| [FormEditor](formeditor#constructor_1)(Document) | تهيئة جديد[`FormEditor`](../formeditor) كائن على قاعدة*document* . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AttachmentName](../../aspose.pdf.facades/formeditor/attachmentname) { get; set; } | الحصول على اسم المرفق أو تعيينه عند تخزين نتيجة العملية في كائنات HttpResponse كمرفق. |
| [ContentDisposition](../../aspose.pdf.facades/formeditor/contentdisposition) { get; set; } | الحصول على أو تعيين كيفية تخزين المحتوى عند تخزين نتيجة العملية في كائن HttpResponse. القيمة المحتملة: مضمنة / مرفق . الافتراضي: مضمنة . |
| [ConvertTo](../../aspose.pdf.facades/formeditor/convertto) { set; } | يحدد تنسيق ملف PDF. سيتم حفظ الملف الناتج في تنسيق الملف المحدد. إذا لم يتم تحديد هذه الخاصية ، فسيتم حفظ الملف بتنسيق PDF الافتراضي بدون تحويل. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | الحصول على واجهة المستند التي تعمل عليها. |
| [ExportItems](../../aspose.pdf.facades/formeditor/exportitems) { get; set; } | يعيّن الخيارات لمربع التحرير والسرد بقيم التصدير. |
| [Facade](../../aspose.pdf.facades/formeditor/facade) { get; set; } | يعين السمات المرئية للحقل. |
| [Items](../../aspose.pdf.facades/formeditor/items) { get; set; } | تعيين العناصر التي ستتم إضافتها إلى مربع قائمة أو مربع تحرير وسرد تم إنشاؤه حديثًا. |
| [RadioButtonItemSize](../../aspose.pdf.facades/formeditor/radiobuttonitemsize) { get; set; } | الحصول على أو تعيين حجم عنصر زر الاختيار (عند إضافة حقل زر اختيار جديد). |
| [RadioGap](../../aspose.pdf.facades/formeditor/radiogap) { get; set; } | العضو الذي يقوم بتسجيل الفجوة بين زري اختيار متجاورين بالبكسل ، الافتراضي هو 50. |
| [RadioHoriz](../../aspose.pdf.facades/formeditor/radiohoriz) { get; set; } | العلامة للإشارة إلى ما إذا كانت أجهزة الراديو مرتبة أفقياً أم رأسياً ، والقيمة الافتراضية هي true . |
| [Response](../../aspose.pdf.facades/formeditor/response) { get; set; } | الحصول على كائن الاستجابة أو تعيينه حيث يتم تخزين نتيجة العملية. |
| [SaveOptions](../../aspose.pdf.facades/formeditor/saveoptions) { get; set; } | الحصول على أو تعيين خيارات الحفظ عند تخزين النتيجة كـ HttpResponse. القيمة الافتراضية: PdfSaveOptions. |
| [SubmitFlag](../../aspose.pdf.facades/formeditor/submitflag) { get; set; } | تعيين أعلام إرسال زر الإرسال |

## طُرق

| اسم | وصف |
| --- | --- |
| [AddField](../../aspose.pdf.facades/formeditor/addfield#addfield)(FieldType, string, int, float, float, float, float) | أضف حقل من النوع المحدد إلى النموذج . |
| [AddField](../../aspose.pdf.facades/formeditor/addfield#addfield_1)(FieldType, string, string, int, float, float, float, float) | أضف حقل من النوع المحدد إلى النموذج . |
| [AddFieldScript](../../aspose.pdf.facades/formeditor/addfieldscript)(string, string) | أضف JavaScript لحقل PushButton. في حالة وجود حدث قديم ، تتم إضافة حدث جديد بعده. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem#addlistitem)(string, string) | إضافة عنصر جديد إلى مربع القائمة. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem#addlistitem_1)(string, string[]) | أضف عنصرًا جديدًا بقيمة تصدير إلى حقل مربع القائمة الحالي ، فقط لحقل مربع التحرير والسرد AcroForm. |
| [AddSubmitBtn](../../aspose.pdf.facades/formeditor/addsubmitbtn)(string, int, string, string, float, float, float, float) | أضف زر الإرسال في النموذج . |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | تهيئة الواجهة . |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | تهيئة الواجهة . |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | تهيئة الواجهة . |
| override [Close](../../aspose.pdf.facades/formeditor/close)() | إغلاق الواجهة . |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield#copyinnerfield)(string, string, int) | نسخ حقل موجود إلى نفس الموضع في رقم الصفحة المحدد. سيتم إنتاج مستند جديد يحتوي على كل شيء في المستند المصدر باستثناء الحقل المنسوخ حديثًا. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield#copyinnerfield_1)(string, string, int, float, float) | نسخ حقل موجود إلى موضع جديد محدد بواسطة كل من رقم الصفحة والإحداثيات. سيتم إنتاج مستند جديد يحتوي على كل شيء يحتويه المستند المصدر باستثناء الحقل المنسوخ حديثًا. |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield#copyouterfield)(string, string) | ينسخ حقل موجود من مستند PDF إلى مستند آخر برقم الصفحة الأصلي والإحداثيات. إشعار: فقط لحقول AcroForm (باستثناء مربع الراديو) . |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield#copyouterfield_1)(string, string, int) | ينسخ حقل موجود من مستند PDF إلى مستند آخر برقم صفحة محدد وإحداثيات أصلية. إشعار: فقط لحقول AcroForm (باستثناء مربع الراديو). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield#copyouterfield_2)(string, string, int, float, float) | ينسخ حقل موجود من مستند PDF إلى مستند آخر برقم الصفحة المحدد والإحداثيات. إشعار: فقط لحقول AcroForm (باستثناء مربع الراديو) . |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield#decoratefield)() | يغير السمات المرئية لجميع الحقول في مستند PDF. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield#decoratefield_1)(FieldType) | يغير السمات المرئية لجميع الحقول بنوع الحقل المحدد. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield#decoratefield_2)(string) | تغيير السمات المرئية للحقل المحدد. |
| [DelListItem](../../aspose.pdf.facades/formeditor/dellistitem)(string, string) | حذف عنصر من حقل القائمة. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | التخلص من الواجهة . |
| [GetFieldAppearance](../../aspose.pdf.facades/formeditor/getfieldappearance)(string) | احصل على إشارات المجال. |
| [MoveField](../../aspose.pdf.facades/formeditor/movefield)(string, float, float, float, float) | تعيين موضع حقل جديد . |
| [RemoveField](../../aspose.pdf.facades/formeditor/removefield)(string) | إزالة الحقل من النموذج . |
| [RemoveFieldAction](../../aspose.pdf.facades/formeditor/removefieldaction)(string) | إزالة إجراء الإرسال من الحقل . |
| [RenameField](../../aspose.pdf.facades/formeditor/renamefield)(string, string) | تغيير اسم الحقل . |
| [ResetFacade](../../aspose.pdf.facades/formeditor/resetfacade)() | إعادة تعيين كافة السمات المرئية إلى قيمة فارغة. |
| [ResetInnerFacade](../../aspose.pdf.facades/formeditor/resetinnerfacade)() | إعادة تعيين كافة السمات المرئية للواجهة الداخلية إلى قيمة فارغة. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | يحفظ مستند PDF في التدفق المحدد. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | يحفظ مستند PDF في الملف المحدد. |
| [SetFieldAlignment](../../aspose.pdf.facades/formeditor/setfieldalignment)(string, int) | تعيين نمط المحاذاة لحقل نصي. |
| [SetFieldAlignmentV](../../aspose.pdf.facades/formeditor/setfieldalignmentv)(string, int) | تعيين نمط المحاذاة الرأسية لحقل نصي. |
| [SetFieldAppearance](../../aspose.pdf.facades/formeditor/setfieldappearance)(string, AnnotationFlags) | تعيين أعلام الحقول |
| [SetFieldAttribute](../../aspose.pdf.facades/formeditor/setfieldattribute)(string, PropertyFlag) | تعيين سمات الحقل. |
| [SetFieldCombNumber](../../aspose.pdf.facades/formeditor/setfieldcombnumber)(string, int) | تعيين عدد الأمشاط لحقل نصي أحادي السطر (الحقل مقسم تلقائيًا إلى العديد من المواضع أو الأمشاط المتباعدة بشكل متساوٍ ، كقيمة معلمة combNumber) . |
| [SetFieldLimit](../../aspose.pdf.facades/formeditor/setfieldlimit)(string, int) | تعيين الحد الأقصى لعدد الأحرف في حقل النص. |
| [SetFieldScript](../../aspose.pdf.facades/formeditor/setfieldscript)(string, string) | قم بتعيين JavaScript لحقل PushButton. في حالة وجود JavaScript قديم ، سيتم استبداله بالجديد. |
| [SetSubmitFlag](../../aspose.pdf.facades/formeditor/setsubmitflag)(string, SubmitFormFlag) | تعيين زر إرسال العلم. |
| [SetSubmitUrl](../../aspose.pdf.facades/formeditor/setsubmiturl)(string, string) | يعين URL للزر . |
| [Single2Multiple](../../aspose.pdf.facades/formeditor/single2multiple)(string) | قم بتغيير حقل نص أحادي السطر إلى حقل متعدد الأسطر. |

### أنظر أيضا

* class [SaveableFacade](../saveablefacade)
* مساحة الاسم [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
