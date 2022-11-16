---
title: IFormEditor
second_title: Aspose.PDF для справки по Java API
description: Класс для редактирования форм добавления/удаления поля и т.д.
type: docs
weight: 69
url: /ru/java/com.aspose.pdf.facades/iformeditor/
---
**Все реализованные интерфейсы:**
java.io.Closeable
```
public interface IFormEditor extends Closeable
```

Класс для редактирования форм (добавление/удаление поля и т.д.)
## Методы

| Method | Description |
| --- | --- |
| [addField(int fieldType, String fieldName, int pageNum, float llx, float lly, float urx, float ury)](#addField-int-java.lang.String-int-float-float-float-float-) | Add field of specified type to the form. |
| [addField(int fieldType, String fieldName, String initValue, int pageNum, float llx, float lly, float urx, float ury)](#addField-int-java.lang.String-java.lang.String-int-float-float-float-float-) | Add field of specified type to the form. |
| [addListItem(String fieldName, String itemName)](#addListItem-java.lang.String-java.lang.String-) | Adds new item to the list box. |
| [addListItem(String fieldName, String[] exportName)](#addListItem-java.lang.String-java.lang.String---) | Add a new item with Export value to the existing list box field, only for AcroForm combo box field. |
| [addSubmitBtn(String fieldName, int page, String label, String url, float llx, float lly, float urx, float ury)](#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-) | Add submit button on the form. |
| [close()](#close--) | Closes object |
| [copyInnerField(String fieldName, String newFieldName, int pageNum)](#copyInnerField-java.lang.String-java.lang.String-int-) | Copies an existing field to the same position in specified page number. |
| [copyInnerField(String fieldName, String newFieldName, int pageNum, float abscissa, float ordinate)](#copyInnerField-java.lang.String-java.lang.String-int-float-float-) | Copies an existing field to a new position specified by both page number and ordinates. |
| [copyOuterField(String srcFileName, String fieldName)](#copyOuterField-java.lang.String-java.lang.String-) | Copies an existing field from one PDF document to another document with original page number and ordinates. |
| [copyOuterField(String srcFileName, String fieldName, int pageNum)](#copyOuterField-java.lang.String-java.lang.String-int-) | Copies an existing field from one PDF document to another document with specified page number and original ordinates. |
| [copyOuterField(String srcFileName, String fieldName, int pageNum, float abscissa, float ordinate)](#copyOuterField-java.lang.String-java.lang.String-int-float-float-) | Copies an existing field from one PDF document to another document with specified page number and ordinates. |
| [decorateField()](#decorateField--) | Changes visual attributes of all fields in the PDF document. |
| [decorateField(int fieldType)](#decorateField-int-) | Changes visual attributes of all fields with the specified field type. |
| [decorateField(String fieldName)](#decorateField-java.lang.String-) | Changes visual attributes of the specified field. |
| [delListItem(String fieldName, String itemName)](#delListItem-java.lang.String-java.lang.String-) | Delete item from the list field. |
| [dispose()](#dispose--) | Closes object |
| [getAttachmentName()](#getAttachmentName--) | Gets name of attachment when result of operation is stored into HttpResponse objects as attachment. |
| [getContentDisposition()](#getContentDisposition--) | Gets how content will be stored when result of operation is stored into HttpResponse object. |
| [getDestFileName()](#getDestFileName--) | Gets destination file name. |
| [getDestStream()](#getDestStream--) | Gets destination stream. |
| [getDocument()](#getDocument--) | Gets the document  FormEditor  is working on. |
| [getExportItems()](#getExportItems--) | Gets options for combo box with export values. |
| [getFacade()](#getFacade--) | Gets visual attributes of the field. |
| [getItems()](#getItems--) | Returns item array |
| [getRadioButtonItemSize()](#getRadioButtonItemSize--) | ```
Gets or sets size of radio button item size (when new radio button field is added).
``` |
| [getRadioGap()](#getRadioGap--) | Get the member to record the gap between two neighboring radio buttons in pixels,default is 50. |
| [getRadioHoriz()](#getRadioHoriz--) | Get the flag to indicate whether the radios are arranged horizontally or vertically, default value is true. |
| [getSaveOptions()](#getSaveOptions--) | Gets save options when result is stored as HttpResponse. |
| [getSrcFileName()](#getSrcFileName--) | Gets name of source file. |
| [getSrcStream()](#getSrcStream--) | Gets source stream. |
| [getSubmitFlag()](#getSubmitFlag--) | Get the submit button's submission flags |
| [moveField(String fieldName, float llx, float lly, float urx, float ury)](#moveField-java.lang.String-float-float-float-float-) | Set new position of field. |
| [removeField(String fieldName)](#removeField-java.lang.String-) | Remove field from the form. |
| [removeFieldAction(String fieldName)](#removeFieldAction-java.lang.String-) | Remove submit action of the field. |
| [renameField(String fieldName, String newFieldName)](#renameField-java.lang.String-java.lang.String-) | Change name of the field. |
| [resetFacade()](#resetFacade--) | Reset all visual attributes to empty value. |
| [resetInnerFacade()](#resetInnerFacade--) | Reset all visual attributes of inner facade to empty value. |
| [save()](#save--) | Saves changes into destination file. |
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
| [setSaveOptions(SaveOptions value)](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Sets save options when result is stored as HttpResponse. |
| [setSrcFileName(String value)](#setSrcFileName-java.lang.String-) | Sets name of source file. |
| [setSrcStream(InputStream value)](#setSrcStream-java.io.InputStream-) | Sets source stream. |
| [setSubmitFlag(int value)](#setSubmitFlag-int-) | Set the submit button's submission flags |
| [setSubmitFlag(String fieldName, int submitFormFlag)](#setSubmitFlag-java.lang.String-int-) | Set submit flag of submit button. |
| [setSubmitUrl(String fieldName, String url)](#setSubmitUrl-java.lang.String-java.lang.String-) | Sets URL of the button. |
| [single2Multiple(String fieldName)](#single2Multiple-java.lang.String-) | Change a single-lined text field to a multiple-lined one. |
### addField(int fieldType, String fieldName, int pageNum, float llx, float lly, float urx, float ury) {#addField-int-java.lang.String-int-float-float-float-float-}
```
открытый абстрактный логический addField (int fieldType, String fieldName, int pageNum, float llx, float lly, float urx, float ury)
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
открытый абстрактный логический addField (int fieldType, String fieldName, String initValue, int pageNum, float llx, float lly, float urx, float ury)
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
### addListItem(String fieldName, String itemName) {#addListItem-java.lang.String-java.lang.String-}
```
public abstract void addListItem (String fieldName, String itemName)
```


Adds new item to the list box.

--------------------

```
FormEditor formEditor = новый FormEditor("PdfForm.pdf", PdfForm_out.pdf");
 formEditor.addListItem("listBoxField", "Элемент 4 (Новый элемент)");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Name of the field of which new item will be added. |
| itemName | java.lang.String | Name if new item. |

### addListItem(String fieldName, String[] exportName) {#addListItem-java.lang.String-java.lang.String---}
```
public abstract void addListItem (String fieldName, String[] имя_экспорта)
```


Add a new item with Export value to the existing list box field, only for AcroForm combo box field.

--------------------

```
FormEditor fe = новый FormEditor("PdfForm.pdf", "FormEditor_AddListItem2.pdf");
 fe.addListItem("listboxField", новая строка[]
 { "4", "Элемент4(Добавлено)" });
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Name of field to which items will be added. |
| exportName | java.lang.String[] | A String array denoting a new list item with Export Value, i.e. (Item Label, Export Value). |

### addSubmitBtn(String fieldName, int page, String label, String url, float llx, float lly, float urx, float ury) {#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-}
```
public abstract void addSubmitBtn (String fieldName, int page, String label, String url, float llx, float lly, float urx, float ury)
```


Add submit button on the form.

--------------------

```
FormEditor formEditor = новый FormEditor("PdfForm.pdf", "FormEditor_AddSubmitBtn.pdf");
 formEditor.addSubmitBtn("отправить", 1, "отправить", "www.check.com", 10, 200, 70, 270);
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

### close() {#close--}
```
публичная абстрактная пустота close()
```


Closes object

### copyInnerField(String fieldName, String newFieldName, int pageNum) {#copyInnerField-java.lang.String-java.lang.String-int-}
```
public abstract void copyInnerField (String fieldName, String newFieldName, int pageNum)
```


Copies an existing field to the same position in specified page number. A new document will be produced, which contains everything the source document has except for the newly copied field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | String value |
| newFieldName | java.lang.String | String value |
| pageNum | int | int value |

### copyInnerField(String fieldName, String newFieldName, int pageNum, float abscissa, float ordinate) {#copyInnerField-java.lang.String-java.lang.String-int-float-float-}
```
public abstract void copyInnerField (String fieldName, String newFieldName, int pageNum, float abscissa, float ордината)
```


Copies an existing field to a new position specified by both page number and ordinates. A new document will be produced, which contains everything the source document has except for the newly copied field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | String value |
| newFieldName | java.lang.String | String value |
| pageNum | int | int value |
| abscissa | float | float value |
| ordinate | float | float value |

### copyOuterField(String srcFileName, String fieldName) {#copyOuterField-java.lang.String-java.lang.String-}
```
public abstract void copyOuterField (String srcFileName, String fieldName)
```


Copies an existing field from one PDF document to another document with original page number and ordinates. Notice: Only for AcroForm fields (excluding radio box).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | java.lang.String | String value |
| fieldName | java.lang.String | String value |

### copyOuterField(String srcFileName, String fieldName, int pageNum) {#copyOuterField-java.lang.String-java.lang.String-int-}
```
public abstract void copyOuterField (String srcFileName, String fieldName, int pageNum)
```


Copies an existing field from one PDF document to another document with specified page number and original ordinates. Notice: Only for AcroForm fields (excluding radio box).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | java.lang.String | String value |
| fieldName | java.lang.String | String value |
| pageNum | int | int value |

### copyOuterField(String srcFileName, String fieldName, int pageNum, float abscissa, float ordinate) {#copyOuterField-java.lang.String-java.lang.String-int-float-float-}
```
public abstract void copyOuterField (String srcFileName, String fieldName, int pageNum, float abscissa, float ордината)
```


Copies an existing field from one PDF document to another document with specified page number and ordinates. Notice: Only for AcroForm fields (excluding radio box).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | java.lang.String | String value |
| fieldName | java.lang.String | String value |
| pageNum | int | int value |
| abscissa | float | float value |
| ordinate | float | float value |

### decorateField() {#decorateField--}
```
публичная абстрактная пустота decorField()
```


Changes visual attributes of all fields in the PDF document.

--------------------

```
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf");
 fe.setFacade(новый FormFieldFacade());
 fe.getFacade().setBackgroundColor(Color.red);
 fe.getFacade().setTextColor(Color.blue);
 fe.getFacade().setBorderColor(Color.Green);
 fe.getFacade().setAlignment(FormFieldFacade.AlignRight);
 // украшаем все поля.
 fe.decorateField();
```

### decorateField(int fieldType) {#decorateField-int-}
```
общественное абстрактное недействительное декоративное поле (int fieldType)
```


Changes visual attributes of all fields with the specified field type.

--------------------

```
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf");
 fe.setFacade(новый FormFieldFacade());
 fe.getFacade().setBackgroundColor(Color.red);
 fe.getFacade().setTextColor(Color.blue);
 fe.getFacade().setBorderColor(Color.green);
 fe.getFacade().setAlignment(FormFieldFacade.AlignRight);
 // украшаем все текстовые поля.
 fe.decorateField(FieldType.Text);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldType | int | Type of fields which will be decorated. |

### decorateField(String fieldName) {#decorateField-java.lang.String-}
```
общественное абстрактное недействительное декоративное поле (String fieldName)
```


Changes visual attributes of the specified field.

--------------------

```
FormEditor fe = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_DecorateField_text.pdf");
 fe.Facade = новый FormFieldFacade();
 fe.Facade.setBackgroundColor(Color.Red);
 fe.Facade.setTextColor(Color.Blue);
 fe.Facade.setBorderColor(Color.Green);
 fe.Facade.setAlignment(FormFieldFacade.AlignCenter);
 fe.decorateField ("текстовое поле");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The fully qualified field name. |

### delListItem(String fieldName, String itemName) {#delListItem-java.lang.String-java.lang.String-}
```
public abstract void delListItem (String fieldName, String itemName)
```


Delete item from the list field.

--------------------

```
formEditor = новый com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_DelListItem.pdf");
 formEditor.delListItem("listboxField", "item2");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Name of the field. |
| itemName | java.lang.String | Name of the item which must be deleted. |

### dispose() {#dispose--}
```
публичная абстрактная пустота dispose()
```


Closes object

### getAttachmentName() {#getAttachmentName--}
```
общедоступная абстрактная строка getAttachmentName()
```


Gets name of attachment when result of operation is stored into HttpResponse objects as attachment.

**Returns:**
java.lang.String - String object
### getContentDisposition() {#getContentDisposition--}
```
общедоступная абстракция int getContentDisposition()
```


Gets how content will be stored when result of operation is stored into HttpResponse object. Possible value: inline / attachment. Default: inline.

**Returns:**
int - ContentDisposition element
### getDestFileName() {#getDestFileName--}
```
общедоступная абстрактная строка getDestFileName()
```


Gets destination file name.

**Returns:**
java.lang.String - string value
### getDestStream() {#getDestStream--}
```
общедоступный абстрактный OutputStream getDestStream()
```


Gets destination stream.

--------------------

```
Редактор FormEditor = новый FormEditor();
 editor.setDestStream(новый FileInputStream("OutFile.pdf"));
```

**Returns:**
java.io.OutputStream - OutputStream object
### getDocument() {#getDocument--}
```
общедоступный абстрактный IDocument getDocument()
```


Gets the document  FormEditor  is working on.

**Returns:**
[IDocument](../../com.aspose.pdf/idocument) - IDocument object
### getExportItems() {#getExportItems--}
```
общедоступная абстрактная строка[][] получитьЭкспортItems()
```


Gets options for combo box with export values.

**Returns:**
java.lang.String[][] - String[][] object
### getFacade() {#getFacade--}
```
открытый абстрактный FormFieldFacade getFacade()
```


Gets visual attributes of the field.

**Returns:**
[FormFieldFacade](../../com.aspose.pdf.facades/formfieldfacade) - FormFieldFacade object
### getItems() {#getItems--}
```
общедоступная абстрактная строка[] получитьЭлементы()
```


Returns item array

**Returns:**
java.lang.String[] - String[] object
### getRadioButtonItemSize() {#getRadioButtonItemSize--}
```
публичный абстрактный двойной getRadioButtonItemSize()
```


```
Получает или задает размер элемента переключателя (при добавлении нового поля переключателя).
 
 
 FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
 formEditor.setRadioGap(4);
 formEditor.setRadioHoriz (ложь);
 formEditor.setRadioButtonItemSize(20);
 formEditor.setItems (новая строка[]
 { "Первый второй третий" });
 formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
 formEditor.save();
```

**Returns:**
double - boolean value
### getRadioGap() {#getRadioGap--}
```
публичный абстрактный поплавок getRadioGap()
```


Get the member to record the gap between two neighboring radio buttons in pixels,default is 50.

**Returns:**
float - float value
### getRadioHoriz() {#getRadioHoriz--}
```
публичное абстрактное логическое значение getRadioHoriz()
```


Get the flag to indicate whether the radios are arranged horizontally or vertically, default value is true.

**Returns:**
boolean - boolean value
### getSaveOptions() {#getSaveOptions--}
```
открытый абстрактный SaveOptions getSaveOptions()
```


Gets save options when result is stored as HttpResponse. Default value: PdfSaveOptions.

**Returns:**
[SaveOptions](../../com.aspose.pdf/saveoptions) - SaveOptions object
### getSrcFileName() {#getSrcFileName--}
```
общедоступная абстрактная строка getSrcFileName()
```


Gets name of source file.

**Returns:**
java.lang.String - string value
### getSrcStream() {#getSrcStream--}
```
общедоступный абстрактный InputStream getSrcStream()
```


Gets source stream.

**Returns:**
java.io.InputStream - InputStream object
### getSubmitFlag() {#getSubmitFlag--}
```
открытый абстрактный int getSubmitFlag()
```


Get the submit button's submission flags

**Returns:**
int - SubmitFormFlag element
### moveField(String fieldName, float llx, float lly, float urx, float ury) {#moveField-java.lang.String-float-float-float-float-}
```
public abstract boolean moveField (String fieldName, float llx, float lly, float urx, float ury)
```


Set new position of field.

--------------------

```
FormEditor formEditor = новый FormEditor("PdfForm.pdf", "FormEditor_MoveField.pdf");
 formEditor.moveField("textField", 20.5f, 20.3f, 120.6f, 40.8f);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Name of field which must be moved. |
| llx | float | Abscissa of the lower-left corner of the field. |
| lly | float | Ordinate of the lower-left corner of the field. |
| urx | float | Abscissa of the upper-right corner of the field. |
| ury | float | Ordinate of the upper-right corner of the field. |

**Returns:**
boolean - true if field position was changed successfully.
### removeField(String fieldName) {#removeField-java.lang.String-}
```
public abstract void removeField (String fieldName)
```


Remove field from the form.

--------------------

```
FormEditr formEditor = новый FormEditor("PdfForm.pdf", "FormEditor_RemoveField.pdf");
 formEditor.removeField("listboxField");
 formEditor.removeField("textField");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Name of the field which must be removed. |

### removeFieldAction(String fieldName) {#removeFieldAction-java.lang.String-}
```
public abstract void removeFieldAction (String fieldName)
```


Remove submit action of the field.

--------------------

```
FormEditor formEditor = новый FormEditor("PdfForm.pdf", "FormEditor_RemoveFieldAction.pdf");
 formEditor.removeFieldAction("btnSubmit");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Name of the field. |

### renameField(String fieldName, String newFieldName) {#renameField-java.lang.String-java.lang.String-}
```
public abstract void renameField (String fieldName, String newFieldName)
```


Change name of the field.

--------------------

```
FormEditor formEditor = новый FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
 formEditor.renameField("textField", "textField_Renamed");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Old name of the field. |
| newFieldName | java.lang.String | New name of the field. |

### resetFacade() {#resetFacade--}
```
public abstract void resetFacade()
```


Reset all visual attributes to empty value.

### resetInnerFacade() {#resetInnerFacade--}
```
public abstract void resetInnerFacade()
```


Reset all visual attributes of inner facade to empty value.

### save() {#save--}
```
публичное абстрактное недействительное сохранение ()
```


Saves changes into destination file.

### setAttachmentName(String value) {#setAttachmentName-java.lang.String-}
```
public abstract void setAttachmentName (строковое значение)
```


Sets name of attachment when result of operation is stored into HttpResponse objects as attachment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String object |

### setContentDisposition(int value) {#setContentDisposition-int-}
```
public abstract void setContentDisposition (значение int)
```


Sets how content will be stored when result of operation is stored into HttpResponse object. Possible value: inline / attachment. Default: inline.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ContentDisposition element |

### setConvertTo(PdfFormat value) {#setConvertTo-com.aspose.pdf.PdfFormat-}
```
public abstract void setConvertTo (значение PdfFormat)
```


Sets [PdfFormat](../../com.aspose.pdf/pdfformat) PDF file format. Result file will be saved in specified file format. If this property is not specified then file will be save in default PDF format without conversion.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PdfFormat](../../com.aspose.pdf/pdfformat) | PdfFormat element |

### setDestFileName(String value) {#setDestFileName-java.lang.String-}
```
public abstract void setDestFileName (строковое значение)
```


Sets destination file name.

--------------------

```
Редактор FormEditor = новый FormEditor();
 editor.setDestFileName("OutFile.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String object |

### setDestStream(OutputStream value) {#setDestStream-java.io.OutputStream-}
```
public abstract void setDestStream (значение OutputStream)
```


Sets destination stream.

--------------------

```
Редактор FormEditor = новый FormEditor();
 editor.setDestStream(новый FileInputStream("OutFile.pdf"));
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.OutputStream | OutputStream object |

### setExportItems(String[][] value) {#setExportItems-java.lang.String-----}
```
public abstract void setExportItems(String[][] ценность)
```


Sets options for combo box with export values.

--------------------

```
FormEditor formEditor = новый FormEditor("PdfForm.pdf", "PdfForm_Updated.pdf"));
 formEditor.setExportItems ( новая строка[][] 
 { 
     новая строка[] { "1", "Елки" }, 
     новая строка[] { "2", "Второй" }, 
     новая строка[] { "3", "Третий" } 
 });
 formEditor.addField(FieldType.ListBox, "AddedListBoxField", "Второй", 1, 10, 30, 110, 130);
 formEditor.save();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[][] | String[][] object |

### setFacade(FormFieldFacade value) {#setFacade-com.aspose.pdf.facades.FormFieldFacade-}
```
public abstract void setFacade (значение FormFieldFacade)
```


Sets visual attributes of the field.

--------------------

```
FormEditor fe = new FormEditor("PdfForm.pdf", "PdfForm_DecorateField_text.pdf");
 fe.setFacade(новый FormFieldFacade());
 fe.getFacade().setBackgroundColor(Color.red);
 fe.getFacade().setTextColor(Color.blue);
 fe.getFacade().setBorderColor(Color.green);
 fe.getFacade().setAlignment(FormFieldFacade.AlignCenter);
 fe.setDecorateField("textField");
 fe.save();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FormFieldFacade](../../com.aspose.pdf.facades/formfieldfacade) | FormFieldFacade object |

### setFieldAlignment(String fieldName, int alignment) {#setFieldAlignment-java.lang.String-int-}
```
открытый абстрактный логический setFieldAlignment (String fieldName, выравнивание int)
```


Set the alignment style of a text field.

--------------------

```
FormEditor formEditor = новый FormEditor("PdfForm.pdf", "FormEditor_updated.pdf"));
  formEditor.setFieldAlignment(fieldName, FormFieldFacade.AlignCenter);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The qualified field name. |
| alignment | int | The alignment style definition, including FormFieldFacade.AlignLeft, FormFieldFacade.AlignCenter and FormFieldFacade.AlignRight. |

**Returns:**
boolean - boolean value
### setFieldAlignmentV(String fieldName, int alignment) {#setFieldAlignmentV-java.lang.String-int-}
```
общедоступный абстрактный логический setFieldAlignmentV (String fieldName, выравнивание int)
```


Set the vertical alignment style of a text field.

--------------------

```
FormEditor fe = новый FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
 fe.setFieldAlignmentV("form1[0].Текстовое поле[0]", FormFieldFacade.AlignBottom);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The qualified field name. |
| alignment | int | The alignment style definition, including FormFieldFacade.AlignTop, FormFieldFacade.AlignMiddle and FormFieldFacade.AlignRight. |

**Returns:**
boolean - If success, return true;else false.
### setFieldAppearance(String fieldName, int flags) {#setFieldAppearance-java.lang.String-int-}
```
общедоступный абстрактный логический setFieldAppearance (String fieldName, int flags)
```


Set field flags

--------------------

```
FormEditor formEditor = новый FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf");
 formEditor.setFieldAppearance("Имя", AnnotationFlags.Hidden);
 formEditor.setFieldAppearance("Телефон", AnnotationFlags.NoView | AnnotationFlags.Print);
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
общедоступный абстрактный логический setFieldAttribute (String fieldName, int flag)
```


Set attributes of field.

--------------------

```
FormEditor formEditor = новый FormEditor("PdfForm.pdf", "PdfForm_SetFieldAttribute.pdf");
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
открытый абстрактный логический setFieldCombNumber (String fieldName, int combNumber)
```


Sets number of combs for a regular single-line text field (the field is automatically divided into as many equally spaced positions, or combs, as the value of combNumber parameter).

--------------------

```
FormEditor formEditor = новый FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf"));
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
открытый абстрактный логический setFieldLimit (String fieldName, int fieldLimit)
```


Sets maximum character count of the text field.

--------------------

```
FormEditor formEditor = новый FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf");
 formEditor.setFieldLimit("textField", 15);
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
общедоступный абстрактный логический setFieldScript (String fieldName, String script)
```


Set JavaScript for a PushButton field. If old JavaScript existed, it will be replaced by the new one.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The fully qualified field name. |
| script | java.lang.String | The Java script to be added/placed into a push button field. |

**Returns:**
boolean - boolean value: If success, return true; else false.
### setItems(String[] value) {#setItems-java.lang.String---}
```
public abstract void setItems (String[] ценность)
```


Sets items which will be added to newly created list box or combo box.

--------------------

```
formEditor = новый com.aspose.pdf.facadesFormEditor("input.pdf", "output.pdf");
 formEditor.setItems (новая строка[]
 { "ААА", "ВВВ", "ССС" });
 formEditor.addField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130);
 formEditor.save();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] | String[] object |

### setRadioButtonItemSize(double value) {#setRadioButtonItemSize-double-}
```
public abstract void setRadioButtonItemSize (двойное значение)
```


```
Получает или задает размер элемента переключателя (при добавлении нового поля переключателя).
 
 
 FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
 formEditor.setRadioGap(4);
 formEditor.setRadioHoriz (ложь);
 formEditor.setRadioButtonItemSize(20);
 formEditor.setItems (новая строка[]
 { "Первый второй третий" });
 formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
 formEditor.save();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### setRadioGap(float value) {#setRadioGap-float-}
```
public abstract void setRadioGap (значение с плавающей запятой)
```


Set the member to record the gap between two neighboring radio buttons in pixels,default is 50.

--------------------

```
formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
 formEditor.setRadioGap(4);
 formEditor.setRadioHoriz (ложь);
 formEditor.setItems (новая строка[]
 { "Первый второй третий" });
 formEditor.addField(FieldType.Radio, "AddedRadioButtonField", "Второй", 1, 10, 30, 110, 130);
 formEditor.save();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | float value |

### setRadioHoriz(boolean value) {#setRadioHoriz-boolean-}
```
public abstract void setRadioHoriz (логическое значение)
```


Set the flag to indicate whether the radios are arranged horizontally or vertically, default value is true.

--------------------

```
formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
 formEditor.setRadioGap(4);
 formEditor.setRadioHoriz (ложь);
 formEditor.setItems (новая строка[]
 { "Первый второй третий" });
 formEditor.addField(FieldType.Radio, "AddedRadioButtonField", "Второй", 1, 10, 30, 110, 130);
 formEditor.save();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setSaveOptions(SaveOptions value) {#setSaveOptions-com.aspose.pdf.SaveOptions-}
```
public abstract void setSaveOptions (значение SaveOptions)
```


Sets save options when result is stored as HttpResponse. Default value: PdfSaveOptions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SaveOptions](../../com.aspose.pdf/saveoptions) | SaveOptions object |

### setSrcFileName(String value) {#setSrcFileName-java.lang.String-}
```
public abstract void setSrcFileName (строковое значение)
```


Sets name of source file.

--------------------

```
Редактор FormEditor = новый FormEditor();
 editor.setSrcFileName("InputFile.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | string value |

### setSrcStream(InputStream value) {#setSrcStream-java.io.InputStream-}
```
public abstract void setSrcStream (значение InputStream)
```


Sets source stream.

--------------------

```
Редактор FormEditor = новый FormEditor();
 editor.setSrcStream(новый FileInputStream("InFile.pdf"));
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.InputStream | InputStream object |

### setSubmitFlag(int value) {#setSubmitFlag-int-}
```
public abstract void setSubmitFlag (значение int)
```


Set the submit button's submission flags

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | SubmitFormFlag element |

### setSubmitFlag(String fieldName, int submitFormFlag) {#setSubmitFlag-java.lang.String-int-}
```
открытый абстрактный логический setSubmitFlag (String fieldName, int submitFormFlag)
```


Set submit flag of submit button.

--------------------

```
FormEditor formEditor = новый FormEditor("PdfForm.pdf", "FormEditor_SetSubmitFlag.pdf");
 formEditor.setSubmitFlag("btnSubmit", SubmitFormFlag.Fdf);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Name of submit button. |
| submitFormFlag | int | Submit flag. |

**Returns:**
boolean - boolean value
### setSubmitUrl(String fieldName, String url) {#setSubmitUrl-java.lang.String-java.lang.String-}
```
общедоступный абстрактный логический setSubmitUrl (String fieldName, String url)
```


Sets URL of the button.

--------------------

```
FormEditor formEditor = новый FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf");
 formEditor.setSubmitUrl("btnSubmit", "www.mysite.com");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Submit button name. |
| url | java.lang.String | Fully qualified URL. |

**Returns:**
boolean - boolean value
### single2Multiple(String fieldName) {#single2Multiple-java.lang.String-}
```
общедоступный абстрактный логический single2Multiple (String fieldName)
```


Change a single-lined text field to a multiple-lined one.

--------------------

```
FormEditor formEditor = новый FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
 formEditor.single2Multiple («текстовое поле»);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The qualified field name. |

**Returns:**
boolean - If success, return true;else false.