---
title: IPdfFileStamp
second_title: Aspose.PDF для справки по Java API
description: интерфейс для добавления штампов, водяных знаков или фона в файлы PDF.
type: docs
weight: 71
url: /ru/java/com.aspose.pdf.facades/ipdffilestamp/
---
```
public interface IPdfFileStamp
```

интерфейс для добавления штампов (водяных знаков или фона) в файлы PDF.
## Поля

| Поле | Описание |
| --- | --- |
| [POS_BOTTOM_LEFT](#POS-BOTTOM-LEFT) | Нижнее левое положение. |
| [POS_BOTTOM_MIDDLE](#POS-BOTTOM-MIDDLE) | Нижнее среднее положение. |
| [POS_BOTTOM_RIGHT](#POS-BOTTOM-RIGHT) | Нижнее правое положение. |
| [POS_SIDES_LEFT](#POS-SIDES-LEFT) | Левое положение. |
| [POS_SIDES_RIGHT](#POS-SIDES-RIGHT) | Правильное положение. |
| [POS_UPPER_LEFT](#POS-UPPER-LEFT) | Верхнее пусть положение. |
| [POS_UPPER_MIDDLE](#POS-UPPER-MIDDLE) | Верхнее среднее положение. |
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
| [close()](#close--) | Закрывает открытые файлы и сохраняет изменения. |
| [dispose()](#dispose--) | Закрывает открытые файлы и сохраняет изменения. |
| [getAttachmentName()](#getAttachmentName--) | Получает имя вложения, когда результат операции сохраняется в объектах HttpResponse как вложение. |
| [getContentDisposition()](#getContentDisposition--) | Получает способ хранения содержимого при сохранении результата операции в объекте HttpResponse. |
| [getDocument()](#getDocument--) | Получает документ, над которым работает PdfFileStamp. |
| [getInputFile()](#getInputFile--) | Получает имя и путь входного файла. |
| [getInputStream()](#getInputStream--) | Получает входной поток. |
| [getKeepSecurity()](#getKeepSecurity--) | Сохраняет безопасность, если это правда. |
| [getOutputFile()](#getOutputFile--) | Получает имя и путь выходного файла. |
| [getOutputStream()](#getOutputStream--) | Получает выходной поток. |
| [getPageHeight()](#getPageHeight--) | Получает высоту первой страницы исходного файла. |
| [getPageNumberRotation()](#getPageNumberRotation--) | Получает поворот номера страницы. |
| [getPageWidth()](#getPageWidth--) | Получает ширину первой страницы во входном файле. |
| [getSaveOptions()](#getSaveOptions--) | Получает параметры сохранения, когда результат сохраняется как HttpResponse. |
| [getStartingNumber()](#getStartingNumber--) | Получает или задает начальный номер первой страницы во входном файле. |
| [setAttachmentName(String value)](#setAttachmentName-java.lang.String-) | Задает имя вложения, когда результат операции сохраняется в объектах HttpResponse как вложение. |
| [setContentDisposition(int value)](#setContentDisposition-int-) | Устанавливает, как содержимое будет сохранено, когда результат операции будет сохранен в объекте HttpResponse. |
| [setConvertTo(PdfFormat value)](#setConvertTo-com.aspose.pdf.PdfFormat-) | Устанавливает формат файла PDF. |
| [setInputFile(String value)](#setInputFile-java.lang.String-) | Устанавливает имя и путь входного файла. |
| [setInputStream(InputStream value)](#setInputStream-java.io.InputStream-) | Устанавливает входной поток. |
| [setKeepSecurity(boolean value)](#setKeepSecurity-boolean-) | Установить сохранение безопасности |
| [setOutputFile(String value)](#setOutputFile-java.lang.String-) | Устанавливает имя и путь выходного файла. |
| [setOutputStream(OutputStream value)](#setOutputStream-java.io.OutputStream-) | Устанавливает или устанавливает выходной поток. |
| [setPageNumberRotation(float value)](#setPageNumberRotation-float-) | Устанавливает поворот номера страницы. |
| [setSaveOptions(SaveOptions value)](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Задает параметры сохранения, когда результат сохраняется как HttpResponse. |
| [setStartingNumber(int value)](#setStartingNumber-int-) | Устанавливает начальный номер для первой страницы во входном файле. |
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

### addFooter(FormattedText formattedText, float bottomMargin) {#addFooter-com.aspose.pdf.facades.FormattedText-float-}
```
public abstract void addFooter(FormattedText formattedText, float bottomMargin)
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
public abstract void addFooter(FormattedText formattedText, float bottomMargin, float leftMargin, float rightMargin)
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
public abstract void addFooter(InputStream imageStream, float bottomMargin)
```


Добавляет изображение в качестве нижнего колонтитула страницы.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
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
public abstract void addFooter(InputStream imageStream, float bottomMargin, float leftMargin, float rightMargin)
```


Добавляет изображение в качестве нижнего колонтитула страницы.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
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
public abstract void addFooter(String imageFile, float bottomMargin)
```


Добавляет изображение в качестве нижнего колонтитула на страницы документа.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
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
public abstract void addFooter(String imageFile, float bottomMargin, float leftMargin, float rightMargin)
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
public abstract void addHeader(FormattedText formattedText, float topMargin)
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
public abstract void addHeader(FormattedText formattedText, float topMargin, float leftMargin, float rightMargin)
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
public abstract void addHeader(InputStream imageStream, float topMargin)
```


Добавляет изображение в качестве заголовка на страницы.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
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
public abstract void addHeader(InputStream inputStream, float topMargin, float leftMargin, float rightMargin)
```


Добавляет изображение вверху страницы.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
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
public abstract void addHeader(String imageFile, float topMargin)
```


Добавляет изображение в качестве заголовка на страницы файла.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
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
public abstract void addHeader(String imageFile, float topMargin, float leftMargin, float rightMargin)
```


Добавляет изображение в качестве заголовка на страницы.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
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
public abstract void addPageNumber(FormattedText formattedText)
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
public abstract void addPageNumber(FormattedText formattedText, float x, float y)
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
public abstract void addPageNumber(FormattedText formattedText, int position)
```


Добавляет номер страницы к страницам.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
 fileStamp.addPageNumber("Page #", PdfFileStamp.PosUpperRight);
 fileStamp.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) |  Объект FormattedText, который содержит формат номера страницы и свойства текста. Этот текст может содержать\# который будет заменен номером страницы. |
| position | int | Позиция, в которой номер страницы будет размещен на странице. 0-нижний средний, 1-нижний правый, 2-верхний правый, 3-боковой правый, 4-верхний средний,5-нижний левый,6-боковой левый,7-верхний левый. Вы можете использовать следующие константы: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

### addPageNumber(FormattedText formattedText, int position, float leftMargin, float rightMargin, float topMargin, float bottomMargin) {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
```
public abstract void addPageNumber(FormattedText formattedText, int position, float leftMargin, float rightMargin, float topMargin, float bottomMargin)
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
public abstract void addPageNumber(String formatString)
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
public abstract void addPageNumber(String formatString, float x, float y)
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
public abstract void addPageNumber(String formatString, int position)
```


Добавляет номер страницы к страницам.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
 fileStamp.addPageNumber("Page #", PdfFileStamp.PosUpperRight);
 fileStamp.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| formatString | java.lang.String |  Формат номера страницы. Этот текст может содержать\# который будет заменен номером страницы. |
| position | int | Позиция, в которой номер страницы будет размещен на странице. 0-нижний средний, 1-нижний правый, 2-верхний правый, 3-боковой правый, 4-верхний средний,5-нижний левый,6-боковой левый,7-верхний левый. Вы можете использовать следующие константы: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

### addPageNumber(String formatString, int position, float leftMargin, float rightMargin, float topMargin, float bottomMargin) {#addPageNumber-java.lang.String-int-float-float-float-float-}
```
public abstract void addPageNumber(String formatString, int position, float leftMargin, float rightMargin, float topMargin, float bottomMargin)
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
public abstract void addStamp(Stamp stamp)
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

### close() {#close--}
```
public abstract void close()
```


Закрывает открытые файлы и сохраняет изменения. Предупреждение. Если указаны входные или выходные потоки, они не закрываются методом Close().

--------------------

```
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
 // поработай немного...
 stamp.close();
```

### dispose() {#dispose--}
```
public abstract void dispose()
```


Закрывает открытые файлы и сохраняет изменения. Предупреждение. Если указаны входные или выходные потоки, они не закрываются методом Close().

--------------------

```
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
 // поработай немного...
 stamp.dispose();
```

Этот метод устарел, вместо него используйте close().

### getAttachmentName() {#getAttachmentName--}
```
public abstract String getAttachmentName()
```


Получает имя вложения, когда результат операции сохраняется в объектах HttpResponse как вложение.

**Возвращает:**
java.lang.String — строковое значение
### getContentDisposition() {#getContentDisposition--}
```
public abstract int getContentDisposition()
```


Получает способ хранения содержимого при сохранении результата операции в объекте HttpResponse. Возможное значение: inline/attachment. По умолчанию: встроенный.

**Возвращает:**
int — элемент ContentDisposition
### getDocument() {#getDocument--}
```
public abstract IDocument getDocument()
```


Получает документ, над которым работает PdfFileStamp.

**Возвращает:**
[IDocument](../../com.aspose.pdf/idocument) - Объект IDocument
### getInputFile() {#getInputFile--}
```
public abstract String getInputFile()
```


Получает имя и путь входного файла.

**Возвращает:**
java.lang.String — строковый объект
### getInputStream() {#getInputStream--}
```
public abstract InputStream getInputStream()
```


Получает входной поток.

**Возвращает:**
java.io.InputStream — объект InputStream
### getKeepSecurity() {#getKeepSecurity--}
```
public abstract boolean getKeepSecurity()
```


Сохраняет безопасность, если это правда. (Эта функция будет реализована в следующих версиях).

**Возвращает:**
boolean - логическое значение
### getOutputFile() {#getOutputFile--}
```
public abstract String getOutputFile()
```


Получает имя и путь выходного файла.

**Возвращает:**
java.lang.String — строковый объект
### getOutputStream() {#getOutputStream--}
```
public abstract OutputStream getOutputStream()
```


Получает выходной поток.

**Возвращает:**
java.io.OutputStream — объект OutputStream
### getPageHeight() {#getPageHeight--}
```
public abstract float getPageHeight()
```


Получает высоту первой страницы исходного файла.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
 System.out.println("Height = " + fileStamp.getPageHeight());
 fileStamp.close();
```

**Возвращает:**
float - плавающее значение
### getPageNumberRotation() {#getPageNumberRotation--}
```
public abstract float getPageNumberRotation()
```


Получает поворот номера страницы. Вращение в градусах. По умолчанию 0.

**Возвращает:**
float - плавающее значение
### getPageWidth() {#getPageWidth--}
```
public abstract float getPageWidth()
```


Получает ширину первой страницы во входном файле.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
 System.out.println("Width = " + fileStamp.getPageWidth());
 fileStamp.close();
```

**Возвращает:**
float - плавающее значение
### getSaveOptions() {#getSaveOptions--}
```
public abstract SaveOptions getSaveOptions()
```


Получает параметры сохранения, когда результат сохраняется как HttpResponse. Значение по умолчанию: пдфсавеоптионс.

**Возвращает:**
[SaveOptions](../../com.aspose.pdf/saveoptions) - Объект SaveOptions
### getStartingNumber() {#getStartingNumber--}
```
public abstract int getStartingNumber()
```


Получает или задает начальный номер первой страницы во входном файле. Следующие страницы будут нумероваться, начиная с этого значения.

**Возвращает:**
интервал - целочисленное значение
### setAttachmentName(String value) {#setAttachmentName-java.lang.String-}
```
public abstract void setAttachmentName(String value)
```


Задает имя вложения, когда результат операции сохраняется в объектах HttpResponse как вложение.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

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

### setInputFile(String value) {#setInputFile-java.lang.String-}
```
public abstract void setInputFile(String value)
```


Устанавливает имя и путь входного файла.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setInputStream(InputStream value) {#setInputStream-java.io.InputStream-}
```
public abstract void setInputStream(InputStream value)
```


Устанавливает входной поток.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.io.InputStream | Объект InputStream |

### setKeepSecurity(boolean value) {#setKeepSecurity-boolean-}
```
public abstract void setKeepSecurity(boolean value)
```


Установить сохранение безопасности

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setOutputFile(String value) {#setOutputFile-java.lang.String-}
```
public abstract void setOutputFile(String value)
```


Устанавливает имя и путь выходного файла.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковый объект |

### setOutputStream(OutputStream value) {#setOutputStream-java.io.OutputStream-}
```
public abstract void setOutputStream(OutputStream value)
```


Устанавливает или устанавливает выходной поток.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.io.OutputStream | Объект OutputStream |

### setPageNumberRotation(float value) {#setPageNumberRotation-float-}
```
public abstract void setPageNumberRotation(float value)
```


Устанавливает поворот номера страницы. Вращение в градусах. По умолчанию 0.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | плавающее значение |

### setSaveOptions(SaveOptions value) {#setSaveOptions-com.aspose.pdf.SaveOptions-}
```
public abstract void setSaveOptions(SaveOptions value)
```


Задает параметры сохранения, когда результат сохраняется как HttpResponse. Значение по умолчанию: пдфсавеоптионс.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [SaveOptions](../../com.aspose.pdf/saveoptions) | Значение SaveOptions |

### setStartingNumber(int value) {#setStartingNumber-int-}
```
public abstract void setStartingNumber(int value)
```


Устанавливает начальный номер для первой страницы во входном файле. Следующие страницы будут нумероваться, начиная с этого значения. Например, если для StartingNumber установлено значение 100, страницы документа будут иметь номера 100, 101, 102...

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
 fileStamp.setStartingNumber(100);
 fileStamp.addPageNumber("Page #");
 fileStamp.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |
