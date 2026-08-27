---
title: "FormWeb"
linktitle: "FormWeb"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "تمثيل واجهة نموذج Acro."
type: docs
weight: 230
url: /ar/java/com.aspose.pdf.facades/formweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormWeb, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormWeb, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.FormWeb

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IForm, ISaveableFacade, Closeable, AutoCloseable

```
public final class FormWeb extends SaveableFacade implements IForm
```

تمثيل واجهة نموذج Acro.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [FormWeb](#FormWeb--) | <p> منشئ FormWeb بدون معلمات. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-com.aspose.pdf.IDocument-) | <p> منشئ FormWeb بدون معلمات. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> منشئ FormWeb بدون معلمات. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-com.aspose.pdf.IDocument-java.lang.String-) | <p> منشئ FormWeb بدون معلمات. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-) | <p> منشئ FormWeb بدون معلمات. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-) | <p> منشئ FormWeb بدون معلمات. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-java.io.OutputStream-) | <p> منشئ FormWeb بدون معلمات. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-java.lang.String-) | <p> منشئ FormWeb بدون معلمات. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-) | <p> منشئ FormWeb بدون معلمات. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-javax.servlet.http.HttpServletResponse-) | <p> منشئ FormWeb بدون معلمات. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-java.io.OutputStream-) | <p> منشئ FormWeb بدون معلمات. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-java.lang.String-) | <p> منشئ FormWeb بدون معلمات. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-java.lang.String-) | ينشئ الواجهة. |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | ينشئ الواجهة. |
| [close](#close--) | يغلق جميع الموارد المفتوحة المستخدمة بواسطة هذا المستند. |
| [dispose](#dispose--) | مهمل. |
| [exportFdf](#exportFdf-java.io.OutputStream-) | يصدّر محتوى حقول PDF إلى تدفق FDF. |
| [exportXfdf](#exportXfdf-java.io.OutputStream-) | يصدّر محتوى حقول PDF إلى تدفق XML. |
| [exportXml](#exportXml-java.io.OutputStream-) | يصدّر محتوى حقول PDF إلى تدفق XML. |
| [extractXfaData](#extractXfaData-java.io.OutputStream-) | يستخرج حزمة بيانات XFA |
| [fillBarcodeField](#fillBarcodeField-java.lang.String-java.lang.String-) | املأ حقل الباركود وفقًا لاسمه المؤهل بالكامل. |
| [fillField](#fillField-java.lang.String-boolean-) | يملأ حقل خانة الاختيار بقيمة منطقية. |
| [fillField](#fillField-java.lang.String-int-) | يملأ حقل زر الراديو بقيمة فهرس صالحة وفقًا لاسم الحقل المؤهل بالكامل. |
| [fillField](#fillField-java.lang.String-java.lang.String-) | يملأ الحقل بقيمة صالحة وفقًا لاسم الحقل المؤهل بالكامل. |
| [fillField](#fillField-java.lang.String-java.lang.String:A-) | املأ حقلًا بتحديدات متعددة. ملاحظة: فقط لحقل قائمة AcroForm. |
| [fillField](#fillField-java.lang.String-java.lang.String-boolean-) | يملأ الحقل بالقيمة المحددة. |
| [fillFields](#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-) | يملأ حقول مربع النص بقيم نصية ويحفظ المستند. |
| [fillImageField](#fillImageField-java.lang.String-java.io.InputStream-) | يوفر إصدارات محملة من الدالة FillImageField. |
| [fillImageField](#fillImageField-java.lang.String-java.lang.String-) | يلصق صورة على حقل الزر الموجود كظهره وفقًا لاسمه المؤهل بالكامل. |
| [flattenAllFields](#flattenAllFields--) | يجعل جميع الحقول ثابتة. |
| [flattenField](#flattenField-java.lang.String-) | يجعل حقلًا محددًا ثابتًا باستخدام اسمه المؤهل بالكامل. |
| [getAttachmentName](#getAttachmentName--) | يحصل على اسم المرفق عندما يتم تخزين نتيجة العملية في كائنات HttpResponse كمرفق. |
| [getButtonOptionCurrentValue](#getButtonOptionCurrentValue-java.lang.String-) | إرجاع القيمة الحالية لحقول خيارات زر الراديو. |
| [getButtonOptionValues](#getButtonOptionValues-java.lang.String-) | الحصول على حقول خيارات زر الراديو والقيم المرتبطة بناءً على اسم الحقل. |
| [getButtonOptionValuesInternal](#getButtonOptionValuesInternal-java.lang.String-) | الحصول على حقول خيارات زر الراديو والقيم المرتبطة بناءً على اسم الحقل. |
| [getContentDisposition](#getContentDisposition--) | سيتم تخزين محتوى Getshow عندما يتم تخزين نتيجة العملية في كائن HttpResponse. |
| [getDestFileName](#getDestFileName--) | مهمل. |
| [getDestStream](#getDestStream--) | مهمل. |
| [getField](#getField-java.lang.String-) | الحصول على قيمة الحقل وفقًا لاسم الحقل. |
| [getFieldFacade](#getFieldFacade-java.lang.String-) | إرجاع كائن FrofmFieldFacade الذي يحتوي على جميع سمات المظهر. |
| [getFieldFlag](#getFieldFlag-java.lang.String-) | إرجاع علامات الحقل. |
| [getFieldLimit](#getFieldLimit-java.lang.String-) | الحصول على قيود حقل النص. |
| [getFieldNames](#getFieldNames--) | الحصول على قائمة بأسماء الحقول في النموذج. |
| [getFieldType](#getFieldType-java.lang.String-) | إرجاع نوع الحقل. |
| [getFormSubmitButtonNames](#getFormSubmitButtonNames--) | الحصول على جميع أسماء أزرار إرسال النموذج. |
| [getFullFieldName](#getFullFieldName-java.lang.String-) | الحصول على الاسم الكامل للحقل وفقًا لاسمه المختصر. |
| [getImportResult](#getImportResult--) | نتيجة آخر عملية استيراد. |
| [getResponse](#getResponse--) | الحصول على أو تعيين كائن Response حيث سيتم تخزين نتيجة العملية. |
| [getRichText](#getRichText-java.lang.String-) | الحصول على قيمة حقل النص الغني، بما في ذلك معلومات formattinf لكل حرف. |
| [getSaveOptions](#getSaveOptions--) | الحصول على أو تعيين خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpResponse. |
| [getSrcFileName](#getSrcFileName--) | مهمل. |
| [getSrcStream](#getSrcStream--) | يحصل على تدفق المصدر. |
| [getSubmitFlags](#getSubmitFlags-java.lang.String-) | إرجاع علامات إرسال زر الإرسال |
| [importFdf](#importFdf-java.io.InputStream-) | استيراد محتوى الحقول من ملف fdf ووضعه في ملف pdf الجديد. |
| [importXfdf](#importXfdf-java.io.InputStream-) | استيراد محتوى الحقول من ملف xfdf(xml) ووضعه في ملف pdf الجديد. |
| [importXml](#importXml-java.io.InputStream-) | يستورد محتوى الحقول من ملف xml ويضعها في ملف pdf الجديد. |
| [importXml](#importXml-java.io.InputStream-boolean-) | يستورد محتوى الحقول من ملف xml ويضعها في ملف pdf الجديد. |
| [importXml](#importXml-java.lang.String-) | يستورد محتوى الحقول من ملف xml ويضعها في ملف pdf الجديد. |
| [isRequiredField](#isRequiredField-java.lang.String-) | يحدد ما إذا كان الحقل مطلوبًا أم لا. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | إعادة تسمية حقل. |
| [save](#save--) | <p> يحفظ قيمة الحقول المملوءة ويغلق مستند PDF المفتوح. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre> |
| [save](#save-java.io.OutputStream-) | <p> يحفظ قيمة الحقول المملوءة ويغلق مستند PDF المفتوح. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre> |
| [save](#save-java.lang.String-) | <p> يحفظ قيمة الحقول المملوءة ويغلق مستند PDF المفتوح. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre> |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | يضبط اسم المرفق عندما يتم تخزين نتيجة العملية في كائنات HttpResponse كمرفق. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | يضبط كيفية تخزين المحتوى عندما يتم تخزين نتيجة العملية في كائن HttpResponse. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | يضبط تنسيق ملف PDF. |
| [setDestFileName](#setDestFileName-java.lang.String-) | مهمل. |
| [setDestStream](#setDestStream-java.io.OutputStream-) | مهمل. |
| [setResponse](#setResponse-javax.servlet.http.HttpServletResponse-) | الحصول على أو تعيين كائن Response حيث سيتم تخزين نتيجة العملية. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | الحصول على أو تعيين خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpResponse. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | مهمل. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | يحصل على تدفق المصدر. |
| [setXfaData](#setXfaData-java.io.InputStream-) | استبدال بيانات XFA بحزمة البيانات المحددة. |

### FormWeb {#FormWeb--}
```
public FormWeb()
```

<p> منشئ FormWeb بدون معلمات. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-com.aspose.pdf.IDocument-}
<p> منشئ FormWeb بدون معلمات. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> منشئ FormWeb بدون معلمات. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-com.aspose.pdf.IDocument-java.lang.String-}
<p> منشئ FormWeb بدون معلمات. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-}
<p> منشئ FormWeb بدون معلمات. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-}
<p> منشئ FormWeb بدون معلمات. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-java.io.OutputStream-}
<p> منشئ FormWeb بدون معلمات. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-java.lang.String-}
<p> منشئ FormWeb بدون معلمات. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.lang.String-}
<p> منشئ FormWeb بدون معلمات. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.lang.String-javax.servlet.http.HttpServletResponse-}
<p> منشئ FormWeb بدون معلمات. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.lang.String-java.io.OutputStream-}
<p> منشئ FormWeb بدون معلمات. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.lang.String-java.lang.String-}
<p> منشئ FormWeb بدون معلمات. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### bindPdf {#bindPdf-java.io.InputStream-java.lang.String-}
ينشئ الواجهة.

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
ينشئ الواجهة.

### close {#close--}
```
public void close()
```

يغلق جميع الموارد المفتوحة المستخدمة بواسطة هذا المستند.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

مهمل.

### exportFdf {#exportFdf-java.io.OutputStream-}
يصدّر محتوى حقول PDF إلى تدفق FDF.

### exportXfdf {#exportXfdf-java.io.OutputStream-}
يصدّر محتوى حقول PDF إلى تدفق XML.

### exportXml {#exportXml-java.io.OutputStream-}
يصدّر محتوى حقول PDF إلى تدفق XML.

### extractXfaData {#extractXfaData-java.io.OutputStream-}
يستخرج حزمة بيانات XFA

### fillBarcodeField {#fillBarcodeField-java.lang.String-java.lang.String-}
املأ حقل الباركود وفقًا لاسمه المؤهل بالكامل.

### fillField {#fillField-java.lang.String-boolean-}
يملأ حقل خانة الاختيار بقيمة منطقية.

### fillField {#fillField-java.lang.String-int-}
يملأ حقل زر الراديو بقيمة فهرس صالحة وفقًا لاسم الحقل المؤهل بالكامل.

### fillField {#fillField-java.lang.String-java.lang.String-}
يملأ الحقل بقيمة صالحة وفقًا لاسم الحقل المؤهل بالكامل.

### fillField {#fillField-java.lang.String-java.lang.String:A-}
املأ حقلًا بتحديدات متعددة. ملاحظة: فقط لحقل قائمة AcroForm.

### fillField {#fillField-java.lang.String-java.lang.String-boolean-}
يملأ الحقل بالقيمة المحددة.

### fillFields {#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-}
يملأ حقول مربع النص بقيم نصية ويحفظ المستند.

### fillImageField {#fillImageField-java.lang.String-java.io.InputStream-}
يوفر إصدارات محملة من الدالة FillImageField.

### fillImageField {#fillImageField-java.lang.String-java.lang.String-}
يلصق صورة على حقل الزر الموجود كظهره وفقًا لاسمه المؤهل بالكامل.

### flattenAllFields {#flattenAllFields--}
```
public void flattenAllFields()
```

يجعل جميع الحقول ثابتة.

### flattenField {#flattenField-java.lang.String-}
يجعل حقلًا محددًا ثابتًا باستخدام اسمه المؤهل بالكامل.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

يحصل على اسم المرفق عندما يتم تخزين نتيجة العملية في كائنات HttpResponse كمرفق.

**Returns:**
كائن سلسلة

### getButtonOptionCurrentValue {#getButtonOptionCurrentValue-java.lang.String-}
إرجاع القيمة الحالية لحقول خيارات زر الراديو.

### getButtonOptionValues {#getButtonOptionValues-java.lang.String-}
الحصول على حقول خيارات زر الراديو والقيم المرتبطة بناءً على اسم الحقل.

### getButtonOptionValuesInternal {#getButtonOptionValuesInternal-java.lang.String-}
الحصول على حقول خيارات زر الراديو والقيم المرتبطة بناءً على اسم الحقل.

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

سيتم تخزين محتوى Getshow عندما يتم تخزين نتيجة العملية في كائن HttpResponse.

**Returns:**
عنصر ContentDisposition

### getDestFileName {#getDestFileName--}
```
@Deprecated public String getDestFileName()
```

مهمل.

**Returns:**
كائن String

### getDestStream {#getDestStream--}
```
@Deprecated public OutputStream getDestStream()
```

مهمل.

**Returns:**
كائن OutputStream

### getField {#getField-java.lang.String-}
الحصول على قيمة الحقل وفقًا لاسم الحقل.

### getFieldFacade {#getFieldFacade-java.lang.String-}
إرجاع كائن FrofmFieldFacade الذي يحتوي على جميع سمات المظهر.

### getFieldFlag {#getFieldFlag-java.lang.String-}
إرجاع علامات الحقل.

### getFieldLimit {#getFieldLimit-java.lang.String-}
الحصول على قيود حقل النص.

### getFieldNames {#getFieldNames--}
```
public String [] getFieldNames()
```

الحصول على قائمة بأسماء الحقول في النموذج.

**Returns:**
String[] كائن

### getFieldType {#getFieldType-java.lang.String-}
إرجاع نوع الحقل.

### getFormSubmitButtonNames {#getFormSubmitButtonNames--}
```
public String [] getFormSubmitButtonNames()
```

الحصول على جميع أسماء أزرار إرسال النموذج.

**Returns:**
String[] كائن

### getFullFieldName {#getFullFieldName-java.lang.String-}
الحصول على الاسم الكامل للحقل وفقًا لاسمه المختصر.

### getImportResult {#getImportResult--}
```
public com.aspose.pdf.facades.AForm.FormImportResult[] getImportResult()
```

نتيجة آخر عملية استيراد.

**Returns:**
FormImportResult[] مصفوفة

### getResponse {#getResponse--}
```
public javax.servlet.http.HttpServletResponse getResponse()
```

الحصول على أو تعيين كائن Response حيث سيتم تخزين نتيجة العملية.

**Returns:**
كائن HttpServletResponse

### getRichText {#getRichText-java.lang.String-}
الحصول على قيمة حقل النص الغني، بما في ذلك معلومات formattinf لكل حرف.

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

الحصول على أو تعيين خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpResponse.

**Returns:**
كائن SaveOptions

### getSrcFileName {#getSrcFileName--}
```
@Deprecated public String getSrcFileName()
```

مهمل.

**Returns:**
كائن String

### getSrcStream {#getSrcStream--}
```
public InputStream getSrcStream()
```

يحصل على تدفق المصدر.

**Returns:**
كائن InputStream

### getSubmitFlags {#getSubmitFlags-java.lang.String-}
إرجاع علامات إرسال زر الإرسال

### importFdf {#importFdf-java.io.InputStream-}
استيراد محتوى الحقول من ملف fdf ووضعه في ملف pdf الجديد.

### importXfdf {#importXfdf-java.io.InputStream-}
استيراد محتوى الحقول من ملف xfdf(xml) ووضعه في ملف pdf الجديد.

### importXml {#importXml-java.io.InputStream-}
يستورد محتوى الحقول من ملف xml ويضعها في ملف pdf الجديد.

### importXml {#importXml-java.io.InputStream-boolean-}
يستورد محتوى الحقول من ملف xml ويضعها في ملف pdf الجديد.

### importXml {#importXml-java.lang.String-}
يستورد محتوى الحقول من ملف xml ويضعها في ملف pdf الجديد.

### isRequiredField {#isRequiredField-java.lang.String-}
يحدد ما إذا كان الحقل مطلوبًا أم لا.

### renameField {#renameField-java.lang.String-java.lang.String-}
إعادة تسمية حقل.

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
يضبط كيفية تخزين المحتوى عندما يتم تخزين نتيجة العملية في كائن HttpResponse.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
يضبط تنسيق ملف PDF.

### setDestFileName {#setDestFileName-java.lang.String-}
مهمل.

### setDestStream {#setDestStream-java.io.OutputStream-}
مهمل.

### setResponse {#setResponse-javax.servlet.http.HttpServletResponse-}
الحصول على أو تعيين كائن Response حيث سيتم تخزين نتيجة العملية.

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
الحصول على أو تعيين خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpResponse.

### setSrcFileName {#setSrcFileName-java.lang.String-}
مهمل.

### setSrcStream {#setSrcStream-java.io.InputStream-}
يحصل على تدفق المصدر.

### setXfaData {#setXfaData-java.io.InputStream-}
استبدال بيانات XFA بحزمة البيانات المحددة.
