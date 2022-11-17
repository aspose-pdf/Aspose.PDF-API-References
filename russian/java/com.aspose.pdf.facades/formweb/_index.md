---
title: FormWeb
second_title: Aspose.PDF для справки по Java API
description: Представление интерфейса формы Acro.
type: docs
weight: 29
url: /ru/java/com.aspose.pdf.facades/formweb/
---
**Наследование:**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade), com.aspose.pdf.facades.AForm

**Все реализованные интерфейсы:**
[com.aspose.pdf.facades.IForm](../../com.aspose.pdf.facades/iform)
```
public final class FormWeb extends AForm implements IForm
```

Представление интерфейса формы Acro.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FormWeb()](#FormWeb--) | Конструктор FormWeb без параметров. |
| [FormWeb(IDocument document)](#FormWeb-com.aspose.pdf.IDocument-) | Инициализирует новый объект FormWeb на основе документа. |
| [FormWeb(IDocument document, OutputStream destStream)](#FormWeb-com.aspose.pdf.IDocument-java.io.OutputStream-) | Инициализирует новый объект FormWeb на основе документа. |
| [FormWeb(IDocument document, String destFileName)](#FormWeb-com.aspose.pdf.IDocument-java.lang.String-) | Инициализирует новый объект FormWeb на основе документа. |
| [FormWeb(InputStream srcStream)](#FormWeb-java.io.InputStream-) | Конструктор для FormWeb. |
| [FormWeb(InputStream inputStream, HttpServletResponse response)](#FormWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-) | Создает FormWeb, который сохраняет результат в объекте HttpResponse. |
| [FormWeb(InputStream srcStream, OutputStream destStream)](#FormWeb-java.io.InputStream-java.io.OutputStream-) | Конструктор FormWeb с двумя параметрами потока. |
| [FormWeb(InputStream srcStream, String destFileName)](#FormWeb-java.io.InputStream-java.lang.String-) | Конструктор FormWeb |
| [FormWeb(String srcFileName)](#FormWeb-java.lang.String-) | Конструктор FormWeb. |
| [FormWeb(String inputFile, HttpServletResponse response)](#FormWeb-java.lang.String-javax.servlet.http.HttpServletResponse-) | Создает FormWeb, который сохраняет результат в объекте HttpResponse. |
| [FormWeb(String srcFileName, OutputStream destStream)](#FormWeb-java.lang.String-java.io.OutputStream-) | Конструктор FormWeb. |
| [FormWeb(String srcFileName, String destFileName)](#FormWeb-java.lang.String-java.lang.String-) | Конструктор класса FormWeb. |
## Методы

| Метод | Описание |
| --- | --- |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | Инициализирует фасад. |
| [bindPdf(InputStream srcStream)](#bindPdf-java.io.InputStream-) | Инициализирует фасад. |
| [bindPdf(InputStream srcStream, String password)](#bindPdf-java.io.InputStream-java.lang.String-) | Инициализирует фасад. |
| [bindPdf(String srcFile)](#bindPdf-java.lang.String-) | Инициализирует фасад. |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | Инициализирует фасад. |
| [close()](#close--) | Закрывает все открытые ресурсы, используемые этим документом. |
| [dispose()](#dispose--) | Закрывает все открытые ресурсы, используемые этим документом. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exportFdf(OutputStream outputFdfStream)](#exportFdf-java.io.OutputStream-) | Экспортирует содержимое полей pdf в поток fdf. |
| [exportXfdf(OutputStream outputXfdfStream)](#exportXfdf-java.io.OutputStream-) | Экспортирует содержимое полей pdf в поток xml. |
| [exportXml(OutputStream outputXmlStream)](#exportXml-java.io.OutputStream-) | Экспортирует содержимое полей pdf в поток xml. |
| [extractXfaData(OutputStream outputXmlStream)](#extractXfaData-java.io.OutputStream-) | Извлекает пакет данных XFA |
| [fillBarcodeField(String fieldName, String data)](#fillBarcodeField-java.lang.String-java.lang.String-) | Заполните поле штрих-кода в соответствии с его полным именем поля. |
| [fillField(String fieldName, boolean beChecked)](#fillField-java.lang.String-boolean-) | Заполняет поле флажка логическим значением. |
| [fillField(String fieldName, int index)](#fillField-java.lang.String-int-) | Заполняет поле переключателя допустимым значением индекса в соответствии с полным именем поля. |
| [fillField(String fieldName, String fieldValue)](#fillField-java.lang.String-java.lang.String-) | Заполняет поле допустимым значением в соответствии с полным именем поля. |
| [fillField(String fieldName, String value, boolean fitFontSize)](#fillField-java.lang.String-java.lang.String-boolean-) | Заполняет поле указанным значением. |
| [fillField(String fieldName, String[] fieldValues)](#fillField-java.lang.String-java.lang.String---) | Заполните поле несколькими вариантами выбора. Примечание: только для поля списка AcroForm. |
| [fillFields(String[] fieldNames, String[] fieldValues, OutputStream output)](#fillFields-java.lang.String---java.lang.String---java.io.OutputStream-) | Заполняет поля текстового поля текстовыми значениями и сохраняет документ. |
| [fillImageField(String fieldName, InputStream imageStream)](#fillImageField-java.lang.String-java.io.InputStream-) | Перегружает функцию FillImageField. |
| [fillImageField(String fieldName, String imageFileName)](#fillImageField-java.lang.String-java.lang.String-) | Вставляет изображение в существующее поле кнопки в качестве внешнего вида в соответствии с полным именем поля. |
| [flattenAllFields()](#flattenAllFields--) | Сглаживает все поля. |
| [flattenField(String fieldName)](#flattenField-java.lang.String-) | Выравнивает указанное поле с полным именем поля. |
| [getAttachmentName()](#getAttachmentName--) | Получает имя вложения, когда результат операции сохраняется в объектах HttpResponse как вложение. |
| [getButtonOptionCurrentValue(String fieldName)](#getButtonOptionCurrentValue-java.lang.String-) | Возвращает текущее значение для полей опций переключателя. |
| [getButtonOptionValues(String fieldName)](#getButtonOptionValues-java.lang.String-) | Получает поля параметров переключателя и связанные значения на основе имени поля. |
| [getButtonOptionValuesInternal(String fieldName)](#getButtonOptionValuesInternal-java.lang.String-) | Получает поля параметров переключателя и связанные значения на основе имени поля. |
| [getClass()](#getClass--) |  |
| [getContentDisposition()](#getContentDisposition--) | Содержимое Getshow будет сохранено, когда результат операции будет сохранен в объекте HttpResponse. |
| [getDestFileName()](#getDestFileName--) | Получает имя файла назначения. |
| [getDestStream()](#getDestStream--) | Получает или задает поток назначения. |
| [getDocument()](#getDocument--) | Получает фасад документа, над которым работает. |
| [getField(String fieldName)](#getField-java.lang.String-) | Получает значение поля в соответствии с его именем поля. |
| [getFieldFacade(String fieldName)](#getFieldFacade-java.lang.String-) | Возвращает объект FromFieldFacade, содержащий все атрибуты внешнего вида. |
| [getFieldFlag(String fieldName)](#getFieldFlag-java.lang.String-) | Возвращает флаги поля. |
| [getFieldLimit(String fieldName)](#getFieldLimit-java.lang.String-) | Получить ограничение текстового поля. |
| [getFieldNames()](#getFieldNames--) | Получает список имен полей в форме. |
| [getFieldType(String fieldName)](#getFieldType-java.lang.String-) | Возвращает тип поля. |
| [getFormSubmitButtonNames()](#getFormSubmitButtonNames--) | Получает все имена кнопок отправки формы. |
| [getFullFieldName(String fieldName)](#getFullFieldName-java.lang.String-) | Получает полное имя поля в соответствии с его коротким именем поля. |
| [getImportResult()](#getImportResult--) | Результат последней операции импорта. |
| [getResponse()](#getResponse--) | Получает или задает объект Response, в котором будет храниться результат операции. |
| [getRichText(String fieldName)](#getRichText-java.lang.String-) | Получите значение поля форматированного текста, включая информацию о форматировании каждого символа. |
| [getSaveOptions()](#getSaveOptions--) | Получает или задает параметры сохранения, когда результат сохраняется как HttpResponse. |
| [getSrcFileName()](#getSrcFileName--) | Получает имя исходного файла. |
| [getSrcStream()](#getSrcStream--) | Получает исходный поток. |
| [getSubmitFlags(String fieldName)](#getSubmitFlags-java.lang.String-) | Возвращает флаги отправки кнопки отправки |
| [hashCode()](#hashCode--) |  |
| [importFdf(InputStream inputFdfStream)](#importFdf-java.io.InputStream-) | Импортирует содержимое полей из файла fdf и помещает их в новый pdf. |
| [importXfdf(InputStream inputXfdfStream)](#importXfdf-java.io.InputStream-) | Импортирует содержимое полей из файла xfdf(xml) и помещает их в новый pdf. |
| [importXml(InputStream inputXmlStream)](#importXml-java.io.InputStream-) | Импортирует содержимое полей из xml-файла и помещает их в новый pdf. |
| [importXml(InputStream inputXmlStream, boolean IgnoreFormTemplateChanges)](#importXml-java.io.InputStream-boolean-) | Импортирует содержимое полей из xml-файла и помещает их в новый pdf. |
| [importXml(String inputXml)](#importXml-java.lang.String-) | Импортирует содержимое полей из xml-файла и помещает их в новый pdf. |
| [isRequiredField(String fieldName)](#isRequiredField-java.lang.String-) | Определяет, является ли поле обязательным или нет. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [renameField(String fieldName, String newFieldName)](#renameField-java.lang.String-java.lang.String-) | Переименовывает поле. |
| [save()](#save--) | Сохраняет значение заполненных полей и закрывает открытый документ Pdf. |
| [save(OutputStream destStream)](#save-java.io.OutputStream-) | Сохраняет документ в указанный поток. |
| [save(String destFile)](#save-java.lang.String-) | Сохраняет документ в указанный файл. |
| [setAttachmentName(String value)](#setAttachmentName-java.lang.String-) | Задает имя вложения, когда результат операции сохраняется в объектах HttpResponse как вложение. |
| [setContentDisposition(int value)](#setContentDisposition-int-) | Устанавливает, как содержимое будет сохранено, когда результат операции будет сохранен в объекте HttpResponse. |
| [setConvertTo(PdfFormat value)](#setConvertTo-com.aspose.pdf.PdfFormat-) | Устанавливает формат файла PDF. |
| [setDestFileName(String value)](#setDestFileName-java.lang.String-) | Устанавливает имя файла назначения. |
| [setDestStream(OutputStream value)](#setDestStream-java.io.OutputStream-) | Получает целевой поток. |
| [setResponse(HttpServletResponse value)](#setResponse-javax.servlet.http.HttpServletResponse-) | Получает или задает объект Response, в котором будет храниться результат операции. |
| [setSaveOptions(SaveOptions value)](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Получает или задает параметры сохранения, когда результат сохраняется как HttpResponse. |
| [setSrcFileName(String value)](#setSrcFileName-java.lang.String-) | Устанавливает имя исходного файла. |
| [setSrcStream(InputStream value)](#setSrcStream-java.io.InputStream-) | Получает исходный поток. |
| [setXfaData(InputStream inputXmlStream)](#setXfaData-java.io.InputStream-) | Заменяет данные XFA указанным пакетом данных. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FormWeb() {#FormWeb--}
```
public FormWeb()
```


Конструктор FormWeb без параметров.

--------------------

```
FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb();
 FormWeb.setSrcFileName("file.pdf");
```

### FormWeb(IDocument document) {#FormWeb-com.aspose.pdf.IDocument-}
```
public FormWeb(IDocument document)
```


Инициализирует новый объект FormWeb на основе документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ пдф. |

### FormWeb(IDocument document, OutputStream destStream) {#FormWeb-com.aspose.pdf.IDocument-java.io.OutputStream-}
```
public FormWeb(IDocument document, OutputStream destStream)
```


Инициализирует новый объект FormWeb на основе документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ пдф. |
| destStream | java.io.OutputStream | Целевой поток. |

### FormWeb(IDocument document, String destFileName) {#FormWeb-com.aspose.pdf.IDocument-java.lang.String-}
```
public FormWeb(IDocument document, String destFileName)
```


Инициализирует новый объект FormWeb на основе документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ пдф. |
| destFileName | java.lang.String | Путь к файлу назначения. |

### FormWeb(InputStream srcStream) {#FormWeb-java.io.InputStream-}
```
public FormWeb(InputStream srcStream)
```


Конструктор для FormWeb.

--------------------

```
FormWeb FormWeb = new FormWeb(new FileInputStream("PdfFormWeb.pdf"));
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcStream | java.io.InputStream | исходный поток. |

### FormWeb(InputStream inputStream, HttpServletResponse response) {#FormWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-}
```
public FormWeb(InputStream inputStream, HttpServletResponse response)
```


Создает FormWeb, который сохраняет результат в объекте HttpResponse.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Поток, содержащий исходный документ. |
| response | javax.servlet.http.HttpServletResponse | Объект HttpResponse, в котором будет сохранен результат. |

### FormWeb(InputStream srcStream, OutputStream destStream) {#FormWeb-java.io.InputStream-java.io.OutputStream-}
```
public FormWeb(InputStream srcStream, OutputStream destStream)
```


Конструктор FormWeb с двумя параметрами потока. Укажите один и тот же поток источника и назначения для добавочного обновления.

--------------------

```
FormWeb FormWeb = new FormWeb(new FileInputStream("InFile.pdf"), new FileOutputStream("OutFile.pdf"));
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcStream | java.io.InputStream | Исходный поток. |
| destStream | java.io.OutputStream | Целевой поток. |

### FormWeb(InputStream srcStream, String destFileName) {#FormWeb-java.io.InputStream-java.lang.String-}
```
public FormWeb(InputStream srcStream, String destFileName)
```


Конструктор FormWeb

--------------------

```
FormWeb FormWeb = new FormWeb(new FileInputStream("PdfFormWeb.pdf"), "PdfFormWeb_Updated.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcStream | java.io.InputStream | Исходный поток. |
| destFileName | java.lang.String | Путь к файлу назначения. |

### FormWeb(String srcFileName) {#FormWeb-java.lang.String-}
```
public FormWeb(String srcFileName)
```


Конструктор FormWeb.

--------------------

```
FormWeb FormWeb = new FormWeb("PdfFormWeb.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFileName | java.lang.String | Путь к исходному файлу. |

### FormWeb(String inputFile, HttpServletResponse response) {#FormWeb-java.lang.String-javax.servlet.http.HttpServletResponse-}
```
public FormWeb(String inputFile, HttpServletResponse response)
```


Создает FormWeb, который сохраняет результат в объекте HttpResponse.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Имя входного файла. |
| response | javax.servlet.http.HttpServletResponse | Объект HttpResponse, в котором будет храниться результат. |

### FormWeb(String srcFileName, OutputStream destStream) {#FormWeb-java.lang.String-java.io.OutputStream-}
```
public FormWeb(String srcFileName, OutputStream destStream)
```


Конструктор FormWeb.

--------------------

```
FormWeb FormWeb = new FormWeb("PdfFormWeb.pdf", "PdfFormWeb_Updated.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFileName | java.lang.String | Путь к исходному файлу. |
| destStream | java.io.OutputStream | Путь к файлу назначения. |

### FormWeb(String srcFileName, String destFileName) {#FormWeb-java.lang.String-java.lang.String-}
```
public FormWeb(String srcFileName, String destFileName)
```


Конструктор класса FormWeb. Укажите одно и то же имя исходного файла и имя файла назначения для выполнения добавочного обновления FormWeb.

--------------------

```
FormWeb FormWeb = new FormWeb("PdfFormWeb.pdf", "PdfFormWeb_Updated.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcFileName | java.lang.String | Путь исходного файла. |
| destFileName | java.lang.String | Путь к файлу назначения. |

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
| srcFile | java.lang.String | PDF-файл. |
| password | java.lang.String | Пароль документа PDF. |

### close() {#close--}
```
public void close()
```


Закрывает все открытые ресурсы, используемые этим документом.

### dispose() {#dispose--}
```
public void dispose()
```


Закрывает все открытые ресурсы, используемые этим документом.

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
### exportFdf(OutputStream outputFdfStream) {#exportFdf-java.io.OutputStream-}
```
public void exportFdf(OutputStream outputFdfStream)
```


Экспортирует содержимое полей pdf в поток fdf.

--------------------

```
Form form = new Form("PdfForm.pdf");
 OutputStream stream = new FileOutputStream("export.fdf");
 form.exportFdf(stream);
 stream.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFdfStream | java.io.OutputStream | Выходной поток fdf. |

### exportXfdf(OutputStream outputXfdfStream) {#exportXfdf-java.io.OutputStream-}
```
public void exportXfdf(OutputStream outputXfdfStream)
```


Экспортирует содержимое полей pdf в поток xml. Значение поля кнопки не будет экспортировано.

--------------------

```
Form form = new Form("PdfForm.pdf");
  FileInputStream fs = new FileInputStream("export.xfdf", FileMode.Create, FileAccess.Write);
  form.exportXfdf(fs);
  fs.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputXfdfStream | java.io.OutputStream | Выходной XML-поток. |

### exportXml(OutputStream outputXmlStream) {#exportXml-java.io.OutputStream-}
```
public void exportXml(OutputStream outputXmlStream)
```


Экспортирует содержимое полей pdf в поток xml. Значение поля кнопки не будет экспортировано.

--------------------

```
Form form = new Form("PdfForm.pdf"));
 OutputStream fs = new FileOutputStream("export.xml");
 form.exportXml(fs);
 fs.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputXmlStream | java.io.OutputStream | Выходной XML-поток. |

### extractXfaData(OutputStream outputXmlStream) {#extractXfaData-java.io.OutputStream-}
```
public void extractXfaData(OutputStream outputXmlStream)
```


Извлекает пакет данных XFA

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputXmlStream | java.io.OutputStream | Поток, в котором будут храниться XML-данные. |

### fillBarcodeField(String fieldName, String data) {#fillBarcodeField-java.lang.String-java.lang.String-}
```
public boolean fillBarcodeField(String fieldName, String data)
```


Заполните поле штрих-кода в соответствии с его полным именем поля.

--------------------

```
Form form = new Form("PdfForm.pdf");
 form.fillBarcodeField("textField", "42207252");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Полное имя поля. |
| data | java.lang.String | Новое значение штрих-кода. |

**Возвращает:**
boolean - Если заполнение прошло успешно, вернуть true; в противном случае ложно.
### fillField(String fieldName, boolean beChecked) {#fillField-java.lang.String-boolean-}
```
public boolean fillField(String fieldName, boolean beChecked)
```


Заполняет поле флажка логическим значением. Примечание: применяется только к флажку. Обратите внимание, что Aspose.Pdf.Facades поддерживает только полные имена полей и не работает с частичными именами полей, в отличие от Aspose.Pdf.Kit; Например, если поле имеет полное имя "Form.Subform.CheckBoxField", вы должны указать полное имя, а не "CheckBoxField". Вы можете использовать свойство FieldNames для просмотра существующих имен полей и поиска нужного поля по частичному имени.

--------------------

```
Form form = new Form("PdfForm.pdf");
 form.fillField("checkboxField", true);


 //как искать поле по частичному имени:
 Form form = new Form("input.pdf", "output.pdf");
 for(String fieldName : form.getFieldNames())
 {
   if (fieldName.endsWith("CheckBoxField"))
   {
     System.out.println("Full name is: " + fieldName);
   }
 }
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Имя поля для заполнения. |
| beChecked | boolean | Логический флаг: true означает, что флажок установлен, а false, чтобы его снять. |

**Возвращает:**
boolean - true, если поле найдено и успешно заполнено.
### fillField(String fieldName, int index) {#fillField-java.lang.String-int-}
```
public boolean fillField(String fieldName, int index)
```


Заполняет поле переключателя допустимым значением индекса в соответствии с полным именем поля. Перед заполнением полей необходимо знать только название поля. В то время как значение может быть указано по его индексу. Примечание. Применяется только к полям Radio Box, Combo Box и List Box. Обратите внимание, что Facades поддерживает только полные имена полей и не работает с частичными именами полей, в отличие от Aspose.Pdf.Kit; Например, если поле имеет полное имя "Form.Subform.ListBoxField", вы должны указать полное имя, а не "ListBoxField". Вы можете использовать свойство FieldNames для просмотра существующих имен полей и поиска нужного поля по частичному имени.

--------------------

```
Form form = new Form("PdfForm.pdf");
 form.fillField("listboxField", 2);
 form.fillField("comboboxField", 2);
 form.fillField("radiobuttonField", 2);


 //как искать поле по частичному имени:
 Form form = new Form("input.pdf", "output.pdf");
 for(String fieldName : form.getFieldNames())
 {
   if (fieldName.endsWith("ListBoxField"))
   {
     System.out.println("Full name is: " + fieldName);
   }
 }
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Название поля для заполнения. |
| index | int | Индекс выбранного элемента. |

**Возвращает:**
boolean - true, если поле найдено и успешно заполнено.
### fillField(String fieldName, String fieldValue) {#fillField-java.lang.String-java.lang.String-}
```
public boolean fillField(String fieldName, String fieldValue)
```


Заполняет поле допустимым значением в соответствии с полным именем поля. Перед заполнением полей должны быть известны имена каждого поля и соответствующие им допустимые значения. И имя, и значение поля чувствительны к регистру. Обратите внимание, что Facades поддерживает только полные имена полей и не работает с частичными именами полей, в отличие от Aspose.Pdf.Kit; Например, если поле имеет полное имя "Form.Subform.TextField", вы должны указать полное имя, а не "TextField". Вы можете использовать свойство FieldNames для просмотра существующих имен полей и поиска нужного поля по частичному имени.

--------------------

```
Form form = new Form("PdfForm.pdf");
 form.fillField("FirstName", "John");
 form.fillField("LastName",  "Smith");


 //как искать поле по частичному имени:
 Form form = new Form("input.pdf", "output.pdf");
 for(String fieldName : form.getFieldNames())
 {
   if (fieldName.endsWith("TextField"))
   {
     System.out.println("Full name is: " + fieldName);
   }
 }
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Имя поля для заполнения. |
| fieldValue | java.lang.String | Значение поля, которое должно быть допустимым значением для некоторых полей. |

**Возвращает:**
boolean - true, если поле найдено и заполнено успешно.
### fillField(String fieldName, String value, boolean fitFontSize) {#fillField-java.lang.String-java.lang.String-boolean-}
```
public boolean fillField(String fieldName, String value, boolean fitFontSize)
```


Заполняет поле указанным значением.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Имя поля |
| value | java.lang.String | Новое значение поля |
| fitFontSize | boolean | Если true, размер шрифта в полях редактирования будет подогнан. |

**Возвращает:**
boolean - true, если поле найдено и успешно заполнено.
### fillField(String fieldName, String[] fieldValues) {#fillField-java.lang.String-java.lang.String---}
```
public void fillField(String fieldName, String[] fieldValues)
```


Заполните поле несколькими вариантами выбора. Примечание: только для поля списка AcroForm.

--------------------

```
Form form = new com.aspose.pdf.Form("PdfForm.pdf", "Form_Updated.pdf");
 form.fillField("ListBox1", new String[] { "Three", "One" });
 form.save();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Полное имя поля. |
| fieldValues | java.lang.String[] | Массив строк, содержащий несколько элементов для выбора. |

### fillFields(String[] fieldNames, String[] fieldValues, OutputStream output) {#fillFields-java.lang.String---java.lang.String---java.io.OutputStream-}
```
public final boolean fillFields(String[] fieldNames, String[] fieldValues, OutputStream output)
```


Заполняет поля текстового поля текстовыми значениями и сохраняет документ. Актуально для подписанных документов. Примечание: применяется только к текстовому полю. И имя, и значение поля чувствительны к регистру.

--------------------

```
Form form = new Form(dataDir + "SignedPdfForm.pdf");
 form.FillFields(new string[] {"Field1"}, new string[] {"+"}, stream);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldNames | java.lang.String[] | Имена полей. |
| fieldValues | java.lang.String[] | Новые значения полей. |
| output | java.io.OutputStream | Поток, где документ будет сохранен. |

**Возвращает:**
boolean - true, если поля были найдены и успешно заполнены.
### fillImageField(String fieldName, InputStream imageStream) {#fillImageField-java.lang.String-java.io.InputStream-}
```
public void fillImageField(String fieldName, InputStream imageStream)
```


Перегружает функцию FillImageField. Вход представляет собой поток изображения.

--------------------

```
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
 form.fillImageField("fieldName", new FileInputStream("file.jpg", FileMode.Open, FileAccess.Read));
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Полное имя поля. |
| imageStream | java.io.InputStream | Поток изображения. |

### fillImageField(String fieldName, String imageFileName) {#fillImageField-java.lang.String-java.lang.String-}
```
public void fillImageField(String fieldName, String imageFileName)
```


Вставляет изображение в существующее поле кнопки в качестве внешнего вида в соответствии с полным именем поля.

--------------------

```
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
 form.fillImageField("fieldName", "file.jpg");
 form.save();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Полное имя поля кнопки изображения. |
| imageFileName | java.lang.String | Путь к файлу изображения, относительный и абсолютный, в порядке. |

### flattenAllFields() {#flattenAllFields--}
```
public void flattenAllFields()
```


Сглаживает все поля.

--------------------

```
Form form = new Form("PdfForm.pdf");
 form.flattenAllFields();
```

### flattenField(String fieldName) {#flattenField-java.lang.String-}
```
public void flattenField(String fieldName)
```


Выравнивает указанное поле с полным именем поля. Любое другое поле останется неизменным. Если fieldName недействительно, все поля останутся неизменными.

--------------------

```
Form form = new Form("PdfForm.pdf");
 form.flattenField("textField");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Имя поля, которое нужно сгладить. |

### getAttachmentName() {#getAttachmentName--}
```
public String getAttachmentName()
```


Получает имя вложения, когда результат операции сохраняется в объектах HttpResponse как вложение.

**Возвращает:**
java.lang.String
### getButtonOptionCurrentValue(String fieldName) {#getButtonOptionCurrentValue-java.lang.String-}
```
public String getButtonOptionCurrentValue(String fieldName)
```


Возвращает текущее значение для полей опций переключателя.

--------------------

```
Form form = new Form("PdfForm.pdf");
 System.out.println(form.GetButtonOptionCurrentValue("btnField"));
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Имя поля |

**Возвращает:**
java.lang.String — Строковое значение для текущей радиогруппы optino. См. также GetButtonOptionValues 
### getButtonOptionValues(String fieldName) {#getButtonOptionValues-java.lang.String-}
```
public Hashtable<String,String> getButtonOptionValues(String fieldName)
```


Получает поля параметров переключателя и связанные значения на основе имени поля. Этот метод имеет значение для групп переключателей.

--------------------

```
Form form = new Form("PdfForm.pdf");
 java.util.Map values = form.getButtonOptionValues("Color");
 System.out.println(values.get("White").toString());
 System.out.println(values.get("Black").toString());
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Имя поля |

**Возвращает:**
java.util.Hashtable<java.lang.String,java.lang.String> — хеш-таблица значений опций с ключами по имени элемента формы
### getButtonOptionValuesInternal(String fieldName) {#getButtonOptionValuesInternal-java.lang.String-}
```
public System.Collections.Generic.Dictionary<String,String> getButtonOptionValuesInternal(String fieldName)
```


Получает поля параметров переключателя и связанные значения на основе имени поля. Этот метод имеет значение для групп переключателей.

--------------------

```
Form form = new Form("PdfForm.pdf");
 Hashtable values = form.getButtonOptionValues("Color");
 System.out.println(values["White"].toString());
 System.out.println(values["Black"].toString());
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Имя поля |

**Возвращает:**
[Dictionary](../../com.aspose.ms.system.collections.generic/dictionary) - Хэш-таблица значений параметров с ключами по имени элемента формы
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


Содержимое Getshow будет сохранено, когда результат операции будет сохранен в объекте HttpResponse. Возможное значение: inline/attachment. По умолчанию: встроенный.

**Возвращает:**
инт
### getDestFileName() {#getDestFileName--}
```
public String getDestFileName()
```


Получает имя файла назначения.

**Возвращает:**
java.lang.String — строковый объект
### getDestStream() {#getDestStream--}
```
public OutputStream getDestStream()
```


Получает или задает поток назначения.

**Возвращает:**
java.io.OutputStream
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


Получает фасад документа, над которым работает.

**Возвращает:**
[IDocument](../../com.aspose.pdf/idocument) - элемент IDocument
### getField(String fieldName) {#getField-java.lang.String-}
```
public String getField(String fieldName)
```


Получает значение поля в соответствии с его именем поля.

--------------------

```
Form form = new Form("PdfForm.pdf");
 System.out.println("Field value = " + form.getField("Field1"));
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Полное имя поля. |

**Возвращает:**
java.lang.String — значение поля.
### getFieldFacade(String fieldName) {#getFieldFacade-java.lang.String-}
```
public FormFieldFacade getFieldFacade(String fieldName)
```


Возвращает объект FromFieldFacade, содержащий все атрибуты внешнего вида.

--------------------

```
com.aspose.pdf.facades.Form form = new com.aspose.pdf.facades.Form("form.pdf"));
 FormFieldFacade field = form.getFieldFacade("field1");
 System.out.println("Color of field border: " + field.getBorderColor());
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Имя поля для чтения. |

**Возвращает:**
[FormFieldFacade](../../com.aspose.pdf.facades/formfieldfacade) - Объект FormFieldFacade
### getFieldFlag(String fieldName) {#getFieldFlag-java.lang.String-}
```
public int getFieldFlag(String fieldName)
```


Возвращает флаги поля.

--------------------

```
Form form = new Form("PdfForm.pdf");
 if (form.getFieldFlag("textField") == ProptyFlag.ReadOnly)
 {
    System.out.println("Field is read-only");
 }
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Имя поля |

**Возвращает:**
int - Флаг свойства (ReadOnly/Required/NoExport
### getFieldLimit(String fieldName) {#getFieldLimit-java.lang.String-}
```
public int getFieldLimit(String fieldName)
```


Получить ограничение текстового поля.

--------------------

```
Form form = new Form("PdfForm.pdf");
 System.out.println(form.getFieldLimit("textfieldBox"));
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Полное имя поля. |

**Возвращает:**
int — Возвращает максимальное количество символов, которое может быть заполнено текстовым полем. Не установлено, вернуть 0.
### getFieldNames() {#getFieldNames--}
```
public String[] getFieldNames()
```


Получает список имен полей в форме.

--------------------

```
Form form = new Form("PdfForm.pdf");
 String[] fields = form.getFieldNames();
 for(String field : fields)
 {
   System.out.println(field);
 }
```

**Возвращает:**
java.lang.String[]
### getFieldType(String fieldName) {#getFieldType-java.lang.String-}
```
public int getFieldType(String fieldName)
```


Возвращает тип поля.

--------------------

```
Form form = new Form("PdfForm.pdf");
 if (form.getFieldType("textField") == FieldType.Text)
 {
    System.out.println("_Type of field is text");
 }
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Имя поля. |

**Возвращает:**
int - Элемент перечисления FileType, соответствующий типу поля.
### getFormSubmitButtonNames() {#getFormSubmitButtonNames--}
```
public String[] getFormSubmitButtonNames()
```


Получает все имена кнопок отправки формы.

--------------------

```
Form form = new Form("PdfForm.pdf");
 String[] submits = form.getFormSubmitButtonNames();
 for(String btn : submits)
 {
   System.out.println(btn);
 }
```

**Возвращает:**
java.lang.String[]
### getFullFieldName(String fieldName) {#getFullFieldName-java.lang.String-}
```
public String getFullFieldName(String fieldName)
```


Получает полное имя поля в соответствии с его коротким именем поля.

--------------------

```
Form form = new Form("PdfForm.pdf");
 System.out.println("Full field name is : " + form.getFullFieldName("textField"));
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Полное имя поля. |

**Возвращает:**
java.lang.String — полное имя поля.
### getImportResult() {#getImportResult--}
```
public AForm.FormImportResult[] getImportResult()
```


Результат последней операции импорта. Массив объектов, описывающих результат импорта для каждого поля.

**Возвращает:**
com.aspose.pdf.facades.AForm.FormImportResult[] - ФормИмпортРезультат[] множество
### getResponse() {#getResponse--}
```
public HttpServletResponse getResponse()
```


Получает или задает объект Response, в котором будет храниться результат операции.

**Возвращает:**
javax.servlet.http.HttpServletResponse — объект HttpServletResponse
### getRichText(String fieldName) {#getRichText-java.lang.String-}
```
public String getRichText(String fieldName)
```


Получите значение поля форматированного текста, включая информацию о форматировании каждого символа.

--------------------

```
Form form = new Form("PdfForm.pdf");
 System.out.println(form.getRichText("txtDescriptionRTF"));
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Полное имя поля для поля Rich Text. |

**Возвращает:**
java.lang.String — возвращает строку, содержащую информацию о форматировании поля Rich Text.
### getSaveOptions() {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```


Получает или задает параметры сохранения, когда результат сохраняется как HttpResponse. Значение по умолчанию: пдфсавеоптионс.

**Возвращает:**
[SaveOptions](../../com.aspose.pdf/saveoptions)
### getSrcFileName() {#getSrcFileName--}
```
public String getSrcFileName()
```


Получает имя исходного файла.

--------------------

```
Form form = new com.aspose.pdf.Form();
   form.setSrcFileName("file.pdf");
```

**Возвращает:**
java.lang.String
### getSrcStream() {#getSrcStream--}
```
public InputStream getSrcStream()
```


Получает исходный поток.

**Возвращает:**
java.io.InputStream
### getSubmitFlags(String fieldName) {#getSubmitFlags-java.lang.String-}
```
public int getSubmitFlags(String fieldName)
```


Возвращает флаги отправки кнопки отправки

--------------------

```
Form form = new Form("PdfForm.pdf");
 System.out.println( ( form.getSubmitFlags("btnSubmit") | SubmitFormFlag.Xfdf != 0) ? " XFDF" : " ");
 /// System.out.println(( form.getSubmitFlags("btnSubmit") | SubmitFormFlag.Fdf != 0) ? "FDF": "");
 System.out.println( ( form.getSubmitFlags("btnSubmit") | SubmitFormFlag.Pdf != 0) ? " PDF" : " ");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Полное имя поля. |

**Возвращает:**
int - флаги отправки кнопки.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### importFdf(InputStream inputFdfStream) {#importFdf-java.io.InputStream-}
```
public void importFdf(InputStream inputFdfStream)
```


Импортирует содержимое полей из файла fdf и помещает их в новый pdf.

--------------------

```
Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf");
 form.importFdf(new FileInputStream("data.fdf"));
 form.save();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFdfStream | java.io.InputStream | Входной поток fdf. |

### importXfdf(InputStream inputXfdfStream) {#importXfdf-java.io.InputStream-}
```
public void importXfdf(InputStream inputXfdfStream)
```


Импортирует содержимое полей из файла xfdf(xml) и помещает их в новый pdf.

--------------------

```
Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf");
 InputStream fs = new FileInputStream("export_old.xfdf");
 form.importXfdf(fs);
 fs.close();
 form.save();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputXfdfStream | java.io.InputStream | Входной поток xfdf(xml). |

### importXml(InputStream inputXmlStream) {#importXml-java.io.InputStream-}
```
public void importXml(InputStream inputXmlStream)
```


Импортирует содержимое полей из xml-файла и помещает их в новый pdf.

--------------------

```
Form form = new Form("PdfForm.pdf");
 InputStream fs = new FileInputStream("import.xml");
 form.importXml(fs);
 form.save("Form_Imported.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputXmlStream | java.io.InputStream | Поток, из которого считывается XML для импорта. |

### importXml(InputStream inputXmlStream, boolean IgnoreFormTemplateChanges) {#importXml-java.io.InputStream-boolean-}
```
public void importXml(InputStream inputXmlStream, boolean IgnoreFormTemplateChanges)
```


Импортирует содержимое полей из xml-файла и помещает их в новый pdf.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputXmlStream | java.io.InputStream | Входной XML-поток. |
| IgnoreFormTemplateChanges | boolean | Если этот параметр имеет значение true, все изменения шаблона формы XFA не будут сохранены. |

### importXml(String inputXml) {#importXml-java.lang.String-}
```
public void importXml(String inputXml)
```


Импортирует содержимое полей из xml-файла и помещает их в новый pdf.

--------------------

```
Form form = new Form("PdfForm.pdf");
 form.importXml("import.xml");
 form.save( "Form_Imported.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputXml | java.lang.String | Поток, из которого считывается XML для импорта. |

### isRequiredField(String fieldName) {#isRequiredField-java.lang.String-}
```
public boolean isRequiredField(String fieldName)
```


Определяет, является ли поле обязательным или нет.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Имя поля. |

**Возвращает:**
boolean - True - поле обязательно для заполнения; в противном случае ложно.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### renameField(String fieldName, String newFieldName) {#renameField-java.lang.String-java.lang.String-}
```
public void renameField(String fieldName, String newFieldName)
```


Переименовывает поле. Подойдет либо поле AcroForm, либо поле XFA.

--------------------

```
Form form = new Form("PdfForm.pdf", "PdfFormUpdated.pdf");
 form.renameField("field", "field1");
 form.save();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | старое имя поля |
| newFieldName | java.lang.String | новое имя поля |

### save() {#save--}
```
public void save()
```


Сохраняет значение заполненных полей и закрывает открытый документ Pdf.

--------------------

```
Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf");
 form.fillField("textField", "new value");
 form.save();
```

### save(OutputStream destStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destStream)
```


Сохраняет документ в указанный поток.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| destStream | java.io.OutputStream | Поток, где документ будет сохранен. |

### save(String destFile) {#save-java.lang.String-}
```
public void save(String destFile)
```


Сохраняет документ в указанный файл.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| destFile | java.lang.String | Файл, в котором будет сохранен документ. |

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


Устанавливает формат файла PDF. Файл результата будет сохранен в указанном формате. Если это свойство не указано, файл будет сохранен в формате PDF по умолчанию без преобразования.

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
Form form = new com.aspose.pdf.Form();
   form.setDestFileName("file.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setDestStream(OutputStream value) {#setDestStream-java.io.OutputStream-}
```
public void setDestStream(OutputStream value)
```


Получает целевой поток.

--------------------

```
Form form = new com.aspose.pdf.Form();
   form.setDestStream (new FileInputStream("file.pdf"));
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.io.OutputStream |  |

### setResponse(HttpServletResponse value) {#setResponse-javax.servlet.http.HttpServletResponse-}
```
public void setResponse(HttpServletResponse value)
```


Получает или задает объект Response, в котором будет храниться результат операции.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | javax.servlet.http.HttpServletResponse | Объект HttpServletResponse |

### setSaveOptions(SaveOptions value) {#setSaveOptions-com.aspose.pdf.SaveOptions-}
```
public void setSaveOptions(SaveOptions value)
```


Получает или задает параметры сохранения, когда результат сохраняется как HttpResponse. Значение по умолчанию: пдфсавеоптионс.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [SaveOptions](../../com.aspose.pdf/saveoptions) |  |

### setSrcFileName(String value) {#setSrcFileName-java.lang.String-}
```
public void setSrcFileName(String value)
```


Устанавливает имя исходного файла.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setSrcStream(InputStream value) {#setSrcStream-java.io.InputStream-}
```
public void setSrcStream(InputStream value)
```


Получает исходный поток.

--------------------

```
Form form = new com.aspose.pdf.Form();
  form.setSrcStream (new FileInputStream("source.pdf")));
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.io.InputStream |  |

### setXfaData(InputStream inputXmlStream) {#setXfaData-java.io.InputStream-}
```
public void setXfaData(InputStream inputXmlStream)
```


Заменяет данные XFA указанным пакетом данных. Пакет данных может быть извлечен с помощью ExtractXfaData.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputXmlStream | java.io.InputStream | Поток, в котором хранится XML. |

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
