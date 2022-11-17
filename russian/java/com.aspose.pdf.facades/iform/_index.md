---
title: IForm
second_title: Aspose.PDF для справки по Java API
description: Класс, представляющий объект формы Acro.
type: docs
weight: 68
url: /ru/java/com.aspose.pdf.facades/iform/
---
**Все реализованные интерфейсы:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public interface IForm extends System.IDisposable, Closeable
```

Класс, представляющий объект формы Acro.
## Методы

| Метод | Описание |
| --- | --- |
| [close()](#close--) | Закрывает открытые файлы без изменений. |
| [exportFdf(OutputStream outputFdfStream)](#exportFdf-java.io.OutputStream-) | Экспортирует содержимое полей pdf в поток fdf. |
| [exportXfdf(OutputStream outputXfdfStream)](#exportXfdf-java.io.OutputStream-) | Экспортирует содержимое полей pdf в поток xml. |
| [exportXml(OutputStream outputXmlStream)](#exportXml-java.io.OutputStream-) | Экспортирует содержимое полей pdf в поток xml. |
| [fillBarcodeField(String fieldName, String data)](#fillBarcodeField-java.lang.String-java.lang.String-) | Заполните поле штрих-кода в соответствии с его полным именем поля. |
| [fillField(String fieldName, boolean beChecked)](#fillField-java.lang.String-boolean-) | Заполняет поле флажка логическим значением. |
| [fillField(String fieldName, int index)](#fillField-java.lang.String-int-) | Заполняет поле переключателя допустимым значением индекса в соответствии с полным именем поля. |
| [fillField(String fieldName, String fieldValue)](#fillField-java.lang.String-java.lang.String-) | Заполняет поле допустимым значением в соответствии с полным именем поля. |
| [fillField(String fieldName, String value, boolean fitFontSize)](#fillField-java.lang.String-java.lang.String-boolean-) | Заполнить поле |
| [fillField(String fieldName, String[] fieldValues)](#fillField-java.lang.String-java.lang.String---) | Заполните поле несколькими вариантами выбора. Примечание: только для поля списка AcroForm. |
| [fillImageField(String fieldName, InputStream imageStream)](#fillImageField-java.lang.String-java.io.InputStream-) | Перегружает функцию FillImageField. |
| [fillImageField(String fieldName, String imageFileName)](#fillImageField-java.lang.String-java.lang.String-) | Вставляет изображение в существующее поле кнопки в качестве внешнего вида в соответствии с полным именем поля. |
| [flattenAllFields()](#flattenAllFields--) | Сглаживает все поля. |
| [flattenField(String fieldName)](#flattenField-java.lang.String-) | Выравнивает указанное поле с полным именем поля. |
| [getAttachmentName()](#getAttachmentName--) | Получает или задает имя вложения, когда результат операции сохраняется в объектах HttpResponse как вложение. |
| [getButtonOptionCurrentValue(String fieldName)](#getButtonOptionCurrentValue-java.lang.String-) | Возвращает текущее значение для полей опций переключателя. |
| [getButtonOptionValues(String fieldName)](#getButtonOptionValues-java.lang.String-) | Получает поля параметров переключателя и связанные значения на основе имени поля. |
| [getButtonOptionValuesInternal(String fieldName)](#getButtonOptionValuesInternal-java.lang.String-) | Получает поля параметров переключателя и связанные значения на основе имени поля. |
| [getContentDisposition()](#getContentDisposition--) | Получает или задает способ сохранения содержимого при сохранении результата операции в объекте HttpResponse. |
| [getDestFileName()](#getDestFileName--) | Получает имя файла назначения. |
| [getDestStream()](#getDestStream--) | Получает целевой поток. |
| [getDocument()](#getDocument--) | Получает документ, над которым работает Form. |
| [getField(String fieldName)](#getField-java.lang.String-) | Получает значение поля в соответствии с его именем поля. |
| [getFieldFacade(String fieldName)](#getFieldFacade-java.lang.String-) | Возвращает объект FromFieldFacade, содержащий все атрибуты внешнего вида. |
| [getFieldFlag(String fieldName)](#getFieldFlag-java.lang.String-) | Возвращает флаги поля. |
| [getFieldLimit(String fieldName)](#getFieldLimit-java.lang.String-) | Получить ограничение текстового поля. |
| [getFieldNames()](#getFieldNames--) | Получает список имен полей в форме. |
| [getFieldType(String fieldName)](#getFieldType-java.lang.String-) | Возвращает тип поля. |
| [getFormSubmitButtonNames()](#getFormSubmitButtonNames--) | Получает все имена кнопок отправки формы. |
| [getFullFieldName(String fieldName)](#getFullFieldName-java.lang.String-) | Получает полное имя поля в соответствии с его коротким именем поля. |
| [getRichText(String fieldName)](#getRichText-java.lang.String-) | Получите значение поля форматированного текста, включая информацию о форматировании каждого символа. |
| [getSaveOptions()](#getSaveOptions--) | Получает или задает параметры сохранения, когда результат сохраняется как HttpResponse. |
| [getSrcFileName()](#getSrcFileName--) | Получает имя исходного файла. |
| [getSrcStream()](#getSrcStream--) | Получает исходный поток. |
| [getSubmitFlags(String fieldName)](#getSubmitFlags-java.lang.String-) | Возвращает флаги отправки кнопки отправки |
| [importFdf(InputStream inputFdfStream)](#importFdf-java.io.InputStream-) | Импортирует содержимое полей из файла fdf и помещает их в новый pdf. |
| [importXfdf(InputStream inputXfdfStream)](#importXfdf-java.io.InputStream-) | Импортирует содержимое полей из файла xfdf(xml) и помещает их в новый pdf. |
| [importXml(InputStream inputXmlStream)](#importXml-java.io.InputStream-) | Импортирует содержимое полей из xml-файла и помещает их в новый pdf. |
| [importXml(InputStream inputXmlStream, boolean IgnoreFormTemplateChanges)](#importXml-java.io.InputStream-boolean-) | Импортирует содержимое полей из xml-файла и помещает их в новый pdf. |
| [renameField(String fieldName, String newFieldName)](#renameField-java.lang.String-java.lang.String-) | Переименовывает поле. |
| [save()](#save--) | Сохраняет значение заполненных полей и закрывает открытый документ Pdf. |
| [setAttachmentName(String value)](#setAttachmentName-java.lang.String-) | Задает имя вложения, когда результат операции сохраняется в объектах HttpResponse как вложение. |
| [setContentDisposition(int value)](#setContentDisposition-int-) | Устанавливает, как содержимое будет сохранено, когда результат операции будет сохранен в объекте HttpResponse. |
| [setConvertTo(PdfFormat value)](#setConvertTo-com.aspose.pdf.PdfFormat-) | Устанавливает формат файла PDF. |
| [setDestFileName(String value)](#setDestFileName-java.lang.String-) | Устанавливает имя файла назначения. |
| [setDestStream(OutputStream value)](#setDestStream-java.io.OutputStream-) | Получает целевой поток. |
| [setSaveOptions(SaveOptions value)](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Получает или задает параметры сохранения, когда результат сохраняется как HttpResponse. |
| [setSrcFileName(String value)](#setSrcFileName-java.lang.String-) | Устанавливает имя исходного файла. |
| [setSrcStream(InputStream value)](#setSrcStream-java.io.InputStream-) | Получает исходный поток. |
### close() {#close--}
```
public abstract void close()
```


Закрывает открытые файлы без изменений.

### exportFdf(OutputStream outputFdfStream) {#exportFdf-java.io.OutputStream-}
```
public abstract void exportFdf(OutputStream outputFdfStream)
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
public abstract void exportXfdf(OutputStream outputXfdfStream)
```


Экспортирует содержимое полей pdf в поток xml. Значение поля кнопки не будет экспортировано.

--------------------

```
Form form = new Form("PdfForm.pdf");
 OutputStream fs = new FileOutputStream("export.xfdf");
 form.exportXfdf(fs);
 fs.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputXfdfStream | java.io.OutputStream | Выходной XML-поток. |

