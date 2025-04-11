---
title: Class Form
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Facades.Form. فئة تمثل كائن نموذج Acro
type: docs
weight: 4290
url: /ar/net/aspose.pdf.facades/form/
---
## فئة النموذج

فئة تمثل كائن نموذج Acro.

```csharp
public sealed class Form : SaveableFacade
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Form](form/#constructor)() | منشئ النموذج بدون معلمات. |
| [Form](form/#constructor_1)(Document) | يقوم بتهيئة كائن `Form` جديد بناءً على *المستند*. |
| [Form](form/#constructor_4)(Stream) | منشئ للنموذج. |
| [Form](form/#constructor_7)(string) | منشئ للنموذج. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/form/convertto/) { set; } | يحدد تنسيق ملف PDF. سيتم حفظ الملف الناتج بالتنسيق المحدد. إذا لم يتم تحديد هذه الخاصية، فسيتم حفظ الملف بالتنسيق الافتراضي PDF بدون تحويل. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | يحصل على واجهة المستند التي يعمل عليها. |
| [FieldNames](../../aspose.pdf.facades/form/fieldnames/) { get; } | يحصل على قائمة بأسماء الحقول في النموذج. |
| [FormSubmitButtonNames](../../aspose.pdf.facades/form/formsubmitbuttonnames/) { get; } | يحصل على جميع أسماء أزرار إرسال النموذج. |
| [ImportResult](../../aspose.pdf.facades/form/importresult/) { get; } | نتيجة آخر عملية استيراد. مصفوفة من الكائنات التي تصف نتيجة الاستيراد لكل حقل. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | يقوم بتهيئة الواجهة. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | يقوم بتهيئة الواجهة. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | يقوم بتهيئة الواجهة. |
| override [Close](../../aspose.pdf.facades/form/close/)() | يغلق الملفات المفتوحة بدون أي تغييرات. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | يتخلص من الواجهة. |
| [ExportFdf](../../aspose.pdf.facades/form/exportfdf/)(Stream) | يصدر محتوى الحقول من PDF إلى تدفق FDF. |
| [ExportJson](../../aspose.pdf.facades/form/exportjson/)(Stream, bool) | يصدر محتويات جميع الحقول في المستند إلى تدفق JSON. قيم حقول الأزرار لا يتم تصديرها. |
| [ExportXfdf](../../aspose.pdf.facades/form/exportxfdf/)(Stream) | يصدر محتوى الحقول من PDF إلى تدفق XML. قيمة حقل الزر لن يتم تصديرها. |
| [ExportXml](../../aspose.pdf.facades/form/exportxml/)(Stream) | يصدر محتوى الحقول من PDF إلى تدفق XML. قيمة حقل الزر لن يتم تصديرها. |
| [ExtractXfaData](../../aspose.pdf.facades/form/extractxfadata/)(Stream) | يستخرج حزمة بيانات XFA |
| [FillBarcodeField](../../aspose.pdf.facades/form/fillbarcodefield/)(string, string) | يملأ حقل رمز شريطي وفقًا لاسمه المؤهل بالكامل. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield)(string, bool) | يملأ حقل مربع الاختيار بقيمة منطقية. ملاحظة: ينطبق فقط على مربع الاختيار. يرجى ملاحظة أن Aspose.Pdf.Facades تدعم فقط أسماء الحقول الكاملة ولا تعمل مع أسماء الحقول الجزئية على عكس Aspose.Pdf.Kit؛ على سبيل المثال، إذا كان للحقل اسم كامل "Form.Subform.CheckBoxField" يجب عليك تحديد الاسم الكامل وليس "CheckBoxField". يمكنك استخدام خاصية FieldNames لاستكشاف أسماء الحقول الموجودة والبحث عن الحقل المطلوب حسب اسمه الجزئي. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_1)(string, int) | يملأ حقل مربع الراديو بقيمة فهرس صالحة وفقًا لاسم الحقل المؤهل بالكامل. قبل ملء الحقول، يجب أن يكون اسم الحقل معروفًا فقط. بينما يمكن تحديد القيمة بواسطة فهرسها. ملاحظة: ينطبق فقط على حقول مربع الراديو ومربع القائمة. يرجى ملاحظة أن Aspose.Pdf.Facades تدعم فقط أسماء الحقول الكاملة ولا تعمل مع أسماء الحقول الجزئية على عكس Aspose.Pdf.Kit؛ على سبيل المثال، إذا كان للحقل اسم كامل "Form.Subform.ListBoxField" يجب عليك تحديد الاسم الكامل وليس "ListBoxField". يمكنك استخدام خاصية FieldNames لاستكشاف أسماء الحقول الموجودة والبحث عن الحقل المطلوب حسب اسمه الجزئي. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_2)(string, string) | يملأ الحقل بقيمة صالحة وفقًا لاسم الحقل المؤهل بالكامل. قبل ملء الحقول، يجب أن تكون أسماء كل الحقول وقيمها الصالحة المعنية معروفة. كل من أسماء الحقول والقيم حساسة لحالة الأحرف. يرجى ملاحظة أن Aspose.Pdf.Facades تدعم فقط أسماء الحقول الكاملة ولا تعمل مع أسماء الحقول الجزئية على عكس Aspose.Pdf.Kit؛ على سبيل المثال، إذا كان للحقل اسم كامل "Form.Subform.TextField" يجب عليك تحديد الاسم الكامل وليس "TextField". يمكنك استخدام خاصية FieldNames لاستكشاف أسماء الحقول الموجودة والبحث عن الحقل المطلوب حسب اسمه الجزئي. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_4)(string, string[]) | يملأ حقلًا مع تحديدات متعددة. ملاحظة: فقط لحقل قائمة AcroForm. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_3)(string, string, bool) | يملأ الحقل بالقيمة المحددة. |
| [FillFields](../../aspose.pdf.facades/form/fillfields/)(string[], string[], out Stream) | يملأ حقول مربع النص بقيم نصية ويحفظ المستند. ذات صلة بالمستندات الموقعة. ملاحظة: ينطبق فقط على مربع النص. كل من أسماء الحقول والقيم حساسة لحالة الأحرف. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield/#fillimagefield)(string, Stream) | يحمل وظيفة FillImageField. الإدخال هو تدفق صورة. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield/#fillimagefield_1)(string, string) | يلصق صورة على حقل الزر الموجود كمظهر له وفقًا لاسم الحقل المؤهل بالكامل. |
| [FlattenAllFields](../../aspose.pdf.facades/form/flattenallfields/)() | يسطح جميع الحقول. |
| [FlattenField](../../aspose.pdf.facades/form/flattenfield/)(string) | يسطح حقلًا محددًا باسم الحقل المؤهل بالكامل. ستبقى أي حقل آخر غير قابل للتغيير. إذا كان اسم الحقل غير صالح، ستبقى جميع الحقول غير قابلة للتغيير. |
| [GetButtonOptionCurrentValue](../../aspose.pdf.facades/form/getbuttonoptioncurrentvalue/)(string) | يعيد القيمة الحالية لحقول خيارات زر الراديو. |
| [GetButtonOptionValues](../../aspose.pdf.facades/form/getbuttonoptionvalues/)(string) | يحصل على حقول خيارات زر الراديو والقيم ذات الصلة بناءً على اسم الحقل. هذه الطريقة لها معنى لمجموعات زر الراديو. |
| [GetField](../../aspose.pdf.facades/form/getfield/)(string) | يحصل على قيمة الحقل وفقًا لاسم الحقل. |
| [GetFieldFacade](../../aspose.pdf.facades/form/getfieldfacade/)(string) | يعيد كائن FrofmFieldFacade الذي يحتوي على جميع سمات المظهر. |
| [GetFieldFlag](../../aspose.pdf.facades/form/getfieldflag/)(string) | يعيد علامات الحقل. |
| [GetFieldLimit](../../aspose.pdf.facades/form/getfieldlimit/)(string) | يحصل على قيود حقل النص. |
| [GetFieldType](../../aspose.pdf.facades/form/getfieldtype/)(string) | يعيد نوع الحقل. |
| [GetFullFieldName](../../aspose.pdf.facades/form/getfullfieldname/)(string) | يحصل على الاسم الكامل للحقل وفقًا لاسمه القصير. |
| [GetRichText](../../aspose.pdf.facades/form/getrichtext/)(string) | يحصل على قيمة حقل النص الغني، بما في ذلك معلومات التنسيق لكل حرف. |
| [GetSubmitFlags](../../aspose.pdf.facades/form/getsubmitflags/)(string) | يعيد علامات تقديم زر الإرسال |
| [ImportFdf](../../aspose.pdf.facades/form/importfdf/)(Stream) | يستورد محتوى الحقول من ملف FDF ويضعها في PDF الجديد. |
| [ImportJson](../../aspose.pdf.facades/form/importjson/)(Stream) | يستورد جميع بيانات الحقول من تدفق JSON إلى حقول المستند، مطابقة الحقول بأسمائها الكاملة. |
| [ImportXfdf](../../aspose.pdf.facades/form/importxfdf/)(Stream) | يستورد محتوى الحقول من ملف XFDF (XML) ويضعها في PDF الجديد. |
| [ImportXml](../../aspose.pdf.facades/form/importxml/#importxml)(Stream) | يستورد محتوى الحقول من ملف XML ويضعها في PDF الجديد. |
| [ImportXml](../../aspose.pdf.facades/form/importxml/#importxml_1)(Stream, bool) | يستورد محتوى الحقول من ملف XML ويضعها في PDF الجديد. |
| [IsRequiredField](../../aspose.pdf.facades/form/isrequiredfield/)(string) | يحدد ما إذا كان الحقل مطلوبًا أم لا. |
| [RenameField](../../aspose.pdf.facades/form/renamefield/)(string, string) | يعيد تسمية حقل. سواء كان حقل AcroForm أو حقل XFA مقبولًا. |
| override [Save](../../aspose.pdf.facades/form/save/#save_1)(Stream) | يحفظ المستند في التدفق المحدد. |
| override [Save](../../aspose.pdf.facades/form/save/#save_2)(string) | يحفظ المستند في الملف المحدد. |
| [SetXfaData](../../aspose.pdf.facades/form/setxfadata/)(Stream) | يستبدل بيانات XFA بحزمة البيانات المحددة. يمكن استخراج حزمة البيانات باستخدام ExtractXfaData. |

## أعضاء آخرون

| الاسم | الوصف |
| --- | --- |
| class [FormImportResult](../../aspose.pdf.facades/form.formimportresult) | فئة تصف نتيجة استيراد الحقل. |
| enum [ImportStatus](../../aspose.pdf.facades/form.importstatus) | حالة الحقل المستورد |

### انظر أيضًا

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)