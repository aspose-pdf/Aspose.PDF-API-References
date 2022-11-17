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

| Метод | Описание |
| --- | --- |
| [addField(int fieldType, String fieldName, int pageNum, float llx, float lly, float urx, float ury)](#addField-int-java.lang.String-int-float-float-float-float-) | Добавить в форму поле указанного типа. |
| [addField(int fieldType, String fieldName, String initValue, int pageNum, float llx, float lly, float urx, float ury)](#addField-int-java.lang.String-java.lang.String-int-float-float-float-float-) | Добавить в форму поле указанного типа. |
| [addListItem(String fieldName, String itemName)](#addListItem-java.lang.String-java.lang.String-) | Добавляет новый элемент в список. |
| [addListItem(String fieldName, String[] exportName)](#addListItem-java.lang.String-java.lang.String---) | Добавьте новый элемент со значением «Экспорт» в существующее поле списка, только для поля со списком AcroForm. |
| [addSubmitBtn(String fieldName, int page, String label, String url, float llx, float lly, float urx, float ury)](#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-) | Добавьте кнопку отправки на форму. |
| [close()](#close--) | Закрывает объект |
| [copyInnerField(String fieldName, String newFieldName, int pageNum)](#copyInnerField-java.lang.String-java.lang.String-int-) | Копирует существующее поле в ту же позицию на странице с указанным номером. |
| [copyInnerField(String fieldName, String newFieldName, int pageNum, float abscissa, float ordinate)](#copyInnerField-java.lang.String-java.lang.String-int-float-float-) | Копирует существующее поле в новую позицию, указанную как номером страницы, так и ординатами. |
| [copyOuterField(String srcFileName, String fieldName)](#copyOuterField-java.lang.String-java.lang.String-) | Копирует существующее поле из одного документа PDF в другой документ с исходным номером страницы и координатами. |
| [copyOuterField(String srcFileName, String fieldName, int pageNum)](#copyOuterField-java.lang.String-java.lang.String-int-) | Копирует существующее поле из одного документа PDF в другой документ с указанным номером страницы и исходными ординатами. |
| [copyOuterField(String srcFileName, String fieldName, int pageNum, float abscissa, float ordinate)](#copyOuterField-java.lang.String-java.lang.String-int-float-float-) | Копирует существующее поле из одного документа PDF в другой документ с указанным номером страницы и координатами. |
| [decorateField()](#decorateField--) | Изменяет визуальные атрибуты всех полей в документе PDF. |
| [decorateField(int fieldType)](#decorateField-int-) | Изменяет визуальные атрибуты всех полей с указанным типом поля. |
| [decorateField(String fieldName)](#decorateField-java.lang.String-) | Изменяет визуальные атрибуты указанного поля. |
| [delListItem(String fieldName, String itemName)](#delListItem-java.lang.String-java.lang.String-) | Удалить элемент из поля списка. |
| [dispose()](#dispose--) | Закрывает объект |
| [getAttachmentName()](#getAttachmentName--) | Получает имя вложения, когда результат операции сохраняется в объектах HttpResponse как вложение. |
| [getContentDisposition()](#getContentDisposition--) | Получает способ хранения содержимого при сохранении результата операции в объекте HttpResponse. |
| [getDestFileName()](#getDestFileName--) | Получает имя файла назначения. |
| [getDestStream()](#getDestStream--) | Получает целевой поток. |
| [getDocument()](#getDocument--) | Получает документ, над которым работает FormEditor. |
| [getExportItems()](#getExportItems--) | Получает параметры для поля со списком с экспортируемыми значениями. |
| [getFacade()](#getFacade--) | Получает визуальные атрибуты поля. |
| [getItems()](#getItems--) | Возвращает массив элементов |
| [getRadioButtonItemSize()](#getRadioButtonItemSize--) | Получает или задает размер элемента переключателя (при добавлении нового поля переключателя). |
| [getRadioGap()](#getRadioGap--) | Заставьте участника записывать промежуток между двумя соседними переключателями в пикселях, по умолчанию 50. |
| [getRadioHoriz()](#getRadioHoriz--) | Получите флаг, чтобы указать, расположены ли радиостанции горизонтально или вертикально, значение по умолчанию — true. |
| [getSaveOptions()](#getSaveOptions--) | Получает параметры сохранения, когда результат сохраняется как HttpResponse. |
| [getSrcFileName()](#getSrcFileName--) | Получает имя исходного файла. |
| [getSrcStream()](#getSrcStream--) | Получает исходный поток. |
| [getSubmitFlag()](#getSubmitFlag--) | Получить флаги отправки кнопки отправки |
| [moveField(String fieldName, float llx, float lly, float urx, float ury)](#moveField-java.lang.String-float-float-float-float-) | Установить новую позицию поля. |
| [removeField(String fieldName)](#removeField-java.lang.String-) | Удалить поле из формы. |
| [removeFieldAction(String fieldName)](#removeFieldAction-java.lang.String-) | Удалить действие отправки поля. |
| [renameField(String fieldName, String newFieldName)](#renameField-java.lang.String-java.lang.String-) | Изменить имя поля. |
| [resetFacade()](#resetFacade--) | Сбросить все визуальные атрибуты до пустого значения. |
| [resetInnerFacade()](#resetInnerFacade--) | Сбросить все визуальные атрибуты внутреннего фасада до пустого значения. |
| [save()](#save--) | Сохраняет изменения в файле назначения. |
| [setAttachmentName(String value)](#setAttachmentName-java.lang.String-) | Задает имя вложения, когда результат операции сохраняется в объектах HttpResponse как вложение. |
| [setContentDisposition(int value)](#setContentDisposition-int-) | Устанавливает, как содержимое будет сохранено, когда результат операции будет сохранен в объекте HttpResponse. |
| [setConvertTo(PdfFormat value)](#setConvertTo-com.aspose.pdf.PdfFormat-) |  Наборы[PdfFormat](../../com.aspose.pdf/pdfformat) Формат файла PDF. |
| [setDestFileName(String value)](#setDestFileName-java.lang.String-) | Устанавливает имя файла назначения. |
| [setDestStream(OutputStream value)](#setDestStream-java.io.OutputStream-) | Устанавливает целевой поток. |
| [setExportItems(String[][] value)](#setExportItems-java.lang.String-----) | Устанавливает параметры для поля со списком с экспортируемыми значениями. |
| [setFacade(FormFieldFacade value)](#setFacade-com.aspose.pdf.facades.FormFieldFacade-) | Задает визуальные атрибуты поля. |
| [setFieldAlignment(String fieldName, int alignment)](#setFieldAlignment-java.lang.String-int-) | Установите стиль выравнивания текстового поля. |
| [setFieldAlignmentV(String fieldName, int alignment)](#setFieldAlignmentV-java.lang.String-int-) | Установите стиль вертикального выравнивания текстового поля. |
| [setFieldAppearance(String fieldName, int flags)](#setFieldAppearance-java.lang.String-int-) | Установить флаги полей |
| [setFieldAttribute(String fieldName, int flag)](#setFieldAttribute-java.lang.String-int-) | Установить атрибуты поля. |
| [setFieldCombNumber(String fieldName, int combNumber)](#setFieldCombNumber-java.lang.String-int-) | Задает количество гребенок для обычного однострочного текстового поля (поле автоматически разбивается на столько равноотстоящих позиций или гребешков, сколько установлено значением параметра combNumber). |
| [setFieldLimit(String fieldName, int fieldLimit)](#setFieldLimit-java.lang.String-int-) | Устанавливает максимальное количество символов в текстовом поле. |
| [setFieldScript(String fieldName, String script)](#setFieldScript-java.lang.String-java.lang.String-) | Установите JavaScript для поля PushButton. |
| [setItems(String[] value)](#setItems-java.lang.String---) | Устанавливает элементы, которые будут добавлены во вновь созданный список или поле со списком. |
| [setRadioButtonItemSize(double value)](#setRadioButtonItemSize-double-) | Получает или задает размер элемента переключателя (при добавлении нового поля переключателя).|
| [setRadioGap(float value)](#setRadioGap-float-) | Настройте элемент для записи промежутка между двумя соседними переключателями в пикселях, по умолчанию 50. |
| [setRadioHoriz(boolean value)](#setRadioHoriz-boolean-) | Установите флаг, чтобы указать, расположены ли радиостанции горизонтально или вертикально, значение по умолчанию — true. |
| [setSaveOptions(SaveOptions value)](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Задает параметры сохранения, когда результат сохраняется как HttpResponse. |
| [setSrcFileName(String value)](#setSrcFileName-java.lang.String-) | Устанавливает имя исходного файла. |
| [setSrcStream(InputStream value)](#setSrcStream-java.io.InputStream-) | Устанавливает исходный поток. |
| [setSubmitFlag(int value)](#setSubmitFlag-int-) | Установите флаги отправки кнопки отправки |
| [setSubmitFlag(String fieldName, int submitFormFlag)](#setSubmitFlag-java.lang.String-int-) | Установите флаг отправки кнопки отправки. |
| [setSubmitUrl(String fieldName, String url)](#setSubmitUrl-java.lang.String-java.lang.String-) | Устанавливает URL кнопки. |
| [single2Multiple(String fieldName)](#single2Multiple-java.lang.String-) | Измените однострочное текстовое поле на многострочное. |
### addField(int fieldType, String fieldName, int pageNum, float llx, float lly, float urx, float ury) {#addField-int-java.lang.String-int-float-float-float-float-}
```
public abstract boolean addField(int fieldType, String fieldName, int pageNum, float llx, float lly, float urx, float ury)
```


Добавить в форму поле указанного типа.

--------------------

```
FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf");
 formEditor.addField(FieldType.Text, "AddedTextField", 1, 10, 30, 110, 46);
 formEditor.save();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldType | int | Тип поля, которое необходимо добавить. |
| fieldName | java.lang.String | Имя поля, которое необходимо добавить. |
| pageNum | int | Номер страницы, на которой должно быть размещено новое поле. |
| llx | float | Абсцисса нижнего левого угла поля. |
| lly | float | Ордината нижнего левого угла поля. |
| urx | float | Абсцисса правого верхнего угла поля. |
| ury | float | Ордината правого верхнего угла поля. |

**Возвращает:**
boolean - true, если поле было успешно добавлено.
### addField(int fieldType, String fieldName, String initValue, int pageNum, float llx, float lly, float urx, float ury) {#addField-int-java.lang.String-java.lang.String-int-float-float-float-float-}
```
public abstract boolean addField(int fieldType, String fieldName, String initValue, int pageNum, float llx, float lly, float urx, float ury)
```


Добавить в форму поле указанного типа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldType | int | Тип поля, которое необходимо добавить. |
| fieldName | java.lang.String | Имя поля, которое необходимо добавить. |
| initValue | java.lang.String | Начальное значение поля. |
| pageNum | int | Номер страницы, на которой должно быть размещено новое поле. |
| llx | float | Абсцисса нижнего левого угла поля. |
| lly | float | Ордината нижнего левого угла поля. |
| urx | float | Абсцисса правого верхнего угла поля. |
| ury | float | Ордината правого верхнего угла поля. |

**Возвращает:**
boolean - true, если поле было успешно добавлено.
### addListItem(String fieldName, String itemName) {#addListItem-java.lang.String-java.lang.String-}
```
public abstract void addListItem(String fieldName, String itemName)
```


Добавляет новый элемент в список.

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", PdfForm_out.pdf");
 formEditor.addListItem("listBoxField", "Item 4 (New Item)");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Имя поля, в которое будет добавлен новый элемент. |
| itemName | java.lang.String | Имя, если новый элемент. |

### addListItem(String fieldName, String[] exportName) {#addListItem-java.lang.String-java.lang.String---}
```
public abstract void addListItem(String fieldName, String[] exportName)
```


Добавьте новый элемент со значением «Экспорт» в существующее поле списка, только для поля со списком AcroForm.

--------------------

```
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_AddListItem2.pdf");
 fe.addListItem("listboxField", new String[]
 { "4", "Item4(Added)" });
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Имя поля, в которое будут добавлены элементы. |
| exportName | java.lang.String[] | Массив строк, обозначающий новый элемент списка со значением экспорта, т. е. (метка элемента, значение экспорта). |

### addSubmitBtn(String fieldName, int page, String label, String url, float llx, float lly, float urx, float ury) {#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-}
```
public abstract void addSubmitBtn(String fieldName, int page, String label, String url, float llx, float lly, float urx, float ury)
```


Добавьте кнопку отправки на форму.

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_AddSubmitBtn.pdf");
 formEditor.addSubmitBtn("submit", 1, "Submit", "www.check.com", 10, 200, 70, 270);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Имя новой кнопки. |
| page | int | Страница, на которой будет размещена кнопка. |
| label | java.lang.String | Надпись на кнопке. |
| url | java.lang.String | URL кнопки отправки. |
| llx | float | Абсцисса нижнего левого угла. |
| lly | float | Ордината нижнего левого угла. |
| urx | float | Абсцисса правого верхнего угла. |
| ury | float | Ордината правого верхнего угла. |

### close() {#close--}
```
public abstract void close()
```


Закрывает объект

### copyInnerField(String fieldName, String newFieldName, int pageNum) {#copyInnerField-java.lang.String-java.lang.String-int-}
```
public abstract void copyInnerField(String fieldName, String newFieldName, int pageNum)
```


Копирует существующее поле в ту же позицию на странице с указанным номером. Будет создан новый документ, содержащий все, что есть в исходном документе, за исключением только что скопированного поля.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Строковое значение |
| newFieldName | java.lang.String | Строковое значение |
| pageNum | int | целое значение |

### copyInnerField(String fieldName, String newFieldName, int pageNum, float abscissa, float ordinate) {#copyInnerField-java.lang.String-java.lang.String-int-float-float-}
```
public abstract void copyInnerField(String fieldName, String newFieldName, int pageNum, float abscissa, float ordinate)
```


Копирует существующее поле в новую позицию, указанную как номером страницы, так и ординатами. Будет создан новый документ, содержащий все, что есть в исходном документе, за исключением только что скопированного поля.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Строковое значение |
| newFieldName | java.lang.String | Строковое значение |
| pageNum | int | целое значение |
| abscissa | float | плавающее значение |
| ordinate | float | плавающее значение |

### copyOuterField(String srcFileName, String fieldName) {#copyOuterField-java.lang.String-java.lang.String-}
```
public abstract void copyOuterField(String srcFileName, String fieldName)
```


Копирует существующее поле из одного документа PDF в другой документ с исходным номером страницы и координатами. Примечание. Только для полей AcroForm (за исключением переключателя).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFileName | java.lang.String | Строковое значение |
| fieldName | java.lang.String | Строковое значение |

### copyOuterField(String srcFileName, String fieldName, int pageNum) {#copyOuterField-java.lang.String-java.lang.String-int-}
```
public abstract void copyOuterField(String srcFileName, String fieldName, int pageNum)
```


Копирует существующее поле из одного документа PDF в другой документ с указанным номером страницы и исходными ординатами. Примечание. Только для полей AcroForm (за исключением переключателя).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFileName | java.lang.String | Строковое значение |
| fieldName | java.lang.String | Строковое значение |
| pageNum | int | целое значение |

### copyOuterField(String srcFileName, String fieldName, int pageNum, float abscissa, float ordinate) {#copyOuterField-java.lang.String-java.lang.String-int-float-float-}
```
public abstract void copyOuterField(String srcFileName, String fieldName, int pageNum, float abscissa, float ordinate)
```


Копирует существующее поле из одного документа PDF в другой документ с указанным номером страницы и координатами. Примечание. Только для полей AcroForm (за исключением переключателя).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFileName | java.lang.String | Строковое значение |
| fieldName | java.lang.String | Строковое значение |
| pageNum | int | целое значение |
| abscissa | float | плавающее значение |
| ordinate | float | плавающее значение |

### decorateField() {#decorateField--}
```
public abstract void decorateField()
```


Изменяет визуальные атрибуты всех полей в документе PDF.

--------------------

```
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf");
 fe.setFacade(new FormFieldFacade());
 fe.getFacade().setBackgroundColor(Color.red);
 fe.getFacade().setTextColor(Color.blue);
 fe.getFacade().setBorderColor(Color.Green);
 fe.getFacade().setAlignment(FormFieldFacade.AlignRight);
 // украсить все поля.
 fe.decorateField();
```

### decorateField(int fieldType) {#decorateField-int-}
```
public abstract void decorateField(int fieldType)
```


Изменяет визуальные атрибуты всех полей с указанным типом поля.

--------------------

```
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf");
 fe.setFacade(new FormFieldFacade());
 fe.getFacade().setBackgroundColor(Color.red);
 fe.getFacade().setTextColor(Color.blue);
 fe.getFacade().setBorderColor(Color.green);
 fe.getFacade().setAlignment(FormFieldFacade.AlignRight);
 // украсить все текстовые поля.
 fe.decorateField(FieldType.Text);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldType | int | Тип полей, которые будут декорированы. |

### decorateField(String fieldName) {#decorateField-java.lang.String-}
```
public abstract void decorateField(String fieldName)
```


Изменяет визуальные атрибуты указанного поля.

--------------------

```
FormEditor fe = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_DecorateField_text.pdf");
 fe.Facade = new FormFieldFacade();
 fe.Facade.setBackgroundColor(Color.Red);
 fe.Facade.setTextColor(Color.Blue);
 fe.Facade.setBorderColor(Color.Green);
 fe.Facade.setAlignment(FormFieldFacade.AlignCenter);
 fe.decorateField("textField");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Полное имя поля. |

### delListItem(String fieldName, String itemName) {#delListItem-java.lang.String-java.lang.String-}
```
public abstract void delListItem(String fieldName, String itemName)
```


Удалить элемент из поля списка.

--------------------

```
formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_DelListItem.pdf");
 formEditor.delListItem("listboxField", "item2");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Имя поля. |
| itemName | java.lang.String | Имя элемента, который необходимо удалить. |

### dispose() {#dispose--}
```
public abstract void dispose()
```


Закрывает объект

### getAttachmentName() {#getAttachmentName--}
```
public abstract String getAttachmentName()
```


Получает имя вложения, когда результат операции сохраняется в объектах HttpResponse как вложение.

**Возвращает:**
java.lang.String — строковый объект
### getContentDisposition() {#getContentDisposition--}
```
public abstract int getContentDisposition()
```


Получает способ хранения содержимого при сохранении результата операции в объекте HttpResponse. Возможное значение: inline/attachment. По умолчанию: встроенный.

**Возвращает:**
int — элемент ContentDisposition
### getDestFileName() {#getDestFileName--}
```
public abstract String getDestFileName()
```


Получает имя файла назначения.

**Возвращает:**
java.lang.String — строковое значение
### getDestStream() {#getDestStream--}
```
public abstract OutputStream getDestStream()
```


Получает целевой поток.

--------------------

```
FormEditor editor = new FormEditor();
 editor.setDestStream(new FileInputStream("OutFile.pdf"));
```

**Возвращает:**
java.io.OutputStream — объект OutputStream
### getDocument() {#getDocument--}
```
public abstract IDocument getDocument()
```


Получает документ, над которым работает FormEditor.

**Возвращает:**
[IDocument](../../com.aspose.pdf/idocument) - Объект IDocument
### getExportItems() {#getExportItems--}
```
public abstract String[][] getExportItems()
```


Получает параметры для поля со списком с экспортируемыми значениями.

**Возвращает:**
java.lang.String[][] - Нить[][] объект
### getFacade() {#getFacade--}
```
public abstract FormFieldFacade getFacade()
```


Получает визуальные атрибуты поля.

**Возвращает:**
[FormFieldFacade](../../com.aspose.pdf.facades/formfieldfacade) - Объект FormFieldFacade
### getItems() {#getItems--}
```
public abstract String[] getItems()
```


Возвращает массив элементов

**Возвращает:**
java.lang.String[] - Нить[] объект
### getRadioButtonItemSize() {#getRadioButtonItemSize--}
```
public abstract double getRadioButtonItemSize()
```


```
Gets or sets size of radio button item size (when new radio button field is added).
 
 
 FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
 formEditor.setRadioGap(4);
 formEditor.setRadioHoriz(false);
 formEditor.setRadioButtonItemSize(20);
 formEditor.setItems(new String[]
 { "First", "Second", "Third" });
 formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
 formEditor.save();
```

**Возвращает:**
двойное - логическое значение
### getRadioGap() {#getRadioGap--}
```
public abstract float getRadioGap()
```


Заставьте участника записывать промежуток между двумя соседними переключателями в пикселях, по умолчанию 50.

**Возвращает:**
float - плавающее значение
### getRadioHoriz() {#getRadioHoriz--}
```
public abstract boolean getRadioHoriz()
```


Получите флаг, чтобы указать, расположены ли радиостанции горизонтально или вертикально, значение по умолчанию — true.

**Возвращает:**
boolean - логическое значение
### getSaveOptions() {#getSaveOptions--}
```
public abstract SaveOptions getSaveOptions()
```


Получает параметры сохранения, когда результат сохраняется как HttpResponse. Значение по умолчанию: пдфсавеоптионс.

**Возвращает:**
[SaveOptions](../../com.aspose.pdf/saveoptions) - Объект SaveOptions
### getSrcFileName() {#getSrcFileName--}
```
public abstract String getSrcFileName()
```


Получает имя исходного файла.

**Возвращает:**
java.lang.String — строковое значение
### getSrcStream() {#getSrcStream--}
```
public abstract InputStream getSrcStream()
```


Получает исходный поток.

**Возвращает:**
java.io.InputStream — объект InputStream
### getSubmitFlag() {#getSubmitFlag--}
```
public abstract int getSubmitFlag()
```


Получить флаги отправки кнопки отправки

**Возвращает:**
int — элемент SubmitFormFlag
### moveField(String fieldName, float llx, float lly, float urx, float ury) {#moveField-java.lang.String-float-float-float-float-}
```
public abstract boolean moveField(String fieldName, float llx, float lly, float urx, float ury)
```


Установить новую позицию поля.

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_MoveField.pdf");
 formEditor.moveField("textField", 20.5f, 20.3f, 120.6f, 40.8f);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Имя поля, которое необходимо переместить. |
| llx | float | Абсцисса нижнего левого угла поля. |
| lly | float | Ордината нижнего левого угла поля. |
| urx | float | Абсцисса правого верхнего угла поля. |
| ury | float | Ордината правого верхнего угла поля. |

**Возвращает:**
boolean - true, если позиция поля была успешно изменена.
### removeField(String fieldName) {#removeField-java.lang.String-}
```
public abstract void removeField(String fieldName)
```


Удалить поле из формы.

--------------------

```
FormEditr formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveField.pdf");
 formEditor.removeField("listboxField");
 formEditor.removeField("textField");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Имя поля, которое необходимо удалить. |

### removeFieldAction(String fieldName) {#removeFieldAction-java.lang.String-}
```
public abstract void removeFieldAction(String fieldName)
```


Удалить действие отправки поля.

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveFieldAction.pdf");
 formEditor.removeFieldAction("btnSubmit");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Имя поля. |

### renameField(String fieldName, String newFieldName) {#renameField-java.lang.String-java.lang.String-}
```
public abstract void renameField(String fieldName, String newFieldName)
```


Изменить имя поля.

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
 formEditor.renameField("textField", "textField_Renamed");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Старое название поля. |
| newFieldName | java.lang.String | Новое имя поля. |

### resetFacade() {#resetFacade--}
```
public abstract void resetFacade()
```


Сбросить все визуальные атрибуты до пустого значения.

### resetInnerFacade() {#resetInnerFacade--}
```
public abstract void resetInnerFacade()
```


Сбросить все визуальные атрибуты внутреннего фасада до пустого значения.

### save() {#save--}
```
public abstract void save()
```


Сохраняет изменения в файле назначения.

### setAttachmentName(String value) {#setAttachmentName-java.lang.String-}
```
public abstract void setAttachmentName(String value)
```


Задает имя вложения, когда результат операции сохраняется в объектах HttpResponse как вложение.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковый объект |

### setContentDisposition(int value) {#setContentDisposition-int-}
```
public abstract void setContentDisposition(int value)
```


Устанавливает, как содержимое будет сохранено, когда результат операции будет сохранен в объекте HttpResponse. Возможное значение: inline/attachment. По умолчанию: встроенный.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент ContentDisposition |

### setConvertTo(PdfFormat value) {#setConvertTo-com.aspose.pdf.PdfFormat-}
```
public abstract void setConvertTo(PdfFormat value)
```


 Наборы[PdfFormat](../../com.aspose.pdf/pdfformat) Формат файла PDF. Файл результата будет сохранен в указанном формате. Если это свойство не указано, файл будет сохранен в формате PDF по умолчанию без преобразования.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfFormat](../../com.aspose.pdf/pdfformat) | Элемент PdfFormat |

### setDestFileName(String value) {#setDestFileName-java.lang.String-}
```
public abstract void setDestFileName(String value)
```


Устанавливает имя файла назначения.

--------------------

```
FormEditor editor = new FormEditor();
 editor.setDestFileName("OutFile.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковый объект |

### setDestStream(OutputStream value) {#setDestStream-java.io.OutputStream-}
```
public abstract void setDestStream(OutputStream value)
```


Устанавливает целевой поток.

--------------------

```
FormEditor editor = new FormEditor();
 editor.setDestStream(new FileInputStream("OutFile.pdf"));
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.io.OutputStream | Объект OutputStream |

### setExportItems(String[][] value) {#setExportItems-java.lang.String-----}
```
public abstract void setExportItems(String[][] value)
```


Устанавливает параметры для поля со списком с экспортируемыми значениями.

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_Updated.pdf"));
 formEditor.setExportItems ( new String[][] 
 { 
     new String[] { "1", "Firs" }, 
     new String[] { "2", "Second" }, 
     new String[] { "3", "Third" } 
 });
 formEditor.addField(FieldType.ListBox, "AddedListBoxField", "Second", 1, 10, 30, 110, 130);
 formEditor.save();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Нить[][] | String[][] объект |

### setFacade(FormFieldFacade value) {#setFacade-com.aspose.pdf.facades.FormFieldFacade-}
```
public abstract void setFacade(FormFieldFacade value)
```


Задает визуальные атрибуты поля.

--------------------

```
FormEditor fe = new FormEditor("PdfForm.pdf", "PdfForm_DecorateField_text.pdf");
 fe.setFacade(new FormFieldFacade());
 fe.getFacade().setBackgroundColor(Color.red);
 fe.getFacade().setTextColor(Color.blue);
 fe.getFacade().setBorderColor(Color.green);
 fe.getFacade().setAlignment(FormFieldFacade.AlignCenter);
 fe.setDecorateField("textField");
 fe.save();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [FormFieldFacade](../../com.aspose.pdf.facades/formfieldfacade) | Объект FormFieldFacade |

### setFieldAlignment(String fieldName, int alignment) {#setFieldAlignment-java.lang.String-int-}
```
public abstract boolean setFieldAlignment(String fieldName, int alignment)
```


Установите стиль выравнивания текстового поля.

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_updated.pdf"));
  formEditor.setFieldAlignment(fieldName, FormFieldFacade.AlignCenter);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Полное имя поля. |
| alignment | int | Определение стиля выравнивания, включая FormFieldFacade.AlignLeft, FormFieldFacade.AlignCenter и FormFieldFacade.AlignRight. |

**Возвращает:**
boolean - логическое значение
### setFieldAlignmentV(String fieldName, int alignment) {#setFieldAlignmentV-java.lang.String-int-}
```
public abstract boolean setFieldAlignmentV(String fieldName, int alignment)
```


Установите стиль вертикального выравнивания текстового поля.

--------------------

```
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
 fe.setFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Полное имя поля. |
| alignment | int | Определение стиля выравнивания, включая FormFieldFacade.AlignTop, FormFieldFacade.AlignMiddle и FormFieldFacade.AlignRight. |

**Возвращает:**
boolean - В случае успеха вернуть true, иначе false.
### setFieldAppearance(String fieldName, int flags) {#setFieldAppearance-java.lang.String-int-}
```
public abstract boolean setFieldAppearance(String fieldName, int flags)
```


Установить флаги полей

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf");
 formEditor.setFieldAppearance("Name", AnnotationFlags.Hidden);
 formEditor.setFieldAppearance("Phone", AnnotationFlags.NoView | AnnotationFlags.Print);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Имя поля, флаги которого необходимо обновить. |
| flags | int | Флаг поля. |

**Возвращает:**
boolean - true, если флаги были успешно обновлены.
### setFieldAttribute(String fieldName, int flag) {#setFieldAttribute-java.lang.String-int-}
```
public abstract boolean setFieldAttribute(String fieldName, int flag)
```


Установить атрибуты поля.

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_SetFieldAttribute.pdf");
 formEditor.setFieldAttribute("listboxField", PropertyFlag.ReadOnly);
 formEditor.setFieldAttribute("textField", PropertyFlag.NoExport);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Имя поля, атрибуты которого должны быть установлены. |
| flag | int | Флаг (NoExport/ReadOnly/Required) |

**Возвращает:**
boolean - true, если атрибут был установлен успешно.
### setFieldCombNumber(String fieldName, int combNumber) {#setFieldCombNumber-java.lang.String-int-}
```
public abstract boolean setFieldCombNumber(String fieldName, int combNumber)
```


Задает количество гребенок для обычного однострочного текстового поля (поле автоматически разбивается на столько равноотстоящих позиций или гребешков, сколько установлено значением параметра combNumber).

--------------------

```
FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf"));
 formEditor.setFieldCombNumber("textCombField", 5);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Полное имя поля. |
| combNumber | int | Количество сот, на которые нужно разделить поле. |

**Возвращает:**
boolean - В случае успеха вернуть true, иначе false.
### setFieldLimit(String fieldName, int fieldLimit) {#setFieldLimit-java.lang.String-int-}
```
public abstract boolean setFieldLimit(String fieldName, int fieldLimit)
```


Устанавливает максимальное количество символов в текстовом поле.

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf");
 formEditor.setFieldLimit("textField", 15);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Имя текстового поля. |
| fieldLimit | int | Новое значение лимита для поля. |

**Возвращает:**
boolean - true, если ограничение поля было успешно установлено.
### setFieldScript(String fieldName, String script) {#setFieldScript-java.lang.String-java.lang.String-}
```
public abstract boolean setFieldScript(String fieldName, String script)
```


Установите JavaScript для поля PushButton. Если старый JavaScript существовал, он будет заменен новым.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Полное имя поля. |
| script | java.lang.String | Java-скрипт, который нужно добавить/поместить в поле кнопки. |

**Возвращает:**
boolean - логическое значение: в случае успеха вернуть true; иначе ложно.
### setItems(String[] value) {#setItems-java.lang.String---}
```
public abstract void setItems(String[] value)
```


Устанавливает элементы, которые будут добавлены во вновь созданный список или поле со списком.

--------------------

```
formEditor = new com.aspose.pdf.facadesFormEditor("input.pdf", "output.pdf");
 formEditor.setItems(new String[]
 { "AAA", "BBB", "CCC" });
 formEditor.addField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130);
 formEditor.save();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Нить[] | String[] объект |

### setRadioButtonItemSize(double value) {#setRadioButtonItemSize-double-}
```
public abstract void setRadioButtonItemSize(double value)
```


```
Gets or sets size of radio button item size (when new radio button field is added).
 
 
 FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
 formEditor.setRadioGap(4);
 formEditor.setRadioHoriz(false);
 formEditor.setRadioButtonItemSize(20);
 formEditor.setItems(new String[]
 { "First", "Second", "Third" });
 formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
 formEditor.save();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setRadioGap(float value) {#setRadioGap-float-}
```
public abstract void setRadioGap(float value)
```


Настройте элемент для записи промежутка между двумя соседними переключателями в пикселях, по умолчанию 50.

--------------------

```
formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
 formEditor.setRadioGap(4);
 formEditor.setRadioHoriz(false);
 formEditor.setItems(new String[]
 { "First", "Second", "Third" });
 formEditor.addField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
 formEditor.save();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | плавающее значение |

### setRadioHoriz(boolean value) {#setRadioHoriz-boolean-}
```
public abstract void setRadioHoriz(boolean value)
```


Установите флаг, чтобы указать, расположены ли радиостанции горизонтально или вертикально, значение по умолчанию — true.

--------------------

```
formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
 formEditor.setRadioGap(4);
 formEditor.setRadioHoriz(false);
 formEditor.setItems(new String[]
 { "First", "Second", "Third" });
 formEditor.addField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
 formEditor.save();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setSaveOptions(SaveOptions value) {#setSaveOptions-com.aspose.pdf.SaveOptions-}
```
public abstract void setSaveOptions(SaveOptions value)
```


Задает параметры сохранения, когда результат сохраняется как HttpResponse. Значение по умолчанию: пдфсавеоптионс.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [SaveOptions](../../com.aspose.pdf/saveoptions) | Объект SaveOptions |

### setSrcFileName(String value) {#setSrcFileName-java.lang.String-}
```
public abstract void setSrcFileName(String value)
```


Устанавливает имя исходного файла.

--------------------

```
FormEditor editor = new FormEditor();
 editor.setSrcFileName("InputFile.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | строковое значение |

### setSrcStream(InputStream value) {#setSrcStream-java.io.InputStream-}
```
public abstract void setSrcStream(InputStream value)
```


Устанавливает исходный поток.

--------------------

```
FormEditor editor = new FormEditor();
 editor.setSrcStream(new FileInputStream("InFile.pdf"));
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.io.InputStream | Объект InputStream |

### setSubmitFlag(int value) {#setSubmitFlag-int-}
```
public abstract void setSubmitFlag(int value)
```


Установите флаги отправки кнопки отправки

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент SubmitFormFlag |

### setSubmitFlag(String fieldName, int submitFormFlag) {#setSubmitFlag-java.lang.String-int-}
```
public abstract boolean setSubmitFlag(String fieldName, int submitFormFlag)
```


Установите флаг отправки кнопки отправки.

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitFlag.pdf");
 formEditor.setSubmitFlag("btnSubmit", SubmitFormFlag.Fdf);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Название кнопки отправки. |
| submitFormFlag | int | Отправить флаг. |

**Возвращает:**
boolean - логическое значение
### setSubmitUrl(String fieldName, String url) {#setSubmitUrl-java.lang.String-java.lang.String-}
```
public abstract boolean setSubmitUrl(String fieldName, String url)
```


Устанавливает URL кнопки.

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf");
 formEditor.setSubmitUrl("btnSubmit", "www.mysite.com");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Отправить название кнопки. |
| url | java.lang.String | Полный URL-адрес. |

**Возвращает:**
boolean - логическое значение
### single2Multiple(String fieldName) {#single2Multiple-java.lang.String-}
```
public abstract boolean single2Multiple(String fieldName)
```


Измените однострочное текстовое поле на многострочное.

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
 formEditor.single2Multiple("textField");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Полное имя поля. |

**Возвращает:**
boolean - В случае успеха вернуть true, иначе false.