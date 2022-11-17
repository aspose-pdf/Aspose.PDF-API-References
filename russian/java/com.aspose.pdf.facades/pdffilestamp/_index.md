---
title: PdfFileStamp
second_title: Aspose.PDF для справки по Java API
description: Класс для добавления штампов, водяных знаков или фона в файлы PDF.
type: docs
weight: 46
url: /ru/java/com.aspose.pdf.facades/pdffilestamp/
---
**Наследование:**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade), com.aspose.pdf.facades.APdfFileStamp

**Все реализованные интерфейсы:**
[com.aspose.pdf.facades.IPdfFileStamp](../../com.aspose.pdf.facades/ipdffilestamp)
```
public final class PdfFileStamp extends APdfFileStamp implements IPdfFileStamp
```

Класс для добавления штампов (водяных знаков или фона) в файлы PDF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfFileStamp()](#PdfFileStamp--) | Конструктор PdfFileStamp. |
| [PdfFileStamp(IDocument document)](#PdfFileStamp-com.aspose.pdf.IDocument-) | Инициализирует новый объект PdfFileStamp на основе документа. |
| [PdfFileStamp(IDocument document, OutputStream outputStream)](#PdfFileStamp-com.aspose.pdf.IDocument-java.io.OutputStream-) | Инициализирует новый объект PdfFileStamp на основе документа. |
| [PdfFileStamp(IDocument document, String outputFile)](#PdfFileStamp-com.aspose.pdf.IDocument-java.lang.String-) | Инициализирует новый объект PdfFileStamp на основе документа. |
| [PdfFileStamp(InputStream inputStream, OutputStream outputStream)](#PdfFileStamp-java.io.InputStream-java.io.OutputStream-) | Конструктор для PdfFileStamp. |
| [PdfFileStamp(InputStream inputStream, OutputStream outputStream, boolean keepSecurity)](#PdfFileStamp-java.io.InputStream-java.io.OutputStream-boolean-) | Конструктор PdfFileStamp. |
| [PdfFileStamp(String inputFile, String outputFile)](#PdfFileStamp-java.lang.String-java.lang.String-) | Конструктор для PdfFileStamp. |
| [PdfFileStamp(String inputFile, String outputFile, boolean keepSecurity)](#PdfFileStamp-java.lang.String-java.lang.String-boolean-) | Конструктор для PdfFileStamp. |
## Поля

| Поле | Описание |
| --- | --- |
| [POS_BOTTOM_LEFT](#POS-BOTTOM-LEFT) | Нижнее левое положение. |
| [POS_BOTTOM_LEFT](#POS-BOTTOM-LEFT) | Нижнее левое положение. |
| [POS_BOTTOM_MIDDLE](#POS-BOTTOM-MIDDLE) | Нижнее среднее положение. |
| [POS_BOTTOM_MIDDLE](#POS-BOTTOM-MIDDLE) | Нижнее среднее положение. |
| [POS_BOTTOM_RIGHT](#POS-BOTTOM-RIGHT) | Нижнее правое положение. |
| [POS_BOTTOM_RIGHT](#POS-BOTTOM-RIGHT) | Нижнее правое положение. |
| [POS_SIDES_LEFT](#POS-SIDES-LEFT) | Левое положение. |
| [POS_SIDES_LEFT](#POS-SIDES-LEFT) | Левое положение. |
| [POS_SIDES_RIGHT](#POS-SIDES-RIGHT) | Правильное положение. |
| [POS_SIDES_RIGHT](#POS-SIDES-RIGHT) | Правильное положение. |
| [POS_UPPER_LEFT](#POS-UPPER-LEFT) | Верхнее пусть положение. |
| [POS_UPPER_LEFT](#POS-UPPER-LEFT) | Верхнее пусть положение. |
| [POS_UPPER_MIDDLE](#POS-UPPER-MIDDLE) | Верхнее среднее положение. |
| [POS_UPPER_MIDDLE](#POS-UPPER-MIDDLE) | Верхнее среднее положение. |
| [POS_UPPER_RIGHT](#POS-UPPER-RIGHT) | Правое верхнее положение. |
| [POS_UPPER_RIGHT](#POS-UPPER-RIGHT) | Правое верхнее положение. |
## Методы

| Метод | Описание |
| --- | --- |
| [addFooter(FormattedText formattedText, float bottomMargin)](#addFooter-com.aspose.pdf.facades.FormattedText-float-) | Добавляет нижний колонтитул на страницы документа. |
| [addFooter(FormattedText formattedText, float bottomMargin, float leftMargin, float rightMargin)](#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-) | Добавляет нижний колонтитул на страницы документа. |
| [addFooter(InputStream imageStream, float bottomMargin)](#addFooter-java.io.InputStream-float-) | Добавляет изображение в качестве нижнего колонтитула страницы. |
| [addFooter(InputStream imageStream, float bottomMargin, float leftMargin, float rightMargin)](#addFooter-java.io.InputStream-float-float-float-) | Добавляет изображение в качестве нижнего колонтитула страницы. |
| [addFooter(String imageFile, float bottomMargin)](#addFooter-java.lang.String-float-) | Добавляет изображение в качестве нижнего колонтитула на страницы документа. |
| [addFooter(String imageFile, float bottomMargin, float leftMargin, float rightMargin)](#addFooter-java.lang.String-float-float-float-) | Добавляет изображение в качестве нижнего колонтитула страниц. |
| [addHeader(FormattedText formattedText, float topMargin)](#addHeader-com.aspose.pdf.facades.FormattedText-float-) | Добавляет заголовок на страницу. |
| [addHeader(FormattedText formattedText, float topMargin, float leftMargin, float rightMargin)](#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-) | Добавляет заголовок к страницам файла. |
| [addHeader(InputStream imageStream, float topMargin)](#addHeader-java.io.InputStream-float-) | Добавляет изображение в качестве заголовка на страницы. |
| [addHeader(InputStream inputStream, float topMargin, float leftMargin, float rightMargin)](#addHeader-java.io.InputStream-float-float-float-) | Добавляет изображение вверху страницы. |
| [addHeader(String imageFile, float topMargin)](#addHeader-java.lang.String-float-) | Добавляет изображение в качестве заголовка на страницы файла. |
| [addHeader(String imageFile, float topMargin, float leftMargin, float rightMargin)](#addHeader-java.lang.String-float-float-float-) | Добавляет изображение в качестве заголовка на страницы. |
| [addPageNumber(FormattedText formattedText)](#addPageNumber-com.aspose.pdf.facades.FormattedText-) | Добавляет номер страницы к странице. |
| [addPageNumber(FormattedText formattedText, float x, float y)](#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-) | Добавляет номер страницы в указанную позицию на странице. |
| [addPageNumber(FormattedText formattedText, int position)](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-) | Добавляет номер страницы к страницам. |
| [addPageNumber(FormattedText formattedText, int position, float leftMargin, float rightMargin, float topMargin, float bottomMargin)](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | Добавляет номер страницы к страницам документа. |
| [addPageNumber(String formatString)](#addPageNumber-java.lang.String-) | Добавьте номер страницы в файл. |
| [addPageNumber(String formatString, float x, float y)](#addPageNumber-java.lang.String-float-float-) | Добавляет номер страницы в указанную позицию на странице. |
| [addPageNumber(String formatString, int position)](#addPageNumber-java.lang.String-int-) | Добавляет номер страницы к страницам. |
| [addPageNumber(String formatString, int position, float leftMargin, float rightMargin, float topMargin, float bottomMargin)](#addPageNumber-java.lang.String-int-float-float-float-float-) | Добавляет номер страницы к страницам документа. |
| [addStamp(Stamp stamp)](#addStamp-com.aspose.pdf.facades.Stamp-) | Добавляет штамп к файлу. |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | Инициализирует фасад. |
| [bindPdf(InputStream srcStream)](#bindPdf-java.io.InputStream-) | Инициализирует фасад. |
| [bindPdf(InputStream srcStream, String password)](#bindPdf-java.io.InputStream-java.lang.String-) | Инициализирует фасад. |
| [bindPdf(String srcFile)](#bindPdf-java.lang.String-) | Инициализирует фасад. |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | Инициализирует фасад. |
| [close()](#close--) | Закрывает открытые файлы и сохраняет изменения. |
| [dispose()](#dispose--) | Закрывает все ресурсы, используемые этим экземпляром. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttachmentName()](#getAttachmentName--) | Получает имя вложения, когда результат операции сохраняется в объектах HttpResponse как вложение. |
| [getClass()](#getClass--) |  |
| [getContentDisposition()](#getContentDisposition--) | Получает способ хранения содержимого при сохранении результата операции в объекте HttpResponse. |
| [getDocument()](#getDocument--) | Получает фасад документа, над которым работает. |
| [getInputFile()](#getInputFile--) | Получает имя и путь входного файла. |
| [getInputStream()](#getInputStream--) | Получает входной поток. |
| [getKeepSecurity()](#getKeepSecurity--) | Сохраняет безопасность, если это правда. |
| [getNumberingStyle()](#getNumberingStyle--) | Получает или задает стиль нумерации страниц. |
| [getOptimizeSize()](#getOptimizeSize--) | Получает или устанавливает флаг оптимизации. |
| [getOutputFile()](#getOutputFile--) | Получает имя и путь выходного файла. |
| [getOutputStream()](#getOutputStream--) | Получает выходной поток. |
| [getPageHeight()](#getPageHeight--) | Получает высоту первой страницы исходного файла. |
| [getPageNumberRotation()](#getPageNumberRotation--) | Получает поворот номера страницы. |
| [getPageWidth()](#getPageWidth--) | Получает ширину первой страницы во входном файле. |
| [getSaveOptions()](#getSaveOptions--) | Получает параметры сохранения, когда результат сохраняется как HttpResponse. |
| [getStampId()](#getStampId--) | Идентификатор штампа следующего добавленного штампа (включая заголовки страниц/гуары/номера страниц). |
| [getStartingNumber()](#getStartingNumber--) | Получает или задает начальный номер первой страницы во входном файле. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream destStream)](#save-java.io.OutputStream-) | Сохраняет документ PDF в указанный поток. |
| [save(String destFile)](#save-java.lang.String-) | Сохраняет документ PDF в указанный файл. |
| [setAttachmentName(String value)](#setAttachmentName-java.lang.String-) | Задает имя вложения, когда результат операции сохраняется в объектах HttpResponse как вложение. |
| [setContentDisposition(int value)](#setContentDisposition-int-) | Устанавливает, как содержимое будет сохранено, когда результат операции будет сохранен в объекте HttpResponse. |
| [setConvertTo(PdfFormat value)](#setConvertTo-com.aspose.pdf.PdfFormat-) | Устанавливает формат файла PDF. |
| [setInputFile(String value)](#setInputFile-java.lang.String-) | Устанавливает имя и путь входного файла. |
| [setInputStream(InputStream value)](#setInputStream-java.io.InputStream-) | Устанавливает входной поток. |
| [setKeepSecurity(boolean value)](#setKeepSecurity-boolean-) | Сохраняет безопасность, если это правда. |
| [setNumberingStyle(int value)](#setNumberingStyle-int-) | Получает или задает стиль нумерации страниц. |
| [setOptimizeSize(boolean value)](#setOptimizeSize-boolean-) | Получает или устанавливает флаг оптимизации. |
| [setOutputFile(String value)](#setOutputFile-java.lang.String-) | Устанавливает имя и путь выходного файла. |
| [setOutputStream(OutputStream value)](#setOutputStream-java.io.OutputStream-) | Устанавливает или устанавливает выходной поток. |
| [setPageNumberRotation(float value)](#setPageNumberRotation-float-) | Устанавливает поворот номера страницы. |
| [setSaveOptions(SaveOptions value)](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Задает параметры сохранения, когда результат сохраняется как HttpResponse. |
| [setStampId(int value)](#setStampId-int-) | Идентификатор штампа следующего добавленного штампа (включая заголовки страниц/гуары/номера страниц). |
| [setStartingNumber(int value)](#setStartingNumber-int-) | Устанавливает начальный номер для первой страницы во входном файле. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfFileStamp() {#PdfFileStamp--}
```
public PdfFileStamp()
```


Конструктор PdfFileStamp. Входной файл и выходной файл могут быть указаны через соответствующие свойства.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp();
 fileStamp.setInputFile ( "input.pdf");
 fileStamp.setOutputFile ( "output.pdf");
```

### PdfFileStamp(IDocument document) {#PdfFileStamp-com.aspose.pdf.IDocument-}
```
public PdfFileStamp(IDocument document)
```


Инициализирует новый объект PdfFileStamp на основе документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ пдф. |

### PdfFileStamp(IDocument document, OutputStream outputStream) {#PdfFileStamp-com.aspose.pdf.IDocument-java.io.OutputStream-}
```
public PdfFileStamp(IDocument document, OutputStream outputStream)
```


Инициализирует новый объект PdfFileStamp на основе документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ пдф. |
| outputStream | java.io.OutputStream | Выходной поток. |

### PdfFileStamp(IDocument document, String outputFile) {#PdfFileStamp-com.aspose.pdf.IDocument-java.lang.String-}
```
public PdfFileStamp(IDocument document, String outputFile)
```


Инициализирует новый объект PdfFileStamp на основе документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ пдф. |
| outputFile | java.lang.String | Имя выходного файла и путь. |

### PdfFileStamp(InputStream inputStream, OutputStream outputStream) {#PdfFileStamp-java.io.InputStream-java.io.OutputStream-}
```
public PdfFileStamp(InputStream inputStream, OutputStream outputStream)
```


Конструктор для PdfFileStamp.

--------------------

```
[SampleCode]
 InputStream input = new FileInputStream("input.pdf");
 OutputStream output = new FileInputStream("output.pdf");
 PdfFileStamp stamp = new PdfFileStamp(input, output);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной поток. |
| outputStream | java.io.OutputStream | Выходной поток. |

### PdfFileStamp(InputStream inputStream, OutputStream outputStream, boolean keepSecurity) {#PdfFileStamp-java.io.InputStream-java.io.OutputStream-boolean-}
```
public PdfFileStamp(InputStream inputStream, OutputStream outputStream, boolean keepSecurity)
```


Конструктор PdfFileStamp.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной поток. |
| outputStream | java.io.OutputStream | Выходной поток. |
| keepSecurity | boolean | Сохраняйте безопасность, если это правда. |

### PdfFileStamp(String inputFile, String outputFile) {#PdfFileStamp-java.lang.String-java.lang.String-}
```
public PdfFileStamp(String inputFile, String outputFile)
```


Конструктор для PdfFileStamp.

--------------------

```
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Введите имя файла и путь. |
| outputFile | java.lang.String | Имя выходного файла и путь. |

### PdfFileStamp(String inputFile, String outputFile, boolean keepSecurity) {#PdfFileStamp-java.lang.String-java.lang.String-boolean-}
```
public PdfFileStamp(String inputFile, String outputFile, boolean keepSecurity)
```


Конструктор для PdfFileStamp.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFile | java.lang.String | Введите имя файла и путь. |
| outputFile | java.lang.String | Имя выходного файла и путь. |
| keepSecurity | boolean | Сохраняйте безопасность, если это правда. |

### POS_BOTTOM_LEFT {#POS-BOTTOM-LEFT}
```
public static final int POS_BOTTOM_LEFT
```


Нижнее левое положение.

### POS_BOTTOM_LEFT {#POS-BOTTOM-LEFT}
```
public static final int POS_BOTTOM_LEFT
```


Нижнее левое положение.

### POS_BOTTOM_MIDDLE {#POS-BOTTOM-MIDDLE}
```
public static final int POS_BOTTOM_MIDDLE
```


Нижнее среднее положение.

### POS_BOTTOM_MIDDLE {#POS-BOTTOM-MIDDLE}
```
public static final int POS_BOTTOM_MIDDLE
```


Нижнее среднее положение.

### POS_BOTTOM_RIGHT {#POS-BOTTOM-RIGHT}
```
public static final int POS_BOTTOM_RIGHT
```


Нижнее правое положение.

### POS_BOTTOM_RIGHT {#POS-BOTTOM-RIGHT}
```
public static final int POS_BOTTOM_RIGHT
```


Нижнее правое положение.

### POS_SIDES_LEFT {#POS-SIDES-LEFT}
```
public static final int POS_SIDES_LEFT
```


Левое положение.

### POS_SIDES_LEFT {#POS-SIDES-LEFT}
```
public static final int POS_SIDES_LEFT
```


Левое положение.

### POS_SIDES_RIGHT {#POS-SIDES-RIGHT}
```
public static final int POS_SIDES_RIGHT
```


Правильное положение.

### POS_SIDES_RIGHT {#POS-SIDES-RIGHT}
```
public static final int POS_SIDES_RIGHT
```


Правильное положение.

### POS_UPPER_LEFT {#POS-UPPER-LEFT}
```
public static final int POS_UPPER_LEFT
```


Верхнее пусть положение.

### POS_UPPER_LEFT {#POS-UPPER-LEFT}
```
public static final int POS_UPPER_LEFT
```


Верхнее пусть положение.

### POS_UPPER_MIDDLE {#POS-UPPER-MIDDLE}
```
public static final int POS_UPPER_MIDDLE
```


Верхнее среднее положение.

### POS_UPPER_MIDDLE {#POS-UPPER-MIDDLE}
```
public static final int POS_UPPER_MIDDLE
```


Верхнее среднее положение.

### POS_UPPER_RIGHT {#POS-UPPER-RIGHT}
```
public static final int POS_UPPER_RIGHT
```


Правое верхнее положение.

### POS_UPPER_RIGHT {#POS-UPPER-RIGHT}
```
public static final int POS_UPPER_RIGHT
```


Правое верхнее положение.

### addFooter(FormattedText formattedText, float bottomMargin) {#addFooter-com.aspose.pdf.facades.FormattedText-float-}
```
public void addFooter(FormattedText formattedText, float bottomMargin)
```


Добавляет нижний колонтитул на страницы документа.

--------------------

```
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
 stamp.addFooter(new FormattedText("Foot of the page"), 10);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | Объект FormattedText, который содержит текст нижнего колонтитула и текстовые свойства. |
| bottomMargin | float | Поля вверху страницы. |

### addFooter(FormattedText formattedText, float bottomMargin, float leftMargin, float rightMargin) {#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-}
```
public void addFooter(FormattedText formattedText, float bottomMargin, float leftMargin, float rightMargin)
```


Добавляет нижний колонтитул на страницы документа.

--------------------

```
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
 stamp.addFooter(new FormattedText("Foot of the page"), 10, 50, 50);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | Объект FormattedText, который содержит текст нижнего колонтитула и текстовые свойства. |
| bottomMargin | float | Поле внизу страницы. |
| leftMargin | float | Поле в левой части страницы. |
| rightMargin | float | Поля в правой части страницы. |

### addFooter(InputStream imageStream, float bottomMargin) {#addFooter-java.io.InputStream-float-}
```
public void addFooter(InputStream imageStream, float bottomMargin)
```


Добавляет изображение в качестве нижнего колонтитула страницы.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
 InputStream input = new FileInputStream("test.jpg");
 fileStamp.addFooter(new FileInputStream("image.jpg"), 50);
 fileStamp.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageStream | java.io.InputStream | Поток содержит данные изображения. |
| bottomMargin | float | Поле внизу страницы. |

### addFooter(InputStream imageStream, float bottomMargin, float leftMargin, float rightMargin) {#addFooter-java.io.InputStream-float-float-float-}
```
public void addFooter(InputStream imageStream, float bottomMargin, float leftMargin, float rightMargin)
```


Добавляет изображение в качестве нижнего колонтитула страницы.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
 InputStream input = new FileInputStream("test.jpg");
 fileStamp.addFooter(new FileInputStream("image.jpg"), 50, 50, 50);
 fileStamp.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageStream | java.io.InputStream | Поток содержит данные изображения. |
| bottomMargin | float | Поле внизу страницы. |
| leftMargin | float | Поле в левой части страницы. |
| rightMargin | float | Поля в правой части страницы. |

### addFooter(String imageFile, float bottomMargin) {#addFooter-java.lang.String-float-}
```
public void addFooter(String imageFile, float bottomMargin)
```


Добавляет изображение в качестве нижнего колонтитула на страницы документа.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
 InputStream input = new FileInputStream("test.jpg");
 fileStamp.addFooter("image.jpg", 50);
 fileStamp.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageFile | java.lang.String | Имя файла изображения и путь. |
| bottomMargin | float | Поле внизу страницы. |

### addFooter(String imageFile, float bottomMargin, float leftMargin, float rightMargin) {#addFooter-java.lang.String-float-float-float-}
```
public void addFooter(String imageFile, float bottomMargin, float leftMargin, float rightMargin)
```


Добавляет изображение в качестве нижнего колонтитула страниц.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageFile | java.lang.String | Имя файла Iamge и путь. |
| bottomMargin | float | Поле внизу страницы. |
| leftMargin | float | Поле в левой части страницы. |
| rightMargin | float | Поля в правой части страницы. |

### addHeader(FormattedText formattedText, float topMargin) {#addHeader-com.aspose.pdf.facades.FormattedText-float-}
```
public void addHeader(FormattedText formattedText, float topMargin)
```


Добавляет заголовок на страницу.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
 fileStamp.addHeader(new FormattedText("Head of the page"), 50);
 fileStamp.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | Текст для заголовка и свойства текста. |
| topMargin | float | Поля вверху страницы. |

### addHeader(FormattedText formattedText, float topMargin, float leftMargin, float rightMargin) {#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-}
```
public void addHeader(FormattedText formattedText, float topMargin, float leftMargin, float rightMargin)
```


Добавляет заголовок к страницам файла.

--------------------

```
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
 stamp.addHeader(new FormattedText("Head of the page"), 10, 50, 50);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | Форматированный текстовый объект, который содержит текст страницы и его свойства. |
| topMargin | float | Поля вверху страницы. |
| leftMargin | float | Поле в левой части страницы. |
| rightMargin | float | Поля в правой части страницы. |

### addHeader(InputStream imageStream, float topMargin) {#addHeader-java.io.InputStream-float-}
```
public void addHeader(InputStream imageStream, float topMargin)
```


Добавляет изображение в качестве заголовка на страницы.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
 InputStream input = new FileInputStream("test.jpg");
 fileStamp.addHeader(new FileInputStream("image.jpg"), 50);
 fileStamp.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageStream | java.io.InputStream | Поток изображения. |
| topMargin | float | Поле вверху страницы. |

### addHeader(InputStream inputStream, float topMargin, float leftMargin, float rightMargin) {#addHeader-java.io.InputStream-float-float-float-}
```
public void addHeader(InputStream inputStream, float topMargin, float leftMargin, float rightMargin)
```


Добавляет изображение вверху страницы.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
 IjnputStream input = new FileInputStream("test.jpg");
 fileStamp.addHeader(new FileInputStream("image.jpg"), 50, 100, 100);
 fileStamp.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Поток, содержащий данные изображения. |
| topMargin | float | Поле вверху страницы. |
| leftMargin | float | Поля в левой части страницы. |
| rightMargin | float | Поля в правой части страницы. |

### addHeader(String imageFile, float topMargin) {#addHeader-java.lang.String-float-}
```
public void addHeader(String imageFile, float topMargin)
```


Добавляет изображение в качестве заголовка на страницы файла.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
 InpetuStream input = new FileInputStream(TestSettings.GetInputFile("test.jpg"));
 fileStamp.addHeader("image.jpg", 50);
 fileStamp.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageFile | java.lang.String | Путь к файлу изображения. |
| topMargin | float | Поле вверху страницы. |

### addHeader(String imageFile, float topMargin, float leftMargin, float rightMargin) {#addHeader-java.lang.String-float-float-float-}
```
public void addHeader(String imageFile, float topMargin, float leftMargin, float rightMargin)
```


Добавляет изображение в качестве заголовка на страницы.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
 InputStream input = new FileInputStream(TestSettings.GetInputFile("test.jpg"));
 fileStamp.addHeader("image.jpg", 50, 100, 100);
 fileStamp.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageFile | java.lang.String | Путь к файлу изображения. |
| topMargin | float | Поле вверху страницы. |
| leftMargin | float | Поля в левой части страницы. |
| rightMargin | float | Поля в правой части страницы. |

### addPageNumber(FormattedText formattedText) {#addPageNumber-com.aspose.pdf.facades.FormattedText-}
```
public void addPageNumber(FormattedText formattedText)
```


Добавляет номер страницы к странице. Номер страницы может содержать\знак #, который будет заменен номером страницы. Номер страницы помещается внизу страницы по центру горизонтально.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
  fileStamp.addPageNumber(new FormattedText("Page #"));
  fileStamp.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | Строка формата для номера страницы представлена как FormattedText. |

### addPageNumber(FormattedText formattedText, float x, float y) {#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-}
```
public void addPageNumber(FormattedText formattedText, float x, float y)
```


Добавляет номер страницы в указанную позицию на странице.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
 fileStamp.addPageNumber(new FormattedText("Page  #"), 123, 357);
 fileStamp.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) |  Форматированный текст, который представляет формат номера страницы и свойства текста. Строка формата может содержать\знак #, который будет заменен номером страницы. |
| x | float | X-координата номера страницы. |
| y | float | Координата Y номера страницы. |

### addPageNumber(FormattedText formattedText, int position) {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-}
```
public void addPageNumber(FormattedText formattedText, int position)
```


Добавляет номер страницы к страницам.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
  fileStamp.addPageNumber("Page #", PdfFileStamp.POS_UPPER_RIGHT);
  fileStamp.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) |  Объект FormattedText, который содержит формат номера страницы и свойства текста. Этот текст может содержать\# который будет заменен номером страницы. |
| position | int | Позиция, в которой номер страницы будет размещен на странице. 0-нижний средний, 1-нижний правый, 2-верхний правый, 3-боковой правый, 4-верхний средний,5-нижний левый,6-боковой левый,7-верхний левый. Вы можете использовать следующие константы: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

### addPageNumber(FormattedText formattedText, int position, float leftMargin, float rightMargin, float topMargin, float bottomMargin) {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
```
public void addPageNumber(FormattedText formattedText, int position, float leftMargin, float rightMargin, float topMargin, float bottomMargin)
```


Добавляет номер страницы к страницам документа.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
  fileStamp.addPageNumber(new FormattedText("Page #"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
  fileStamp.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | Объект FormattedText, который представляет формат номера страницы и свойства текста. |
| position | int | Позиция, в которой номер страницы будет размещен на странице. 0-нижний средний, 1-нижний правый, 2-верхний правый, 3-боковой правый, 4-верхний средний,5-нижний левый,6-боковой левый,7-верхний левый. Вы можете использовать следующие константы: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | float | Поля по левому краю страницы. |
| rightMargin | float | Поля по правому краю страницы. |
| topMargin | float | Поля по верхнему краю страницы. |
| bottomMargin | float | Поле по нижнему краю страницы. |

### addPageNumber(String formatString) {#addPageNumber-java.lang.String-}
```
public void addPageNumber(String formatString)
```


 Добавьте номер страницы в файл. Текст номера страницы может содержать\# знак, который будет заменен номером страницы. Номер страницы помещается внизу страницы по центру горизонтально.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
  fileStamp.addPageNumber("Page #");
  fileStamp.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| formatString | java.lang.String | Текст номера страницы |

### addPageNumber(String formatString, float x, float y) {#addPageNumber-java.lang.String-float-float-}
```
public void addPageNumber(String formatString, float x, float y)
```


Добавляет номер страницы в указанную позицию на странице.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
 fileStamp.addPageNumber(new FormattedText("Page  #"), 123, 357);
 fileStamp.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| formatString | java.lang.String |  Строка формата. Строка формата может содержать\знак #, который будет заменен номером страницы. |
| x | float | X-координата номера страницы. |
| y | float | Координата Y номера страницы. |

### addPageNumber(String formatString, int position) {#addPageNumber-java.lang.String-int-}
```
public void addPageNumber(String formatString, int position)
```


Добавляет номер страницы к страницам.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
  fileStamp.addPageNumber("Page #", PdfFileStamp.POS_UPPER_RIGHT);
  fileStamp.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| formatString | java.lang.String |  Формат номера страницы. Этот текст может содержать\# который будет заменен номером страницы. |
| position | int | Позиция, в которой номер страницы будет размещен на странице. 0-нижний средний, 1-нижний правый, 2-верхний правый, 3-боковой правый, 4-верхний средний,5-нижний левый,6-боковой левый,7-верхний левый. Вы можете использовать следующие константы: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

### addPageNumber(String formatString, int position, float leftMargin, float rightMargin, float topMargin, float bottomMargin) {#addPageNumber-java.lang.String-int-float-float-float-float-}
```
public void addPageNumber(String formatString, int position, float leftMargin, float rightMargin, float topMargin, float bottomMargin)
```


Добавляет номер страницы к страницам документа.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
  fileStamp.addPageNumber("Page #", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
  fileStamp.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| formatString | java.lang.String | Строка формата для номера страницы. |
| position | int | Позиция, в которой номер страницы будет размещен на странице. 0-нижний средний, 1-нижний правый, 2-верхний правый, 3-боковой правый, 4-верхний средний,5-нижний левый,6-боковой левый,7-верхний левый. Вы можете использовать следующие константы: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | float | Поля по левому краю страницы. |
| rightMargin | float | Поля по правому краю страницы. |
| topMargin | float | Поля по верхнему краю страницы. |
| bottomMargin | float | Поле по нижнему краю страницы. |

### addStamp(Stamp stamp) {#addStamp-com.aspose.pdf.facades.Stamp-}
```
public void addStamp(Stamp stamp)
```


Добавляет штамп к файлу.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
 Stamp stamp = new com.aspose.pdf.facades.Stamp();
 stamp.setOrigin(140, 400);
 stamp.setImageSize(50, 50);
 stamp.setOpacity(0.8f);
 stamp.isBackground(true);
 stamp.bindImage("image.jpg");
 fileStamp.addStamp(stamp);
 fileStamp.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| stamp | [Stamp](../../com.aspose.pdf.facades/stamp) | Штамп объект который. |

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


Закрывает открытые файлы и сохраняет изменения. Предупреждение. Если указаны входные или выходные потоки, они не закрываются методом Close().

--------------------

```
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
 //поработай немного...
 stamp.close();
```

### dispose() {#dispose--}
```
public void dispose()
```


Закрывает все ресурсы, используемые этим экземпляром.

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
java.lang.String — строковое значение
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
int — элемент ContentDisposition
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


Получает фасад документа, над которым работает.

**Возвращает:**
[IDocument](../../com.aspose.pdf/idocument) - элемент IDocument
### getInputFile() {#getInputFile--}
```
public String getInputFile()
```


Получает имя и путь входного файла.

**Возвращает:**
java.lang.String — строковое значение
### getInputStream() {#getInputStream--}
```
public InputStream getInputStream()
```


Получает входной поток.

Устарело("Используйте метод bindPdf(inputFile) для инициализации фасада.")

**Возвращает:**
java.io.InputStream — объект InputStream
### getKeepSecurity() {#getKeepSecurity--}
```
public boolean getKeepSecurity()
```


Сохраняет безопасность, если это правда. (Эта функция будет реализована в следующих версиях).

**Возвращает:**
boolean - логическое значение
### getNumberingStyle() {#getNumberingStyle--}
```
public int getNumberingStyle()
```


Получает или задает стиль нумерации страниц. Возможные значения: цифры арабские, цифры римские прописные, цифры римские строчные, буквы прописные, буквы строчные

**Возвращает:**
int - элемент стиля нумерации
### getOptimizeSize() {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```


Получает или устанавливает флаг оптимизации. Равные потоки ресурсов в результирующем файле объединяются в один объект PDF, если этот флаг установлен. Это позволяет уменьшить результирующий размер файла, но может привести к замедлению выполнения и увеличению требований к памяти. Значение по умолчанию: ложь.

**Возвращает:**
boolean - логическое значение
### getOutputFile() {#getOutputFile--}
```
public String getOutputFile()
```


Получает имя и путь выходного файла.

Obsolete("Используйте метод Save(outputFile) для получения фасадных результатов.")

**Возвращает:**
java.lang.String — строковое значение
### getOutputStream() {#getOutputStream--}
```
public OutputStream getOutputStream()
```


Получает выходной поток.

**Возвращает:**
java.io.OutputStream — объект OutputStream
### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


Получает высоту первой страницы исходного файла.

**Возвращает:**
float - плавающее значение

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
 System.out.println("Height = " + fileStamp.getPageHeight());
 fileStamp.close();
```
### getPageNumberRotation() {#getPageNumberRotation--}
```
public float getPageNumberRotation()
```


Получает поворот номера страницы. Вращение в градусах. По умолчанию 0.

**Возвращает:**
float - плавающее значение
### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


Получает ширину первой страницы во входном файле.

**Возвращает:**
float - плавающее значение

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
 System.out.println("Width = " + fileStamp.getPageWidth());
 fileStamp.close();
```
### getSaveOptions() {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```


Получает параметры сохранения, когда результат сохраняется как HttpResponse. Значение по умолчанию: пдфсавеоптионс.

**Возвращает:**
[SaveOptions](../../com.aspose.pdf/saveoptions) - Объект SaveOptions
### getStampId() {#getStampId--}
```
public int getStampId()
```


Идентификатор штампа следующего добавленного штампа (включая заголовки страниц/гуары/номера страниц).

**Возвращает:**
интервал - целочисленное значение
### getStartingNumber() {#getStartingNumber--}
```
public int getStartingNumber()
```


Получает или задает начальный номер первой страницы во входном файле. Следующие страницы будут нумероваться, начиная с этого значения.

**Возвращает:**
интервал - целочисленное значение
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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
| value | java.lang.String | Строковое значение |

### setContentDisposition(int value) {#setContentDisposition-int-}
```
public void setContentDisposition(int value)
```


Устанавливает, как содержимое будет сохранено, когда результат операции будет сохранен в объекте HttpResponse. Возможное значение: inline/attachment. По умолчанию: встроенный.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент ContentDisposition |

### setConvertTo(PdfFormat value) {#setConvertTo-com.aspose.pdf.PdfFormat-}
```
public void setConvertTo(PdfFormat value)
```


Устанавливает формат файла PDF. Файл результата будет сохранен в указанном формате. Если это свойство не указано, файл будет сохранен в формате PDF по умолчанию без преобразования.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfFormat](../../com.aspose.pdf/pdfformat) | Элемент PdfFormat |

### setInputFile(String value) {#setInputFile-java.lang.String-}
```
public void setInputFile(String value)
```


Устанавливает имя и путь входного файла.

Устарело("Используйте метод bindPdf(inputFile) для инициализации фасада.")

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setInputStream(InputStream value) {#setInputStream-java.io.InputStream-}
```
public void setInputStream(InputStream value)
```


Устанавливает входной поток.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.io.InputStream | Объект InputStream |

### setKeepSecurity(boolean value) {#setKeepSecurity-boolean-}
```
public void setKeepSecurity(boolean value)
```


Сохраняет безопасность, если это правда. (Эта функция будет реализована в следующих версиях).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setNumberingStyle(int value) {#setNumberingStyle-int-}
```
public void setNumberingStyle(int value)
```


Получает или задает стиль нумерации страниц. Возможные значения: цифры арабские, цифры римские прописные, цифры римские строчные, буквы прописные, буквы строчные

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент стиля нумерации |

### setOptimizeSize(boolean value) {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```


Получает или устанавливает флаг оптимизации. Равные потоки ресурсов в результирующем файле объединяются в один объект PDF, если этот флаг установлен. Это позволяет уменьшить результирующий размер файла, но может привести к замедлению выполнения и увеличению требований к памяти. Значение по умолчанию: ложь.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setOutputFile(String value) {#setOutputFile-java.lang.String-}
```
public void setOutputFile(String value)
```


Устанавливает имя и путь выходного файла.

Obsolete("Используйте метод Save(outputFile) для получения фасадных результатов.")

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setOutputStream(OutputStream value) {#setOutputStream-java.io.OutputStream-}
```
public void setOutputStream(OutputStream value)
```


Устанавливает или устанавливает выходной поток.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.io.OutputStream | Объект OutputStream |

### setPageNumberRotation(float value) {#setPageNumberRotation-float-}
```
public void setPageNumberRotation(float value)
```


Устанавливает поворот номера страницы. Вращение в градусах. По умолчанию 0.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | плавающее значение |

### setSaveOptions(SaveOptions value) {#setSaveOptions-com.aspose.pdf.SaveOptions-}
```
public void setSaveOptions(SaveOptions value)
```


Задает параметры сохранения, когда результат сохраняется как HttpResponse. Значение по умолчанию: пдфсавеоптионс.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [SaveOptions](../../com.aspose.pdf/saveoptions) | Объект SaveOptions |

### setStampId(int value) {#setStampId-int-}
```
public void setStampId(int value)
```


Идентификатор штампа следующего добавленного штампа (включая заголовки страниц/гуары/номера страниц).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setStartingNumber(int value) {#setStartingNumber-int-}
```
public void setStartingNumber(int value)
```


Устанавливает начальный номер для первой страницы во входном файле. Следующие страницы будут нумероваться, начиная с этого значения. Например, если для StartingNumber установлено значение 100, страницы документа будут иметь номера 100, 101, 102...

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
 fileStamp.setStartingNumber(100);
 fileStamp.addPageNumber("Page #");
 fileStamp.close();
``` |

### toString() {#toString--}
```
публичная строка toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
публичный окончательный недействительный ожидание ()
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
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
