---
title: "الفئة Form"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "Aspose.Pdf.Facades.Form class. فئة تمثل كائن نموذج Acro"
type: docs
weight: 4410
url: /ar/net/aspose.pdf.facades/form/
---
## Form class

فئة تمثل كائن نموذج Acro.

```csharp
public sealed class Form : SaveableFacade
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Form](form/#constructor)() | منشئ Form بدون معلمات. |
| [Form](form/#constructor_1)(Document) | يُهيئ كائن `Form` جديد بناءً على *document*. |
| [Form](form/#constructor_4)(Stream) | منشئ للنموذج. |
| [Form](form/#constructor_7)(string) | منشئ Form. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/form/convertto/) { set; } | يضبط تنسيق ملف PDF. سيتم حفظ الملف الناتج بالتنسيق المحدد. إذا لم يتم تحديد هذه الخاصية، فسيتم حفظ الملف بتنسيق PDF الافتراضي دون تحويل. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | يحصل على واجهة المستند التي يتم العمل عليها. |
| [FieldNames](../../aspose.pdf.facades/form/fieldnames/) { get; } | يحصل على قائمة بأسماء الحقول في النموذج. |
| [FormSubmitButtonNames](../../aspose.pdf.facades/form/formsubmitbuttonnames/) { get; } | يحصل على جميع أسماء أزرار إرسال النموذج. |
| [ImportResult](../../aspose.pdf.facades/form/importresult/) { get; } | نتيجة آخر عملية استيراد. مصفوفة من الكائنات التي تصف نتيجة الاستيراد لكل حقل. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | يُهيئ الواجهة. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | يُهيئ الواجهة. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | يُهيئ الواجهة. |
| override [Close](../../aspose.pdf.facades/form/close/)() | يغلق الملفات المفتوحة دون أي تغييرات. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | يتخلص من الواجهة. |
| [ExportFdf](../../aspose.pdf.facades/form/exportfdf/)(Stream) | يصدّر محتوى حقول الـ pdf إلى تدفق fdf. |
| [ExportJson](../../aspose.pdf.facades/form/exportjson/)(Stream, bool) | يصدّر محتويات جميع الحقول في المستند إلى تدفق JSON. لا يتم تصدير قيم حقول الأزرار. |
| [ExportXfdf](../../aspose.pdf.facades/form/exportxfdf/)(Stream) | يصدّر محتوى حقول الـ pdf إلى تدفق XML. لن يتم تصدير قيمة حقل الزر. |
| [ExportXml](../../aspose.pdf.facades/form/exportxml/)(Stream) | يصدّر محتوى حقول الـ pdf إلى تدفق XML. لن يتم تصدير قيمة حقل الزر. |
| [ExtractXfaData](../../aspose.pdf.facades/form/extractxfadata/)(Stream) | يستخرج حزمة بيانات XFA |
| [FillBarcodeField](../../aspose.pdf.facades/form/fillbarcodefield/)(string, string) | املأ حقل الباركود وفقًا لاسمه الكامل المؤهل. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield)(string, bool) | يملى حقل خانة الاختيار بقيمة منطقية. ملاحظة: يُطبق فقط على خانة الاختيار. يرجى ملاحظة أن **Aspose.Pdf.Facades** يدعم فقط الأسماء الكاملة للحقول ولا يعمل مع الأسماء الجزئية على عكس **Aspose.Pdf.Kit**؛ على سبيل المثال إذا كان للحقول اسم كامل \"Form.Subform.CheckBoxField\" يجب تحديد الاسم الكامل وليس \"CheckBoxField\". يمكنك استخدام خاصية FieldNames لاستكشاف أسماء الحقول الموجودة والبحث عن الحقل المطلوب باسمه الجزئي. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_1)(string, int) | يملى حقل صندوق الراديو بقيمة فهرس صالحة وفقًا لاسم الحقل الكامل المؤهل. قبل ملء الحقول، يجب معرفة اسم الحقل فقط. ويمكن تحديد القيمة بواسطة فهرسها. ملاحظة: يُطبق فقط على حقول صندوق الراديو، صندوق القائمة المنسدلة وصندوق القائمة. يرجى ملاحظة أن **Aspose.Pdf.Facades** يدعم فقط الأسماء الكاملة للحقول ولا يعمل مع الأسماء الجزئية على عكس **Aspose.Pdf.Kit**؛ على سبيل المثال إذا كان للحقول اسم كامل \"Form.Subform.ListBoxField\" يجب تحديد الاسم الكامل وليس \"ListBoxField\". يمكنك استخدام خاصية FieldNames لاستكشاف أسماء الحقول الموجودة والبحث عن الحقل المطلوب باسمه الجزئي. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_2)(string, string) | يملى الحقل بقيمة صالحة وفقًا لاسم الحقل الكامل المؤهل. قبل ملء الحقول، يجب معرفة أسماء جميع الحقول والقيم الصالحة المقابلة لها. كل من أسماء الحقول والقيم حساسة لحالة الأحرف. يرجى ملاحظة أن **Aspose.Pdf.Facades** يدعم فقط الأسماء الكاملة للحقول ولا يعمل مع الأسماء الجزئية على عكس **Aspose.Pdf.Kit**؛ على سبيل المثال إذا كان للحقول اسم كامل \"Form.Subform.TextField\" يجب تحديد الاسم الكامل وليس \"TextField\". يمكنك استخدام خاصية FieldNames لاستكشاف أسماء الحقول الموجودة والبحث عن الحقل المطلوب باسمه الجزئي. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_4)(string, string[]) | املأ حقلًا بتحديدات متعددة. ملاحظة: فقط لحقل قائمة AcroForm. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_3)(string, string, bool) | يملى الحقل بالقيمة المحددة. |
| [FillFields](../../aspose.pdf.facades/form/fillfields/)(string[], string[], out Stream) | يملى حقول مربع النص بقيم نصية ويحفظ المستند. يتعلق بالمستندات الموقعة. ملاحظة: يُطبق فقط على مربع النص. كل من أسماء الحقول والقيم حساسة لحالة الأحرف. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield/#fillimagefield)(string, Stream) | يحمّل نسخة مفرطة من دالة FillImageField. الإدخال هو تدفق صورة. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield/#fillimagefield_1)(string, string) | يلصق صورة على حقل الزر الموجود كظهوره وفقًا لاسمه الكامل المؤهل. |
| [FlattenAllFields](../../aspose.pdf.facades/form/flattenallfields/)() | يقوم بتسطيح جميع الحقول. |
| [FlattenField](../../aspose.pdf.facades/form/flattenfield/)(string) | يقوم بتسطيح حقل محدد باستخدام اسمه الكامل المؤهل. ستبقى جميع الحقول الأخرى غير قابلة للتغيير. إذا كان اسم الحقل غير صالح، ستبقى جميع الحقول غير قابلة للتغيير. |
| [GetButtonOptionCurrentValue](../../aspose.pdf.facades/form/getbuttonoptioncurrentvalue/)(string) | يعيد القيمة الحالية لحقول خيارات زر الراديو. |
| [GetButtonOptionValues](../../aspose.pdf.facades/form/getbuttonoptionvalues/)(string) | يحصل على حقول خيارات زر الراديو والقيم المرتبطة بناءً على اسم الحقل. لهذه الطريقة معنى في مجموعات أزرار الراديو. |
| [GetField](../../aspose.pdf.facades/form/getfield/)(string) | يحصل على قيمة الحقل وفقًا لاسمه. |
| [GetFieldFacade](../../aspose.pdf.facades/form/getfieldfacade/)(string) | يعيد كائن FrogmFieldFacade يحتوي على جميع سمات المظهر. |
| [GetFieldFlag](../../aspose.pdf.facades/form/getfieldflag/)(string) | يعيد علامات الحقل. |
| [GetFieldLimit](../../aspose.pdf.facades/form/getfieldlimit/)(string) | احصل على قيود حقل النص. |
| [GetFieldType](../../aspose.pdf.facades/form/getfieldtype/)(string) | يعيد نوع الحقل. |
| [GetFullFieldName](../../aspose.pdf.facades/form/getfullfieldname/)(string) | يحصل على الاسم الكامل للحقول بناءً على اسمها المختصر. |
| [GetRichText](../../aspose.pdf.facades/form/getrichtext/)(string) | احصل على قيمة حقل النص الغني، بما في ذلك معلومات التنسيق لكل حرف. |
| [GetSubmitFlags](../../aspose.pdf.facades/form/getsubmitflags/)(string) | يعيد أعلام الإرسال لزر الإرسال |
| [ImportFdf](../../aspose.pdf.facades/form/importfdf/)(Stream) | يستورد محتوى الحقول من ملف fdf ويضعها في ملف pdf الجديد. |
| [ImportJson](../../aspose.pdf.facades/form/importjson/)(Stream) | يستورد جميع بيانات الحقول من تدفق JSON إلى حقول المستند، مطابقة الحقول بأسمائها الكاملة. |
| [ImportXfdf](../../aspose.pdf.facades/form/importxfdf/)(Stream) | يستورد محتوى الحقول من ملف xfdf(xml) ويضعها في ملف pdf الجديد. |
| [ImportXml](../../aspose.pdf.facades/form/importxml/#importxml)(Stream) | يستورد محتوى الحقول من ملف xml ويضعها في ملف pdf الجديد. |
| [ImportXml](../../aspose.pdf.facades/form/importxml/#importxml_1)(Stream, bool) | يستورد محتوى الحقول من ملف xml ويضعها في ملف pdf الجديد. |
| [IsRequiredField](../../aspose.pdf.facades/form/isrequiredfield/)(string) | يحدد ما إذا كان الحقل مطلوبًا أم لا. |
| [RenameField](../../aspose.pdf.facades/form/renamefield/)(string, string) | يعيد تسمية حقل. سواء كان حقل AcroForm أو حقل XFA مقبول. |
| override [Save](../../aspose.pdf.facades/form/save/#save_1)(Stream) | يحفظ المستند في التدفق المحدد. |
| override [Save](../../aspose.pdf.facades/form/save/#save_2)(string) | يحفظ المستند في الملف المحدد. |
| [SetXfaData](../../aspose.pdf.facades/form/setxfadata/)(Stream) | يستبدل بيانات XFA بحزمة البيانات المحددة. يمكن استخراج حزمة البيانات باستخدام ExtractXfaData. |

## الأعضاء الآخرين

| الاسم | الوصف |
| --- | --- |
| class [FormImportResult](../../aspose.pdf.facades/form.formimportresult) | الفئة التي تصف نتيجة استيراد الحقل. |
| enum [ImportStatus](../../aspose.pdf.facades/form.importstatus) | حالة الحقل المستورد |

### انظر أيضًا

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


