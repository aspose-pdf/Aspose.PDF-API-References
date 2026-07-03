---
title: FormEditor
second_title: Aspose.PDF for Java API Reference
description: Class for editing forms (adding/deleting field etc)
type: docs
weight: 200
url: /java/com.aspose.pdf.facades/formeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.FormEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IFormEditor, ISaveableFacade, Closeable, AutoCloseable

```
public final class FormEditor extends SaveableFacade implements IFormEditor
```

Class for editing forms (adding/deleting field etc)

## Constructors

| Constructor | Description |
| --- | --- |
| [FormEditor](#FormEditor--) | <p> Constructor for FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-com.aspose.pdf.IDocument-) | <p> Constructor for FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Constructor for FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-com.aspose.pdf.IDocument-java.lang.String-) | <p> Constructor for FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-java.io.InputStream-java.io.OutputStream-) | <p> Constructor for FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-java.lang.String-java.lang.String-) | <p> Constructor for FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |

## Methods

| Method | Description |
| --- | --- |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-) | <p> Add field of specified type to the form. </p> <hr> <pre> FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf"); formEditor.addField(FieldType.Text, "AddedTextField", 1, 10, 30, 110, 46); formEditor.save(); </pre> |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-) | Add field of specified type to the form. |
| [addFieldScript](#addFieldScript-java.lang.String-java.lang.String-) | Add JavaScript for a PushButton field. |
| [addListItem](#addListItem-java.lang.String-java.lang.String-) | <p> Adds new item to the list box. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", PdfForm_out.pdf"); formEditor.addListItem("listBoxField", "Item 4 (New Item)"); </pre> |
| [addListItem](#addListItem-java.lang.String-java.lang.String:A-) | <p> Add a new item with Export value to the existing list box field, only for AcroForm combo box field. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_AddListItem2.pdf"); fe.addListItem("listboxField", new String[] { "4", "Item4(Added)" }); </pre> |
| [addSubmitBtn](#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-) | <p> Add submit button on the form. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_AddSubmitBtn.pdf"); formEditor.addSubmitBtn("submit", 1, "Submit", "www.check.com", 10, 200, 70, 270); </pre> |
| [close](#close--) | Close object instance |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-) | Copies an existing field to the same position in specified page number. A new document will be produced, which contains everything the source document has except for the newly copied field. |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-float-float-) | Copies an existing field to a new position specified by both page number and ordinates. A new document will be produced, which contains everything the source document has except for the newly copied field. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-) | Copies an existing field from one PDF document to another document with original page number and ordinates. Notice: Only for AcroForm fields (excluding radio box). |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-) | Copies an existing field from one PDF document to another document with specified page number and original ordinates. Notice: Only for AcroForm fields (excluding radio box). |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-float-float-) | Copies an existing field from one PDF document to another document with specified page number and ordinates. Notice: Only for AcroForm fields (excluding radio box). |
| [decorateField](#decorateField--) | <p> Changes visual attributes of all fields in the PDF document. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre> |
| [decorateField](#decorateField-com.aspose.pdf.facades.FieldType-) | <p> Changes visual attributes of all fields in the PDF document. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre> |
| [decorateField](#decorateField-java.lang.String-) | <p> Changes visual attributes of all fields in the PDF document. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre> |
| [delListItem](#delListItem-java.lang.String-java.lang.String-) | <p> Delete item from the list field. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_DelListItem.pdf"); formEditor.delListItem("listboxField", "item2"); </pre> |
| [dispose](#dispose--) | Close object instance This method is obsolete, use close() instead. |
| [getAttachmentName](#getAttachmentName--) | Gets name of attachment when result of operation is stored into HttpResponse objects as attachment. |
| [getContentDisposition](#getContentDisposition--) | Gets how content will be stored when result of operation is stored into HttpResponse object. Possible value: inline / attachment. Default: inline. |
| [getDestFileName](#getDestFileName--) | Gets destination file name. |
| [getDestStream](#getDestStream--) | <p> Gets destination stream. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream("OutFile.pdf")); </pre> |
| [getDocument](#getDocument--) | Gets the document {@code FormEditor} is working on. |
| [getExportItems](#getExportItems--) | <p> Gets options for combo box with export values. </p> <hr> |
| [getFacade](#getFacade--) | Gets visual attributes of the field. |
| [getFieldAppearance](#getFieldAppearance-java.lang.String-) | Get field flags. |
| [getItems](#getItems--) | Get Items which will be added to newly created list box or combo box. |
| [getRadioButtonItemSize](#getRadioButtonItemSize--) | Gets or sets size of radio button item size (when new radio button field is added). FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save(); |
| [getRadioGap](#getRadioGap--) | Get the member to record the gap between two neighboring radio buttons in pixels,default is 50. |
| [getRadioHoriz](#getRadioHoriz--) | <p> Get the flag to indicate whether the radios are arranged horizontally or vertically, default value is true. |
| [getSaveOptions](#getSaveOptions--) | Gets save options when result is stored as HttpResponse. Default value: PdfSaveOptions. |
| [getSrcFileName](#getSrcFileName--) | Gets name of source file. |
| [getSrcStream](#getSrcStream--) | Gets source stream. |
| [getSubmitFlag](#getSubmitFlag--) | Get the submit button's submission flags |
| [moveField](#moveField-java.lang.String-float-float-float-float-) | <p> Set new position of field. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_MoveField.pdf"); formEditor.moveField("textField", 20.5f, 20.3f, 120.6f, 40.8f); </pre> |
| [removeField](#removeField-java.lang.String-) | <p> Remove field from the form. </p> <hr> <pre> FormEditr formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveField.pdf"); formEditor.removeField("listboxField"); formEditor.removeField("textField"); </pre> |
| [removeFieldAction](#removeFieldAction-java.lang.String-) | <p> Remove submit action of the field. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveFieldAction.pdf"); formEditor.removeFieldAction("btnSubmit"); </pre> |
| [renameField](#renameField-java.lang.String-java.lang.String-) | <p> Change name of the field. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf"); formEditor.renameField("textField", "textField_Renamed"); </pre> |
| [resetFacade](#resetFacade--) | Reset all visual attribtues to empty value. |
| [resetInnerFacade](#resetInnerFacade--) | Reset all visual attribtues of inner facade to empty value. |
| [save](#save--) | Saves changes into destination file. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Sets name of attachment when result of operation is stored into HttpResponse objects as attachment. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Sets how content will be stored when result of operation is stored into HttpResponse object. Possible value: inline / attachment. Default: inline. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Sets {@link PdfFormat} PDF file format. Result file will be saved in specified file format. If this property is not specified then file will be save in default PDF format without conversion. |
| [setDestFileName](#setDestFileName-java.lang.String-) | <p> Sets destination file name. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestFileName("OutFile.pdf"); </pre> |
| [setDestStream](#setDestStream-java.io.OutputStream-) | <p> Sets destination stream. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream("OutFile.pdf")); </pre> |
| [setExportItems](#setExportItems-java.lang.String:A:A-) | <p> Sets options for combo box with export values. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_Updated.pdf")); formEditor.setExportItems ( new String[][] { new String[] { "1", "Firs" }, new String[] { "2", "Second" }, new String[] { "3", "Third" } }); formEditor.addField(FieldType.ListBox, "AddedListBoxField", "Second", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setFacade](#setFacade-com.aspose.pdf.facades.FormFieldFacade-) | <p> Sets visual attributes of the field. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "PdfForm_DecorateField_text.pdf"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.green); fe.getFacade().setAlignment(FormFieldFacade.AlignCenter); fe.setDecorateField("textField"); fe.save(); </pre> |
| [setFieldAlignment](#setFieldAlignment-java.lang.String-int-) | <p> Set the alignment style of a text field. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_updated.pdf")); formEditor.setFieldAlignment(fieldName, FormFieldFacade.AlignCenter); </pre> |
| [setFieldAlignmentV](#setFieldAlignmentV-java.lang.String-int-) | <p> Set the vertical alignment style of a text field. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf"); fe.setFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom); </pre> |
| [setFieldAppearance](#setFieldAppearance-java.lang.String-int-) | <p> Set field flags </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf"); formEditor.setFieldAppearance("Name", AnnotationFlags.Hidden); formEditor.setFieldAppearance("Phone", AnnotationFlags.NoView \| AnnotationFlags.Print); </pre> |
| [setFieldAttribute](#setFieldAttribute-java.lang.String-int-) | <p> Set attributes of field. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_SetFieldAttribute.pdf"); formEditor.setFieldAttribute("listboxField", PropertyFlag.ReadOnly); formEditor.setFieldAttribute("textField", PropertyFlag.NoExport); </pre> |
| [setFieldCombNumber](#setFieldCombNumber-java.lang.String-int-) | <p> Sets number of combs for a regular single-line text field (the field is automatically divided into as many equally spaced positions, or combs, as the value of combNumber parameter). </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf")); formEditor.setFieldCombNumber("textCombField", 5); </pre> |
| [setFieldLimit](#setFieldLimit-java.lang.String-int-) | <p> Sets maximum character count of the text field. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf"); formEditor.setFieldLimit("textField", 15); </pre> |
| [setFieldScript](#setFieldScript-java.lang.String-java.lang.String-) | Set JavaScript for a PushButton field. If old JavaScript existed, it will be replaced by the new one. |
| [setItems](#setItems-java.lang.String:A-) | <p> Sets items which will be added to newly created list box or combo box. </p> <hr> <pre> formEditor = new com.aspose.pdf.facadesFormEditor("input.pdf", "output.pdf"); formEditor.setItems(new String[] { "AAA", "BBB", "CCC" }); formEditor.addField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setRadioButtonItemSize](#setRadioButtonItemSize-double-) | Gets or sets size of radio button item size (when new radio button field is added). FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save(); |
| [setRadioGap](#setRadioGap-float-) | <p> Set the member to record the gap between two neighboring radio buttons in pixels,default is 50. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setRadioHoriz](#setRadioHoriz-boolean-) | <p> Set the flag to indicate whether the radios are arranged horizontally or vertically, default value is true. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Sets save options when result is stored as HttpResponse. Default value: PdfSaveOptions. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | <p> Sets name of source file. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcFileName("InputFile.pdf"); </pre> |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | <p> Sets source stream. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcStream(new FileInputStream("InFile.pdf")); </pre> |
| [setSubmitFlag](#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-) | <p> Set submit flag of submit button. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitFlag.pdf"); formEditor.setSubmitFlag("btnSubmit", SubmitFormFlag.Fdf); </pre> |
| [setSubmitFlag](#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-) | Set the submit button's submission flags |
| [setSubmitUrl](#setSubmitUrl-java.lang.String-java.lang.String-) | <p> Sets URL of the button. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf"); formEditor.setSubmitUrl("btnSubmit", "www.mysite.com"); </pre> |
| [single2Multiple](#single2Multiple-java.lang.String-) | <p> Change a single-lined text field to a multiple-lined one. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf"); formEditor.single2Multiple("textField"); </pre> |

### FormEditor {#FormEditor--}
```
public FormEditor()
```

<p> Constructor for FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-com.aspose.pdf.IDocument-}
<p> Constructor for FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Constructor for FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-com.aspose.pdf.IDocument-java.lang.String-}
<p> Constructor for FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-java.io.InputStream-java.io.OutputStream-}
<p> Constructor for FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-java.lang.String-java.lang.String-}
<p> Constructor for FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-}
<p> Add field of specified type to the form. </p> <hr> <pre> FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf"); formEditor.addField(FieldType.Text, "AddedTextField", 1, 10, 30, 110, 46); formEditor.save(); </pre>

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-}
Add field of specified type to the form.

### addFieldScript {#addFieldScript-java.lang.String-java.lang.String-}
Add JavaScript for a PushButton field.

### addListItem {#addListItem-java.lang.String-java.lang.String-}
<p> Adds new item to the list box. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", PdfForm_out.pdf"); formEditor.addListItem("listBoxField", "Item 4 (New Item)"); </pre>

### addListItem {#addListItem-java.lang.String-java.lang.String:A-}
<p> Add a new item with Export value to the existing list box field, only for AcroForm combo box field. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_AddListItem2.pdf"); fe.addListItem("listboxField", new String[] { "4", "Item4(Added)" }); </pre>

### addSubmitBtn {#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-}
<p> Add submit button on the form. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_AddSubmitBtn.pdf"); formEditor.addSubmitBtn("submit", 1, "Submit", "www.check.com", 10, 200, 70, 270); </pre>

### close {#close--}
```
public void close()
```

Close object instance

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-}
Copies an existing field to the same position in specified page number. A new document will be produced, which contains everything the source document has except for the newly copied field.

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-float-float-}
Copies an existing field to a new position specified by both page number and ordinates. A new document will be produced, which contains everything the source document has except for the newly copied field.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-}
Copies an existing field from one PDF document to another document with original page number and ordinates. Notice: Only for AcroForm fields (excluding radio box).

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-}
Copies an existing field from one PDF document to another document with specified page number and original ordinates. Notice: Only for AcroForm fields (excluding radio box).

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-float-float-}
Copies an existing field from one PDF document to another document with specified page number and ordinates. Notice: Only for AcroForm fields (excluding radio box).

### decorateField {#decorateField--}
```
public void decorateField()
```

<p> Changes visual attributes of all fields in the PDF document. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre>

### decorateField {#decorateField-com.aspose.pdf.facades.FieldType-}
<p> Changes visual attributes of all fields in the PDF document. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre>

### decorateField {#decorateField-java.lang.String-}
<p> Changes visual attributes of all fields in the PDF document. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre>

### delListItem {#delListItem-java.lang.String-java.lang.String-}
<p> Delete item from the list field. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_DelListItem.pdf"); formEditor.delListItem("listboxField", "item2"); </pre>

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Close object instance This method is obsolete, use close() instead.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Gets name of attachment when result of operation is stored into HttpResponse objects as attachment.

**Returns:**
String object

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

Gets how content will be stored when result of operation is stored into HttpResponse object. Possible value: inline / attachment. Default: inline.

**Returns:**
ContentDisposition element @see ContentDisposition

### getDestFileName {#getDestFileName--}
```
public String getDestFileName()
```

Gets destination file name.

**Returns:**
string object

### getDestStream {#getDestStream--}
```
public OutputStream getDestStream()
```

<p> Gets destination stream. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream("OutFile.pdf")); </pre>

**Returns:**
OutputStream object

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Gets the document {@code FormEditor} is working on.

**Returns:**
IDocument object

### getExportItems {#getExportItems--}
```
public String [][] getExportItems()
```

<p> Gets options for combo box with export values. </p> <hr>

**Returns:**
String[][] object

### getFacade {#getFacade--}
```
public FormFieldFacade getFacade()
```

Gets visual attributes of the field.

**Returns:**
FormFieldFacade object

### getFieldAppearance {#getFieldAppearance-java.lang.String-}
Get field flags.

### getItems {#getItems--}
```
public String [] getItems()
```

Get Items which will be added to newly created list box or combo box.

**Returns:**
String[] object

### getRadioButtonItemSize {#getRadioButtonItemSize--}
```
public double getRadioButtonItemSize()
```

Gets or sets size of radio button item size (when new radio button field is added). FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save();

**Returns:**
double value

### getRadioGap {#getRadioGap--}
```
public float getRadioGap()
```

Get the member to record the gap between two neighboring radio buttons in pixels,default is 50.

**Returns:**
float value

### getRadioHoriz {#getRadioHoriz--}
```
public boolean getRadioHoriz()
```

<p> Get the flag to indicate whether the radios are arranged horizontally or vertically, default value is true.

**Returns:**
boolean value

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Gets save options when result is stored as HttpResponse. Default value: PdfSaveOptions.

**Returns:**
SaveOptions object

### getSrcFileName {#getSrcFileName--}
```
public String getSrcFileName()
```

Gets name of source file.

**Returns:**
string object

### getSrcStream {#getSrcStream--}
```
public InputStream getSrcStream()
```

Gets source stream.

**Returns:**
InputStream object

### getSubmitFlag {#getSubmitFlag--}
```
public SubmitFormFlag getSubmitFlag()
```

Get the submit button's submission flags

**Returns:**
SubmitFormFlag element @see SubmitFormFlag

### moveField {#moveField-java.lang.String-float-float-float-float-}
<p> Set new position of field. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_MoveField.pdf"); formEditor.moveField("textField", 20.5f, 20.3f, 120.6f, 40.8f); </pre>

### removeField {#removeField-java.lang.String-}
<p> Remove field from the form. </p> <hr> <pre> FormEditr formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveField.pdf"); formEditor.removeField("listboxField"); formEditor.removeField("textField"); </pre>

### removeFieldAction {#removeFieldAction-java.lang.String-}
<p> Remove submit action of the field. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveFieldAction.pdf"); formEditor.removeFieldAction("btnSubmit"); </pre>

### renameField {#renameField-java.lang.String-java.lang.String-}
<p> Change name of the field. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf"); formEditor.renameField("textField", "textField_Renamed"); </pre>

### resetFacade {#resetFacade--}
```
public void resetFacade()
```

Reset all visual attribtues to empty value.

### resetInnerFacade {#resetInnerFacade--}
```
public void resetInnerFacade()
```

Reset all visual attribtues of inner facade to empty value.

### save {#save--}
```
@Deprecated public void save()
```

Saves changes into destination file.

### setAttachmentName {#setAttachmentName-java.lang.String-}
Sets name of attachment when result of operation is stored into HttpResponse objects as attachment.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Sets how content will be stored when result of operation is stored into HttpResponse object. Possible value: inline / attachment. Default: inline.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Sets {@link PdfFormat} PDF file format. Result file will be saved in specified file format. If this property is not specified then file will be save in default PDF format without conversion.

### setDestFileName {#setDestFileName-java.lang.String-}
<p> Sets destination file name. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestFileName("OutFile.pdf"); </pre>

### setDestStream {#setDestStream-java.io.OutputStream-}
<p> Sets destination stream. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream("OutFile.pdf")); </pre>

### setExportItems {#setExportItems-java.lang.String:A:A-}
<p> Sets options for combo box with export values. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_Updated.pdf")); formEditor.setExportItems ( new String[][] { new String[] { "1", "Firs" }, new String[] { "2", "Second" }, new String[] { "3", "Third" } }); formEditor.addField(FieldType.ListBox, "AddedListBoxField", "Second", 1, 10, 30, 110, 130); formEditor.save(); </pre>

### setFacade {#setFacade-com.aspose.pdf.facades.FormFieldFacade-}
<p> Sets visual attributes of the field. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "PdfForm_DecorateField_text.pdf"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.green); fe.getFacade().setAlignment(FormFieldFacade.AlignCenter); fe.setDecorateField("textField"); fe.save(); </pre>

### setFieldAlignment {#setFieldAlignment-java.lang.String-int-}
<p> Set the alignment style of a text field. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_updated.pdf")); formEditor.setFieldAlignment(fieldName, FormFieldFacade.AlignCenter); </pre>

### setFieldAlignmentV {#setFieldAlignmentV-java.lang.String-int-}
<p> Set the vertical alignment style of a text field. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf"); fe.setFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom); </pre>

### setFieldAppearance {#setFieldAppearance-java.lang.String-int-}
<p> Set field flags </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf"); formEditor.setFieldAppearance("Name", AnnotationFlags.Hidden); formEditor.setFieldAppearance("Phone", AnnotationFlags.NoView | AnnotationFlags.Print); </pre>

### setFieldAttribute {#setFieldAttribute-java.lang.String-int-}
<p> Set attributes of field. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_SetFieldAttribute.pdf"); formEditor.setFieldAttribute("listboxField", PropertyFlag.ReadOnly); formEditor.setFieldAttribute("textField", PropertyFlag.NoExport); </pre>

### setFieldCombNumber {#setFieldCombNumber-java.lang.String-int-}
<p> Sets number of combs for a regular single-line text field (the field is automatically divided into as many equally spaced positions, or combs, as the value of combNumber parameter). </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf")); formEditor.setFieldCombNumber("textCombField", 5); </pre>

### setFieldLimit {#setFieldLimit-java.lang.String-int-}
<p> Sets maximum character count of the text field. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf"); formEditor.setFieldLimit("textField", 15); </pre>

### setFieldScript {#setFieldScript-java.lang.String-java.lang.String-}
Set JavaScript for a PushButton field. If old JavaScript existed, it will be replaced by the new one.

### setItems {#setItems-java.lang.String:A-}
<p> Sets items which will be added to newly created list box or combo box. </p> <hr> <pre> formEditor = new com.aspose.pdf.facadesFormEditor("input.pdf", "output.pdf"); formEditor.setItems(new String[] { "AAA", "BBB", "CCC" }); formEditor.addField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130); formEditor.save(); </pre>

### setRadioButtonItemSize {#setRadioButtonItemSize-double-}
```
public void setRadioButtonItemSize(double value)
```

Gets or sets size of radio button item size (when new radio button field is added). FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save();

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setRadioGap {#setRadioGap-float-}
```
public void setRadioGap(float value)
```

<p> Set the member to record the gap between two neighboring radio buttons in pixels,default is 50. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save(); </pre>

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | float value |

### setRadioHoriz {#setRadioHoriz-boolean-}
```
public void setRadioHoriz(boolean value)
```

<p> Set the flag to indicate whether the radios are arranged horizontally or vertically, default value is true. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save(); </pre>

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Sets save options when result is stored as HttpResponse. Default value: PdfSaveOptions.

### setSrcFileName {#setSrcFileName-java.lang.String-}
<p> Sets name of source file. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcFileName("InputFile.pdf"); </pre>

### setSrcStream {#setSrcStream-java.io.InputStream-}
<p> Sets source stream. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcStream(new FileInputStream("InFile.pdf")); </pre>

### setSubmitFlag {#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-}
<p> Set submit flag of submit button. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitFlag.pdf"); formEditor.setSubmitFlag("btnSubmit", SubmitFormFlag.Fdf); </pre>

### setSubmitFlag {#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-}
Set the submit button's submission flags

### setSubmitUrl {#setSubmitUrl-java.lang.String-java.lang.String-}
<p> Sets URL of the button. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf"); formEditor.setSubmitUrl("btnSubmit", "www.mysite.com"); </pre>

### single2Multiple {#single2Multiple-java.lang.String-}
<p> Change a single-lined text field to a multiple-lined one. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf"); formEditor.single2Multiple("textField"); </pre>