### exportXml(OutputStream outputXmlStream) {#exportXml-java.io.OutputStream-}
```
public abstract void exportXml(OutputStream outputXmlStream)
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
| outputXmlStream | java.io.OutputStream | Объект OutputStream |

### fillBarcodeField(String fieldName, String data) {#fillBarcodeField-java.lang.String-java.lang.String-}
```
public abstract boolean fillBarcodeField(String fieldName, String data)
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
public abstract boolean fillField(String fieldName, boolean beChecked)
```


Заполняет поле флажка логическим значением. Примечание: применяется только к флажку. Обратите внимание, что Facades поддерживает только полные имена полей и не работает с частичными именами полей, в отличие от Aspose.Pdf.Kit; Например, если поле имеет полное имя "Form.Subform.CheckBoxField", вы должны указать полное имя, а не "CheckBoxField". Вы можете использовать свойство FieldNames для просмотра существующих имен полей и поиска нужного поля по частичному имени.

--------------------

```
Form form = new Form("PdfForm.pdf");
 form.fillField("checkboxField", true);
 
 // как искать поле по частичному имени:
 Form form = new Form("input.pdf", "output.pdf");
 for (String fieldName : form.getFieldNames())
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
| beChecked | boolean | Логический флаг: true означает, что флажок установлен, а false, чтобы снять его. |

