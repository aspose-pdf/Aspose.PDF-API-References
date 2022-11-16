---
title: FormEditorWeb
second_title: 用于 Java API 参考的 Aspose.PDF
description: 用于编辑表单添加/删除字段等的类
type: docs
weight: 27
url: /zh/java/com.aspose.pdf.facades/formeditorweb/
---
**遗产：**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade), com.aspose.pdf.facades.AFormEditor

**所有已实现的接口：**
[com.aspose.pdf.facades.IFormEditor](../../com.aspose.pdf.facades/iformeditor)
```
public final class FormEditorWeb extends AFormEditor implements IFormEditor
```

用于编辑表单的类（添加/删除字段等）
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FormEditorWeb()](#FormEditorWeb--) | FormEditorWeb 的构造函数。 |
| [FormEditorWeb(IDocument document)](#FormEditorWeb-com.aspose.pdf.IDocument-) | 在文档的基础上初始化新的 FormEditorWeb 对象。 |
| [FormEditorWeb(IDocument document, OutputStream destStream)](#FormEditorWeb-com.aspose.pdf.IDocument-java.io.OutputStream-) | 在文档的基础上初始化新的 FormEditorWeb 对象。 |
| [FormEditorWeb(IDocument document, String destFileName)](#FormEditorWeb-com.aspose.pdf.IDocument-java.lang.String-) | 在文档的基础上初始化新的 FormEditorWeb 对象。 |
| [FormEditorWeb(InputStream inputStream, HttpServletResponse response)](#FormEditorWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-) | 创建 FormEditorWeb，它将结果保存到 HttpResponse 对象中。 |
| [FormEditorWeb(InputStream srcStream, OutputStream destStream)](#FormEditorWeb-java.io.InputStream-java.io.OutputStream-) | FormEditorWeb 的构造函数。 |
| [FormEditorWeb(String inputFile, HttpServletResponse response)](#FormEditorWeb-java.lang.String-javax.servlet.http.HttpServletResponse-) | 创建 FormEditorWeb，它将结果保存到 HttpResponse 对象中。 |
| [FormEditorWeb(String srcFileName, String destFileName)](#FormEditorWeb-java.lang.String-java.lang.String-) | FormEditorWeb 的构造函数 |
## 方法

| Method | Description |
| --- | --- |
| [addField(int fieldType, String fieldName, int pageNum, float llx, float lly, float urx, float ury)](#addField-int-java.lang.String-int-float-float-float-float-) | Add field of specified type to the form. |
| [addField(int fieldType, String fieldName, String initValue, int pageNum, float llx, float lly, float urx, float ury)](#addField-int-java.lang.String-java.lang.String-int-float-float-float-float-) | Add field of specified type to the form. |
| [addFieldScript(String fieldName, String script)](#addFieldScript-java.lang.String-java.lang.String-) | Add JavaScript for a PushButton field. |
| [addListItem(String fieldName, String itemName)](#addListItem-java.lang.String-java.lang.String-) | Adds new item to the list box. |
| [addListItem(String fieldName, String[] exportName)](#addListItem-java.lang.String-java.lang.String---) | Add a new item with Export value to the existing list box field, only for AcroForm combo box field. |
| [addSubmitBtn(String fieldName, int page, String label, String url, float llx, float lly, float urx, float ury)](#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-) | Add submit button on the form. |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | Initializes the facade. |
| [bindPdf(InputStream srcStream)](#bindPdf-java.io.InputStream-) | Initializes the facade. |
| [bindPdf(InputStream srcStream, String password)](#bindPdf-java.io.InputStream-java.lang.String-) | Initializes the facade. |
| [bindPdf(String srcFile)](#bindPdf-java.lang.String-) | Initializes the facade. |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | Initializes the facade. |
| [close()](#close--) | Closes all resources used by this document. |
| [copyInnerField(String fieldName, String newFieldName, int pageNum)](#copyInnerField-java.lang.String-java.lang.String-int-) | Copies an existing field to the same position in specified page number. |
| [copyInnerField(String fieldName, String newFieldName, int pageNum, float abscissa, float ordinate)](#copyInnerField-java.lang.String-java.lang.String-int-float-float-) | Copies an existing field to a new position specified by both page number and ordinates. |
| [copyOuterField(String srcFileName, String fieldName)](#copyOuterField-java.lang.String-java.lang.String-) | Copies an existing field from one PDF document to another document with original page number and ordinates. |
| [copyOuterField(String srcFileName, String fieldName, int pageNum)](#copyOuterField-java.lang.String-java.lang.String-int-) | Copies an existing field from one PDF document to another document with specified page number and original ordinates. |
| [copyOuterField(String srcFileName, String fieldName, int pageNum, float abscissa, float ordinate)](#copyOuterField-java.lang.String-java.lang.String-int-float-float-) | Copies an existing field from one PDF document to another document with specified page number and ordinates. |
| [decorateField()](#decorateField--) | Changes visual attributes of all fields in the PDF document. |
| [decorateField(int fieldType)](#decorateField-int-) | Changes visual attributes of all fields with the specified field type. |
| [decorateField(String fieldName)](#decorateField-java.lang.String-) | Changes visual attributes of the specified field. |
| [delListItem(String fieldName, String itemName)](#delListItem-java.lang.String-java.lang.String-) | Delete item from the list field. |
| [dispose()](#dispose--) | Closes all resources used by this document. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttachmentName()](#getAttachmentName--) | Gets name of attachment when result of operation is stored into HttpResponse objects as attachment. |
| [getClass()](#getClass--) |  |
| [getContentDisposition()](#getContentDisposition--) | Gets how content will be stored when result of operation is stored into HttpResponse object. |
| [getDestFileName()](#getDestFileName--) | Gets destination file name. |
| [getDestStream()](#getDestStream--) | Gets destination stream. |
| [getDocument()](#getDocument--) | Gets the document facade is working on. |
| [getExportItems()](#getExportItems--) | Gets options for combo box with export values. |
| [getFacade()](#getFacade--) | Gets visual attributes of the field. |
| [getFieldAppearance(String fieldName)](#getFieldAppearance-java.lang.String-) | Get field flags. |
| [getItems()](#getItems--) |  |
| [getRadioButtonItemSize()](#getRadioButtonItemSize--) | Gets or sets size of radio button item size (when new radio button field is added). |
| [getRadioGap()](#getRadioGap--) | Get the member to record the gap between two neighboring radio buttons in pixels,default is 50. |
| [getRadioHoriz()](#getRadioHoriz--) | Get the flag to indicate whether the radios are arranged horizontally or vertically, default value is true. |
| [getResponse()](#getResponse--) | Gets Response object where result of operation will be stored. |
| [getSaveOptions()](#getSaveOptions--) | Gets save options when result is stored as HttpResponse. |
| [getSrcFileName()](#getSrcFileName--) | Gets name of source file. |
| [getSrcStream()](#getSrcStream--) | Gets source stream. |
| [getSubmitFlag()](#getSubmitFlag--) | Get the submit button's submission flags |
| [hashCode()](#hashCode--) |  |
| [moveField(String fieldName, float llx, float lly, float urx, float ury)](#moveField-java.lang.String-float-float-float-float-) | Set new position of field. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeField(String fieldName)](#removeField-java.lang.String-) | Remove field from the form. |
| [removeFieldAction(String fieldName)](#removeFieldAction-java.lang.String-) | Remove submit action of the field. |
| [renameField(String fieldName, String newFieldName)](#renameField-java.lang.String-java.lang.String-) | Change name of the field. |
| [resetFacade()](#resetFacade--) | Reset all visual attributes to empty value. |
| [resetInnerFacade()](#resetInnerFacade--) | Reset all visual attributes of inner facade to empty value. |
| [save()](#save--) | Saves changes into destination file. |
| [save(OutputStream destStream)](#save-java.io.OutputStream-) | Saves the PDF document to the specified stream. |
| [save(String destFile)](#save-java.lang.String-) | Saves the PDF document to the specified file. |
| [setAttachmentName(String value)](#setAttachmentName-java.lang.String-) | Sets name of attachment when result of operation is stored into HttpResponse objects as attachment. |
| [setContentDisposition(int value)](#setContentDisposition-int-) | Sets how content will be stored when result of operation is stored into HttpResponse object. |
| [setConvertTo(PdfFormat value)](#setConvertTo-com.aspose.pdf.PdfFormat-) | Sets [PdfFormat](../../com.aspose.pdf/pdfformat) PDF file format. |
| [setDestFileName(String value)](#setDestFileName-java.lang.String-) | Sets destination file name. |
| [setDestStream(OutputStream value)](#setDestStream-java.io.OutputStream-) | Sets destination stream. |
| [setExportItems(String[][] value)](#setExportItems-java.lang.String-----) | Sets options for combo box with export values. |
| [setFacade(FormFieldFacade value)](#setFacade-com.aspose.pdf.facades.FormFieldFacade-) | Sets visual attributes of the field. |
| [setFieldAlignment(String fieldName, int alignment)](#setFieldAlignment-java.lang.String-int-) | Set the alignment style of a text field. |
| [setFieldAlignmentV(String fieldName, int alignment)](#setFieldAlignmentV-java.lang.String-int-) | Set the vertical alignment style of a text field. |
| [setFieldAppearance(String fieldName, int flags)](#setFieldAppearance-java.lang.String-int-) | Set field flags |
| [setFieldAttribute(String fieldName, int flag)](#setFieldAttribute-java.lang.String-int-) | Set attributes of field. |
| [setFieldCombNumber(String fieldName, int combNumber)](#setFieldCombNumber-java.lang.String-int-) | Sets number of combs for a regular single-line text field (the field is automatically divided into as many equally spaced positions, or combs, as the value of combNumber parameter). |
| [setFieldLimit(String fieldName, int fieldLimit)](#setFieldLimit-java.lang.String-int-) | Sets maximum character count of the text field. |
| [setFieldScript(String fieldName, String script)](#setFieldScript-java.lang.String-java.lang.String-) | Set JavaScript for a PushButton field. |
| [setItems(String[] value)](#setItems-java.lang.String---) | Sets items which will be added to newly created list box or combo box. |
| [setRadioButtonItemSize(double value)](#setRadioButtonItemSize-double-) | ```
Gets or sets size of radio button item size (when new radio button field is added).
``` |
| [setRadioGap(float value)](#setRadioGap-float-) | Set the member to record the gap between two neighboring radio buttons in pixels,default is 50. |
| [setRadioHoriz(boolean value)](#setRadioHoriz-boolean-) | Set the flag to indicate whether the radios are arranged horizontally or vertically, default value is true. |
| [setResponse(HttpServletResponse value)](#setResponse-javax.servlet.http.HttpServletResponse-) | Sets Response object where result of operation will be stored. |
| [setSaveOptions(SaveOptions value)](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Sets save options when result is stored as HttpResponse. |
| [setSrcFileName(String value)](#setSrcFileName-java.lang.String-) | Sets name of source file. |
| [setSrcStream(InputStream value)](#setSrcStream-java.io.InputStream-) | Sets source stream. |
| [setSubmitFlag(int value)](#setSubmitFlag-int-) | Set the submit button's submission flags |
| [setSubmitFlag(String fieldName, int submitFormFlag)](#setSubmitFlag-java.lang.String-int-) | Set submit flag of submit button. |
| [setSubmitUrl(String fieldName, String url)](#setSubmitUrl-java.lang.String-java.lang.String-) | Sets URL of the button. |
| [single2Multiple(String fieldName)](#single2Multiple-java.lang.String-) | Change a single-lined text field to a multiple-lined one. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FormEditorWeb() {#FormEditorWeb--}
```
公共 FormEditorWeb()
```


Constructor for FormEditorWeb.

--------------------

```
FormEditorWeb FormEditorWeb = new FormEditorWeb();
```

### FormEditorWeb(IDocument document) {#FormEditorWeb-com.aspose.pdf.IDocument-}
```
公共 FormEditorWeb（IDocument 文档）
```


Initializes new  FormEditorWeb  object on base of the  document .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Pdf document. |

### FormEditorWeb(IDocument document, OutputStream destStream) {#FormEditorWeb-com.aspose.pdf.IDocument-java.io.OutputStream-}
```
公共 FormEditorWeb（IDocument 文档，OutputStream destStream）
```


Initializes new  FormEditorWeb  object on base of the  document .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Pdf document. |
| destStream | java.io.OutputStream | Destination stream. |

### FormEditorWeb(IDocument document, String destFileName) {#FormEditorWeb-com.aspose.pdf.IDocument-java.lang.String-}
```
公共 FormEditorWeb（IDocument 文档，字符串 destFileName）
```


Initializes new  FormEditorWeb  object on base of the  document .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Pdf document. |
| destFileName | java.lang.String | Path of the destination file. |

### FormEditorWeb(InputStream inputStream, HttpServletResponse response) {#FormEditorWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-}
```
公共 FormEditorWeb（InputStream inputStream，HttpServletResponse 响应）
```


Creates FormEditorWeb which will save result into HttpResponse object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Source stream. |
| response | javax.servlet.http.HttpServletResponse | HttpResponse object where result will be saved. |

### FormEditorWeb(InputStream srcStream, OutputStream destStream) {#FormEditorWeb-java.io.InputStream-java.io.OutputStream-}
```
公共 FormEditorWeb（输入流 srcStream，输出流 destStream）
```


Constructor for FormEditorWeb.

--------------------

```
FormEditorWeb FormEditorWeb = new FormEditorWeb(new FileInputStream("InFile.pdf"), new FileOutputStream("OutFile.pdf"));
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | java.io.InputStream | Source stream. |
| destStream | java.io.OutputStream | Destination stream. |

### FormEditorWeb(String inputFile, HttpServletResponse response) {#FormEditorWeb-java.lang.String-javax.servlet.http.HttpServletResponse-}
```
公共 FormEditorWeb（字符串输入文件，HttpServletResponse 响应）
```


Creates FormEditorWeb which will save result into HttpResponse object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Source file name. |
| response | javax.servlet.http.HttpServletResponse | HttpResponse objects where result be saved. |

### FormEditorWeb(String srcFileName, String destFileName) {#FormEditorWeb-java.lang.String-java.lang.String-}
```
公共 FormEditorWeb（字符串 srcFileName，字符串 destFileName）
```


Constructor for FormEditorWeb

--------------------

```
FormEditorWeb FormEditorWeb = new FormEditorWeb("InFile.pdf", "OutFile.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | java.lang.String | Name of source file. |
| destFileName | java.lang.String | Name of destination file. |

### addField(int fieldType, String fieldName, int pageNum, float llx, float lly, float urx, float ury) {#addField-int-java.lang.String-int-float-float-float-float-}
```
public boolean addField(int fieldType, String fieldName, int pageNum, float llx, float lly, float urx, float ury)
```


Add field of specified type to the form.

--------------------

```
FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf");
 formEditor.addField(FieldType.Text, "AddedTextField", 1, 10, 30, 110, 46);
 formEditor.save();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldType | int | Type of the field which must be added. |
| fieldName | java.lang.String | Name of the field which must be added. |
| pageNum | int | Page number where new field must be placed. |
| llx | float | Abscissa of the lower-left corner of the field. |
| lly | float | Ordinate of the lower-left corner of the field. |
| urx | float | Abscissa of the upper-right corner of the field. |
| ury | float | Ordinate of the upper-right corner of the field. |

**Returns:**
boolean - true if field was successfully added.
### addField(int fieldType, String fieldName, String initValue, int pageNum, float llx, float lly, float urx, float ury) {#addField-int-java.lang.String-java.lang.String-int-float-float-float-float-}
```
public boolean addField(int fieldType, String fieldName, String initValue, int pageNum, float llx, float lly, float urx, float ury)
```


Add field of specified type to the form.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldType | int | Type of the field which must be added. |
| fieldName | java.lang.String | Name of the field which must be added. |
| initValue | java.lang.String | Initial value of the field. |
| pageNum | int | Page number where new field must be placed. |
| llx | float | Abscissa of the lower-left corner of the field. |
| lly | float | Ordinate of the lower-left corner of the field. |
| urx | float | Abscissa of the upper-right corner of the field. |
| ury | float | Ordinate of the upper-right corner of the field. |

**Returns:**
boolean - true if field was successfully added.
### addFieldScript(String fieldName, String script) {#addFieldScript-java.lang.String-java.lang.String-}
```
public boolean addFieldScript(String fieldName, String script)
```


Add JavaScript for a PushButton field. If old event exists, new event is added after it.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The fully qualified field name. |
| script | java.lang.String | The Java script to be added/placed into a push button field. |

**Returns:**
boolean - True in case script was added successfully.
### addListItem(String fieldName, String itemName) {#addListItem-java.lang.String-java.lang.String-}
```
public void addListItem(String fieldName, String itemName)
```


Adds new item to the list box.

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", PdfForm_out.pdf");
 formEditor.addListItem("listBoxField", "Item 4 (New Item)");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Name of the field ot which new item will be added. |
| itemName | java.lang.String | Name if new item. |

### addListItem(String fieldName, String[] exportName) {#addListItem-java.lang.String-java.lang.String---}
```
public void addListItem(String fieldName, String[] 导出名称)
```


Add a new item with Export value to the existing list box field, only for AcroForm combo box field.

--------------------

```
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_AddListItem2.pdf");
  fe.addListItem("listboxField", new String[] { "4", "Item4(Added)" });
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Name of field to which items will be added. |
| exportName | java.lang.String[] | A String array denoting a new list item with Export Value, i.e. (Item Label, Export Value). |

### addSubmitBtn(String fieldName, int page, String label, String url, float llx, float lly, float urx, float ury) {#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-}
```
public void addSubmitBtn(String fieldName, int page, String label, String url, float llx, float lly, float urx, float ury)
```


Add submit button on the form.

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_AddSubmitBtn.pdf");
 formEditor.addSubmitBtn("提交", 1, "提交", "www.check.com", 10, 200, 70, 270);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Name of new button. |
| page | int | Page where button will be placed. |
| label | java.lang.String | Button caption. |
| url | java.lang.String | URL of the submit button. |
| llx | float | Abscissa of the lower-left corner. |
| lly | float | Ordinate of the lower-left corner. |
| urx | float | Abscissa of the upper-right corner. |
| ury | float | Ordinate of the upper-right corner. |

### bindPdf(IDocument srcDoc) {#bindPdf-com.aspose.pdf.IDocument-}
```
public void bindPdf(IDocument srcDoc)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcDoc | [IDocument](../../com.aspose.pdf/idocument) | The Document object. |

### bindPdf(InputStream srcStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream srcStream)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | java.io.InputStream | The stream of PDF file. |

### bindPdf(InputStream srcStream, String password) {#bindPdf-java.io.InputStream-java.lang.String-}
```
public void bindPdf(InputStream srcStream, String password)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | java.io.InputStream | The stream of PDF file. |
| password | java.lang.String | The password of the PDF document. |

### bindPdf(String srcFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String srcFile)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcFile | java.lang.String | The PDF file. |

### bindPdf(String srcFile, String password) {#bindPdf-java.lang.String-java.lang.String-}
```
public void bindPdf(String srcFile, String password)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcFile | java.lang.String | The PDF file |
| password | java.lang.String | The password of the PDF document. |

### close() {#close--}
```
公共无效关闭（）
```


Closes all resources used by this document.

### copyInnerField(String fieldName, String newFieldName, int pageNum) {#copyInnerField-java.lang.String-java.lang.String-int-}
```
public void copyInnerField(String fieldName, String newFieldName, int pageNum)
```


Copies an existing field to the same position in specified page number. A new document will be produced, which contains everything the source document has except for the newly copied field.

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
 //在第二页上创建文本字段的副本。
 formEditor.copyInnerField("textField", "textFieldCopy", 2);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The old fully qualified field name. |
| newFieldName | java.lang.String | The new fully qualified field name. If null, it will be set as fieldName + "~". |
| pageNum | int | The number of page to hold the new field. If -1, new field will be copid to the same page as old one hosted. |

### copyInnerField(String fieldName, String newFieldName, int pageNum, float abscissa, float ordinate) {#copyInnerField-java.lang.String-java.lang.String-int-float-float-}
```
public void copyInnerField(String fieldName, String newFieldName, int pageNum, float abscissa, float ordinate)
```


Copies an existing field to a new position specified by both page number and ordinates. A new document will be produced, which contains everything the source document has except for the newly copied field.

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
 //在第二页上创建文本字段的副本。
 formEditor.copyInnerField("textField", "textFieldCopy", 2, 100, 200);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The old fully qualified field name. |
| newFieldName | java.lang.String | The new fully qualified field name. If null, it will be set as fieldName + "~". |
| pageNum | int | The number of page to hold the new field. If -1, new field will be copid to the same page as old one hosted. |
| abscissa | float | The abscissa of the new field. If -1, the abscissa will be equaled to the original one. |
| ordinate | float | The ordinate of the new field. If -1, the ordinate will be equaled to the original one. |

### copyOuterField(String srcFileName, String fieldName) {#copyOuterField-java.lang.String-java.lang.String-}
```
public void copyOuterField(String srcFileName, String fieldName)
```


Copies an existing field from one PDF document to another document with original page number and ordinates. Notice: Only for AcroForm fields (excluding radio box).

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
 //将文本字段从 source.pdf 复制到 PdfForm.pdf
 formEditor.copyOuterField("source.pdf", "textField");
 formEditor.save();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | java.lang.String | The name of PDF document which contains the field to be copied. |
| fieldName | java.lang.String | The original fully qualified field name. |

### copyOuterField(String srcFileName, String fieldName, int pageNum) {#copyOuterField-java.lang.String-java.lang.String-int-}
```
public void copyOuterField(String srcFileName, String fieldName, int pageNum)
```


Copies an existing field from one PDF document to another document with specified page number and original ordinates. Notice: Only for AcroForm fields (excluding radio box).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | java.lang.String | The name of PDF document which contains the field to be copied. |
| fieldName | java.lang.String | The original fully qualified field name. |
| pageNum | int |  |

### copyOuterField(String srcFileName, String fieldName, int pageNum, float abscissa, float ordinate) {#copyOuterField-java.lang.String-java.lang.String-int-float-float-}
```
public void copyOuterField(String srcFileName, String fieldName, int pageNum, float abscissa, float ordinate)
```


Copies an existing field from one PDF document to another document with specified page number and ordinates. Notice: Only for AcroForm fields (excluding radio box).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | java.lang.String | The old fully qualified field name. |
| fieldName | java.lang.String | The new fully qualified field name. If null, it will be set as fieldName + "~". |
| pageNum | int | The number of page to hold the new field. If -1, new field will be copid to the same page as old one hosted. |
| abscissa | float | The abscissa of the new field. If -1, the abscissa will be equaled to the original one. |
| ordinate | float | The ordinate of the new field. If -1, the ordinate will be equaled to the original one. |

### decorateField() {#decorateField--}
```
公共无效装饰字段（）
```


Changes visual attributes of all fields in the PDF document.

--------------------

```
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf");
 fe.setFacade ( new FormFieldFacade());
 fe.getFacade().setBackgroundColor ( Color.red);
 fe.getFacade().setTextColor (Color.blue);
 fe.getFacade().setBorderColor (Color.Green);
 fe.getFacade().setAlignment(FormFieldFacade.AlignRight);
 //装饰所有字段。
 fe.decorateField();
```

### decorateField(int fieldType) {#decorateField-int-}
```
public void decorateField(int fieldType)
```


Changes visual attributes of all fields with the specified field type.

--------------------

```
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf");
 fe.setFacade ( new FormFieldFacade());
 fe.getFacade().setBackgroundColor ( Color.red);
 fe.getFacade().setTextColor (Color.blue);
 fe.getFacade().setBorderColor (Color.green);
 fe.getFacade().setAlignment ( FormFieldFacade.AlignRight);
 //装饰所有文本字段。
 fe.decorateField(FieldType.Text);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldType | int | Type of fields which will be decorated. |

### decorateField(String fieldName) {#decorateField-java.lang.String-}
```
public void decorateField(String fieldName)
```


Changes visual attributes of the specified field.

--------------------

```
FormEditor fe = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_DecorateField_text.pdf");
 fe.Facade = new FormFieldFacade();
 fe.Facade.setBackgroundColor (Color.Red);
 fe.Facade.setTextColor (Color.Blue);
 fe.Facade.setBorderColor (Color.Green);
 fe.Facade.setAlignment ( FormFieldFacade.AlignCenter);
 fe.decorateField("文本字段");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The fully qualified field name. |

### delListItem(String fieldName, String itemName) {#delListItem-java.lang.String-java.lang.String-}
```
public void delListItem(String fieldName, String itemName)
```


Delete item from the list field.

--------------------

```
formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_DelListItem.pdf");
 formEditor.delListItem("listboxField", "item2");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Name of the field. |
| itemName | java.lang.String | Name of the item which must be deleted. |

### dispose() {#dispose--}
```
公共无效处置（）
```


Closes all resources used by this document.

This method is obsolete, use close() instead.

### equals(Object arg0) {#equals-java.lang.Object-}
```
公共布尔等于（对象 arg0）
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAttachmentName() {#getAttachmentName--}
```
公共字符串 getAttachmentName()
```


Gets name of attachment when result of operation is stored into HttpResponse objects as attachment.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContentDisposition() {#getContentDisposition--}
```
公共 int getContentDisposition()
```


Gets how content will be stored when result of operation is stored into HttpResponse object. Possible value: inline / attachment. Default: inline.

**Returns:**
int
### getDestFileName() {#getDestFileName--}
```
公共字符串 getDestFileName()
```


Gets destination file name.

**Returns:**
java.lang.String
### getDestStream() {#getDestStream--}
```
公共 OutputStream getDestStream()
```


Gets destination stream.

--------------------

```
FormEditor editor = new FormEditor();
 editor.setDestStream ( new FileInputStream("OutFile.pdf"));
```

**Returns:**
java.io.OutputStream
### getDocument() {#getDocument--}
```
公共 IDocument getDocument()
```


Gets the document facade is working on.

**Returns:**
[IDocument](../../com.aspose.pdf/idocument) - IDocument element
### getExportItems() {#getExportItems--}
```
公共字符串[][getExportItems()
```


Gets options for combo box with export values.

**Returns:**
java.lang.String[][] - String[][] array
### getFacade() {#getFacade--}
```
公共 FormFieldFacade getFacade()
```


Gets visual attributes of the field.

**Returns:**
[FormFieldFacade](../../com.aspose.pdf.facades/formfieldfacade)
### getFieldAppearance(String fieldName) {#getFieldAppearance-java.lang.String-}
```
public int getFieldAppearance（字符串字段名）
```


Get field flags.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Name of the field. |

**Returns:**
int - Set of field flags
### getItems() {#getItems--}
```
公共字符串[] 获取项目（）
```


Returns item array

**Returns:**
java.lang.String[]
### getRadioButtonItemSize() {#getRadioButtonItemSize--}
```
公共双 getRadioButtonItemSize()
```


Gets or sets size of radio button item size (when new radio button field is added).

```
formEditor = new FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
 formEditor.setRadioGap(4);
 formEditor.setRadioHoriz ( false);
 formEditor.setRadioButtonItemSize ( 20);
 formEditor.setItems ( 新字符串[{ “第一第二第三” }）;
 formEditor.addField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
 formEditor.save();
```

**Returns:**
double - double value
### getRadioGap() {#getRadioGap--}
```
公共浮动 getRadioGap()
```


Get the member to record the gap between two neighboring radio buttons in pixels,default is 50.

**Returns:**
float
### getRadioHoriz() {#getRadioHoriz--}
```
公共布尔 getRadioHoriz()
```


Get the flag to indicate whether the radios are arranged horizontally or vertically, default value is true.

**Returns:**
boolean
### getResponse() {#getResponse--}
```
公共 HttpServletResponse getResponse()
```


Gets Response object where result of operation will be stored.

**Returns:**
javax.servlet.http.HttpServletResponse - HttpServletResponse object
### getSaveOptions() {#getSaveOptions--}
```
公共保存选项 getSaveOptions()
```


Gets save options when result is stored as HttpResponse. Default value: PdfSaveOptions.

**Returns:**
[SaveOptions](../../com.aspose.pdf/saveoptions)
### getSrcFileName() {#getSrcFileName--}
```
公共字符串 getSrcFileName()
```


Gets name of source file.

**Returns:**
java.lang.String
### getSrcStream() {#getSrcStream--}
```
公共 InputStream getSrcStream()
```


Gets source stream.

**Returns:**
java.io.InputStream
### getSubmitFlag() {#getSubmitFlag--}
```
公共 int getSubmitFlag()
```


Get the submit button's submission flags

**Returns:**
int - SubmitFormFlag element
### hashCode() {#hashCode--}
```
公共本机 int hashCode()
```




**Returns:**
int
### moveField(String fieldName, float llx, float lly, float urx, float ury) {#moveField-java.lang.String-float-float-float-float-}
```
public boolean moveField(String fieldName, float llx, float lly, float urx, float ury)
```


Set new position of field.

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_MoveField.pdf");
 formEditor.moveField("textField", 20.5f, 20.3f, 120.6f, 40.8f);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Name of field which must be moved. |
| llx | float | Abscissa of the lower-left corner of the field. |
| lly | float | Ordinate of the lower-left coerner of the field. |
| urx | float | Abscissa of the upper-right corner of the field. |
| ury | float | Ordinate of the upper-right corner of the field. |

**Returns:**
boolean - true if field position was changed successfully.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeField(String fieldName) {#removeField-java.lang.String-}
```
public void removeField(String fieldName)
```


Remove field from the form.

--------------------

```
FormEditr formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveField.pdf");
 formEditor.removeField("listboxField");
 formEditor.removeField("文本字段");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Name of the field which must be removed. |

### removeFieldAction(String fieldName) {#removeFieldAction-java.lang.String-}
```
public void removeFieldAction(String fieldName)
```


Remove submit action of the field.

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveFieldAction.pdf");
 formEditor.removeFieldAction("btnSubmit");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Name of the field. |

### renameField(String fieldName, String newFieldName) {#renameField-java.lang.String-java.lang.String-}
```
public void renameField(String fieldName, String newFieldName)
```


Change name of the field.

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
 formEditor.renameField("textField", "textField_Renamed");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Old name of the field. |
| newFieldName | java.lang.String | New name of the field. |

### resetFacade() {#resetFacade--}
```
公共无效重置门面（）
```


Reset all visual attributes to empty value.

### resetInnerFacade() {#resetInnerFacade--}
```
public void resetInnerFacade()
```


Reset all visual attributes of inner facade to empty value.

### save() {#save--}
```
公共无效保存（）
```


Saves changes into destination file.

### save(OutputStream destStream) {#save-java.io.OutputStream-}
```
公共无效保存（OutputStream destStream）
```


Saves the PDF document to the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destStream | java.io.OutputStream | The destination stream. |

### save(String destFile) {#save-java.lang.String-}
```
公共无效保存（字符串 destFile）
```


Saves the PDF document to the specified file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destFile | java.lang.String | The destination file. |

### setAttachmentName(String value) {#setAttachmentName-java.lang.String-}
```
public void setAttachmentName（字符串值）
```


Sets name of attachment when result of operation is stored into HttpResponse objects as attachment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setContentDisposition(int value) {#setContentDisposition-int-}
```
public void setContentDisposition(int 值)
```


Sets how content will be stored when result of operation is stored into HttpResponse object. Possible value: inline / attachment. Default: inline.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setConvertTo(PdfFormat value) {#setConvertTo-com.aspose.pdf.PdfFormat-}
```
public void setConvertTo(PdfFormat 值)
```


Sets [PdfFormat](../../com.aspose.pdf/pdfformat) PDF file format. Result file will be saved in specified file format. If this property is not specified then file will be save in default PDF format without conversion.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PdfFormat](../../com.aspose.pdf/pdfformat) |  |

### setDestFileName(String value) {#setDestFileName-java.lang.String-}
```
public void setDestFileName(字符串值)
```


Sets destination file name.

--------------------

```
FormEditor editor = new FormEditor();
 editor.setDestFileName("OutFile.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setDestStream(OutputStream value) {#setDestStream-java.io.OutputStream-}
```
public void setDestStream(OutputStream 值)
```


Sets destination stream.

--------------------

```
FormEditor editor = new FormEditor();
 editor.setDestStream ( new FileInputStream("OutFile.pdf"));
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.OutputStream |  |

### setExportItems(String[][] value) {#setExportItems-java.lang.String-----}
```
public void setExportItems(字符串[][] 价值）
```


Sets options for combo box with export values.

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_Updated.pdf"));
 formEditor.setExportItems ( 新字符串[][]
 {
     新字符串[{ “1”, “冷杉” },
     新字符串[] { "2", "第二个" },
     新字符串[] { "3", "第三" }
 });
 formEditor.addField(FieldType.ListBox, "AddedListBoxField", "Second", 1, 10, 30, 110, 130);
 formEditor.save();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[][] |  |

### setFacade(FormFieldFacade value) {#setFacade-com.aspose.pdf.facades.FormFieldFacade-}
```
public void setFacade(FormFieldFacade 值)
```


Sets visual attributes of the field.

--------------------

```
FormEditor fe = new FormEditor("PdfForm.pdf", "PdfForm_DecorateField_text.pdf");
 fe.setFacade ( new FormFieldFacade());
 fe.getFacade().setBackgroundColor ( Color.red);
 fe.getFacade().setTextColor (Color.blue);
 fe.getFacade().setBorderColor (Color.green);
 fe.getFacade().setAlignment ( FormFieldFacade.AlignCenter);
 fe.setDecorateField("文本字段");
 fe.save();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FormFieldFacade](../../com.aspose.pdf.facades/formfieldfacade) |  |

### setFieldAlignment(String fieldName, int alignment) {#setFieldAlignment-java.lang.String-int-}
```
public boolean setFieldAlignment(String fieldName, int alignment)
```


Set the alignment style of a text field.

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_updated.pdf"));
  formEditor.setFieldAlignment(fieldName, FormFieldFacade.AlignCenter);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The qualified field name. |
| alignment | int | The alignment style definition, including FormFieldFacade.AlignLeft, FormFieldFacade.AlignCenter and FormFieldFacade.AlignRight. |

**Returns:**
boolean
### setFieldAlignmentV(String fieldName, int alignment) {#setFieldAlignmentV-java.lang.String-int-}
```
public boolean setFieldAlignmentV(String fieldName, int alignment)
```


Set the vertical alignment style of a text field.

--------------------

```
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
  fe.setFieldAlignmentV("form1[0].文本域[0]", FormFieldFacade.AlignBottom);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The qualified field name. |
| alignment | int | The alignment style definition, including FormFieldFacade.AlignTop, FormFieldFacade.AlignMiddle and FormFieldFacade.AlignRight. |

**Returns:**
boolean
### setFieldAppearance(String fieldName, int flags) {#setFieldAppearance-java.lang.String-int-}
```
public boolean setFieldAppearance(String fieldName, int flags)
```


Set field flags

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf");
 formEditor.setFieldAppearance("名称", AnnotationFlags.Hidden);
 formEditor.setFieldAppearance("Phone", AnnotationFlags.NoView | AnnotationFlags.Print);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Name of field whose flags should be updated. |
| flags | int | Flag of the field. |

**Returns:**
boolean - true if flags were updated successfully.
### setFieldAttribute(String fieldName, int flag) {#setFieldAttribute-java.lang.String-int-}
```
public boolean setFieldAttribute(String fieldName, int flag)
```


Set attributes of field.

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_SetFieldAttribute.pdf");
 formEditor.setFieldAttribute("listboxField", PropertyFlag.ReadOnly);
 formEditor.setFieldAttribute("textField", PropertyFlag.NoExport);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Name of field which attributes should be set. |
| flag | int | Flag (NoExport/ReadOnly/Required) |

**Returns:**
boolean - true if attribute was set successfully.
### setFieldCombNumber(String fieldName, int combNumber) {#setFieldCombNumber-java.lang.String-int-}
```
public boolean setFieldCombNumber(String fieldName, int combNumber)
```


Sets number of combs for a regular single-line text field (the field is automatically divided into as many equally spaced positions, or combs, as the value of combNumber parameter).

--------------------

```
FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf"));
 formEditor.setFieldCombNumber("textCombField", 5);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The qualified field name. |
| combNumber | int | The number of combs to divide the field into. |

**Returns:**
boolean - If success, return true;else false.
### setFieldLimit(String fieldName, int fieldLimit) {#setFieldLimit-java.lang.String-int-}
```
public boolean setFieldLimit(String fieldName, int fieldLimit)
```


Sets maximum character count of the text field.

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf");
 formEditor.setFieldLimit("文本字段", 15);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Name of the text field. |
| fieldLimit | int | New value of limit for the field. |

**Returns:**
boolean - true if field limit was successfully set.
### setFieldScript(String fieldName, String script) {#setFieldScript-java.lang.String-java.lang.String-}
```
public boolean setFieldScript(String fieldName, String script)
```


Set JavaScript for a PushButton field. If old JavaScript existed, it will be replaced by the new one.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The fully qualified field name. |
| script | java.lang.String | The Java script to be added/placed into a push button field. |

**Returns:**
boolean
### setItems(String[] value) {#setItems-java.lang.String---}
```
public void setItems(字符串[] 价值）
```


Sets items which will be added to newly created list box or combo box.

--------------------

```
formEditor = new com.aspose.pdf.facadesFormEditor("input.pdf", "output.pdf");
  formEditor.setItems ( 新字符串[] { "AAA", "BBB", "CCC" });
  formEditor.addField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130);
  formEditor.save();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### setRadioButtonItemSize(double value) {#setRadioButtonItemSize-double-}
```
public void setRadioButtonItemSize(双值)
```


```
获取或设置单选按钮项目的大小（添加新的单选按钮字段时）。


 FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "
 FormEditor_AddField_RadioButton.pdf");
 formEditor.setRadioGap(4);
 formEditor.setRadioHoriz(false);
 formEditor.setRadioButtonItemSize(20);
 formEditor.setItems(新字符串[]
 “第一第二第三” }）;
 formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, "AddedRadioButtonField", "
 第二", 1, 10, 30, 110, 130);
 formEditor.save();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### setRadioGap(float value) {#setRadioGap-float-}
```
public void setRadioGap(浮点值)
```


Set the member to record the gap between two neighboring radio buttons in pixels,default is 50.

--------------------

```
formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
 formEditor.setRadioGap(4);
 formEditor.setRadioHoriz ( false);
 formEditor.setItems ( 新字符串[{ “第一第二第三” }）;
 formEditor.addField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
 formEditor.save();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setRadioHoriz(boolean value) {#setRadioHoriz-boolean-}
```
public void setRadioHoriz(布尔值)
```


Set the flag to indicate whether the radios are arranged horizontally or vertically, default value is true.

--------------------

```
formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
 formEditor.setRadioGap(4);
 formEditor.setRadioHoriz ( false);
 formEditor.setItems ( 新字符串[{ “第一第二第三” }）;
 formEditor.addField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
 formEditor.save();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setResponse(HttpServletResponse value) {#setResponse-javax.servlet.http.HttpServletResponse-}
```
public void setResponse(HttpServletResponse 值)
```


Sets Response object where result of operation will be stored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | javax.servlet.http.HttpServletResponse | HttpServletResponse object |

### setSaveOptions(SaveOptions value) {#setSaveOptions-com.aspose.pdf.SaveOptions-}
```
public void setSaveOptions（SaveOptions 值）
```


Sets save options when result is stored as HttpResponse. Default value: PdfSaveOptions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SaveOptions](../../com.aspose.pdf/saveoptions) |  |

### setSrcFileName(String value) {#setSrcFileName-java.lang.String-}
```
public void setSrcFileName(字符串值)
```


Sets name of source file.

--------------------

```
FormEditor editor = new FormEditor();
 editor.setSrcFileName("输入文件.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setSrcStream(InputStream value) {#setSrcStream-java.io.InputStream-}
```
public void setSrcStream(InputStream 值)
```


Sets source stream.

--------------------

```
FormEditor editor = new FormEditor();
 editor.setSrcStream(new FileInputStream("InFile.pdf"));
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.InputStream |  |

### setSubmitFlag(int value) {#setSubmitFlag-int-}
```
public void setSubmitFlag(int 值)
```


Set the submit button's submission flags

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | SubmitFormFlag element |

### setSubmitFlag(String fieldName, int submitFormFlag) {#setSubmitFlag-java.lang.String-int-}
```
public boolean setSubmitFlag(String fieldName, int submitFormFlag)
```


Set submit flag of submit button.

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitFlag.pdf");
 formEditor.setSubmitFlag("btnSubmit", SubmitFormFlag.Fdf);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Name of submit button. |
| submitFormFlag | int | Submit flag. |

**Returns:**
boolean - true if field was found and submit flag was successfully set.
### setSubmitUrl(String fieldName, String url) {#setSubmitUrl-java.lang.String-java.lang.String-}
```
public boolean setSubmitUrl(String fieldName, String url)
```


Sets URL of the button.

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf");
 formEditor.setSubmitUrl("btnSubmit", "www.mysite.com");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Submit button name. |
| url | java.lang.String | Fully qualified URL. |

**Returns:**
boolean - true if URL for button was successfully set.
### single2Multiple(String fieldName) {#single2Multiple-java.lang.String-}
```
公共布尔 single2Multiple（字符串字段名）
```


Change a single-lined text field to a multiple-lined one.

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
 formEditor.single2Multiple("文本字段");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The qualified field name. |

**Returns:**
boolean - If success, return true;else false.
### toString() {#toString--}
```
公共字符串 toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
公共最终无效等待（）
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
公共最终无效等待（长 arg0，int arg1）
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
