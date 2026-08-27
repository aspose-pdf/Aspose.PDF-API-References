---
title: "الفئة FormEditor"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Facades.FormEditor. فئة لتعديل النماذج وإضافة/حذف الحقول وما إلى ذلك"
type: docs
weight: 4450
url: /ar/net/aspose.pdf.facades/formeditor/
---
## FormEditor class

فئة لتحرير النماذج (إضافة/حذف الحقول إلخ)

```csharp
public sealed class FormEditor : SaveableFacade
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [FormEditor](formeditor/#constructor)() | منشئ لفئة FormEditor. |
| [FormEditor](formeditor/#constructor_1)(Document) | يُهيئ كائن `FormEditor` جديد على أساس *المستند*. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/formeditor/convertto/) { set; } | يضبط تنسيق ملف PDF. سيتم حفظ الملف الناتج بالتنسيق المحدد. إذا لم يتم تحديد هذه الخاصية، فسيتم حفظ الملف بتنسيق PDF الافتراضي دون تحويل. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | يحصل على واجهة المستند التي يتم العمل عليها. |
| [ExportItems](../../aspose.pdf.facades/formeditor/exportitems/) { get; set; } | يضبط خيارات صندوق القائمة المنسدلة مع قيم التصدير. |
| [Facade](../../aspose.pdf.facades/formeditor/facade/) { get; set; } | يضبط السمات البصرية للحقل. |
| [Items](../../aspose.pdf.facades/formeditor/items/) { get; set; } | يضبط العناصر التي ستُضاف إلى صندوق القائمة أو صندوق القائمة المنسدلة الذي تم إنشاؤه حديثًا. |
| [RadioButtonItemSize](../../aspose.pdf.facades/formeditor/radiobuttonitemsize/) { get; set; } | يحصل أو يضبط حجم عنصر زر الاختيار (عند إضافة حقل زر اختيار جديد). |
| [RadioGap](../../aspose.pdf.facades/formeditor/radiogap/) { get; set; } | العضو لتسجيل الفجوة بين زري اختيار متجاورين بالبكسل، القيمة الافتراضية هي 50. |
| [RadioHoriz](../../aspose.pdf.facades/formeditor/radiohoriz/) { get; set; } | العلم للإشارة إلى ما إذا كانت أزرار الاختيار مرتبة أفقياً أم عمودياً، القيمة الافتراضية هي true. |
| [SubmitFlag](../../aspose.pdf.facades/formeditor/submitflag/) { get; set; } | ضبط أعلام الإرسال لزر الإرسال. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddField](../../aspose.pdf.facades/formeditor/addfield/#addfield)(FieldType, string, int, float, float, float, float) | إضافة حقل من النوع المحدد إلى النموذج. |
| [AddField](../../aspose.pdf.facades/formeditor/addfield/#addfield_1)(FieldType, string, string, int, float, float, float, float) | إضافة حقل من النوع المحدد إلى النموذج. |
| [AddFieldScript](../../aspose.pdf.facades/formeditor/addfieldscript/)(string, string) | إضافة JavaScript لحقل زر ضغط. إذا كان هناك حدث قديم، يُضاف الحدث الجديد بعده. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem/#addlistitem)(string, string) | يضيف عنصرًا جديدًا إلى صندوق القائمة. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem/#addlistitem_1)(string, string[]) | إضافة عنصر جديد بقيمة تصدير إلى حقل صندوق القائمة الموجود، فقط لحقل صندوق القائمة المنسدلة في AcroForm. |
| [AddSubmitBtn](../../aspose.pdf.facades/formeditor/addsubmitbtn/)(string, int, string, string, float, float, float, float) | إضافة زر إرسال إلى النموذج. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | يُهيئ الواجهة. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | يُهيئ الواجهة. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | يُهيئ الواجهة. |
| override [Close](../../aspose.pdf.facades/formeditor/close/)() | يغلق الواجهة. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield/#copyinnerfield)(string, string, int) | ينسخ حقلًا موجودًا إلى نفس الموقع في رقم الصفحة المحدد. سيتم إنشاء مستند جديد يحتوي على كل ما يحتويه المستند الأصلي باستثناء الحقل المنسوخ حديثًا. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield/#copyinnerfield_1)(string, string, int, float, float) | ينسخ حقلًا موجودًا إلى موقع جديد يتم تحديده برقم الصفحة والإحداثيات. سيتم إنشاء مستند جديد يحتوي على كل ما يحتويه المستند الأصلي باستثناء الحقل المنسوخ حديثًا. |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield)(string, string) | ينسخ حقلًا موجودًا من مستند PDF إلى مستند آخر مع رقم الصفحة الأصلي والإحداثيات. ملاحظة: يقتصر على حقول AcroForm (باستثناء صندوق الاختيار). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield_1)(string, string, int) | ينسخ حقلًا موجودًا من مستند PDF إلى مستند آخر مع رقم الصفحة المحدد والإحداثيات الأصلية. ملاحظة: يقتصر على حقول AcroForm (باستثناء صندوق الاختيار). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield_2)(string, string, int, float, float) | ينسخ حقلًا موجودًا من مستند PDF إلى مستند آخر مع رقم الصفحة والإحداثيات المحددة. ملاحظة: يقتصر على حقول AcroForm (باستثناء صندوق الاختيار). |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield)() | يغيّر السمات البصرية لجميع الحقول في مستند PDF. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield_1)(FieldType) | يغيّر السمات البصرية لجميع الحقول ذات النوع المحدد. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield_2)(string) | يغيّر السمات البصرية للحقول المحددة. |
| [DelListItem](../../aspose.pdf.facades/formeditor/dellistitem/)(string, string) | احذف العنصر من حقل القائمة. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | يتخلص من الواجهة. |
| [GetFieldAppearance](../../aspose.pdf.facades/formeditor/getfieldappearance/)(string) | احصل على أعلام الحقل. |
| [MoveField](../../aspose.pdf.facades/formeditor/movefield/)(string, float, float, float, float) | حدد الموقع الجديد للحقول. |
| [RemoveField](../../aspose.pdf.facades/formeditor/removefield/)(string) | أزل الحقل من النموذج. |
| [RemoveFieldAction](../../aspose.pdf.facades/formeditor/removefieldaction/)(string) | أزل إجراء الإرسال للحقول. |
| [RenameField](../../aspose.pdf.facades/formeditor/renamefield/)(string, string) | غيّر اسم الحقل. |
| [ResetFacade](../../aspose.pdf.facades/formeditor/resetfacade/)() | أعد تعيين جميع السمات البصرية إلى قيمة فارغة. |
| [ResetInnerFacade](../../aspose.pdf.facades/formeditor/resetinnerfacade/)() | أعد تعيين جميع السمات البصرية للواجهة الداخلية إلى قيمة فارغة. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | يحفظ مستند PDF إلى الدفق المحدد. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | يحفظ مستند PDF إلى الملف المحدد. |
| [SetFieldAlignment](../../aspose.pdf.facades/formeditor/setfieldalignment/)(string, int) | حدد نمط المحاذاة لحقل النص. |
| [SetFieldAlignmentV](../../aspose.pdf.facades/formeditor/setfieldalignmentv/)(string, int) | حدد نمط المحاذاة العمودية لحقل النص. |
| [SetFieldAppearance](../../aspose.pdf.facades/formeditor/setfieldappearance/)(string, AnnotationFlags) | حدد أعلام الحقل |
| [SetFieldAttribute](../../aspose.pdf.facades/formeditor/setfieldattribute/)(string, PropertyFlag) | حدد سمات الحقل. |
| [SetFieldCombNumber](../../aspose.pdf.facades/formeditor/setfieldcombnumber/)(string, int) | يحدد عدد الأعمدة لحقل نص أحادي السطر عادي (يتم تقسيم الحقل تلقائيًا إلى عدد من المواقع المتساوية المسافة، أو الأعمدة، وفقًا لقيمة معامل combNumber). |
| [SetFieldLimit](../../aspose.pdf.facades/formeditor/setfieldlimit/)(string, int) | يضبط الحد الأقصى لعدد الأحرف لحقل النص. |
| [SetFieldScript](../../aspose.pdf.facades/formeditor/setfieldscript/)(string, string) | تعيين JavaScript لحقل PushButton. إذا كان JavaScript القديم موجودًا، سيتم استبداله بالجديد. |
| [SetSubmitFlag](../../aspose.pdf.facades/formeditor/setsubmitflag/)(string, SubmitFormFlag) | تعيين علامة الإرسال لزر الإرسال. |
| [SetSubmitUrl](../../aspose.pdf.facades/formeditor/setsubmiturl/)(string, string) | يضبط URL للزر. |
| [Single2Multiple](../../aspose.pdf.facades/formeditor/single2multiple/)(string) | تحويل حقل نص أحادي السطر إلى حقل نص متعدد الأسطر. |

### انظر أيضًا

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