**Возвращает:**
boolean - логическое значение
### fillField(String fieldName, int index) {#fillField-java.lang.String-int-}
```
public abstract boolean fillField(String fieldName, int index)
```


Заполняет поле переключателя допустимым значением индекса в соответствии с полным именем поля. Перед заполнением полей необходимо знать только название поля. В то время как значение может быть указано по его индексу. Примечание. Применяется только к полям Radio Box, Combo Box и List Box. Обратите внимание, что Facades поддерживает только полные имена полей и не работает с частичными именами полей, в отличие от Aspose.Pdf.Kit; Например, если поле имеет полное имя "Form.Subform.ListBoxField", вы должны указать полное имя, а не "ListBoxField". Вы можете использовать свойство FieldNames для просмотра существующих имен полей и поиска нужного поля по частичному имени.

--------------------

```
Form form = new Form("PdfForm.pdf");
 form.fillField("listboxField", 2);
 form.fillField("comboboxField", 2);
 form.fillField("radiobuttonField", 2);
 
 
 // как искать поле по частичному имени:
 Form form = new Form("input.pdf", "output.pdf");
 for (String fieldName : form.getFieldNames())
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
| fieldName | java.lang.String | Имя поля для заполнения. |
| index | int | Индекс выбранного блока во всей группе радиоблоков. |

**Возвращает:**
boolean - логическое значение
### fillField(String fieldName, String fieldValue) {#fillField-java.lang.String-java.lang.String-}
```
public abstract boolean fillField(String fieldName, String fieldValue)
```


Заполняет поле допустимым значением в соответствии с полным именем поля. Перед заполнением полей должны быть известны имена каждого поля и соответствующие им допустимые значения. И имя, и значение поля чувствительны к регистру. Обратите внимание, что Facades поддерживает только полные имена полей и не работает с частичными именами полей, в отличие от Aspose.Pdf.Kit; Например, если поле имеет полное имя "Form.Subform.TextField", вы должны указать полное имя, а не "TextField". Вы можете использовать свойство FieldNames для просмотра существующих имен полей и поиска нужного поля по частичному имени.

--------------------

```
Form form = new Form("PdfForm.pdf");
 form.fillField("FirstName", "John");
 form.fillField("LastName", "Smith");
 
 
 
 // как искать поле по частичному имени:
 Form form = new Form("input.pdf", "output.pdf");
 for (String fieldName : form.getFieldNames())
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
boolean - логическое значение
### fillField(String fieldName, String value, boolean fitFontSize) {#fillField-java.lang.String-java.lang.String-boolean-}
```
public abstract boolean fillField(String fieldName, String value, boolean fitFontSize)
```


Заполнить поле

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Имя поля |
| value | java.lang.String | Новое значение поля |
| fitFontSize | boolean | Если true, размер шрифта в полях редактирования будет подогнан. |

**Возвращает:**
boolean - логическое значение
### fillField(String fieldName, String[] fieldValues) {#fillField-java.lang.String-java.lang.String---}
```
public abstract void fillField(String fieldName, String[] fieldValues)
```


Заполните поле несколькими вариантами выбора. Примечание: только для поля списка AcroForm.

--------------------

```
Form form = new com.aspose.pdf.Form("PdfForm.pdf", "Form_Updated.pdf");
 form.fillField("ListBox1", new String[]
 { "Three", "One" });
 form.save();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Полное имя поля. |
| fieldValues | java.lang.String[] | Массив строк, содержащий несколько элементов для выбора. |

### fillImageField(String fieldName, InputStream imageStream) {#fillImageField-java.lang.String-java.io.InputStream-}
```
public abstract void fillImageField(String fieldName, InputStream imageStream)
```


Перегружает функцию FillImageField. Вход представляет собой поток изображения.

--------------------

```
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
 form.fillImageField("fieldName", new FileInputStream("file.jpg"));
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Полное имя поля. |
| imageStream | java.io.InputStream | Поток изображения. |

