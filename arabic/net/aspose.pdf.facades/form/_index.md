---
title: Form
second_title: Aspose.PDF لمرجع .NET API
description: فئة تمثل كائن نموذج Acro .
type: docs
weight: 2300
url: /ar/net/aspose.pdf.facades/form/
---
## Form class

فئة تمثل كائن نموذج Acro .

```csharp
public sealed class Form : SaveableFacade
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [Form](form#constructor)() | مُنشئ النموذج بدون معلمات. |
| [Form](form#constructor_1)(Document) | تهيئة جديد[`Form`](../form) كائن على قاعدة*document* . |
| [Form](form#constructor_4)(Stream) | مُنشئ النموذج . |
| [Form](form#constructor_8)(string) | منشئ النموذج . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AttachmentName](../../aspose.pdf.facades/form/attachmentname) { get; set; } | الحصول على اسم المرفق أو تعيينه عند تخزين نتيجة العملية في كائنات HttpResponse كمرفق. |
| [ContentDisposition](../../aspose.pdf.facades/form/contentdisposition) { get; set; } | الحصول على أو تعيين كيفية تخزين المحتوى عند تخزين نتيجة العملية في كائن HttpResponse. القيمة المحتملة: مضمنة / مرفق . الافتراضي: مضمنة . |
| [ConvertTo](../../aspose.pdf.facades/form/convertto) { set; } | يحدد تنسيق ملف PDF. سيتم حفظ الملف الناتج في تنسيق الملف المحدد. إذا لم يتم تحديد هذه الخاصية ، فسيتم حفظ الملف بتنسيق PDF الافتراضي بدون تحويل. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | الحصول على واجهة المستند التي تعمل عليها. |
| [FieldNames](../../aspose.pdf.facades/form/fieldnames) { get; } | الحصول على قائمة بأسماء الحقول في النموذج . |
| [FormSubmitButtonNames](../../aspose.pdf.facades/form/formsubmitbuttonnames) { get; } | يحصل على جميع أسماء أزرار إرسال النموذج . |
| [ImportResult](../../aspose.pdf.facades/form/importresult) { get; } | نتيجة آخر عملية استيراد. مصفوفة من الكائنات التي وصفت نتيجة الاستيراد لكل حقل. |
| [Response](../../aspose.pdf.facades/form/response) { get; set; } | الحصول على كائن الاستجابة أو تعيينه حيث يتم تخزين نتيجة العملية. |
| [SaveOptions](../../aspose.pdf.facades/form/saveoptions) { get; set; } | الحصول على أو تعيين خيارات الحفظ عند تخزين النتيجة كـ HttpResponse. القيمة الافتراضية: PdfSaveOptions. |

## طُرق

| اسم | وصف |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | تهيئة الواجهة . |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | تهيئة الواجهة . |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | تهيئة الواجهة . |
| override [Close](../../aspose.pdf.facades/form/close)() | إغلاق الملفات المفتوحة دون أي تغييرات. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | التخلص من الواجهة . |
| [ExportFdf](../../aspose.pdf.facades/form/exportfdf)(Stream) | يصدر محتوى حقول pdf إلى تيار fdf. |
| [ExportXfdf](../../aspose.pdf.facades/form/exportxfdf)(Stream) | يصدر محتوى حقول ملف pdf إلى تيار xml . لن يتم تصدير قيمة حقل الزر. |
| [ExportXml](../../aspose.pdf.facades/form/exportxml)(Stream) | يصدر محتوى حقول ملف pdf إلى تيار xml . لن يتم تصدير قيمة حقل الزر. |
| [ExtractXfaData](../../aspose.pdf.facades/form/extractxfadata)(Stream) | استخراج حزمة بيانات XFA |
| [FillBarcodeField](../../aspose.pdf.facades/form/fillbarcodefield)(string, string) | املأ حقل الباركود وفقًا لاسم الحقل المؤهل بالكامل. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield)(string, bool) | يملأ حقل خانة الاختيار بقيمة منطقية. ملاحظة: يتم تطبيقه على خانة الاختيار فقط. يرجى ملاحظة أن Aspose.Pdf.Facades يدعم أسماء الحقول الكاملة فقط ولا يعمل مع أسماء الحقول الجزئية على عكس Aspose.Pdf .Kit على سبيل المثال إذا كان الحقل يحتوي على الاسم الكامل "Form.Subform.CheckBoxField" ، يجب عليك تحديد الاسم الكامل وليس "CheckBoxField". يمكنك استخدام خاصية أسماء الحقول لاستكشاف أسماء الحقول الموجودة والبحث في الحقل المطلوب باسمه الجزئي. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield_1)(string, int) | يملأ حقل مربع الراديو بقيمة فهرس صالحة وفقًا لاسم حقل مؤهل بالكامل. قبل ملء الحقول ، يجب معرفة اسم الحقل فقط. بينما يمكن تحديد القيمة من خلال فهرسها. إشعار: يتم تطبيقه فقط على حقول Radio Box و Combo Box و List Box . يرجى ملاحظة أن Aspose.Pdf.Facades يدعم أسماء الحقول الكاملة فقط ولا يعمل مع أسماء الحقول الجزئية على النقيض من Aspose.Pdf.Kit على سبيل المثال إذا كان الحقل يحتوي على الاسم الكامل "Form.Subform.ListBoxField" يجب عليك تحديد الاسم الكامل وليس "ListBoxField". يمكنك استخدام خاصية أسماء الحقول لاستكشاف أسماء الحقول الموجودة والبحث في الحقل المطلوب باسمه الجزئي. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield_2)(string, string) | يملأ الحقل بقيمة صالحة وفقًا لاسم حقل مؤهل بالكامل. قبل ملء الحقول ، يجب معرفة أسماء كل حقل والقيم الصالحة المقابلة له. كل من اسم الحقول وقيمها حساسة لحالة الأحرف. Aspose.Pdf.Facades يدعم أسماء الحقول الكاملة فقط ولا يعمل مع أسماء الحقول الجزئية على عكس Aspose.Pdf.Kit على سبيل المثال إذا كان الحقل يحتوي على الاسم الكامل "Form.Subform.TextField" ، يجب عليك تحديد الاسم الكامل وليس "مجال التحرير مكان كتابة النص". يمكنك استخدام خاصية أسماء الحقول لاستكشاف أسماء الحقول الموجودة والبحث في الحقل المطلوب باسمه الجزئي. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield_4)(string, string[]) | قم بتعبئة الحقل بالعديد من التحديدات. ملاحظة: فقط لحقل قائمة AcroForm . |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield_3)(string, string, bool) | يملأ الحقل بقيمة محددة. |
| [FillFields](../../aspose.pdf.facades/form/fillfields)(string[], string[], out Stream) | يملأ حقول مربع النص بقيم نصية ويحفظ المستند. مناسب للمستندات الموقعة. إشعار: يتم تطبيقه فقط على مربع النص. كل من اسم الحقول والقيم حساسة لحالة الأحرف. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield#fillimagefield)(string, Stream) | وظيفة Overloads الخاصة بـ FillImageField. الإدخال عبارة عن دفق صورة. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield#fillimagefield_1)(string, string) | يلصق صورة في حقل الزر الموجود كمظهر لها وفقًا لاسم الحقل المؤهل بالكامل . |
| [FlattenAllFields](../../aspose.pdf.facades/form/flattenallfields)() | تسطيح كافة الحقول. |
| [FlattenField](../../aspose.pdf.facades/form/flattenfield)(string) | يقوم بتسوية حقل محدد باسم الحقل المؤهل بالكامل. سيظل أي حقل آخر غير قابل للتغيير. إذا كان اسم الحقل غير صالح ، ستظل جميع الحقول غير قابلة للتغيير. |
| [GetButtonOptionCurrentValue](../../aspose.pdf.facades/form/getbuttonoptioncurrentvalue)(string) | إرجاع القيمة الحالية لحقول خيار زر الاختيار. |
| [GetButtonOptionValues](../../aspose.pdf.facades/form/getbuttonoptionvalues)(string) | الحصول على حقول خيار زر التحديد والقيم ذات الصلة بناءً على اسم الحقل. هذه الطريقة لها معنى لمجموعات أزرار الاختيار. |
| [GetField](../../aspose.pdf.facades/form/getfield)(string) | الحصول على قيمة الحقل وفقًا لاسم الحقل الخاص به. |
| [GetFieldFacade](../../aspose.pdf.facades/form/getfieldfacade)(string) | إرجاع كائن FrofmFieldFacade يحتوي على كافة سمات المظهر. |
| [GetFieldFlag](../../aspose.pdf.facades/form/getfieldflag)(string) | إرجاع أعلام الحقل . |
| [GetFieldLimit](../../aspose.pdf.facades/form/getfieldlimit)(string) | احصل على حدود حقل النص . |
| [GetFieldType](../../aspose.pdf.facades/form/getfieldtype)(string) | إرجاع نوع الحقل. |
| [GetFullFieldName](../../aspose.pdf.facades/form/getfullfieldname)(string) | الحصول على اسم الحقل الكامل وفقًا لاسم الحقل المختصر . |
| [GetRichText](../../aspose.pdf.facades/form/getrichtext)(string) | احصل على قيمة حقل نص منسق ، بما في ذلك معلومات التنسيق لكل حرف. |
| [GetSubmitFlags](../../aspose.pdf.facades/form/getsubmitflags)(string) | إرجاع أعلام الإرسال لزر الإرسال |
| [ImportFdf](../../aspose.pdf.facades/form/importfdf)(Stream) | يستورد محتوى الحقول من ملف fdf ويضعها في ملف pdf الجديد. |
| [ImportXfdf](../../aspose.pdf.facades/form/importxfdf)(Stream) | يستورد محتوى الحقول من ملف xfdf (xml) ويضعها في ملف pdf الجديد. |
| [ImportXml](../../aspose.pdf.facades/form/importxml#importxml)(Stream) | يستورد محتوى الحقول من ملف xml ويضعها في ملف pdf الجديد. |
| [ImportXml](../../aspose.pdf.facades/form/importxml#importxml_1)(Stream, bool) | يستورد محتوى الحقول من ملف xml ويضعها في ملف pdf الجديد. |
| [IsRequiredField](../../aspose.pdf.facades/form/isrequiredfield)(string) | لتحديد ما إذا كان الحقل مطلوبًا أم لا. |
| [RenameField](../../aspose.pdf.facades/form/renamefield)(string, string) | يعيد تسمية حقل. إما حقل AcroForm أو حقل XFA على ما يرام. |
| override [Save](../../aspose.pdf.facades/form/save#save_1)(Stream) | يحفظ المستند في تيار محدد. |
| override [Save](../../aspose.pdf.facades/form/save#save_2)(string) | يحفظ المستند في الملف المحدد. |
| [SetXfaData](../../aspose.pdf.facades/form/setxfadata)(Stream) | يستبدل بيانات XFA بحزمة بيانات محددة. يمكن استخراج حزمة البيانات باستخدام ExtractXfaData. |

## أعضاء آخرون

| اسم | وصف |
| --- | --- |
| class [FormImportResult](form.formimportresult) | الفئة التي تصف النتيجة في حالة استيراد الحقل. |
| enum [ImportStatus](form.importstatus) | حالة الحقل المستورد |

### أنظر أيضا

* class [SaveableFacade](../saveablefacade)
* مساحة الاسم [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
