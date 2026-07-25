---
title: "FormEditorWeb"
linktitle: "FormEditorWeb"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة لتعديل النماذج (إضافة/حذف الحقول إلخ)"
type: docs
weight: 210
url: /ar/java/com.aspose.pdf.facades/formeditorweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditorWeb, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditorWeb, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.FormEditorWeb

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IFormEditor, ISaveableFacade, Closeable, AutoCloseable

```
public final class FormEditorWeb extends SaveableFacade implements IFormEditor
```

فئة لتعديل النماذج (إضافة/حذف الحقول إلخ)

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [FormEditorWeb](#FormEditorWeb--) | <p> منشئ لـ FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-com.aspose.pdf.IDocument-) | <p> منشئ لـ FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> منشئ لـ FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-com.aspose.pdf.IDocument-java.lang.String-) | <p> منشئ لـ FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-) | <p> منشئ لـ FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.io.InputStream-java.io.OutputStream-) | <p> منشئ لـ FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.lang.String-javax.servlet.http.HttpServletResponse-) | <p> منشئ لـ FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.lang.String-java.lang.String-) | <p> منشئ لـ FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-) | أضف حقلًا من النوع المحدد إلى النموذج. |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-) | أضف حقلًا من النوع المحدد إلى النموذج. |
| [addFieldScript](#addFieldScript-java.lang.String-java.lang.String-) | أضف JavaScript لحقل زر الضغط. |
| [addListItem](#addListItem-java.lang.String-java.lang.String-) | يضيف عنصرًا جديدًا إلى صندوق القائمة. |
| [addListItem](#addListItem-java.lang.String-java.lang.String:A-) | أضف عنصرًا جديدًا بقيمة Export إلى حقل صندوق القائمة الموجود، فقط لحقل مربع اختيار AcroForm. |
| [addSubmitBtn](#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-) | أضف زر إرسال على النموذج. |
| [close](#close--) | يغلق جميع الموارد المستخدمة بواسطة هذا المستند. |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-) | ينسخ حقلًا موجودًا إلى نفس الموقع في رقم الصفحة المحدد. |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-float-float-) | ينسخ حقلًا موجودًا إلى موقع جديد محدد برقم الصفحة والإحداثيات. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-) | ينسخ حقلًا موجودًا من مستند PDF إلى مستند آخر مع رقم الصفحة الأصلي والإحداثيات. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-) | ينسخ حقلًا موجودًا من مستند PDF إلى مستند آخر مع رقم الصفحة المحدد والإحداثيات الأصلية. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-float-float-) | ينسخ حقلًا موجودًا من مستند PDF إلى مستند آخر مع رقم الصفحة المحدد والإحداثيات. |
| [decorateField](#decorateField--) | يغيّر السمات البصرية لجميع الحقول في مستند PDF. |
| [decorateField](#decorateField-com.aspose.pdf.facades.FieldType-) | يغيّر السمات البصرية لجميع الحقول بالنوع المحدد. |
| [decorateField](#decorateField-java.lang.String-) | يغيّر السمات البصرية للحقول المحددة. |
| [delListItem](#delListItem-java.lang.String-java.lang.String-) | احذف العنصر من حقل القائمة. |
| [dispose](#dispose--) | مهمل. |
| [getAttachmentName](#getAttachmentName--) | يحصل على اسم المرفق عندما يتم تخزين نتيجة العملية في كائنات HttpResponse كمرفق. |
| [getContentDisposition](#getContentDisposition--) | يحصل على كيفية تخزين المحتوى عندما يتم تخزين نتيجة العملية في كائن HttpResponse. |
| [getDestFileName](#getDestFileName--) | مهمل. |
| [getDestStream](#getDestStream--) | يحصل على تدفق الوجهة. |
| [getExportItems](#getExportItems--) | يحصل على الخيارات لمربع السحب مع قيم التصدير. |
| [getFacade](#getFacade--) | يحصل على السمات البصرية للحقل. |
| [getFieldAppearance](#getFieldAppearance-java.lang.String-) | احصل على أعلام الحقل. |
| [getItems](#getItems--) | يعيد مصفوفة العناصر |
| [getRadioButtonItemSize](#getRadioButtonItemSize--) | يحصل أو يضبط حجم عنصر زر الراديو (عند إضافة حقل زر راديو جديد). |
| [getRadioGap](#getRadioGap--) | احصل على العضو لتسجيل الفجوة بين زرّي راديو متجاورين بالبكسل، الافتراضي هو 50. |
| [getRadioHoriz](#getRadioHoriz--) | احصل على العلامة التي تشير إلى ما إذا كانت أزرار الراديو مرتبة أفقياً أو عمودياً، القيمة الافتراضية هي true. |
| [getResponse](#getResponse--) | يحصل على كائن Response حيث سيتم تخزين نتيجة العملية. |
| [getSaveOptions](#getSaveOptions--) | يحصل على خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpResponse. |
| [getSrcFileName](#getSrcFileName--) | مهمل. |
| [getSrcStream](#getSrcStream--) | يحصل على تدفق المصدر. |
| [getSubmitFlag](#getSubmitFlag--) | احصل على أعلام إرسال زر الإرسال |
| [moveField](#moveField-java.lang.String-float-float-float-float-) | ضبط الموضع الجديد للحقل. |
| [removeField](#removeField-java.lang.String-) | إزالة الحقل من النموذج. |
| [removeFieldAction](#removeFieldAction-java.lang.String-) | إزالة إجراء الإرسال للحقل. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | تغيير اسم الحقل. |
| [resetFacade](#resetFacade--) | إعادة تعيين جميع السمات البصرية إلى قيمة فارغة. |
| [resetInnerFacade](#resetInnerFacade--) | إعادة تعيين جميع السمات البصرية للواجهة الداخلية إلى قيمة فارغة. |
| [save](#save--) | يحفظ التغييرات في ملف الوجهة. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | يضبط اسم المرفق عندما يتم تخزين نتيجة العملية في كائنات HttpResponse كمرفق. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | يضبط كيفية تخزين المحتوى عندما يتم تخزين نتيجة العملية في كائن HttpResponse. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | يضبط تنسيق ملف PDF بصيغة PdfFormat. |
| [setDestFileName](#setDestFileName-java.lang.String-) | مهمل. |
| [setDestStream](#setDestStream-java.io.OutputStream-) | يضبط تدفق الوجهة. |
| [setExportItems](#setExportItems-java.lang.String:A:A-) | يضبط الخيارات لمربع السحب مع قيم التصدير. |
| [setFacade](#setFacade-com.aspose.pdf.facades.FormFieldFacade-) | يضبط السمات البصرية للحقل. |
| [setFieldAlignment](#setFieldAlignment-java.lang.String-int-) | ضبط نمط محاذاة حقل النص. |
| [setFieldAlignmentV](#setFieldAlignmentV-java.lang.String-int-) | ضبط نمط المحاذاة العمودية لحقل النص. |
| [setFieldAppearance](#setFieldAppearance-java.lang.String-int-) | ضبط علامات الحقل |
| [setFieldAttribute](#setFieldAttribute-java.lang.String-int-) | ضبط سمات الحقل. |
| [setFieldCombNumber](#setFieldCombNumber-java.lang.String-int-) | يضبط عدد الفواصل لحقل نص أحادي السطر عادي (يتم تقسيم الحقل تلقائيًا إلى عدد من المواقع المتساوية المسافة، أو الفواصل، وفقًا لقيمة معامل combNumber). |
| [setFieldLimit](#setFieldLimit-java.lang.String-int-) | يضبط الحد الأقصى لعدد الأحرف في حقل النص. |
| [setFieldScript](#setFieldScript-java.lang.String-java.lang.String-) | ضبط JavaScript لحقل PushButton. |
| [setItems](#setItems-java.lang.String:A-) | يضبط العناصر التي ستُضاف إلى صندوق القائمة أو مربع السحب الذي تم إنشاؤه حديثًا. |
| [setRadioButtonItemSize](#setRadioButtonItemSize-double-) | يحصل أو يضبط حجم عنصر زر الراديو (عند إضافة حقل زر راديو جديد). |
| [setRadioGap](#setRadioGap-float-) | ضبط العضو لتسجيل الفجوة بين زرين راديو متجاورين بالبكسل، القيمة الافتراضية هي 50. |
| [setRadioHoriz](#setRadioHoriz-boolean-) | ضبط العلامة التي تشير إلى ما إذا كانت أزرار الراديو مرتبة أفقياً أو عمودياً، القيمة الافتراضية هي true. |
| [setResponse](#setResponse-javax.servlet.http.HttpServletResponse-) | يضبط كائن Response حيث سيتم تخزين نتيجة العملية. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | يضبط خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpResponse. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | مهمل. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | يضبط تدفق المصدر. |
| [setSubmitFlag](#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-) | ضبط علامة الإرسال لزر الإرسال. |
| [setSubmitFlag](#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-) | قم بتعيين علامات الإرسال لزر الإرسال |
| [setSubmitUrl](#setSubmitUrl-java.lang.String-java.lang.String-) | يضبط عنوان URL للزر. |
| [single2Multiple](#single2Multiple-java.lang.String-) | تغيير حقل نصي سطر واحد إلى حقل متعدد الأسطر. |

### FormEditorWeb {#FormEditorWeb--}
```
public FormEditorWeb()
```

<p> منشئ لـ FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-com.aspose.pdf.IDocument-}
<p> منشئ لـ FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> منشئ لـ FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-com.aspose.pdf.IDocument-java.lang.String-}
<p> منشئ لـ FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-}
<p> منشئ لـ FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.io.InputStream-java.io.OutputStream-}
<p> منشئ لـ FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.lang.String-javax.servlet.http.HttpServletResponse-}
<p> منشئ لـ FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.lang.String-java.lang.String-}
<p> منشئ لـ FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-}
أضف حقلًا من النوع المحدد إلى النموذج.

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-}
أضف حقلًا من النوع المحدد إلى النموذج.

### addFieldScript {#addFieldScript-java.lang.String-java.lang.String-}
أضف JavaScript لحقل زر الضغط.

### addListItem {#addListItem-java.lang.String-java.lang.String-}
يضيف عنصرًا جديدًا إلى صندوق القائمة.

### addListItem {#addListItem-java.lang.String-java.lang.String:A-}
أضف عنصرًا جديدًا بقيمة Export إلى حقل صندوق القائمة الموجود، فقط لحقل مربع اختيار AcroForm.

### addSubmitBtn {#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-}
أضف زر إرسال على النموذج.

### close {#close--}
```
public void close()
```

يغلق جميع الموارد المستخدمة بواسطة هذا المستند.

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-}
ينسخ حقلًا موجودًا إلى نفس الموقع في رقم الصفحة المحدد.

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-float-float-}
ينسخ حقلًا موجودًا إلى موقع جديد محدد برقم الصفحة والإحداثيات.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-}
ينسخ حقلًا موجودًا من مستند PDF إلى مستند آخر مع رقم الصفحة الأصلي والإحداثيات.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-}
ينسخ حقلًا موجودًا من مستند PDF إلى مستند آخر مع رقم الصفحة المحدد والإحداثيات الأصلية.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-float-float-}
ينسخ حقلًا موجودًا من مستند PDF إلى مستند آخر مع رقم الصفحة المحدد والإحداثيات.

### decorateField {#decorateField--}
```
public void decorateField()
```

يغيّر السمات البصرية لجميع الحقول في مستند PDF.

### decorateField {#decorateField-com.aspose.pdf.facades.FieldType-}
يغيّر السمات البصرية لجميع الحقول بالنوع المحدد.

### decorateField {#decorateField-java.lang.String-}
يغيّر السمات البصرية للحقول المحددة.

### delListItem {#delListItem-java.lang.String-java.lang.String-}
احذف العنصر من حقل القائمة.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

مهمل.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

يحصل على اسم المرفق عندما يتم تخزين نتيجة العملية في كائنات HttpResponse كمرفق.

**Returns:**
كائن String

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

يحصل على كيفية تخزين المحتوى عندما يتم تخزين نتيجة العملية في كائن HttpResponse.

**Returns:**
عنصر ContentDisposition

### getDestFileName {#getDestFileName--}
```
@Deprecated public String getDestFileName()
```

مهمل.

**Returns:**
قيمة السلسلة

### getDestStream {#getDestStream--}
```
public OutputStream getDestStream()
```

يحصل على تدفق الوجهة.

**Returns:**
كائن OutputStream

### getExportItems {#getExportItems--}
```
public String [][] getExportItems()
```

يحصل على الخيارات لمربع السحب مع قيم التصدير.

**Returns:**
مصفوفة String[][]

### getFacade {#getFacade--}
```
public FormFieldFacade getFacade()
```

يحصل على السمات البصرية للحقل.

**Returns:**
كائن FormFieldFacade

### getFieldAppearance {#getFieldAppearance-java.lang.String-}
احصل على أعلام الحقل.

### getItems {#getItems--}
```
public String [] getItems()
```

يعيد مصفوفة العناصر

**Returns:**
String[] كائن

### getRadioButtonItemSize {#getRadioButtonItemSize--}
```
public double getRadioButtonItemSize()
```

يحصل أو يضبط حجم عنصر زر الراديو (عند إضافة حقل زر راديو جديد).

**Returns:**
قيمة double

### getRadioGap {#getRadioGap--}
```
public float getRadioGap()
```

احصل على العضو لتسجيل الفجوة بين زرّي راديو متجاورين بالبكسل، الافتراضي هو 50.

**Returns:**
قيمة عائمة

### getRadioHoriz {#getRadioHoriz--}
```
public boolean getRadioHoriz()
```

احصل على العلامة التي تشير إلى ما إذا كانت أزرار الراديو مرتبة أفقياً أو عمودياً، القيمة الافتراضية هي true.

**Returns:**
قيمة منطقية

### getResponse {#getResponse--}
```
public javax.servlet.http.HttpServletResponse getResponse()
```

يحصل على كائن Response حيث سيتم تخزين نتيجة العملية.

**Returns:**
كائن HttpServletResponse

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

يحصل على خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpResponse.

**Returns:**
كائن SaveOptions

### getSrcFileName {#getSrcFileName--}
```
@Deprecated public String getSrcFileName()
```

مهمل.

**Returns:**
قيمة السلسلة

### getSrcStream {#getSrcStream--}
```
public InputStream getSrcStream()
```

يحصل على تدفق المصدر.

**Returns:**
كائن InputStream

### getSubmitFlag {#getSubmitFlag--}
```
public SubmitFormFlag getSubmitFlag()
```

احصل على أعلام إرسال زر الإرسال

**Returns:**
عنصر SubmitFormFlag

### moveField {#moveField-java.lang.String-float-float-float-float-}
ضبط الموضع الجديد للحقل.

### removeField {#removeField-java.lang.String-}
إزالة الحقل من النموذج.

### removeFieldAction {#removeFieldAction-java.lang.String-}
إزالة إجراء الإرسال للحقل.

### renameField {#renameField-java.lang.String-java.lang.String-}
تغيير اسم الحقل.

### resetFacade {#resetFacade--}
```
public void resetFacade()
```

إعادة تعيين جميع السمات البصرية إلى قيمة فارغة.

### resetInnerFacade {#resetInnerFacade--}
```
public void resetInnerFacade()
```

إعادة تعيين جميع السمات البصرية للواجهة الداخلية إلى قيمة فارغة.

### save {#save--}
```
public void save()
```

يحفظ التغييرات في ملف الوجهة.

### setAttachmentName {#setAttachmentName-java.lang.String-}
يضبط اسم المرفق عندما يتم تخزين نتيجة العملية في كائنات HttpResponse كمرفق.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
يضبط كيفية تخزين المحتوى عندما يتم تخزين نتيجة العملية في كائن HttpResponse.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
يضبط تنسيق ملف PDF بصيغة PdfFormat.

### setDestFileName {#setDestFileName-java.lang.String-}
مهمل.

### setDestStream {#setDestStream-java.io.OutputStream-}
يضبط تدفق الوجهة.

### setExportItems {#setExportItems-java.lang.String:A:A-}
يضبط الخيارات لمربع السحب مع قيم التصدير.

### setFacade {#setFacade-com.aspose.pdf.facades.FormFieldFacade-}
يضبط السمات البصرية للحقل.

### setFieldAlignment {#setFieldAlignment-java.lang.String-int-}
ضبط نمط محاذاة حقل النص.

### setFieldAlignmentV {#setFieldAlignmentV-java.lang.String-int-}
ضبط نمط المحاذاة العمودية لحقل النص.

### setFieldAppearance {#setFieldAppearance-java.lang.String-int-}
ضبط علامات الحقل

### setFieldAttribute {#setFieldAttribute-java.lang.String-int-}
ضبط سمات الحقل.

### setFieldCombNumber {#setFieldCombNumber-java.lang.String-int-}
يضبط عدد الفواصل لحقل نص أحادي السطر عادي (يتم تقسيم الحقل تلقائيًا إلى عدد من المواقع المتساوية المسافة، أو الفواصل، وفقًا لقيمة معامل combNumber).

### setFieldLimit {#setFieldLimit-java.lang.String-int-}
يضبط الحد الأقصى لعدد الأحرف في حقل النص.

### setFieldScript {#setFieldScript-java.lang.String-java.lang.String-}
ضبط JavaScript لحقل PushButton.

### setItems {#setItems-java.lang.String:A-}
يضبط العناصر التي ستُضاف إلى صندوق القائمة أو مربع السحب الذي تم إنشاؤه حديثًا.

### setRadioButtonItemSize {#setRadioButtonItemSize-double-}
```
public void setRadioButtonItemSize(double value)
```

يحصل أو يضبط حجم عنصر زر الراديو (عند إضافة حقل زر راديو جديد).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setRadioGap {#setRadioGap-float-}
```
public void setRadioGap(float value)
```

ضبط العضو لتسجيل الفجوة بين زرين راديو متجاورين بالبكسل، القيمة الافتراضية هي 50.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة عائمة |

### setRadioHoriz {#setRadioHoriz-boolean-}
```
public void setRadioHoriz(boolean value)
```

ضبط العلامة التي تشير إلى ما إذا كانت أزرار الراديو مرتبة أفقياً أو عمودياً، القيمة الافتراضية هي true.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setResponse {#setResponse-javax.servlet.http.HttpServletResponse-}
يضبط كائن Response حيث سيتم تخزين نتيجة العملية.

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
يضبط خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpResponse.

### setSrcFileName {#setSrcFileName-java.lang.String-}
مهمل.

### setSrcStream {#setSrcStream-java.io.InputStream-}
يضبط تدفق المصدر.

### setSubmitFlag {#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-}
ضبط علامة الإرسال لزر الإرسال.

### setSubmitFlag {#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-}
قم بتعيين علامات الإرسال لزر الإرسال

### setSubmitUrl {#setSubmitUrl-java.lang.String-java.lang.String-}
يضبط عنوان URL للزر.

### single2Multiple {#single2Multiple-java.lang.String-}
تغيير حقل نصي سطر واحد إلى حقل متعدد الأسطر.