### fillImageField(String fieldName, String imageFileName) {#fillImageField-java.lang.String-java.lang.String-}
```
public abstract void fillImageField(String fieldName, String imageFileName)
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
public abstract void flattenAllFields()
```


Сглаживает все поля.

--------------------

```
Form form = new Form("PdfForm.pdf");
 form.flattenAllFields();
```

### flattenField(String fieldName) {#flattenField-java.lang.String-}
```
public abstract void flattenField(String fieldName)
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
public abstract String getAttachmentName()
```


Получает или задает имя вложения, когда результат операции сохраняется в объектах HttpResponse как вложение.

**Возвращает:**
java.lang.String — строковый объект
### getButtonOptionCurrentValue(String fieldName) {#getButtonOptionCurrentValue-java.lang.String-}
```
public abstract String getButtonOptionCurrentValue(String fieldName)
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
public abstract Hashtable<String,String> getButtonOptionValues(String fieldName)
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
public abstract System.Collections.Generic.Dictionary<String,String> getButtonOptionValuesInternal(String fieldName)
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
[Dictionary](../../com.aspose.ms.system.collections.generic/dictionary) - Хэш-таблица значений параметров с ключами по имени элемента формы
### getContentDisposition() {#getContentDisposition--}
```
public abstract int getContentDisposition()
```


Получает или задает способ сохранения содержимого при сохранении результата операции в объекте HttpResponse. Возможное значение: inline/attachment. По умолчанию: встроенный.

**Возвращает:**
int — элемент ContentDisposition
### getDestFileName() {#getDestFileName--}
```
public abstract String getDestFileName()
```


Получает имя файла назначения.

**Возвращает:**
java.lang.String — строковый объект
### getDestStream() {#getDestStream--}
```
public abstract OutputStream getDestStream()
```


Получает целевой поток.

**Возвращает:**
java.io.OutputStream — объект OutputStream
### getDocument() {#getDocument--}
```
public abstract IDocument getDocument()
```


Получает документ, над которым работает Form.

**Возвращает:**
[IDocument](../../com.aspose.pdf/idocument) - Объект IDocument
### getField(String fieldName) {#getField-java.lang.String-}
```
public abstract String getField(String fieldName)
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
public abstract FormFieldFacade getFieldFacade(String fieldName)
```


Возвращает объект FromFieldFacade, содержащий все атрибуты внешнего вида.

--------------------

```
com.aspose.pdf.facades.Form form = new com.aspose.pdf.facades.Form("form.pdf"));
 FormFieldFacade field = form.getFieldFacade("field1");
 System.out.println("Color of field border: " + field.BorderColor);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Имя поля для чтения. |

**Возвращает:**
[FormFieldFacade](../../com.aspose.pdf.facades/formfieldfacade) - Объект FormFieldFacade
### getFieldFlag(String fieldName) {#getFieldFlag-java.lang.String-}
```
public abstract int getFieldFlag(String fieldName)
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
public abstract int getFieldLimit(String fieldName)
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
public abstract String[] getFieldNames()
```


Получает список имен полей в форме.

--------------------

```
Form form = new Form("PdfForm.pdf");
 String[] fields = form.getFieldNames();
 for (String field : fields)
 {
     System.out.println(field);
 }
```

**Возвращает:**
java.lang.String[] - Нить[] объект
### getFieldType(String fieldName) {#getFieldType-java.lang.String-}
```
public abstract int getFieldType(String fieldName)
```


Возвращает тип поля.

--------------------

```
Form form = new Form("PdfForm.pdf");
 if (form.GetFieldType("textField") == FieldType.Text)
 {
     System.out.println("Type of field is text");
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
public abstract String[] getFormSubmitButtonNames()
```


Получает все имена кнопок отправки формы.

--------------------

```
Form form = new Form("PdfForm.pdf");
 String[] submits = form.getFormSubmitButtonNames();
 for (String btn : submits)
 {
     System.out.println(btn);
 }
```

**Возвращает:**
java.lang.String[] - Нить[] объект
### getFullFieldName(String fieldName) {#getFullFieldName-java.lang.String-}
```
public abstract String getFullFieldName(String fieldName)
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
### getRichText(String fieldName) {#getRichText-java.lang.String-}
```
public abstract String getRichText(String fieldName)
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
public abstract SaveOptions getSaveOptions()
```


Получает или задает параметры сохранения, когда результат сохраняется как HttpResponse. Значение по умолчанию: пдфсавеоптионс.

**Возвращает:**
[SaveOptions](../../com.aspose.pdf/saveoptions) - Объект SaveOptions
### getSrcFileName() {#getSrcFileName--}
```
public abstract String getSrcFileName()
```


Получает имя исходного файла.

--------------------

```
Form form = new com.aspose.pdf.Form();
 form.setSrcFileName("file.pdf");
