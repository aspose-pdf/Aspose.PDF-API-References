---
title: Class FormEditor
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Facades.FormEditor. فئة لتحرير النماذج وإضافة/حذف الحقول وما إلى ذلك
type: docs
weight: 4330
url: /ar/net/aspose.pdf.facades/formeditor/
---
## فئة محرر النموذج

فئة لتحرير النماذج (إضافة/حذف الحقول وما إلى ذلك)

```csharp
public sealed class FormEditor : SaveableFacade
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [FormEditor](formeditor/#constructor)() | منشئ لفئة محرر النموذج. |
| [FormEditor](formeditor/#constructor_1)(Document) | يقوم بتهيئة كائن `FormEditor` جديد بناءً على *المستند*. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/formeditor/convertto/) { set; } | يحدد تنسيق ملف PDF. سيتم حفظ الملف الناتج بالتنسيق المحدد. إذا لم يتم تحديد هذه الخاصية، فسيتم حفظ الملف بالتنسيق الافتراضي PDF دون تحويل. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | يحصل على واجهة المستند التي يعمل عليها. |
| [ExportItems](../../aspose.pdf.facades/formeditor/exportitems/) { get; set; } | يحدد الخيارات لعنصر القائمة المنسدلة مع قيم التصدير. |
| [Facade](../../aspose.pdf.facades/formeditor/facade/) { get; set; } | يحدد الخصائص المرئية للحقل. |
| [Items](../../aspose.pdf.facades/formeditor/items/) { get; set; } | يحدد العناصر التي ستتم إضافتها إلى مربع القائمة أو القائمة المنسدلة التي تم إنشاؤها حديثًا. |
| [RadioButtonItemSize](../../aspose.pdf.facades/formeditor/radiobuttonitemsize/) { get; set; } | يحصل على أو يحدد حجم عنصر زر الراديو (عند إضافة حقل زر راديو جديد). |
| [RadioGap](../../aspose.pdf.facades/formeditor/radiogap/) { get; set; } | العضو لتسجيل الفجوة بين زري راديو متجاورين بالبكسل، القيمة الافتراضية هي 50. |
| [RadioHoriz](../../aspose.pdf.facades/formeditor/radiohoriz/) { get; set; } | العلامة للإشارة إلى ما إذا كانت الأزرار مرتبة أفقيًا أو عموديًا، القيمة الافتراضية هي true. |
| [SubmitFlag](../../aspose.pdf.facades/formeditor/submitflag/) { get; set; } | تعيين علامات تقديم زر الإرسال |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddField](../../aspose.pdf.facades/formeditor/addfield/#addfield)(FieldType, string, int, float, float, float, float) | إضافة حقل من النوع المحدد إلى النموذج. |
| [AddField](../../aspose.pdf.facades/formeditor/addfield/#addfield_1)(FieldType, string, string, int, float, float, float, float) | إضافة حقل من النوع المحدد إلى النموذج. |
| [AddFieldScript](../../aspose.pdf.facades/formeditor/addfieldscript/)(string, string) | إضافة JavaScript لحقل زر الدفع. إذا كان هناك حدث قديم، يتم إضافة الحدث الجديد بعده. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem/#addlistitem)(string, string) | إضافة عنصر جديد إلى مربع القائمة. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem/#addlistitem_1)(string, string[]) | إضافة عنصر جديد مع قيمة تصدير إلى حقل مربع القائمة الموجود، فقط لحقل القائمة المنسدلة AcroForm. |
| [AddSubmitBtn](../../aspose.pdf.facades/formeditor/addsubmitbtn/)(string, int, string, string, float, float, float, float) | إضافة زر إرسال إلى النموذج. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | يقوم بتهيئة الواجهة. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | يقوم بتهيئة الواجهة. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | يقوم بتهيئة الواجهة. |
| override [Close](../../aspose.pdf.facades/formeditor/close/)() | يغلق الواجهة. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield/#copyinnerfield)(string, string, int) | ينسخ حقلًا موجودًا إلى نفس الموضع في رقم الصفحة المحدد. سيتم إنتاج مستند جديد يحتوي على كل ما يحتويه المستند المصدر باستثناء الحقل المنسوخ حديثًا. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield/#copyinnerfield_1)(string, string, int, float, float) | ينسخ حقلًا موجودًا إلى موضع جديد محدد بواسطة كل من رقم الصفحة والإحداثيات. سيتم إنتاج مستند جديد يحتوي على كل ما يحتويه المستند المصدر باستثناء الحقل المنسوخ حديثًا. |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield)(string, string) | ينسخ حقلًا موجودًا من مستند PDF واحد إلى مستند آخر مع رقم الصفحة الأصلي والإحداثيات. ملاحظة: فقط لحقول AcroForm (باستثناء مربع الراديو). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield_1)(string, string, int) | ينسخ حقلًا موجودًا من مستند PDF واحد إلى مستند آخر مع رقم الصفحة المحدد والإحداثيات الأصلية. ملاحظة: فقط لحقول AcroForm (باستثناء مربع الراديو). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield_2)(string, string, int, float, float) | ينسخ حقلًا موجودًا من مستند PDF واحد إلى مستند آخر مع رقم الصفحة المحدد والإحداثيات. ملاحظة: فقط لحقول AcroForm (باستثناء مربع الراديو). |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield)() | يغير الخصائص المرئية لجميع الحقول في مستند PDF. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield_1)(FieldType) | يغير الخصائص المرئية لجميع الحقول من نوع الحقل المحدد. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield_2)(string) | يغير الخصائص المرئية للحقل المحدد. |
| [DelListItem](../../aspose.pdf.facades/formeditor/dellistitem/)(string, string) | حذف عنصر من حقل القائمة. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | يتخلص من الواجهة. |
| [GetFieldAppearance](../../aspose.pdf.facades/formeditor/getfieldappearance/)(string) | الحصول على علامات الحقل. |
| [MoveField](../../aspose.pdf.facades/formeditor/movefield/)(string, float, float, float, float) | تعيين الموضع الجديد للحقل. |
| [RemoveField](../../aspose.pdf.facades/formeditor/removefield/)(string) | إزالة الحقل من النموذج. |
| [RemoveFieldAction](../../aspose.pdf.facades/formeditor/removefieldaction/)(string) | إزالة إجراء الإرسال للحقل. |
| [RenameField](../../aspose.pdf.facades/formeditor/renamefield/)(string, string) | تغيير اسم الحقل. |
| [ResetFacade](../../aspose.pdf.facades/formeditor/resetfacade/)() | إعادة تعيين جميع الخصائص المرئية إلى قيمة فارغة. |
| [ResetInnerFacade](../../aspose.pdf.facades/formeditor/resetinnerfacade/)() | إعادة تعيين جميع الخصائص المرئية للواجهة الداخلية إلى قيمة فارغة. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | يحفظ مستند PDF إلى التدفق المحدد. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | يحفظ مستند PDF إلى الملف المحدد. |
| [SetFieldAlignment](../../aspose.pdf.facades/formeditor/setfieldalignment/)(string, int) | تعيين نمط المحاذاة لحقل النص. |
| [SetFieldAlignmentV](../../aspose.pdf.facades/formeditor/setfieldalignmentv/)(string, int) | تعيين نمط المحاذاة العمودية لحقل النص. |
| [SetFieldAppearance](../../aspose.pdf.facades/formeditor/setfieldappearance/)(string, AnnotationFlags) | تعيين علامات الحقل |
| [SetFieldAttribute](../../aspose.pdf.facades/formeditor/setfieldattribute/)(string, PropertyFlag) | تعيين خصائص الحقل. |
| [SetFieldCombNumber](../../aspose.pdf.facades/formeditor/setfieldcombnumber/)(string, int) | يحدد عدد الأقسام لحقل نص عادي ذو سطر واحد (يتم تقسيم الحقل تلقائيًا إلى عدد من المواضع المتباعدة بالتساوي، أو الأقسام، كما هو محدد في قيمة معلمة combNumber). |
| [SetFieldLimit](../../aspose.pdf.facades/formeditor/setfieldlimit/)(string, int) | يحدد الحد الأقصى لعدد الأحرف في حقل النص. |
| [SetFieldScript](../../aspose.pdf.facades/formeditor/setfieldscript/)(string, string) | تعيين JavaScript لحقل زر الدفع. إذا كان هناك JavaScript قديم، سيتم استبداله بالجديد. |
| [SetSubmitFlag](../../aspose.pdf.facades/formeditor/setsubmitflag/)(string, SubmitFormFlag) | تعيين علامة الإرسال لزر الإرسال. |
| [SetSubmitUrl](../../aspose.pdf.facades/formeditor/setsubmiturl/)(string, string) | يحدد عنوان URL للزر. |
| [Single2Multiple](../../aspose.pdf.facades/formeditor/single2multiple/)(string) | تغيير حقل نص ذو سطر واحد إلى حقل نص متعدد الأسطر. |

### انظر أيضًا

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)