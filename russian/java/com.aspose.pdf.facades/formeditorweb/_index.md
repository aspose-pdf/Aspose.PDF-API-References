---
title: FormEditorWeb
second_title: Aspose.PDF для справки по Java API
description: Класс для редактирования форм, добавления/удаления полей и т.д.
type: docs
weight: 27
url: /ru/java/com.aspose.pdf.facades/formeditorweb/
---
**Наследование:**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade), com.aspose.pdf.facades.AFormEditor

**Все реализованные интерфейсы:**
[com.aspose.pdf.facades.IFormEditor](../../com.aspose.pdf.facades/iformeditor)
```
public final class FormEditorWeb extends AFormEditor implements IFormEditor
```

Класс для редактирования форм (добавление/удаление поля и т.д.)
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FormEditorWeb()](#FormEditorWeb--) | Конструктор для FormEditorWeb. |
| [FormEditorWeb(IDocument document)](#FormEditorWeb-com.aspose.pdf.IDocument-) | Инициализирует новый объект FormEditorWeb на основе документа. |
| [FormEditorWeb(IDocument document, OutputStream destStream)](#FormEditorWeb-com.aspose.pdf.IDocument-java.io.OutputStream-) | Инициализирует новый объект FormEditorWeb на основе документа. |
| [FormEditorWeb(IDocument document, String destFileName)](#FormEditorWeb-com.aspose.pdf.IDocument-java.lang.String-) | Инициализирует новый объект FormEditorWeb на основе документа. |
| [FormEditorWeb(InputStream inputStream, HttpServletResponse response)](#FormEditorWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-) | Создает FormEditorWeb, который сохраняет результат в объекте HttpResponse. |
| [FormEditorWeb(InputStream srcStream, OutputStream destStream)](#FormEditorWeb-java.io.InputStream-java.io.OutputStream-) | Конструктор для FormEditorWeb. |
| [FormEditorWeb(String inputFile, HttpServletResponse response)](#FormEditorWeb-java.lang.String-javax.servlet.http.HttpServletResponse-) | Создает FormEditorWeb, который сохраняет результат в объекте HttpResponse. |
| [FormEditorWeb(String srcFileName, String destFileName)](#FormEditorWeb-java.lang.String-java.lang.String-) | Конструктор для FormEditorWeb |
## Методы

| Метод | Описание |
| --- | --- |
| [addField(int fieldType, String fieldName, int pageNum, float llx, float lly, float urx, float ury)](#addField-int-java.lang.String-int-float-float-float-float-) | Добавить в форму поле указанного типа. |
| [addField(int fieldType, String fieldName, String initValue, int pageNum, float llx, float lly, float urx, float ury)](#addField-int-java.lang.String-java.lang.String-int-float-float-float-float-) | Добавить в форму поле указанного типа. |
| [addFieldScript(String fieldName, String script)](#addFieldScript-java.lang.String-java.lang.String-) | Добавьте JavaScript для поля PushButton. |
| [addListItem(String fieldName, String itemName)](#addListItem-java.lang.String-java.lang.String-) | Добавляет новый элемент в список. |
| [addListItem(String fieldName, String[] exportName)](#addListItem-java.lang.String-java.lang.String---) | Добавьте новый элемент со значением «Экспорт» в существующее поле списка, только для поля со списком AcroForm. |
| [addSubmitBtn(String fieldName, int page, String label, String url, float llx, float lly, float urx, float ury)](#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-) | Добавьте кнопку отправки на форму. |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | Инициализирует фасад. |
| [bindPdf(InputStream srcStream)](#bindPdf-java.io.InputStream-) | Инициализирует фасад. |
| [bindPdf(InputStream srcStream, String password)](#bindPdf-java.io.InputStream-java.lang.String-) | Инициализирует фасад. |
| [bindPdf(String srcFile)](#bindPdf-java.lang.String-) | Инициализирует фасад. |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | Инициализирует фасад. |
| [close()](#close--) | Закрывает все ресурсы, используемые этим документом. |
| [copyInnerField(String fieldName, String newFieldName, int pageNum)](#copyInnerField-java.lang.String-java.lang.String-int-) | Копирует существующее поле в ту же позицию на странице с указанным номером. |
| [copyInnerField(String fieldName, String newFieldName, int pageNum, float abscissa, float ordinate)](#copyInnerField-java.lang.String-java.lang.String-int-float-float-) | Копирует существующее поле в новую позицию, указанную как номером страницы, так и ординатами. |
| [copyOuterField(String srcFileName, String fieldName)](#copyOuterField-java.lang.String-java.lang.String-) | Копирует существующее поле из одного документа PDF в другой документ с исходным номером страницы и координатами. |
| [copyOuterField(String srcFileName, String fieldName, int pageNum)](#copyOuterField-java.lang.String-java.lang.String-int-) | Копирует существующее поле из одного документа PDF в другой документ с указанным номером страницы и исходными ординатами. |
| [copyOuterField(String srcFileName, String fieldName, int pageNum, float abscissa, float ordinate)](#copyOuterField-java.lang.String-java.lang.String-int-float-float-) | Копирует существующее поле из одного документа PDF в другой документ с указанным номером страницы и координатами. |
| [decorateField()](#decorateField--) | Изменяет визуальные атрибуты всех полей в документе PDF. |
| [decorateField(int fieldType)](#decorateField-int-) | Изменяет визуальные атрибуты всех полей с указанным типом поля. |
| [decorateField(String fieldName)](#decorateField-java.lang.String-) | Изменяет визуальные атрибуты указанного поля. |
| [delListItem(String fieldName, String itemName)](#delListItem-java.lang.String-java.lang.String-) | Удалить элемент из поля списка. |
| [dispose()](#dispose--) | Закрывает все ресурсы, используемые этим документом. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttachmentName()](#getAttachmentName--) | Получает имя вложения, когда результат операции сохраняется в объектах HttpResponse как вложение. |
| [getClass()](#getClass--) |  |
| [getContentDisposition()](#getContentDisposition--) | Получает способ хранения содержимого при сохранении результата операции в объекте HttpResponse. |
| [getDestFileName()](#getDestFileName--) | Получает имя файла назначения. |
| [getDestStream()](#getDestStream--) | Получает целевой поток. |
| [getDocument()](#getDocument--) | Получает фасад документа, над которым работает. |
| [getExportItems()](#getExportItems--) | Получает параметры для поля со списком с экспортируемыми значениями. |
| [getFacade()](#getFacade--) | Получает визуальные атрибуты поля. |
| [getFieldAppearance(String fieldName)](#getFieldAppearance-java.lang.String-) | Получить полевые флаги. |
| [getItems()](#getItems--) |  |
| [getRadioButtonItemSize()](#getRadioButtonItemSize--) | Получает или задает размер элемента переключателя (при добавлении нового поля переключателя). |
| [getRadioGap()](#getRadioGap--) | Заставьте участника записывать промежуток между двумя соседними переключателями в пикселях, по умолчанию 50. |
| [getRadioHoriz()](#getRadioHoriz--) | Получите флаг, чтобы указать, расположены ли радиостанции горизонтально или вертикально, значение по умолчанию — true. |
| [getResponse()](#getResponse--) | Получает объект Response, в котором будет храниться результат операции. |
| [getSaveOptions()](#getSaveOptions--) | Получает параметры сохранения, когда результат сохраняется как HttpResponse. |
| [getSrcFileName()](#getSrcFileName--) | Получает имя исходного файла. |
| [getSrcStream()](#getSrcStream--) | Получает исходный поток. |
| [getSubmitFlag()](#getSubmitFlag--) | Получить флаги отправки кнопки отправки |
| [hashCode()](#hashCode--) |  |
| [moveField(String fieldName, float llx, float lly, float urx, float ury)](#moveField-java.lang.String-float-float-float-float-) | Установить новую позицию поля. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeField(String fieldName)](#removeField-java.lang.String-) | Удалить поле из формы. |
| [removeFieldAction(String fieldName)](#removeFieldAction-java.lang.String-) | Удалить действие отправки поля. |
| [renameField(String fieldName, String newFieldName)](#renameField-java.lang.String-java.lang.String-) | Изменить имя поля. |
| [resetFacade()](#resetFacade--) | Сбросить все визуальные атрибуты до пустого значения. |
| [resetInnerFacade()](#resetInnerFacade--) | Сбросить все визуальные атрибуты внутреннего фасада до пустого значения. |
| [save()](#save--) | Сохраняет изменения в файле назначения. |
| [save(OutputStream destStream)](#save-java.io.OutputStream-) | Сохраняет документ PDF в указанный поток. |
| [save(String destFile)](#save-java.lang.String-) | Сохраняет документ PDF в указанный файл. |
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
| [setResponse(HttpServletResponse value)](#setResponse-javax.servlet.http.HttpServletResponse-) | Задает объект Response, в котором будет храниться результат операции. |
| [setSaveOptions(SaveOptions value)](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Задает параметры сохранения, когда результат сохраняется как HttpResponse. |
| [setSrcFileName(String value)](#setSrcFileName-java.lang.String-) | Устанавливает имя исходного файла. |
| [setSrcStream(InputStream value)](#setSrcStream-java.io.InputStream-) | Устанавливает исходный поток. |
| [setSubmitFlag(int value)](#setSubmitFlag-int-) | Установите флаги отправки кнопки отправки |
| [setSubmitFlag(String fieldName, int submitFormFlag)](#setSubmitFlag-java.lang.String-int-) | Установите флаг отправки кнопки отправки. |
| [setSubmitUrl(String fieldName, String url)](#setSubmitUrl-java.lang.String-java.lang.String-) | Устанавливает URL кнопки. |
| [single2Multiple(String fieldName)](#single2Multiple-java.lang.String-) | Измените однострочное текстовое поле на многострочное. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FormEditorWeb() {#FormEditorWeb--}
```
public FormEditorWeb()
```


Конструктор для FormEditorWeb.

--------------------

```
FormEditorWeb FormEditorWeb = new FormEditorWeb();
```

### FormEditorWeb(IDocument document) {#FormEditorWeb-com.aspose.pdf.IDocument-}
```
public FormEditorWeb(IDocument document)
```


Инициализирует новый объект FormEditorWeb на основе документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ пдф. |

### FormEditorWeb(IDocument document, OutputStream destStream) {#FormEditorWeb-com.aspose.pdf.IDocument-java.io.OutputStream-}
```
public FormEditorWeb(IDocument document, OutputStream destStream)
```


Инициализирует новый объект FormEditorWeb на основе документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ пдф. |
| destStream | java.io.OutputStream | Целевой поток. |

### FormEditorWeb(IDocument document, String destFileName) {#FormEditorWeb-com.aspose.pdf.IDocument-java.lang.String-}
```
public FormEditorWeb(IDocument document, String destFileName)
```


Инициализирует новый объект FormEditorWeb на основе документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ пдф. |
| destFileName | java.lang.String | Путь к файлу назначения. |

### FormEditorWeb(InputStream inputStream, HttpServletResponse response) {#FormEditorWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-}
```
public FormEditorWeb(InputStream inputStream, HttpServletResponse response)
```


Создает FormEditorWeb, который сохраняет результат в объекте HttpResponse.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Исходный поток. |
| response | javax.servlet.http.HttpServletResponse | Объект HttpResponse, в котором будет сохранен результат. |

### FormEditorWeb(InputStream srcStream, OutputStream destStream) {#FormEditorWeb-java.io.InputStream-java.io.OutputStream-}
```
public FormEditorWeb(InputStream srcStream, OutputStream destStream)
```


Конструктор для FormEditorWeb.

--------------------

```
FormEditorWeb FormEditorWeb = new FormEditorWeb(new FileInputStream("InFile.pdf"), new FileOutputStream("OutFile.pdf"));
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcStream | java.io.InputStream | Исходный поток. |
| destStream | java.io.OutputStream | Целевой поток. |

### FormEditorWeb(String inputFile, HttpServletResponse response) {#FormEditorWeb-java.lang.String-javax.servlet.http.HttpServletResponse-}
```
public FormEditorWeb(String inputFile, HttpServletResponse response)
```


Создает FormEditorWeb, который сохраняет результат в объекте HttpResponse.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Имя исходного файла. |
| response | javax.servlet.http.HttpServletResponse | Объекты HttpResponse, в которых будет сохранен результат. |

### FormEditorWeb(String srcFileName, String destFileName) {#FormEditorWeb-java.lang.String-java.lang.String-}
```
public FormEditorWeb(String srcFileName, String destFileName)
```


Конструктор для FormEditorWeb

--------------------

```
FormEditorWeb FormEditorWeb = new FormEditorWeb("InFile.pdf", "OutFile.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFileName | java.lang.String | Имя исходного файла. |
| destFileName | java.lang.String | Имя файла назначения. |

### addField(int fieldType, String fieldName, int pageNum, float llx, float lly, float urx, float ury) {#addField-int-java.lang.String-int-float-float-float-float-}
```
public boolean addField(int fieldType, String fieldName, int pageNum, float llx, float lly, float urx, float ury)
```


Добавить в форму поле указанного типа.

--------------------

```
FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf");
 formEditor.addField(FieldType.Text, "AddedTextField",  1, 10, 30, 110, 46);
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
public boolean addField(int fieldType, String fieldName, String initValue, int pageNum, float llx, float lly, float urx, float ury)
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
### addFieldScript(String fieldName, String script) {#addFieldScript-java.lang.String-java.lang.String-}
```
public boolean addFieldScript(String fieldName, String script)
```


Добавьте JavaScript для поля PushButton. Если старое событие существует, новое событие добавляется после него.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Полное имя поля. |
| script | java.lang.String | Java-скрипт, который нужно добавить/поместить в поле кнопки. |

**Возвращает:**
boolean - True, если скрипт был успешно добавлен.
### addListItem(String fieldName, String itemName) {#addListItem-java.lang.String-java.lang.String-}
```
public void addListItem(String fieldName, String itemName)
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
public void addListItem(String fieldName, String[] exportName)
```


Добавьте новый элемент со значением «Экспорт» в существующее поле списка, только для поля со списком AcroForm.

--------------------

```
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_AddListItem2.pdf");
  fe.addListItem("listboxField", new String[] { "4", "Item4(Added)" });
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Имя поля, в которое будут добавлены элементы. |
| exportName | java.lang.String[] | Массив строк, обозначающий новый элемент списка со значением экспорта, т. е. (метка элемента, значение экспорта). |

### addSubmitBtn(String fieldName, int page, String label, String url, float llx, float lly, float urx, float ury) {#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-}
```
public void addSubmitBtn(String fieldName, int page, String label, String url, float llx, float lly, float urx, float ury)
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

### bindPdf(IDocument srcDoc) {#bindPdf-com.aspose.pdf.IDocument-}
```
public void bindPdf(IDocument srcDoc)
```


Инициализирует фасад.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcDoc | [IDocument](../../com.aspose.pdf/idocument) | Объект Документ. |

### bindPdf(InputStream srcStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream srcStream)
```


Инициализирует фасад.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcStream | java.io.InputStream | Поток файла PDF. |

### bindPdf(InputStream srcStream, String password) {#bindPdf-java.io.InputStream-java.lang.String-}
```
public void bindPdf(InputStream srcStream, String password)
```


Инициализирует фасад.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcStream | java.io.InputStream | Поток файла PDF. |
| password | java.lang.String | Пароль документа PDF. |

### bindPdf(String srcFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String srcFile)
```


Инициализирует фасад.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFile | java.lang.String | PDF-файл. |

### bindPdf(String srcFile, String password) {#bindPdf-java.lang.String-java.lang.String-}
```
public void bindPdf(String srcFile, String password)
```


Инициализирует фасад.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFile | java.lang.String | PDF-файл |
| password | java.lang.String | Пароль документа PDF. |

### close() {#close--}
```
public void close()
```


Закрывает все ресурсы, используемые этим документом.

### copyInnerField(String fieldName, String newFieldName, int pageNum) {#copyInnerField-java.lang.String-java.lang.String-int-}
```
public void copyInnerField(String fieldName, String newFieldName, int pageNum)
```


Копирует существующее поле в ту же позицию на странице с указанным номером. Будет создан новый документ, содержащий все, что есть в исходном документе, за исключением только что скопированного поля.

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
 //Creates copy of text field on second page.
 formEditor.copyInnerField("textField", "textFieldCopy", 2);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Старое полное имя поля. |
| newFieldName | java.lang.String | Новое полное имя поля. Если значение null, оно будет установлено как fieldName + "~". |
| pageNum | int | Номер страницы для хранения нового поля. Если -1, новое поле будет копировано на ту же страницу, что и старое. |

### copyInnerField(String fieldName, String newFieldName, int pageNum, float abscissa, float ordinate) {#copyInnerField-java.lang.String-java.lang.String-int-float-float-}
```
public void copyInnerField(String fieldName, String newFieldName, int pageNum, float abscissa, float ordinate)
```


Копирует существующее поле в новую позицию, указанную как номером страницы, так и ординатами. Будет создан новый документ, содержащий все, что есть в исходном документе, за исключением только что скопированного поля.

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
 //Creates copy of text field on second page.
 formEditor.copyInnerField("textField", "textFieldCopy", 2, 100, 200);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Старое полное имя поля. |
| newFieldName | java.lang.String | Новое полное имя поля. Если значение null, оно будет установлено как fieldName + "~". |
| pageNum | int | Номер страницы для хранения нового поля. Если -1, новое поле будет копировано на ту же страницу, что и старое. |
| abscissa | float | Абсцисса нового поля. Если -1, абсцисса будет равна исходной. |
| ordinate | float | Ордината нового поля. Если -1, ордината будет равна исходной. |

### copyOuterField(String srcFileName, String fieldName) {#copyOuterField-java.lang.String-java.lang.String-}
```
public void copyOuterField(String srcFileName, String fieldName)
```


Копирует существующее поле из одного документа PDF в другой документ с исходным номером страницы и координатами. Примечание. Только для полей AcroForm (за исключением переключателя).

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
 //copies text field from source.pdf to PdfForm.pdf
 formEditor.copyOuterField("source.pdf", "textField");
 formEditor.save();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFileName | java.lang.String | Имя документа PDF, содержащего копируемое поле. |
| fieldName | java.lang.String | Исходное полное имя поля. |

### copyOuterField(String srcFileName, String fieldName, int pageNum) {#copyOuterField-java.lang.String-java.lang.String-int-}
```
public void copyOuterField(String srcFileName, String fieldName, int pageNum)
```


Копирует существующее поле из одного документа PDF в другой документ с указанным номером страницы и исходными ординатами. Примечание. Только для полей AcroForm (за исключением переключателя).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFileName | java.lang.String | Имя документа PDF, содержащего копируемое поле. |
| fieldName | java.lang.String | Исходное полное имя поля. |
| pageNum | int |  |

### copyOuterField(String srcFileName, String fieldName, int pageNum, float abscissa, float ordinate) {#copyOuterField-java.lang.String-java.lang.String-int-float-float-}
```
public void copyOuterField(String srcFileName, String fieldName, int pageNum, float abscissa, float ordinate)
```


Копирует существующее поле из одного документа PDF в другой документ с указанным номером страницы и координатами. Примечание. Только для полей AcroForm (за исключением переключателя).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFileName | java.lang.String | Старое полное имя поля. |
| fieldName | java.lang.String | Новое полное имя поля. Если значение null, оно будет установлено как fieldName + "~". |
| pageNum | int | Номер страницы для хранения нового поля. Если -1, новое поле будет копировано на ту же страницу, что и старое. |
| abscissa | float | Абсцисса нового поля. Если -1, абсцисса будет равна исходной. |
| ordinate | float | Ордината нового поля. Если -1, ордината будет равна исходной. |

### decorateField() {#decorateField--}
```
public void decorateField()
```


Изменяет визуальные атрибуты всех полей в документе PDF.

--------------------

```
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf");
 fe.setFacade ( new FormFieldFacade());
 fe.getFacade().setBackgroundColor ( Color.red);
 fe.getFacade().setTextColor ( Color.blue);
 fe.getFacade().setBorderColor ( Color.Green);
 fe.getFacade().setAlignment( FormFieldFacade.AlignRight);
 //decorate all fields.
 fe.decorateField();
```

### decorateField(int fieldType) {#decorateField-int-}
```
public void decorateField(int fieldType)
```


Изменяет визуальные атрибуты всех полей с указанным типом поля.

--------------------

```
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_DecorateField.pdf");
 fe.setFacade ( new FormFieldFacade());
 fe.getFacade().setBackgroundColor ( Color.red);
 fe.getFacade().setTextColor ( Color.blue);
 fe.getFacade().setBorderColor ( Color.green);
 fe.getFacade().setAlignment ( FormFieldFacade.AlignRight);
 //decorate all text fields.
 fe.decorateField(FieldType.Text);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldType | int | Тип полей, которые будут декорированы. |

### decorateField(String fieldName) {#decorateField-java.lang.String-}
```
public void decorateField(String fieldName)
```


Изменяет визуальные атрибуты указанного поля.

--------------------

```
FormEditor fe = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_DecorateField_text.pdf");
 fe.Facade = new FormFieldFacade();
 fe.Facade.setBackgroundColor ( Color.Red);
 fe.Facade.setTextColor ( Color.Blue);
 fe.Facade.setBorderColor ( Color.Green);
 fe.Facade.setAlignment ( FormFieldFacade.AlignCenter);
 fe.decorateField("textField");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Полное имя поля. |

### delListItem(String fieldName, String itemName) {#delListItem-java.lang.String-java.lang.String-}
```
public void delListItem(String fieldName, String itemName)
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
public void dispose()
```


Закрывает все ресурсы, используемые этим документом.

Этот метод устарел, вместо него используйте close().

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Возвращает:**
логический
### getAttachmentName() {#getAttachmentName--}
```
public String getAttachmentName()
```


Получает имя вложения, когда результат операции сохраняется в объектах HttpResponse как вложение.

**Возвращает:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getContentDisposition() {#getContentDisposition--}
```
public int getContentDisposition()
```


Получает способ хранения содержимого при сохранении результата операции в объекте HttpResponse. Возможное значение: inline/attachment. По умолчанию: встроенный.

**Возвращает:**
инт
### getDestFileName() {#getDestFileName--}
```
public String getDestFileName()
```


Получает имя файла назначения.

**Возвращает:**
java.lang.String
### getDestStream() {#getDestStream--}
```
public OutputStream getDestStream()
```


Получает целевой поток.

--------------------

```
FormEditor editor = new FormEditor();
 editor.setDestStream ( new FileInputStream("OutFile.pdf"));
```

**Возвращает:**
java.io.OutputStream
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


Получает фасад документа, над которым работает.

**Возвращает:**
[IDocument](../../com.aspose.pdf/idocument) - элемент IDocument
### getExportItems() {#getExportItems--}
```
public String[][] getExportItems()
```


Получает параметры для поля со списком с экспортируемыми значениями.

**Возвращает:**
java.lang.String[][] - Нить[][] множество
### getFacade() {#getFacade--}
```
public FormFieldFacade getFacade()
```


Получает визуальные атрибуты поля.

**Возвращает:**
[FormFieldFacade](../../com.aspose.pdf.facades/formfieldfacade)
### getFieldAppearance(String fieldName) {#getFieldAppearance-java.lang.String-}
```
public int getFieldAppearance(String fieldName)
```


Получить полевые флаги.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Имя поля. |

**Возвращает:**
int - Набор флагов поля
### getItems() {#getItems--}
```
public String[] getItems()
```


Возвращает массив элементов

**Возвращает:**
java.lang.String[]
### getRadioButtonItemSize() {#getRadioButtonItemSize--}
```
public double getRadioButtonItemSize()
```


Получает или задает размер элемента переключателя (при добавлении нового поля переключателя).

```
formEditor = new FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
 formEditor.setRadioGap ( 4);
 formEditor.setRadioHoriz ( false);
 formEditor.setRadioButtonItemSize ( 20);
 formEditor.setItems ( new String[] { "First", "Second", "Third" });
 formEditor.addField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
 formEditor.save();
```

**Возвращает:**
двойное - двойное значение
### getRadioGap() {#getRadioGap--}
```
public float getRadioGap()
```


Заставьте участника записывать промежуток между двумя соседними переключателями в пикселях, по умолчанию 50.

**Возвращает:**
плавать
### getRadioHoriz() {#getRadioHoriz--}
```
public boolean getRadioHoriz()
```


Получите флаг, чтобы указать, расположены ли радиостанции горизонтально или вертикально, значение по умолчанию — true.

**Возвращает:**
логический
### getResponse() {#getResponse--}
```
public HttpServletResponse getResponse()
```


Получает объект Response, в котором будет храниться результат операции.

**Возвращает:**
javax.servlet.http.HttpServletResponse — объект HttpServletResponse
### getSaveOptions() {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```


Получает параметры сохранения, когда результат сохраняется как HttpResponse. Значение по умолчанию: пдфсавеоптионс.

**Возвращает:**
[SaveOptions](../../com.aspose.pdf/saveoptions)
### getSrcFileName() {#getSrcFileName--}
```
public String getSrcFileName()
```


Получает имя исходного файла.

**Возвращает:**
java.lang.String
### getSrcStream() {#getSrcStream--}
```
public InputStream getSrcStream()
```


Получает исходный поток.

**Возвращает:**
java.io.InputStream
### getSubmitFlag() {#getSubmitFlag--}
```
public int getSubmitFlag()
```


Получить флаги отправки кнопки отправки

**Возвращает:**
int — элемент SubmitFormFlag
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### moveField(String fieldName, float llx, float lly, float urx, float ury) {#moveField-java.lang.String-float-float-float-float-}
```
public boolean moveField(String fieldName, float llx, float lly, float urx, float ury)
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
public void removeFieldAction(String fieldName)
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
public void renameField(String fieldName, String newFieldName)
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
public void resetFacade()
```


Сбросить все визуальные атрибуты до пустого значения.

### resetInnerFacade() {#resetInnerFacade--}
```
public void resetInnerFacade()
```


Сбросить все визуальные атрибуты внутреннего фасада до пустого значения.

### save() {#save--}
```
public void save()
```


Сохраняет изменения в файле назначения.

### save(OutputStream destStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destStream)
```


Сохраняет документ PDF в указанный поток.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| destStream | java.io.OutputStream | Целевой поток. |

### save(String destFile) {#save-java.lang.String-}
```
public void save(String destFile)
```


Сохраняет документ PDF в указанный файл.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| destFile | java.lang.String | Файл назначения. |

### setAttachmentName(String value) {#setAttachmentName-java.lang.String-}
```
public void setAttachmentName(String value)
```


Задает имя вложения, когда результат операции сохраняется в объектах HttpResponse как вложение.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setContentDisposition(int value) {#setContentDisposition-int-}
```
public void setContentDisposition(int value)
```


Устанавливает, как содержимое будет сохранено, когда результат операции будет сохранен в объекте HttpResponse. Возможное значение: inline/attachment. По умолчанию: встроенный.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### setConvertTo(PdfFormat value) {#setConvertTo-com.aspose.pdf.PdfFormat-}
```
public void setConvertTo(PdfFormat value)
```


 Наборы[PdfFormat](../../com.aspose.pdf/pdfformat) Формат файла PDF. Файл результата будет сохранен в указанном формате. Если это свойство не указано, файл будет сохранен в формате PDF по умолчанию без преобразования.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfFormat](../../com.aspose.pdf/pdfformat) |  |

### setDestFileName(String value) {#setDestFileName-java.lang.String-}
```
public void setDestFileName(String value)
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
| value | java.lang.String |  |

### setDestStream(OutputStream value) {#setDestStream-java.io.OutputStream-}
```
public void setDestStream(OutputStream value)
```


Устанавливает целевой поток.

--------------------

```
FormEditor editor = new FormEditor();
 editor.setDestStream ( new FileInputStream("OutFile.pdf"));
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.io.OutputStream |  |

### setExportItems(String[][] value) {#setExportItems-java.lang.String-----}
```
public void setExportItems(String[][] value)
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
| value | java.lang.String[][] |  |

### setFacade(FormFieldFacade value) {#setFacade-com.aspose.pdf.facades.FormFieldFacade-}
```
public void setFacade(FormFieldFacade value)
```


Задает визуальные атрибуты поля.

--------------------

```
FormEditor fe = new FormEditor("PdfForm.pdf", "PdfForm_DecorateField_text.pdf");
 fe.setFacade ( new FormFieldFacade());
 fe.getFacade().setBackgroundColor ( Color.red);
 fe.getFacade().setTextColor ( Color.blue);
 fe.getFacade().setBorderColor ( Color.green);
 fe.getFacade().setAlignment ( FormFieldFacade.AlignCenter);
 fe.setDecorateField("textField");
 fe.save();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [FormFieldFacade](../../com.aspose.pdf.facades/formfieldfacade) |  |

### setFieldAlignment(String fieldName, int alignment) {#setFieldAlignment-java.lang.String-int-}
```
public boolean setFieldAlignment(String fieldName, int alignment)
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
логический
### setFieldAlignmentV(String fieldName, int alignment) {#setFieldAlignmentV-java.lang.String-int-}
```
public boolean setFieldAlignmentV(String fieldName, int alignment)
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
логический
### setFieldAppearance(String fieldName, int flags) {#setFieldAppearance-java.lang.String-int-}
```
public boolean setFieldAppearance(String fieldName, int flags)
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
public boolean setFieldAttribute(String fieldName, int flag)
```


Установить атрибуты поля.

--------------------

```
FormEditor formEditor = new FormEditor("PdfForm.pdf",  "PdfForm_SetFieldAttribute.pdf");
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
public boolean setFieldCombNumber(String fieldName, int combNumber)
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
public boolean setFieldLimit(String fieldName, int fieldLimit)
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
public boolean setFieldScript(String fieldName, String script)
```


Установите JavaScript для поля PushButton. Если старый JavaScript существовал, он будет заменен новым.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Полное имя поля. |
| script | java.lang.String | Java-скрипт, который нужно добавить/поместить в поле кнопки. |

**Возвращает:**
логический
### setItems(String[] value) {#setItems-java.lang.String---}
```
public void setItems(String[] value)
```


Устанавливает элементы, которые будут добавлены во вновь созданный список или поле со списком.

--------------------

```
formEditor = new com.aspose.pdf.facadesFormEditor("input.pdf", "output.pdf");
  formEditor.setItems ( new String[] { "AAA", "BBB", "CCC" });
  formEditor.addField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130);
  formEditor.save();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String[] |  |

### setRadioButtonItemSize(double value) {#setRadioButtonItemSize-double-}
```
public void setRadioButtonItemSize(double value)
```

```
Gets or sets size of radio button item size (when new radio button field is added).

 FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "
 FormEditor_AddField_RadioButton.pdf");
 formEditor.setRadioGap(4);
 formEditor.setRadioHoriz(false);
 formEditor.setRadioButtonItemSize(20);
 formEditor.setItems(new String[]
 { "First", "Second", "Third" });
 formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, "AddedRadioButtonField", "
 Second", 1, 10, 30, 110, 130);
 formEditor.save();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setRadioGap(float value) {#setRadioGap-float-}
```
public void setRadioGap(float value)
```


Настройте элемент для записи промежутка между двумя соседними переключателями в пикселях, по умолчанию 50.

--------------------

```
formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
 formEditor.setRadioGap ( 4);
 formEditor.setRadioHoriz ( false);
 formEditor.setItems ( new String[] { "First", "Second", "Third" });
 formEditor.addField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
 formEditor.save();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### setRadioHoriz(boolean value) {#setRadioHoriz-boolean-}
```
public void setRadioHoriz(boolean value)
```


Установите флаг, чтобы указать, расположены ли радиостанции горизонтально или вертикально, значение по умолчанию — true.

--------------------

```
formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf");
 formEditor.setRadioGap ( 4);
 formEditor.setRadioHoriz ( false);
 formEditor.setItems ( new String[] { "First", "Second", "Third" });
 formEditor.addField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130);
 formEditor.save();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### setResponse(HttpServletResponse value) {#setResponse-javax.servlet.http.HttpServletResponse-}
```
public void setResponse(HttpServletResponse value)
```


Задает объект Response, в котором будет храниться результат операции.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | javax.servlet.http.HttpServletResponse | Объект HttpServletResponse |

### setSaveOptions(SaveOptions value) {#setSaveOptions-com.aspose.pdf.SaveOptions-}
```
public void setSaveOptions(SaveOptions value)
```


Задает параметры сохранения, когда результат сохраняется как HttpResponse. Значение по умолчанию: пдфсавеоптионс.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [SaveOptions](../../com.aspose.pdf/saveoptions) |  |

### setSrcFileName(String value) {#setSrcFileName-java.lang.String-}
```
public void setSrcFileName(String value)
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
| value | java.lang.String |  |

### setSrcStream(InputStream value) {#setSrcStream-java.io.InputStream-}
```
public void setSrcStream(InputStream value)
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
| value | java.io.InputStream |  |

### setSubmitFlag(int value) {#setSubmitFlag-int-}
```
public void setSubmitFlag(int value)
```


Установите флаги отправки кнопки отправки

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент SubmitFormFlag |

### setSubmitFlag(String fieldName, int submitFormFlag) {#setSubmitFlag-java.lang.String-int-}
```
public boolean setSubmitFlag(String fieldName, int submitFormFlag)
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
boolean - true, если поле найдено и флаг отправки успешно установлен.
### setSubmitUrl(String fieldName, String url) {#setSubmitUrl-java.lang.String-java.lang.String-}
```
public boolean setSubmitUrl(String fieldName, String url)
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
boolean - true, если URL для кнопки был успешно установлен.
### single2Multiple(String fieldName) {#single2Multiple-java.lang.String-}
```
public boolean single2Multiple(String fieldName)
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
### toString() {#toString--}
```
public String toString()
```




**Возвращает:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