```

**Возвращает:**
java.lang.String — строковый объект
### getSrcStream() {#getSrcStream--}
```
public abstract InputStream getSrcStream()
```


Получает исходный поток.

**Возвращает:**
java.io.InputStream — объект InputStream
### getSubmitFlags(String fieldName) {#getSubmitFlags-java.lang.String-}
```
public abstract int getSubmitFlags(String fieldName)
```


Возвращает флаги отправки кнопки отправки

--------------------

```
Form form = new Form("PdfForm.pdf");
 System.out.println((form.getSubmitFlags("btnSubmit") | SubmitFormFlag.Xfdf != 0) ? " XFDF" : " ");
 // / System.out.println( ( form.getSubmitFlags("btnSubmit") | SubmitFormFlag.Fdf
 // != 0) ? "ФДФ": "");
 System.out.println((form.getSubmitFlags("btnSubmit") | SubmitFormFlag.Pdf != 0) ? " PDF" : " ");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | java.lang.String | Полное имя поля. |

**Возвращает:**
int — элемент SubmitFormFlag
### importFdf(InputStream inputFdfStream) {#importFdf-java.io.InputStream-}
```
public abstract void importFdf(InputStream inputFdfStream)
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
public abstract void importXfdf(InputStream inputXfdfStream)
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
public abstract void importXml(InputStream inputXmlStream)
```


Импортирует содержимое полей из xml-файла и помещает их в новый pdf.

--------------------

```
Form form = new Form("PdfForm.pdf", "Form_Imported.pdf");
 InputStream fs = new FileInputStream("import.xml");
 form.importXml(fs);
 form.save();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputXmlStream | java.io.InputStream | Объект InputStream |

### importXml(InputStream inputXmlStream, boolean IgnoreFormTemplateChanges) {#importXml-java.io.InputStream-boolean-}
```
public abstract void importXml(InputStream inputXmlStream, boolean IgnoreFormTemplateChanges)
```


Импортирует содержимое полей из xml-файла и помещает их в новый pdf.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputXmlStream | java.io.InputStream | Входной XML-поток. |
| IgnoreFormTemplateChanges | boolean | Если этот параметр имеет значение true, все изменения шаблона формы XFA не будут сохранены. |

### renameField(String fieldName, String newFieldName) {#renameField-java.lang.String-java.lang.String-}
```
public abstract void renameField(String fieldName, String newFieldName)
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
public abstract void save()
```


Сохраняет значение заполненных полей и закрывает открытый документ Pdf.

--------------------

```
Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf");
 form.fillField("textField", "new value");
 form.save();
```

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


Устанавливает формат файла PDF. Файл результата будет сохранен в указанном формате. Если это свойство не указано, файл будет сохранен в формате PDF по умолчанию без преобразования.

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
Form form = new com.aspose.pdf.Form();
 form.setDestFileName("file.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковый объект |

### setDestStream(OutputStream value) {#setDestStream-java.io.OutputStream-}
```
public abstract void setDestStream(OutputStream value)
```


Получает целевой поток.

--------------------

```
Form form = new com.aspose.pdf.Form();
 form.DestStream = new FileInputStream("file.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.io.OutputStream | Объект OutputStream |

### setSaveOptions(SaveOptions value) {#setSaveOptions-com.aspose.pdf.SaveOptions-}
```
public abstract void setSaveOptions(SaveOptions value)
```


Получает или задает параметры сохранения, когда результат сохраняется как HttpResponse. Значение по умолчанию: пдфсавеоптионс.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [SaveOptions](../../com.aspose.pdf/saveoptions) | Объект SaveOptions |

### setSrcFileName(String value) {#setSrcFileName-java.lang.String-}
```
public abstract void setSrcFileName(String value)
```


Устанавливает имя исходного файла.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковый объект |

### setSrcStream(InputStream value) {#setSrcStream-java.io.InputStream-}
```
public abstract void setSrcStream(InputStream value)
```


Получает исходный поток.

--------------------

```
Form form = new com.aspose.pdf.Form();
 form.setSrcStream(new FileInputStream("source.pdf"));
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.io.InputStream | Объект InputStream |
