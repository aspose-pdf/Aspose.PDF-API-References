---
title: "نموذج"
linktitle: "نموذج"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثل كائن نموذج Acro."
type: docs
weight: 170
url: /ar/java/com.aspose.pdf.facades/form/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.Form, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.Form, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.Form

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IForm, ISaveableFacade, Closeable, AutoCloseable

```
public final class Form extends SaveableFacade
```

فئة تمثل كائن نموذج Acro.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Form](#Form--) | <p> منشئ Form بدون معلمات. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-com.aspose.pdf.IDocument-) | <p> منشئ Form بدون معلمات. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> منشئ Form بدون معلمات. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-com.aspose.pdf.IDocument-java.lang.String-) | <p> منشئ Form بدون معلمات. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.io.InputStream-) | <p> منشئ Form بدون معلمات. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.io.InputStream-java.io.OutputStream-) | <p> منشئ Form بدون معلمات. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.io.InputStream-java.lang.String-) | <p> منشئ Form بدون معلمات. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.lang.String-) | <p> منشئ Form بدون معلمات. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.lang.String-java.io.OutputStream-) | <p> منشئ Form بدون معلمات. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.lang.String-java.lang.String-) | <p> منشئ Form بدون معلمات. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-java.lang.String-) | ينشئ الواجهة. |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | ينشئ الواجهة. |
| [close](#close--) | يغلق الملفات المفتوحة دون أي تغييرات. |
| [dispose](#dispose--) | يغلق جميع الموارد المفتوحة. هذه الطريقة مهجورة، استخدم close() بدلاً من ذلك. |
| [exportFdf](#exportFdf-java.io.OutputStream-) | <p> يصدّر محتوى حقول الـ pdf إلى تدفق fdf. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); OutputStream stream = new FileOutputStream(\"export.fdf\"); form.exportFdf(stream); stream.close(); </pre> |
| [exportXfdf](#exportXfdf-java.io.OutputStream-) | <p> يصدّر محتوى حقول الـ pdf إلى تدفق xml. لن يتم تصدير قيمة حقل الزر. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); FileInputStream fs = new FileInputStream(\"export.xfdf\", FileMode.Create, FileAccess.Write); form.exportXfdf(fs); fs.close(); </pre> |
| [exportXml](#exportXml-java.io.OutputStream-) | <p> يصدّر محتوى حقول الـ pdf إلى تدفق xml. لن يتم تصدير قيمة حقل الزر. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\")); OutputStream fs = new FileOutputStream(\"export.xml\"); form.exportXml(fs); fs.close(); </pre> |
| [extractXfaData](#extractXfaData-java.io.OutputStream-) | يستخرج حزمة بيانات XFA |
| [fillBarcodeField](#fillBarcodeField-java.lang.String-java.lang.String-) | <p> املأ حقل الباركود وفقًا لاسمه المؤهل بالكامل. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillBarcodeField(\"textField\", \"42207252\"); </pre> |
| [fillField](#fillField-java.lang.String-boolean-) | <p> يملأ حقل خانة الاختيار (check box) بقيمة منطقية. ملاحظة: يُطبق فقط على Check Box. يرجى ملاحظة أن Facades يدعم فقط أسماء الحقول الكاملة ولا يعمل مع الأسماء الجزئية على عكس Aspose.Pdf.Kit؛ على سبيل المثال إذا كان للحقول اسم كامل \"Form.Subform.CheckBoxField\" يجب تحديد الاسم الكامل وليس \"CheckBoxField\". يمكنك استخدام الخاصية FieldNames لاستكشاف أسماء الحقول الموجودة والبحث عن الحقل المطلوب باسمه الجزئي. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"checkboxField\", true); //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"CheckBoxField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre> |
| [fillField](#fillField-java.lang.String-int-) | <p> يملأ حقل صندوق الراديو بقيمة فهرس صالحة وفقًا لاسم الحقل المؤهل بالكامل. قبل ملء الحقول، يجب معرفة اسم الحقل فقط. يمكن تحديد القيمة بواسطة فهرسها. ملاحظة: يُطبق فقط على حقول صندوق الراديو، صندوق القوائم المنسدلة وصندوق القائمة. يرجى ملاحظة أن Facades يدعم فقط أسماء الحقول الكاملة ولا يعمل مع الأسماء الجزئية على عكس Aspose.Pdf.Kit؛ على سبيل المثال إذا كان للحقول اسم كامل \"Form.Subform.ListBoxField\" يجب تحديد الاسم الكامل وليس \"ListBoxField\". يمكنك استخدام الخاصية FieldNames لاستكشاف أسماء الحقول الموجودة والبحث عن الحقل المطلوب باسمه الجزئي. </p> <hr> <pre> //1 Form form = new Form("PdfForm.pdf"); form.fillField("listboxField", 2); form.fillField("comboboxField", 2); form.fillField("radiobuttonField", 2); //2 //how to search field by its partial name: Form form = new Form("input.pdf", "output.pdf"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith("ListBoxField")) { System.out.println("Full name is: " + fieldName); } } </pre> |
| [fillField](#fillField-java.lang.String-java.lang.String-) | <p> يملأ الحقل بقيمة صالحة وفقًا لاسم الحقل المؤهل بالكامل. قبل ملء الحقول، يجب معرفة أسماء جميع الحقول والقيم الصالحة المقابلة لها. كل من أسماء الحقول والقيم حساسة لحالة الأحرف. يرجى ملاحظة أن Facades يدعم فقط أسماء الحقول الكاملة ولا يعمل مع الأسماء الجزئية على عكس Aspose.Pdf.Kit؛ على سبيل المثال إذا كان للحقول اسم كامل \"Form.Subform.TextField\" يجب تحديد الاسم الكامل وليس \"TextField\". يمكنك استخدام الخاصية FieldNames لاستكشاف أسماء الحقول الموجودة والبحث عن الحقل المطلوب باسمه الجزئي. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.fillField("FirstName", "John"); form.fillField("LastName", "Smith"); //how to search field by its partial name: Form form = new Form("input.pdf", "output.pdf"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith("TextField")) { System.out.println("Full name is: " + fieldName); } } </pre> |
| [fillField](#fillField-java.lang.String-java.lang.String:A-) | <p> املأ حقلًا بتحديدات متعددة. ملاحظة: فقط لحقل قائمة AcroForm. </p> <hr> <pre> Form form = new com.aspose.pdf.Form("PdfForm.pdf", "Form_Updated.pdf"); form.fillField("ListBox1", new String[] { "Three", "One" }); form.save(); </pre> |
| [fillField](#fillField-java.lang.String-java.lang.String-boolean-) | يملأ الحقل بالقيمة المحددة. |
| [fillFields](#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-) | يملأ حقول مربع النص بقيم نصية ويحفظ المستند. |
| [fillImageField](#fillImageField-java.lang.String-java.io.InputStream-) | <p> يحمّل نسخة مفرطة من دالة FillImageField. الإدخال هو تدفق صورة. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf"); form.fillImageField("fieldName", new FileInputStream("file.jpg", FileMode.Open, FileAccess.Read)); </pre> |
| [fillImageField](#fillImageField-java.lang.String-java.lang.String-) | <p> يلصق صورة على حقل الزر الموجود كالمظهر الخاص به وفقًا لاسم الحقل المؤهل بالكامل. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf"); form.fillImageField("fieldName", "file.jpg"); form.save(); </pre> |
| [flattenAllFields](#flattenAllFields--) | <p> يقوم بتسوية جميع الحقول. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.flattenAllFields(); </pre> |
| [flattenField](#flattenField-java.lang.String-) | <p> يقوم بتسوية حقل محدد باستخدام اسم الحقل المؤهل بالكامل. سيبقى أي حقل آخر غير قابل للتغيير. إذا كان اسم الحقل غير صالح، ستبقى جميع الحقول غير قابلة للتغيير. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.flattenField("textField"); </pre> |
| [getAttachmentName](#getAttachmentName--) | يحصل على اسم المرفق عندما يتم تخزين نتيجة العملية في كائنات HttpResponse كمرفق. |
| [getButtonOptionCurrentValue](#getButtonOptionCurrentValue-java.lang.String-) | <p> يرجع القيمة الحالية لحقول خيارات زر الراديو. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.GetButtonOptionCurrentValue("btnField")); </pre> |
| [getButtonOptionValues](#getButtonOptionValues-java.lang.String-) | <p> يحصل على حقول خيارات زر الراديو والقيم المرتبطة بناءً على اسم الحقل. هذه الطريقة ذات معنى لمجموعات أزرار الراديو. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); java.util.Map values = form.getButtonOptionValues("Color"); System.out.println(values.get("White").toString()); System.out.println(values.get("Black").toString()); </pre> |
| [getButtonOptionValuesInternal](#getButtonOptionValuesInternal-java.lang.String-) | <p> يحصل على حقول خيارات زر الراديو والقيم المرتبطة بناءً على اسم الحقل. هذه الطريقة لها معنى لمجموعات أزرار الراديو. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); Hashtable values = form.getButtonOptionValues("Color"); System.out.println(values["White"].toString()); System.out.println(values["Black"].toString()); </pre> |
| [getContentDisposition](#getContentDisposition--) | يحصل أو يضبط كيفية تخزين المحتوى عندما يتم تخزين نتيجة العملية في كائن HttpResponse. القيم الممكنة: inline / attachment. القيمة الافتراضية: inline. |
| [getDestFileName](#getDestFileName--) | يحصل على اسم ملف الوجهة. |
| [getDestStream](#getDestStream--) | يحصل أو يضبط تدفق الوجهة. |
| [getField](#getField-java.lang.String-) | <p> يحصل على قيمة الحقل وفقًا لاسم الحقل. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println("Field value = " + form.getField("Field1")); </pre> |
| [getFieldFacade](#getFieldFacade-java.lang.String-) | <p> يرجع كائن FormFieldFacade يحتوي على جميع سمات المظهر. </p> <hr> <pre> com.aspose.pdf.facades.Form form = new com.aspose.pdf.facades.Form("form.pdf")); FormFieldFacade field = form.getFieldFacade("field1"); System.out.println("Color of field border: " + field.getBorderColor()); </pre> |
| [getFieldFlag](#getFieldFlag-java.lang.String-) | <p> يرجع أعلام الحقل. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); if (form.getFieldFlag("textField") == ProptyFlag.ReadOnly) { System.out.println("Field is read-only"); } </pre> |
| [getFieldLimit](#getFieldLimit-java.lang.String-) | <p> احصل على حد حقل النص. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.getFieldLimit("textfieldBox")); </pre> |
| [getFieldNames](#getFieldNames--) | <p> يحصل على قائمة بأسماء الحقول في النموذج. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); String[] fields = form.getFieldNames(); for(String field : fields) { System.out.println(field); } </pre> |
| [getFieldType](#getFieldType-java.lang.String-) | <p> يرجع نوع الحقل. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); if (form.getFieldType("textField") == FieldType.Text) { System.out.println("Type of field is text"); } </pre> |
| [getFormSubmitButtonNames](#getFormSubmitButtonNames--) | <p> يحصل على جميع أسماء أزرار إرسال النموذج. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); String[] submits = form.getFormSubmitButtonNames(); for(String btn : submits) { System.out.println(btn); } </pre> |
| [getFullFieldName](#getFullFieldName-java.lang.String-) | <p> يحصل على الاسم الكامل للحقل وفقًا لاسمه المختصر. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println("Full field name is : " + form.getFullFieldName("textField")); </pre> |
| [getImportResult](#getImportResult--) | نتيجة عملية الاستيراد الأخيرة. مصفوفة من الكائنات التي تصف نتيجة الاستيراد لكل حقل. |
| [getRichText](#getRichText-java.lang.String-) | <p> احصل على قيمة حقل النص الغني، بما في ذلك معلومات التنسيق لكل حرف. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.getRichText("txtDescriptionRTF")); </pre> |
| [getSaveOptions](#getSaveOptions--) | يحصل أو يضبط خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpResponse. القيمة الافتراضية: PdfSaveOptions. |
| [getSrcFileName](#getSrcFileName--) | <p> يحصل على اسم ملف المصدر. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcFileName("file.pdf"); </pre> |
| [getSrcStream](#getSrcStream--) | يحصل على تدفق المصدر. |
| [getSubmitFlags](#getSubmitFlags-java.lang.String-) | <p> Returns the submit button's submission flags </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println( ( form.getSubmitFlags("btnSubmit") \ | SubmitFormFlag.Xfdf != 0) ? " XFDF" : " "); /// System.out.println( ( form.getSubmitFlags("btnSubmit") \ | SubmitFormFlag.Fdf != 0) ? " FDF" : " "); System.out.println( ( form.getSubmitFlags("btnSubmit") \ | SubmitFormFlag.Pdf != 0) ? " PDF" : " "); </pre> |
| [importFdf](#importFdf-java.io.InputStream-) | <p> يستورد محتوى الحقول من ملف fdf ويضعها في ملف pdf الجديد. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf"); form.importFdf(new FileInputStream("data.fdf")); form.save(); </pre> |
| [importXfdf](#importXfdf-java.io.InputStream-) | <p> يستورد محتوى الحقول من ملف xfdf (xml) ويضعها في ملف pdf الجديد. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf"); InputStream fs = new FileInputStream("export_old.xfdf"); form.importXfdf(fs); fs.close(); form.save(); </pre> |
| [importXml](#importXml-java.io.InputStream-) | <p> يستورد محتوى الحقول من ملف xml ويضعها في ملف pdf الجديد. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); InputStream fs = new FileInputStream("import.xml"); form.importXml(fs); form.save("Form_Imported.pdf"); </pre> |
| [importXml](#importXml-java.io.InputStream-boolean-) | يستورد محتوى الحقول من ملف xml ويضعها في ملف pdf الجديد. |
| [importXml](#importXml-java.lang.String-) | <p> يستورد محتوى الحقول من ملف xml ويضعها في ملف pdf الجديد. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.importXml("import.xml"); form.save( "Form_Imported.pdf"); </pre> |
| [isRequiredField](#isRequiredField-java.lang.String-) | يحدد ما إذا كان الحقل مطلوبًا أم لا. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | <p> يعيد تسمية حقل. إما حقل AcroForm أو حقل XFA مقبول. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfFormUpdated.pdf"); form.renameField("field", "field1"); form.save(); </pre> |
| [save](#save--) | <p> يحفظ قيمة الحقول المملوءة ويغلق مستند PDF المفتوح. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre> |
| [save](#save-java.io.OutputStream-) | <p> يحفظ قيمة الحقول المملوءة ويغلق مستند PDF المفتوح. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre> |
| [save](#save-java.lang.String-) | <p> يحفظ قيمة الحقول المملوءة ويغلق مستند PDF المفتوح. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre> |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | يضبط اسم المرفق عندما يتم تخزين نتيجة العملية في كائنات HttpResponse كمرفق. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | يضبط كيفية تخزين المحتوى عندما يتم تخزين نتيجة العملية في كائن HttpResponse. القيم الممكنة: inline / attachment. الافتراضي: inline. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | يضبط تنسيق ملف PDF. سيتم حفظ الملف الناتج بالتنسيق المحدد. إذا لم يتم تحديد هذه الخاصية فسيتم حفظ الملف بالتنسيق الافتراضي PDF دون تحويل. |
| [setDestFileName](#setDestFileName-java.lang.String-) | <p> يضبط اسم الملف الوجهة. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestFileName("file.pdf"); </pre> |
| [setDestStream](#setDestStream-java.io.OutputStream-) | <p> يحصل على تدفق الوجهة. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestStream (new FileInputStream("file.pdf")); </pre> |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | يحصل أو يضبط خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpResponse. القيمة الافتراضية: PdfSaveOptions. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | يضبط اسم الملف المصدر. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | <p> يحصل على تدفق المصدر. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcStream (new FileInputStream("source.pdf"))); </pre> |
| [setXfaData](#setXfaData-java.io.InputStream-) | يستبدل بيانات XFA بحزمة البيانات المحددة. قد يتم استخراج حزمة البيانات باستخدام ExtractXfaData. |

### Form {#Form--}
```
public Form()
```

<p> منشئ Form بدون معلمات. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-com.aspose.pdf.IDocument-}
<p> منشئ Form بدون معلمات. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> منشئ Form بدون معلمات. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-com.aspose.pdf.IDocument-java.lang.String-}
<p> منشئ Form بدون معلمات. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.io.InputStream-}
<p> منشئ Form بدون معلمات. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.io.InputStream-java.io.OutputStream-}
<p> منشئ Form بدون معلمات. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.io.InputStream-java.lang.String-}
<p> منشئ Form بدون معلمات. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.lang.String-}
<p> منشئ Form بدون معلمات. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.lang.String-java.io.OutputStream-}
<p> منشئ Form بدون معلمات. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.lang.String-java.lang.String-}
<p> منشئ Form بدون معلمات. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### bindPdf {#bindPdf-java.io.InputStream-java.lang.String-}
ينشئ الواجهة.

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
ينشئ الواجهة.

### close {#close--}
```
public void close()
```

يغلق الملفات المفتوحة دون أي تغييرات.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

يغلق جميع الموارد المفتوحة. هذه الطريقة مهجورة، استخدم close() بدلاً من ذلك.

### exportFdf {#exportFdf-java.io.OutputStream-}
<p> يصدّر محتوى حقول الـ pdf إلى تدفق fdf. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); OutputStream stream = new FileOutputStream(\"export.fdf\"); form.exportFdf(stream); stream.close(); </pre>

### exportXfdf {#exportXfdf-java.io.OutputStream-}
<p> يصدّر محتوى حقول الـ pdf إلى تدفق xml. لن يتم تصدير قيمة حقل الزر. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); FileInputStream fs = new FileInputStream(\"export.xfdf\", FileMode.Create, FileAccess.Write); form.exportXfdf(fs); fs.close(); </pre>

### exportXml {#exportXml-java.io.OutputStream-}
<p> يصدّر محتوى حقول الـ pdf إلى تدفق xml. لن يتم تصدير قيمة حقل الزر. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\")); OutputStream fs = new FileOutputStream(\"export.xml\"); form.exportXml(fs); fs.close(); </pre>

### extractXfaData {#extractXfaData-java.io.OutputStream-}
يستخرج حزمة بيانات XFA

### fillBarcodeField {#fillBarcodeField-java.lang.String-java.lang.String-}
<p> املأ حقل الباركود وفقًا لاسمه المؤهل بالكامل. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillBarcodeField(\"textField\", \"42207252\"); </pre>

### fillField {#fillField-java.lang.String-boolean-}
<p> يملأ حقل خانة الاختيار (check box) بقيمة منطقية. ملاحظة: يُطبق فقط على Check Box. يرجى ملاحظة أن Facades يدعم فقط أسماء الحقول الكاملة ولا يعمل مع الأسماء الجزئية على عكس Aspose.Pdf.Kit؛ على سبيل المثال إذا كان للحقول اسم كامل \"Form.Subform.CheckBoxField\" يجب تحديد الاسم الكامل وليس \"CheckBoxField\". يمكنك استخدام الخاصية FieldNames لاستكشاف أسماء الحقول الموجودة والبحث عن الحقل المطلوب باسمه الجزئي. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"checkboxField\", true); //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"CheckBoxField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre>

### fillField {#fillField-java.lang.String-int-}
<p> يملأ حقل صندوق الراديو بقيمة فهرس صالحة وفقًا لاسم الحقل المؤهل بالكامل. قبل ملء الحقول، يجب معرفة اسم الحقل فقط. يمكن تحديد القيمة بواسطة فهرسها. ملاحظة: يُطبق فقط على حقول صندوق الراديو، صندوق القوائم المنسدلة وصندوق القائمة. يرجى ملاحظة أن Facades يدعم فقط أسماء الحقول الكاملة ولا يعمل مع الأسماء الجزئية على عكس Aspose.Pdf.Kit؛ على سبيل المثال إذا كان للحقول اسم كامل \"Form.Subform.ListBoxField\" يجب تحديد الاسم الكامل وليس \"ListBoxField\". يمكنك استخدام الخاصية FieldNames لاستكشاف أسماء الحقول الموجودة والبحث عن الحقل المطلوب باسمه الجزئي. </p> <hr> <pre> //1 Form form = new Form("PdfForm.pdf"); form.fillField("listboxField", 2); form.fillField("comboboxField", 2); form.fillField("radiobuttonField", 2); //2 //how to search field by its partial name: Form form = new Form("input.pdf", "output.pdf"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith("ListBoxField")) { System.out.println("Full name is: " + fieldName); } } </pre>

### fillField {#fillField-java.lang.String-java.lang.String-}
<p> يملأ الحقل بقيمة صالحة وفقًا لاسم الحقل المؤهل بالكامل. قبل ملء الحقول، يجب معرفة أسماء جميع الحقول والقيم الصالحة المقابلة لها. كل من أسماء الحقول والقيم حساسة لحالة الأحرف. يرجى ملاحظة أن Facades يدعم فقط أسماء الحقول الكاملة ولا يعمل مع الأسماء الجزئية على عكس Aspose.Pdf.Kit؛ على سبيل المثال إذا كان للحقول اسم كامل \"Form.Subform.TextField\" يجب تحديد الاسم الكامل وليس \"TextField\". يمكنك استخدام الخاصية FieldNames لاستكشاف أسماء الحقول الموجودة والبحث عن الحقل المطلوب باسمه الجزئي. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.fillField("FirstName", "John"); form.fillField("LastName", "Smith"); //how to search field by its partial name: Form form = new Form("input.pdf", "output.pdf"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith("TextField")) { System.out.println("Full name is: " + fieldName); } } </pre>

### fillField {#fillField-java.lang.String-java.lang.String:A-}
<p> املأ حقلًا بتحديدات متعددة. ملاحظة: فقط لحقل قائمة AcroForm. </p> <hr> <pre> Form form = new com.aspose.pdf.Form("PdfForm.pdf", "Form_Updated.pdf"); form.fillField("ListBox1", new String[] { "Three", "One" }); form.save(); </pre>

### fillField {#fillField-java.lang.String-java.lang.String-boolean-}
يملأ الحقل بالقيمة المحددة.

### fillFields {#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-}
يملأ حقول مربع النص بقيم نصية ويحفظ المستند.

### fillImageField {#fillImageField-java.lang.String-java.io.InputStream-}
<p> يحمّل نسخة مفرطة من دالة FillImageField. الإدخال هو تدفق صورة. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf"); form.fillImageField("fieldName", new FileInputStream("file.jpg", FileMode.Open, FileAccess.Read)); </pre>

### fillImageField {#fillImageField-java.lang.String-java.lang.String-}
<p> يلصق صورة على حقل الزر الموجود كالمظهر الخاص به وفقًا لاسم الحقل المؤهل بالكامل. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf"); form.fillImageField("fieldName", "file.jpg"); form.save(); </pre>

### flattenAllFields {#flattenAllFields--}
```
public void flattenAllFields()
```

<p> يقوم بتسوية جميع الحقول. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.flattenAllFields(); </pre>

### flattenField {#flattenField-java.lang.String-}
<p> يقوم بتسوية حقل محدد باستخدام اسم الحقل المؤهل بالكامل. سيبقى أي حقل آخر غير قابل للتغيير. إذا كان اسم الحقل غير صالح، ستبقى جميع الحقول غير قابلة للتغيير. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.flattenField("textField"); </pre>

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

يحصل على اسم المرفق عندما يتم تخزين نتيجة العملية في كائنات HttpResponse كمرفق.

**Returns:**
كائن سلسلة

### getButtonOptionCurrentValue {#getButtonOptionCurrentValue-java.lang.String-}
<p> يرجع القيمة الحالية لحقول خيارات زر الراديو. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.GetButtonOptionCurrentValue("btnField")); </pre>

### getButtonOptionValues {#getButtonOptionValues-java.lang.String-}
<p> يحصل على حقول خيارات زر الراديو والقيم المرتبطة بناءً على اسم الحقل. هذه الطريقة ذات معنى لمجموعات أزرار الراديو. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); java.util.Map values = form.getButtonOptionValues("Color"); System.out.println(values.get("White").toString()); System.out.println(values.get("Black").toString()); </pre>

### getButtonOptionValuesInternal {#getButtonOptionValuesInternal-java.lang.String-}
<p> يحصل على حقول خيارات زر الراديو والقيم المرتبطة بناءً على اسم الحقل. هذه الطريقة لها معنى لمجموعات أزرار الراديو. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); Hashtable values = form.getButtonOptionValues("Color"); System.out.println(values["White"].toString()); System.out.println(values["Black"].toString()); </pre>

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

يحصل أو يضبط كيفية تخزين المحتوى عندما يتم تخزين نتيجة العملية في كائن HttpResponse. القيم الممكنة: inline / attachment. القيمة الافتراضية: inline.

**Returns:**
عنصر ContentDisposition @see ContentDisposition

### getDestFileName {#getDestFileName--}
```
@Deprecated public String getDestFileName()
```

يحصل على اسم ملف الوجهة.

**Returns:**
كائن سلسلة

### getDestStream {#getDestStream--}
```
@Deprecated public OutputStream getDestStream()
```

يحصل أو يضبط تدفق الوجهة.

**Returns:**
كائن OutputStream

### getField {#getField-java.lang.String-}
<p> يحصل على قيمة الحقل وفقًا لاسم الحقل. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println("Field value = " + form.getField("Field1")); </pre>

### getFieldFacade {#getFieldFacade-java.lang.String-}
<p> يرجع كائن FormFieldFacade يحتوي على جميع سمات المظهر. </p> <hr> <pre> com.aspose.pdf.facades.Form form = new com.aspose.pdf.facades.Form("form.pdf")); FormFieldFacade field = form.getFieldFacade("field1"); System.out.println("Color of field border: " + field.getBorderColor()); </pre>

### getFieldFlag {#getFieldFlag-java.lang.String-}
<p> يرجع أعلام الحقل. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); if (form.getFieldFlag("textField") == ProptyFlag.ReadOnly) { System.out.println("Field is read-only"); } </pre>

### getFieldLimit {#getFieldLimit-java.lang.String-}
<p> احصل على حد حقل النص. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.getFieldLimit("textfieldBox")); </pre>

### getFieldNames {#getFieldNames--}
```
public String [] getFieldNames()
```

<p> يحصل على قائمة بأسماء الحقول في النموذج. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); String[] fields = form.getFieldNames(); for(String field : fields) { System.out.println(field); } </pre>

**Returns:**
String[] كائن

### getFieldType {#getFieldType-java.lang.String-}
<p> يرجع نوع الحقل. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); if (form.getFieldType("textField") == FieldType.Text) { System.out.println("Type of field is text"); } </pre>

### getFormSubmitButtonNames {#getFormSubmitButtonNames--}
```
public String [] getFormSubmitButtonNames()
```

<p> يحصل على جميع أسماء أزرار إرسال النموذج. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); String[] submits = form.getFormSubmitButtonNames(); for(String btn : submits) { System.out.println(btn); } </pre>

**Returns:**
String[] كائن

### getFullFieldName {#getFullFieldName-java.lang.String-}
<p> يحصل على الاسم الكامل للحقل وفقًا لاسمه المختصر. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println("Full field name is : " + form.getFullFieldName("textField")); </pre>

### getImportResult {#getImportResult--}
```
public com.aspose.pdf.facades.AForm.FormImportResult[] getImportResult()
```

نتيجة عملية الاستيراد الأخيرة. مصفوفة من الكائنات التي تصف نتيجة الاستيراد لكل حقل.

**Returns:**
FormImportResult[] مصفوفة

### getRichText {#getRichText-java.lang.String-}
<p> احصل على قيمة حقل النص الغني، بما في ذلك معلومات التنسيق لكل حرف. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.getRichText("txtDescriptionRTF")); </pre>

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

يحصل أو يضبط خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpResponse. القيمة الافتراضية: PdfSaveOptions.

**Returns:**
كائن SaveOptions

### getSrcFileName {#getSrcFileName--}
```
@Deprecated public String getSrcFileName()
```

<p> يحصل على اسم ملف المصدر. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcFileName("file.pdf"); </pre>

**Returns:**
كائن سلسلة

### getSrcStream {#getSrcStream--}
```
public InputStream getSrcStream()
```

يحصل على تدفق المصدر.

**Returns:**
كائن InputStream

### getSubmitFlags {#getSubmitFlags-java.lang.String-}
<p> يرجع أعلام إرسال زر الإرسال </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println( ( form.getSubmitFlags("btnSubmit") | SubmitFormFlag.Xfdf != 0) ? " XFDF" : " "); /// System.out.println( ( form.getSubmitFlags("btnSubmit") | SubmitFormFlag.Fdf != 0) ? " FDF" : " "); System.out.println( ( form.getSubmitFlags("btnSubmit") | SubmitFormFlag.Pdf != 0) ? " PDF" : " "); </pre>

### importFdf {#importFdf-java.io.InputStream-}
<p> يستورد محتوى الحقول من ملف fdf ويضعها في ملف pdf الجديد. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf"); form.importFdf(new FileInputStream("data.fdf")); form.save(); </pre>

### importXfdf {#importXfdf-java.io.InputStream-}
<p> يستورد محتوى الحقول من ملف xfdf (xml) ويضعها في ملف pdf الجديد. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf"); InputStream fs = new FileInputStream("export_old.xfdf"); form.importXfdf(fs); fs.close(); form.save(); </pre>

### importXml {#importXml-java.io.InputStream-}
<p> يستورد محتوى الحقول من ملف xml ويضعها في ملف pdf الجديد. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); InputStream fs = new FileInputStream("import.xml"); form.importXml(fs); form.save("Form_Imported.pdf"); </pre>

### importXml {#importXml-java.io.InputStream-boolean-}
يستورد محتوى الحقول من ملف xml ويضعها في ملف pdf الجديد.

### importXml {#importXml-java.lang.String-}
<p> يستورد محتوى الحقول من ملف xml ويضعها في ملف pdf الجديد. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.importXml("import.xml"); form.save( "Form_Imported.pdf"); </pre>

### isRequiredField {#isRequiredField-java.lang.String-}
يحدد ما إذا كان الحقل مطلوبًا أم لا.

### renameField {#renameField-java.lang.String-java.lang.String-}
<p> يعيد تسمية حقل. إما حقل AcroForm أو حقل XFA مقبول. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfFormUpdated.pdf"); form.renameField("field", "field1"); form.save(); </pre>

### save {#save--}
```
public void save()
```

<p> يحفظ قيمة الحقول المملوءة ويغلق مستند PDF المفتوح. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre>

### save {#save-java.io.OutputStream-}
<p> يحفظ قيمة الحقول المملوءة ويغلق مستند PDF المفتوح. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre>

### save {#save-java.lang.String-}
<p> يحفظ قيمة الحقول المملوءة ويغلق مستند PDF المفتوح. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre>

### setAttachmentName {#setAttachmentName-java.lang.String-}
يضبط اسم المرفق عندما يتم تخزين نتيجة العملية في كائنات HttpResponse كمرفق.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
يضبط كيفية تخزين المحتوى عندما يتم تخزين نتيجة العملية في كائن HttpResponse. القيم الممكنة: inline / attachment. الافتراضي: inline.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
يضبط تنسيق ملف PDF. سيتم حفظ الملف الناتج بالتنسيق المحدد. إذا لم يتم تحديد هذه الخاصية فسيتم حفظ الملف بالتنسيق الافتراضي PDF دون تحويل.

### setDestFileName {#setDestFileName-java.lang.String-}
<p> يضبط اسم الملف الوجهة. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestFileName("file.pdf"); </pre>

### setDestStream {#setDestStream-java.io.OutputStream-}
<p> يحصل على تدفق الوجهة. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestStream (new FileInputStream("file.pdf")); </pre>

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
يحصل أو يضبط خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpResponse. القيمة الافتراضية: PdfSaveOptions.

### setSrcFileName {#setSrcFileName-java.lang.String-}
يضبط اسم الملف المصدر.

### setSrcStream {#setSrcStream-java.io.InputStream-}
<p> يحصل على تدفق المصدر. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcStream (new FileInputStream("source.pdf"))); </pre>

### setXfaData {#setXfaData-java.io.InputStream-}
يستبدل بيانات XFA بحزمة البيانات المحددة. قد يتم استخراج حزمة البيانات باستخدام ExtractXfaData.
