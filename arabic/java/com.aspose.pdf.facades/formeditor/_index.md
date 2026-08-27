---
title: "FormEditor"
linktitle: "FormEditor"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة لتحرير النماذج (إضافة/حذف الحقول وما إلى ذلك)."
type: docs
weight: 200
url: /ar/java/com.aspose.pdf.facades/formeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.FormEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IFormEditor, ISaveableFacade, Closeable, AutoCloseable

```
public final class FormEditor extends SaveableFacade implements IFormEditor
```

فئة لتحرير النماذج (إضافة/حذف الحقول وما إلى ذلك).

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [FormEditor](#FormEditor--) | <p> منشئ لـ FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-com.aspose.pdf.IDocument-) | <p> منشئ لـ FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> منشئ لـ FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-com.aspose.pdf.IDocument-java.lang.String-) | <p> منشئ لـ FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-java.io.InputStream-java.io.OutputStream-) | <p> منشئ لـ FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-java.lang.String-java.lang.String-) | <p> منشئ لـ FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-) | <p> أضف حقلًا من النوع المحدد إلى النموذج. </p> <hr> <pre> FormEditor formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_Text.pdf\"); formEditor.addField(FieldType.Text, \"AddedTextField\", 1, 10, 30, 110, 46); formEditor.save(); </pre> |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-) | أضف حقلًا من النوع المحدد إلى النموذج. |
| [addFieldScript](#addFieldScript-java.lang.String-java.lang.String-) | أضف JavaScript لحقل زر الضغط. |
| [addListItem](#addListItem-java.lang.String-java.lang.String-) | <p> يضيف عنصرًا جديدًا إلى صندوق القائمة. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", PdfForm_out.pdf\"); formEditor.addListItem(\"listBoxField\", \"Item 4 (New Item)\"); </pre> |
| [addListItem](#addListItem-java.lang.String-java.lang.String:A-) | <p> أضف عنصرًا جديدًا بقيمة تصدير إلى حقل صندوق القائمة الموجود، فقط لحقل صندوق الجمع AcroForm. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_AddListItem2.pdf\"); fe.addListItem(\"listboxField\", new String[] { \"4\", \"Item4(Added)\" }); </pre> |
| [addSubmitBtn](#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-) | <p> أضف زر إرسال إلى النموذج. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_AddSubmitBtn.pdf\"); formEditor.addSubmitBtn(\"submit\", 1, \"Submit\", \"www.check.com\", 10, 200, 70, 270); </pre> |
| [close](#close--) | إغلاق نسخة الكائن |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-) | ينسخ حقلًا موجودًا إلى نفس الموقع في رقم الصفحة المحدد. سيتم إنشاء مستند جديد يحتوي على كل ما في المستند الأصلي باستثناء الحقل المنسوخ حديثًا. |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-float-float-) | ينسخ حقلًا موجودًا إلى موقع جديد يحدده كل من رقم الصفحة والإحداثيات. سيتم إنشاء مستند جديد يحتوي على كل ما في المستند الأصلي باستثناء الحقل المنسوخ حديثًا. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-) | ينسخ حقلًا موجودًا من مستند PDF إلى مستند آخر مع رقم الصفحة الأصلي والإحداثيات. ملاحظة: يقتصر على حقول AcroForm (باستثناء صندوق الراديو). |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-) | ينسخ حقلًا موجودًا من مستند PDF إلى مستند آخر مع رقم الصفحة المحدد والإحداثيات الأصلية. ملاحظة: يقتصر على حقول AcroForm (باستثناء صندوق الراديو). |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-float-float-) | ينسخ حقلًا موجودًا من مستند PDF إلى مستند آخر مع رقم الصفحة والإحداثيات المحددة. ملاحظة: يقتصر على حقول AcroForm (باستثناء صندوق الراديو). |
| [decorateField](#decorateField--) | <p> يغيّر السمات البصرية لجميع الحقول في مستند PDF. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre> |
| [decorateField](#decorateField-com.aspose.pdf.facades.FieldType-) | <p> يغيّر السمات البصرية لجميع الحقول في مستند PDF. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre> |
| [decorateField](#decorateField-java.lang.String-) | <p> يغيّر السمات البصرية لجميع الحقول في مستند PDF. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre> |
| [delListItem](#delListItem-java.lang.String-java.lang.String-) | <p> حذف عنصر من حقل القائمة. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_DelListItem.pdf\"); formEditor.delListItem(\"listboxField\", \"item2\"); </pre> |
| [dispose](#dispose--) | إغلاق كائن المثيل هذه الطريقة مهجورة، استخدم close() بدلاً من ذلك. |
| [getAttachmentName](#getAttachmentName--) | يحصل على اسم المرفق عندما يتم تخزين نتيجة العملية في كائنات HttpResponse كمرفق. |
| [getContentDisposition](#getContentDisposition--) | يحصل على طريقة تخزين المحتوى عندما يتم تخزين نتيجة العملية في كائن HttpResponse. القيم الممكنة: inline / attachment. الافتراضي: inline. |
| [getDestFileName](#getDestFileName--) | يحصل على اسم ملف الوجهة. |
| [getDestStream](#getDestStream--) | <p> يحصل على تدفق الوجهة. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream(\"OutFile.pdf\")); </pre> |
| [getDocument](#getDocument--) | يحصل على المستند الذي يعمل عليه {@code FormEditor}. |
| [getExportItems](#getExportItems--) | <p> يحصل على الخيارات لصندوق الجمع مع قيم التصدير. </p> <hr> |
| [getFacade](#getFacade--) | يحصل على السمات البصرية للحقل. |
| [getFieldAppearance](#getFieldAppearance-java.lang.String-) | احصل على أعلام الحقل. |
| [getItems](#getItems--) | احصل على العناصر التي ستُضاف إلى صندوق القائمة أو صندوق الجمع الذي تم إنشاؤه حديثًا. |
| [getRadioButtonItemSize](#getRadioButtonItemSize--) | يحصل أو يضبط حجم عنصر زر الراديو (عند إضافة حقل زر راديو جديد). FormEditor formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); |
| [getRadioGap](#getRadioGap--) | احصل على العضو لتسجيل الفجوة بين زرّي راديو متجاورين بالبكسل، الافتراضي هو 50. |
| [getRadioHoriz](#getRadioHoriz--) | <p> احصل على العلامة لتحديد ما إذا كانت أزرار الراديو مرتبة أفقيًا أم عموديًا، القيمة الافتراضية هي true. |
| [getSaveOptions](#getSaveOptions--) | يحصل على خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpResponse. القيمة الافتراضية: PdfSaveOptions. |
| [getSrcFileName](#getSrcFileName--) | يحصل على اسم ملف المصدر. |
| [getSrcStream](#getSrcStream--) | يحصل على تدفق المصدر. |
| [getSubmitFlag](#getSubmitFlag--) | احصل على أعلام إرسال زر الإرسال |
| [moveField](#moveField-java.lang.String-float-float-float-float-) | <p> اضبط الموضع الجديد للحقل. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_MoveField.pdf\"); formEditor.moveField(\"textField\", 20.5f, 20.3f, 120.6f, 40.8f); </pre> |
| [removeField](#removeField-java.lang.String-) | <p> إزالة الحقل من النموذج. </p> <hr> <pre> FormEditr formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_RemoveField.pdf\"); formEditor.removeField(\"listboxField\"); formEditor.removeField(\"textField\"); </pre> |
| [removeFieldAction](#removeFieldAction-java.lang.String-) | <p> إزالة إجراء الإرسال للحقل. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_RemoveFieldAction.pdf\"); formEditor.removeFieldAction(\"btnSubmit\"); </pre> |
| [renameField](#renameField-java.lang.String-java.lang.String-) | <p> تغيير اسم الحقل. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_updated.pdf\"); formEditor.renameField(\"textField\", \"textField_Renamed\"); </pre> |
| [resetFacade](#resetFacade--) | إعادة تعيين جميع السمات البصرية إلى قيمة فارغة. |
| [resetInnerFacade](#resetInnerFacade--) | إعادة تعيين جميع السمات البصرية للواجهة الداخلية إلى قيمة فارغة. |
| [save](#save--) | يحفظ التغييرات في ملف الوجهة. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | يضبط اسم المرفق عندما يتم تخزين نتيجة العملية في كائنات HttpResponse كمرفق. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | يضبط كيفية تخزين المحتوى عندما يتم تخزين نتيجة العملية في كائن HttpResponse. القيم الممكنة: inline / attachment. الافتراضي: inline. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | يضبط تنسيق ملف PDF {@link PdfFormat}. سيتم حفظ ملف النتيجة بالتنسيق المحدد. إذا لم يتم تحديد هذه الخاصية فسيتم حفظ الملف بالتنسيق الافتراضي PDF دون تحويل. |
| [setDestFileName](#setDestFileName-java.lang.String-) | <p> يضبط اسم ملف الوجهة. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestFileName("OutFile.pdf"); </pre> |
| [setDestStream](#setDestStream-java.io.OutputStream-) | <p> يضبط تدفق الوجهة. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream("OutFile.pdf")); </pre> |
| [setExportItems](#setExportItems-java.lang.String:A:A-) | <p> يضبط خيارات صندوق القوائم مع قيم التصدير. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_Updated.pdf")); formEditor.setExportItems ( new String[][] { new String[] { "1", "Firs" }, new String[] { "2", "Second" }, new String[] { "3", "Third" } }); formEditor.addField(FieldType.ListBox, "AddedListBoxField", "Second", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setFacade](#setFacade-com.aspose.pdf.facades.FormFieldFacade-) | <p> يضبط السمات البصرية للحقل. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "PdfForm_DecorateField_text.pdf"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.green); fe.getFacade().setAlignment(FormFieldFacade.AlignCenter); fe.setDecorateField("textField"); fe.save(); </pre> |
| [setFieldAlignment](#setFieldAlignment-java.lang.String-int-) | <p> يضبط نمط محاذاة حقل النص. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_updated.pdf")); formEditor.setFieldAlignment(fieldName, FormFieldFacade.AlignCenter); </pre> |
| [setFieldAlignmentV](#setFieldAlignmentV-java.lang.String-int-) | <p> يضبط نمط المحاذاة العمودية لحقل النص. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf"); fe.setFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom); </pre> |
| [setFieldAppearance](#setFieldAppearance-java.lang.String-int-) | <p> Set field flags </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf"); formEditor.setFieldAppearance("Name", AnnotationFlags.Hidden); formEditor.setFieldAppearance("Phone", AnnotationFlags.NoView \ | AnnotationFlags.Print); </pre> |
| [setFieldAttribute](#setFieldAttribute-java.lang.String-int-) | <p> يضبط سمات الحقل. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_SetFieldAttribute.pdf"); formEditor.setFieldAttribute("listboxField", PropertyFlag.ReadOnly); formEditor.setFieldAttribute("textField", PropertyFlag.NoExport); </pre> |
| [setFieldCombNumber](#setFieldCombNumber-java.lang.String-int-) | <p> يضبط عدد الفواصل (combs) لحقل نص أحادي السطر عادي (يتم تقسيم الحقل تلقائيًا إلى عدد من المواقع المتساوية المسافة، أو الفواصل، وفقًا لقيمة المعامل combNumber). </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf")); formEditor.setFieldCombNumber("textCombField", 5); </pre> |
| [setFieldLimit](#setFieldLimit-java.lang.String-int-) | <p> يضبط الحد الأقصى لعدد الأحرف في حقل النص. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf"); formEditor.setFieldLimit("textField", 15); </pre> |
| [setFieldScript](#setFieldScript-java.lang.String-java.lang.String-) | يضبط JavaScript لحقل زر الضغط. إذا كان هناك JavaScript قديم، سيتم استبداله بالجديد. |
| [setItems](#setItems-java.lang.String:A-) | <p> يضبط العناصر التي ستُضاف إلى صندوق القائمة أو صندوق القوائم المنسدلة الذي تم إنشاؤه حديثًا. </p> <hr> <pre> formEditor = new com.aspose.pdf.facadesFormEditor("input.pdf", "output.pdf"); formEditor.setItems(new String[] { "AAA", "BBB", "CCC" }); formEditor.addField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setRadioButtonItemSize](#setRadioButtonItemSize-double-) | يحصل أو يضبط حجم عنصر زر الراديو (عند إضافة حقل زر راديو جديد). FormEditor formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); |
| [setRadioGap](#setRadioGap-float-) | <p> يضبط الخاصية لتسجيل الفجوة بين زري الراديو المتجاورين بالبكسل، الافتراضي هو 50. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setRadioHoriz](#setRadioHoriz-boolean-) | <p> قم بتعيين العلامة لتحديد ما إذا كانت أزرار الراديو مرتبة أفقياً أو عمودياً، القيمة الافتراضية هي true. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | يضبط خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpResponse. القيمة الافتراضية: PdfSaveOptions. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | <p> يضبط اسم ملف المصدر. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcFileName(\"InputFile.pdf\"); </pre> |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | <p> يضبط تدفق المصدر. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcStream(new FileInputStream(\"InFile.pdf\")); </pre> |
| [setSubmitFlag](#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-) | <p> قم بتعيين علامة الإرسال لزر الإرسال. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_SetSubmitFlag.pdf\"); formEditor.setSubmitFlag(\"btnSubmit\", SubmitFormFlag.Fdf); </pre> |
| [setSubmitFlag](#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-) | قم بتعيين علامات الإرسال لزر الإرسال |
| [setSubmitUrl](#setSubmitUrl-java.lang.String-java.lang.String-) | <p> يضبط عنوان URL للزر. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_SetSubmitUrl.pdf\"); formEditor.setSubmitUrl(\"btnSubmit\", \"www.mysite.com\"); </pre> |
| [single2Multiple](#single2Multiple-java.lang.String-) | <p> غيّر حقل النص ذو السطر الواحد إلى حقل متعدد الأسطر. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_updated.pdf\"); formEditor.single2Multiple(\"textField\"); </pre> |

### FormEditor {#FormEditor--}
```
public FormEditor()
```

<p> منشئ لـ FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-com.aspose.pdf.IDocument-}
<p> منشئ لـ FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> منشئ لـ FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-com.aspose.pdf.IDocument-java.lang.String-}
<p> منشئ لـ FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-java.io.InputStream-java.io.OutputStream-}
<p> منشئ لـ FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-java.lang.String-java.lang.String-}
<p> منشئ لـ FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-}
<p> أضف حقلًا من النوع المحدد إلى النموذج. </p> <hr> <pre> FormEditor formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_Text.pdf\"); formEditor.addField(FieldType.Text, \"AddedTextField\", 1, 10, 30, 110, 46); formEditor.save(); </pre>

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-}
أضف حقلًا من النوع المحدد إلى النموذج.

### addFieldScript {#addFieldScript-java.lang.String-java.lang.String-}
أضف JavaScript لحقل زر الضغط.

### addListItem {#addListItem-java.lang.String-java.lang.String-}
<p> يضيف عنصرًا جديدًا إلى صندوق القائمة. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", PdfForm_out.pdf\"); formEditor.addListItem(\"listBoxField\", \"Item 4 (New Item)\"); </pre>

### addListItem {#addListItem-java.lang.String-java.lang.String:A-}
<p> أضف عنصرًا جديدًا بقيمة تصدير إلى حقل صندوق القائمة الموجود، فقط لحقل صندوق الجمع AcroForm. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_AddListItem2.pdf\"); fe.addListItem(\"listboxField\", new String[] { \"4\", \"Item4(Added)\" }); </pre>

### addSubmitBtn {#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-}
<p> أضف زر إرسال إلى النموذج. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_AddSubmitBtn.pdf\"); formEditor.addSubmitBtn(\"submit\", 1, \"Submit\", \"www.check.com\", 10, 200, 70, 270); </pre>

### close {#close--}
```
public void close()
```

إغلاق نسخة الكائن

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-}
ينسخ حقلًا موجودًا إلى نفس الموقع في رقم الصفحة المحدد. سيتم إنشاء مستند جديد يحتوي على كل ما في المستند الأصلي باستثناء الحقل المنسوخ حديثًا.

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-float-float-}
ينسخ حقلًا موجودًا إلى موقع جديد يحدده كل من رقم الصفحة والإحداثيات. سيتم إنشاء مستند جديد يحتوي على كل ما في المستند الأصلي باستثناء الحقل المنسوخ حديثًا.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-}
ينسخ حقلًا موجودًا من مستند PDF إلى مستند آخر مع رقم الصفحة الأصلي والإحداثيات. ملاحظة: يقتصر على حقول AcroForm (باستثناء صندوق الراديو).

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-}
ينسخ حقلًا موجودًا من مستند PDF إلى مستند آخر مع رقم الصفحة المحدد والإحداثيات الأصلية. ملاحظة: يقتصر على حقول AcroForm (باستثناء صندوق الراديو).

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-float-float-}
ينسخ حقلًا موجودًا من مستند PDF إلى مستند آخر مع رقم الصفحة والإحداثيات المحددة. ملاحظة: يقتصر على حقول AcroForm (باستثناء صندوق الراديو).

### decorateField {#decorateField--}
```
public void decorateField()
```

<p> يغيّر السمات البصرية لجميع الحقول في مستند PDF. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre>

### decorateField {#decorateField-com.aspose.pdf.facades.FieldType-}
<p> يغيّر السمات البصرية لجميع الحقول في مستند PDF. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre>

### decorateField {#decorateField-java.lang.String-}
<p> يغيّر السمات البصرية لجميع الحقول في مستند PDF. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre>

### delListItem {#delListItem-java.lang.String-java.lang.String-}
<p> حذف عنصر من حقل القائمة. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_DelListItem.pdf\"); formEditor.delListItem(\"listboxField\", \"item2\"); </pre>

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

إغلاق كائن المثيل هذه الطريقة مهجورة، استخدم close() بدلاً من ذلك.

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

يحصل على طريقة تخزين المحتوى عندما يتم تخزين نتيجة العملية في كائن HttpResponse. القيم الممكنة: inline / attachment. الافتراضي: inline.

**Returns:**
عنصر ContentDisposition @see ContentDisposition

### getDestFileName {#getDestFileName--}
```
public String getDestFileName()
```

يحصل على اسم ملف الوجهة.

**Returns:**
كائن سلسلة

### getDestStream {#getDestStream--}
```
public OutputStream getDestStream()
```

<p> يحصل على تدفق الوجهة. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream(\"OutFile.pdf\")); </pre>

**Returns:**
كائن OutputStream

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

يحصل على المستند الذي يعمل عليه {@code FormEditor}.

**Returns:**
كائن IDocument

### getExportItems {#getExportItems--}
```
public String [][] getExportItems()
```

<p> يحصل على الخيارات لصندوق الجمع مع قيم التصدير. </p> <hr>

**Returns:**
كائن String[][]

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

احصل على العناصر التي ستُضاف إلى صندوق القائمة أو صندوق الجمع الذي تم إنشاؤه حديثًا.

**Returns:**
String[] كائن

### getRadioButtonItemSize {#getRadioButtonItemSize--}
```
public double getRadioButtonItemSize()
```

يحصل أو يضبط حجم عنصر زر الراديو (عند إضافة حقل زر راديو جديد). FormEditor formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save();

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

<p> احصل على العلامة لتحديد ما إذا كانت أزرار الراديو مرتبة أفقيًا أم عموديًا، القيمة الافتراضية هي true.

**Returns:**
قيمة منطقية

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

يحصل على خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpResponse. القيمة الافتراضية: PdfSaveOptions.

**Returns:**
كائن SaveOptions

### getSrcFileName {#getSrcFileName--}
```
public String getSrcFileName()
```

يحصل على اسم ملف المصدر.

**Returns:**
كائن سلسلة

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
عنصر SubmitFormFlag @see SubmitFormFlag

### moveField {#moveField-java.lang.String-float-float-float-float-}
<p> اضبط الموضع الجديد للحقل. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_MoveField.pdf\"); formEditor.moveField(\"textField\", 20.5f, 20.3f, 120.6f, 40.8f); </pre>

### removeField {#removeField-java.lang.String-}
<p> إزالة الحقل من النموذج. </p> <hr> <pre> FormEditr formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_RemoveField.pdf\"); formEditor.removeField(\"listboxField\"); formEditor.removeField(\"textField\"); </pre>

### removeFieldAction {#removeFieldAction-java.lang.String-}
<p> إزالة إجراء الإرسال للحقل. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_RemoveFieldAction.pdf\"); formEditor.removeFieldAction(\"btnSubmit\"); </pre>

### renameField {#renameField-java.lang.String-java.lang.String-}
<p> تغيير اسم الحقل. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_updated.pdf\"); formEditor.renameField(\"textField\", \"textField_Renamed\"); </pre>

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
@Deprecated public void save()
```

يحفظ التغييرات في ملف الوجهة.

### setAttachmentName {#setAttachmentName-java.lang.String-}
يضبط اسم المرفق عندما يتم تخزين نتيجة العملية في كائنات HttpResponse كمرفق.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
يضبط كيفية تخزين المحتوى عندما يتم تخزين نتيجة العملية في كائن HttpResponse. القيم الممكنة: inline / attachment. الافتراضي: inline.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
يضبط تنسيق ملف PDF {@link PdfFormat}. سيتم حفظ ملف النتيجة بالتنسيق المحدد. إذا لم يتم تحديد هذه الخاصية فسيتم حفظ الملف بالتنسيق الافتراضي PDF دون تحويل.

### setDestFileName {#setDestFileName-java.lang.String-}
<p> يضبط اسم ملف الوجهة. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestFileName("OutFile.pdf"); </pre>

### setDestStream {#setDestStream-java.io.OutputStream-}
<p> يضبط تدفق الوجهة. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream("OutFile.pdf")); </pre>

### setExportItems {#setExportItems-java.lang.String:A:A-}
<p> يضبط خيارات صندوق القوائم مع قيم التصدير. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_Updated.pdf")); formEditor.setExportItems ( new String[][] { new String[] { "1", "Firs" }, new String[] { "2", "Second" }, new String[] { "3", "Third" } }); formEditor.addField(FieldType.ListBox, "AddedListBoxField", "Second", 1, 10, 30, 110, 130); formEditor.save(); </pre>

### setFacade {#setFacade-com.aspose.pdf.facades.FormFieldFacade-}
<p> يضبط السمات البصرية للحقل. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "PdfForm_DecorateField_text.pdf"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.green); fe.getFacade().setAlignment(FormFieldFacade.AlignCenter); fe.setDecorateField("textField"); fe.save(); </pre>

### setFieldAlignment {#setFieldAlignment-java.lang.String-int-}
<p> يضبط نمط محاذاة حقل النص. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_updated.pdf")); formEditor.setFieldAlignment(fieldName, FormFieldFacade.AlignCenter); </pre>

### setFieldAlignmentV {#setFieldAlignmentV-java.lang.String-int-}
<p> يضبط نمط المحاذاة العمودية لحقل النص. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf"); fe.setFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom); </pre>

### setFieldAppearance {#setFieldAppearance-java.lang.String-int-}
<p> قم بتعيين أعلام الحقل </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm1.pdf\", \"FormEditor_SetFieldAppearance.pdf\"); formEditor.setFieldAppearance(\"Name\", AnnotationFlags.Hidden); formEditor.setFieldAppearance(\"Phone\", AnnotationFlags.NoView | AnnotationFlags.Print); </pre>

### setFieldAttribute {#setFieldAttribute-java.lang.String-int-}
<p> يضبط سمات الحقل. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_SetFieldAttribute.pdf"); formEditor.setFieldAttribute("listboxField", PropertyFlag.ReadOnly); formEditor.setFieldAttribute("textField", PropertyFlag.NoExport); </pre>

### setFieldCombNumber {#setFieldCombNumber-java.lang.String-int-}
<p> يضبط عدد الفواصل (combs) لحقل نص أحادي السطر عادي (يتم تقسيم الحقل تلقائيًا إلى عدد من المواقع المتساوية المسافة، أو الفواصل، وفقًا لقيمة المعامل combNumber). </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf")); formEditor.setFieldCombNumber("textCombField", 5); </pre>

### setFieldLimit {#setFieldLimit-java.lang.String-int-}
<p> يضبط الحد الأقصى لعدد الأحرف في حقل النص. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf"); formEditor.setFieldLimit("textField", 15); </pre>

### setFieldScript {#setFieldScript-java.lang.String-java.lang.String-}
يضبط JavaScript لحقل زر الضغط. إذا كان هناك JavaScript قديم، سيتم استبداله بالجديد.

### setItems {#setItems-java.lang.String:A-}
<p> يضبط العناصر التي ستُضاف إلى صندوق القائمة أو صندوق القوائم المنسدلة الذي تم إنشاؤه حديثًا. </p> <hr> <pre> formEditor = new com.aspose.pdf.facadesFormEditor("input.pdf", "output.pdf"); formEditor.setItems(new String[] { "AAA", "BBB", "CCC" }); formEditor.addField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130); formEditor.save(); </pre>

### setRadioButtonItemSize {#setRadioButtonItemSize-double-}
```
public void setRadioButtonItemSize(double value)
```

يحصل أو يضبط حجم عنصر زر الراديو (عند إضافة حقل زر راديو جديد). FormEditor formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save();

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setRadioGap {#setRadioGap-float-}
```
public void setRadioGap(float value)
```

<p> يضبط الخاصية لتسجيل الفجوة بين زري الراديو المتجاورين بالبكسل، الافتراضي هو 50. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save(); </pre>

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة عائمة |

### setRadioHoriz {#setRadioHoriz-boolean-}
```
public void setRadioHoriz(boolean value)
```

<p> قم بتعيين العلامة لتحديد ما إذا كانت أزرار الراديو مرتبة أفقياً أو عمودياً، القيمة الافتراضية هي true. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); </pre>

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
يضبط خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpResponse. القيمة الافتراضية: PdfSaveOptions.

### setSrcFileName {#setSrcFileName-java.lang.String-}
<p> يضبط اسم ملف المصدر. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcFileName(\"InputFile.pdf\"); </pre>

### setSrcStream {#setSrcStream-java.io.InputStream-}
<p> يضبط تدفق المصدر. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcStream(new FileInputStream(\"InFile.pdf\")); </pre>

### setSubmitFlag {#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-}
<p> قم بتعيين علامة الإرسال لزر الإرسال. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_SetSubmitFlag.pdf\"); formEditor.setSubmitFlag(\"btnSubmit\", SubmitFormFlag.Fdf); </pre>

### setSubmitFlag {#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-}
قم بتعيين علامات الإرسال لزر الإرسال

### setSubmitUrl {#setSubmitUrl-java.lang.String-java.lang.String-}
<p> يضبط عنوان URL للزر. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_SetSubmitUrl.pdf\"); formEditor.setSubmitUrl(\"btnSubmit\", \"www.mysite.com\"); </pre>

### single2Multiple {#single2Multiple-java.lang.String-}
<p> غيّر حقل النص ذو السطر الواحد إلى حقل متعدد الأسطر. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_updated.pdf\"); formEditor.single2Multiple(\"textField\"); </pre>
