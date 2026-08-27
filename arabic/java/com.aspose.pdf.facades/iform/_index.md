---
title: "IForm"
linktitle: "IForm"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثل كائن نموذج Acro."
type: docs
weight: 250
url: /ar/java/com.aspose.pdf.facades/iform/
---
```
public interface IForm extends com.aspose.ms.System.IDisposable, Closeable
```

فئة تمثل كائن نموذج Acro.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [close](#close--) | يغلق الملفات المفتوحة دون أي تغييرات. |
| [exportFdf](#exportFdf-java.io.OutputStream-) | يصدّر محتوى حقول PDF إلى تدفق FDF. |
| [exportXfdf](#exportXfdf-java.io.OutputStream-) | يصدّر محتوى حقول PDF إلى تدفق XML. |
| [exportXml](#exportXml-java.io.OutputStream-) | يصدّر محتوى حقول PDF إلى تدفق XML. |
| [fillBarcodeField](#fillBarcodeField-java.lang.String-java.lang.String-) | املأ حقل الباركود وفقًا لاسمه المؤهل بالكامل. |
| [fillField](#fillField-java.lang.String-boolean-) | يملأ حقل خانة الاختيار بقيمة منطقية. |
| [fillField](#fillField-java.lang.String-int-) | يملأ حقل زر الراديو بقيمة فهرس صالحة وفقًا لاسم الحقل المؤهل بالكامل. |
| [fillField](#fillField-java.lang.String-java.lang.String-) | يملأ الحقل بقيمة صالحة وفقًا لاسم الحقل المؤهل بالكامل. |
| [fillField](#fillField-java.lang.String-java.lang.String:A-) | املأ حقلًا بتحديدات متعددة. ملاحظة: فقط لحقل قائمة AcroForm. |
| [fillField](#fillField-java.lang.String-java.lang.String-boolean-) | FillField |
| [fillImageField](#fillImageField-java.lang.String-java.io.InputStream-) | يوفر إصدارات محملة من الدالة FillImageField. |
| [fillImageField](#fillImageField-java.lang.String-java.lang.String-) | يلصق صورة على حقل الزر الموجود كظهره وفقًا لاسمه المؤهل بالكامل. |
| [flattenAllFields](#flattenAllFields--) | يجعل جميع الحقول ثابتة. |
| [flattenField](#flattenField-java.lang.String-) | يجعل حقلًا محددًا ثابتًا باستخدام اسمه المؤهل بالكامل. |
| [getAttachmentName](#getAttachmentName--) | يحصل أو يعيّن اسم المرفق عندما يتم تخزين نتيجة العملية في كائنات HttpResponse كمرفق. |
| [getButtonOptionCurrentValue](#getButtonOptionCurrentValue-java.lang.String-) | إرجاع القيمة الحالية لحقول خيارات زر الراديو. |
| [getButtonOptionValues](#getButtonOptionValues-java.lang.String-) | الحصول على حقول خيارات زر الراديو والقيم المرتبطة بناءً على اسم الحقل. |
| [getButtonOptionValuesInternal](#getButtonOptionValuesInternal-java.lang.String-) | الحصول على حقول خيارات زر الراديو والقيم المرتبطة بناءً على اسم الحقل. |
| [getContentDisposition](#getContentDisposition--) | يحصل أو يعيّن كيفية تخزين المحتوى عندما يتم تخزين نتيجة العملية في كائن HttpResponse. |
| [getDestFileName](#getDestFileName--) | يحصل على اسم ملف الوجهة. |
| [getDestStream](#getDestStream--) | يحصل على تدفق الوجهة. |
| [getDocument](#getDocument--) | يحصل على نموذج المستند الذي يتم العمل عليه. |
| [getField](#getField-java.lang.String-) | الحصول على قيمة الحقل وفقًا لاسم الحقل. |
| [getFieldFacade](#getFieldFacade-java.lang.String-) | إرجاع كائن FrofmFieldFacade الذي يحتوي على جميع سمات المظهر. |
| [getFieldFlag](#getFieldFlag-java.lang.String-) | إرجاع علامات الحقل. |
| [getFieldLimit](#getFieldLimit-java.lang.String-) | الحصول على قيود حقل النص. |
| [getFieldNames](#getFieldNames--) | الحصول على قائمة بأسماء الحقول في النموذج. |
| [getFieldType](#getFieldType-java.lang.String-) | إرجاع نوع الحقل. |
| [getFormSubmitButtonNames](#getFormSubmitButtonNames--) | الحصول على جميع أسماء أزرار إرسال النموذج. |
| [getFullFieldName](#getFullFieldName-java.lang.String-) | الحصول على الاسم الكامل للحقل وفقًا لاسمه المختصر. |
| [getRichText](#getRichText-java.lang.String-) | الحصول على قيمة حقل النص الغني، بما في ذلك معلومات formattinf لكل حرف. |
| [getSaveOptions](#getSaveOptions--) | الحصول على أو تعيين خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpResponse. |
| [getSrcFileName](#getSrcFileName--) | يحصل على اسم ملف المصدر. |
| [getSrcStream](#getSrcStream--) | يحصل على تدفق المصدر. |
| [getSubmitFlags](#getSubmitFlags-java.lang.String-) | إرجاع علامات إرسال زر الإرسال |
| [importFdf](#importFdf-java.io.InputStream-) | استيراد محتوى الحقول من ملف fdf ووضعه في ملف pdf الجديد. |
| [importXfdf](#importXfdf-java.io.InputStream-) | استيراد محتوى الحقول من ملف xfdf(xml) ووضعه في ملف pdf الجديد. |
| [importXml](#importXml-java.io.InputStream-) | يستورد محتوى الحقول من ملف xml ويضعها في ملف pdf الجديد. |
| [importXml](#importXml-java.io.InputStream-boolean-) | يستورد محتوى الحقول من ملف xml ويضعها في ملف pdf الجديد. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | إعادة تسمية حقل. |
| [save](#save--) | يحفظ قيمة الحقول المملوءة ويغلق مستند PDF المفتوح. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | يضبط اسم المرفق عندما يتم تخزين نتيجة العملية في كائنات HttpResponse كمرفق. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | يضبط كيفية تخزين المحتوى عندما يتم تخزين نتيجة العملية في كائن HttpResponse. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | يضبط تنسيق ملف PDF. |
| [setDestFileName](#setDestFileName-java.lang.String-) | يضبط اسم ملف الوجهة. |
| [setDestStream](#setDestStream-java.io.OutputStream-) | يحصل على تدفق الوجهة. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | الحصول على أو تعيين خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpResponse. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | يضبط اسم الملف المصدر. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | يحصل على تدفق المصدر. |

### close {#close--}
```
void close()
```

يغلق الملفات المفتوحة دون أي تغييرات.

### exportFdf {#exportFdf-java.io.OutputStream-}
يصدّر محتوى حقول PDF إلى تدفق FDF.

### exportXfdf {#exportXfdf-java.io.OutputStream-}
يصدّر محتوى حقول PDF إلى تدفق XML.

### exportXml {#exportXml-java.io.OutputStream-}
يصدّر محتوى حقول PDF إلى تدفق XML.

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
FillField

### fillImageField {#fillImageField-java.lang.String-java.io.InputStream-}
يوفر إصدارات محملة من الدالة FillImageField.

### fillImageField {#fillImageField-java.lang.String-java.lang.String-}
يلصق صورة على حقل الزر الموجود كظهره وفقًا لاسمه المؤهل بالكامل.

### flattenAllFields {#flattenAllFields--}
```
void flattenAllFields()
```

يجعل جميع الحقول ثابتة.

### flattenField {#flattenField-java.lang.String-}
يجعل حقلًا محددًا ثابتًا باستخدام اسمه المؤهل بالكامل.

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

يحصل أو يعيّن اسم المرفق عندما يتم تخزين نتيجة العملية في كائنات HttpResponse كمرفق.

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
ContentDisposition getContentDisposition()
```

يحصل أو يعيّن كيفية تخزين المحتوى عندما يتم تخزين نتيجة العملية في كائن HttpResponse.

**Returns:**
عنصر ContentDisposition

### getDestFileName {#getDestFileName--}
```
String getDestFileName()
```

يحصل على اسم ملف الوجهة.

**Returns:**
كائن String

### getDestStream {#getDestStream--}
```
OutputStream getDestStream()
```

يحصل على تدفق الوجهة.

**Returns:**
كائن OutputStream

### getDocument {#getDocument--}
```
IDocument getDocument()
```

يحصل على نموذج المستند الذي يتم العمل عليه.

**Returns:**
كائن IDocument

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
String [] getFieldNames()
```

الحصول على قائمة بأسماء الحقول في النموذج.

**Returns:**
String[] كائن

### getFieldType {#getFieldType-java.lang.String-}
إرجاع نوع الحقل.

### getFormSubmitButtonNames {#getFormSubmitButtonNames--}
```
String [] getFormSubmitButtonNames()
```

الحصول على جميع أسماء أزرار إرسال النموذج.

**Returns:**
String[] كائن

### getFullFieldName {#getFullFieldName-java.lang.String-}
الحصول على الاسم الكامل للحقل وفقًا لاسمه المختصر.

### getRichText {#getRichText-java.lang.String-}
الحصول على قيمة حقل النص الغني، بما في ذلك معلومات formattinf لكل حرف.

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

الحصول على أو تعيين خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpResponse.

**Returns:**
كائن SaveOptions

### getSrcFileName {#getSrcFileName--}
```
String getSrcFileName()
```

يحصل على اسم ملف المصدر.

**Returns:**
كائن String

### getSrcStream {#getSrcStream--}
```
InputStream getSrcStream()
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

### renameField {#renameField-java.lang.String-java.lang.String-}
إعادة تسمية حقل.

### save {#save--}
```
void save()
```

يحفظ قيمة الحقول المملوءة ويغلق مستند PDF المفتوح.

### setAttachmentName {#setAttachmentName-java.lang.String-}
يضبط اسم المرفق عندما يتم تخزين نتيجة العملية في كائنات HttpResponse كمرفق.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
يضبط كيفية تخزين المحتوى عندما يتم تخزين نتيجة العملية في كائن HttpResponse.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
يضبط تنسيق ملف PDF.

### setDestFileName {#setDestFileName-java.lang.String-}
يضبط اسم ملف الوجهة.

### setDestStream {#setDestStream-java.io.OutputStream-}
يحصل على تدفق الوجهة.

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
الحصول على أو تعيين خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpResponse.

### setSrcFileName {#setSrcFileName-java.lang.String-}
يضبط اسم الملف المصدر.

### setSrcStream {#setSrcStream-java.io.InputStream-}
يحصل على تدفق المصدر.
