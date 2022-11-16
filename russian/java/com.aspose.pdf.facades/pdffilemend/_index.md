---
title: PdfFileMend
second_title: Aspose.PDF для справки по Java API
description: Представляет класс для добавления текстов и изображений на страницы существующего документа PDF.
type: docs
weight: 42
url: /ru/java/com.aspose.pdf.facades/pdffilemend/
---
**Наследование:**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade)
```
public final class PdfFileMend extends SaveableFacade
```

Представляет класс для добавления текстов и изображений на страницы существующего документа PDF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfFileMend()](#PdfFileMend--) | Конструктор. |
| [PdfFileMend(String inputFileName, String outputFileName)](#PdfFileMend-java.lang.String-java.lang.String-) | Конструктор. |
| [PdfFileMend(InputStream inputStream, OutputStream outputStream)](#PdfFileMend-java.io.InputStream-java.io.OutputStream-) | Конструктор. |
| [PdfFileMend(System.IO.Stream inputStream, System.IO.Stream outputStream)](#PdfFileMend-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | Конструктор. |
| [PdfFileMend(IDocument document)](#PdfFileMend-com.aspose.pdf.IDocument-) | Инициализирует новый объект PdfFileMend на основе документа. |
| [PdfFileMend(IDocument document, String outputFileName)](#PdfFileMend-com.aspose.pdf.IDocument-java.lang.String-) | Инициализирует новый объект PdfFileMend на основе документа. |
| [PdfFileMend(IDocument document, System.IO.Stream outputStream)](#PdfFileMend-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-) | Инициализирует новый объект PdfFileMend на основе документа. |
## Методы

| Метод | Описание |
| --- | --- |
| [addImage(InputStream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)](#addImage-java.io.InputStream-int-float-float-float-float-) | Добавляет изображение на указанную страницу PDF-документа по указанным координатам. |
| [addImage(InputStream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, CompositingParameters compositingParameters)](#addImage-java.io.InputStream-int-float-float-float-float-com.aspose.pdf.CompositingParameters-) | Добавляет изображение на указанную страницу PDF-документа по указанным координатам. |
| [addImage(InputStream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)](#addImage-java.io.InputStream-int---float-float-float-float-) | Добавляет изображение на указанные страницы документа PDF в указанных координатах. |
| [addImage(InputStream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, CompositingParameters compositingParameters)](#addImage-java.io.InputStream-int---float-float-float-float-com.aspose.pdf.CompositingParameters-) | Добавляет изображение на указанные страницы документа PDF в указанных координатах. |
| [addImage(String imageName, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)](#addImage-java.lang.String-int-float-float-float-float-) | Добавляет изображение на указанную страницу PDF-документа по указанным координатам. |
| [addImage(String imageName, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, CompositingParameters compositingParameters)](#addImage-java.lang.String-int-float-float-float-float-com.aspose.pdf.CompositingParameters-) | Добавляет изображение на указанную страницу PDF-документа по указанным координатам. |
| [addImage(String imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)](#addImage-java.lang.String-int---float-float-float-float-) | Добавляет изображение на указанные страницы документа PDF в указанных координатах. |
| [addImage(String imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, CompositingParameters compositingParameters)](#addImage-java.lang.String-int---float-float-float-float-com.aspose.pdf.CompositingParameters-) | Добавляет изображение на указанные страницы документа PDF в указанных координатах. |
| [addText(FormattedText text, int pageNum, float lowerLeftX, float lowerLeftY)](#addText-com.aspose.pdf.facades.FormattedText-int-float-float-) | Не реализованы. |
| [addText(FormattedText text, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)](#addText-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | Не реализованы. |
| [addText(FormattedText text, Integer[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)](#addText-com.aspose.pdf.facades.FormattedText-java.lang.Integer---float-float-float-float-) | Не реализованы. |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | Инициализирует фасад. |
| [bindPdf(InputStream srcStream)](#bindPdf-java.io.InputStream-) | Инициализирует фасад. |
| [bindPdf(InputStream srcStream, String password)](#bindPdf-java.io.InputStream-java.lang.String-) | Инициализирует фасад. |
| [bindPdf(String srcFile)](#bindPdf-java.lang.String-) | Инициализирует фасад. |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | Инициализирует фасад. |
| [close()](#close--) | Закрывает объект PdfFileMend. |
| [dispose()](#dispose--) | Закрывает объект PdfFileMend. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | Получает документ, над которым работает PdfFileMend. |
| [getInputFile()](#getInputFile--) | Получает входной файл. |
| [getInputStream()](#getInputStream--) | Получает входной поток. |
| [getOutputFile()](#getOutputFile--) | Получает выходной файл. |
| [getOutputStream()](#getOutputStream--) | Получает выходной поток. |
| [getTextPositioningMode()](#getTextPositioningMode--) | Получает стратегию позиционирования текста. |
| [getWrapMode()](#getWrapMode--) | Получает алгоритм переноса слов. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream destStream)](#save-java.io.OutputStream-) | Сохраняет документ PDF в указанный файл. |
| [save(String destFile)](#save-java.lang.String-) | Сохраняет документ PDF в указанный файл. |
| [setInputFile(String value)](#setInputFile-java.lang.String-) |  |
| [setInputStream(InputStream value)](#setInputStream-java.io.InputStream-) | Устанавливает входной поток. |
| [setOutputFile(String value)](#setOutputFile-java.lang.String-) | Устанавливает выходной файл. |
| [setOutputStream(OutputStream value)](#setOutputStream-java.io.OutputStream-) | Этот метод устарел. |
| [setTextPositioningMode(int value)](#setTextPositioningMode-int-) | Задает стратегию позиционирования текста. |
| [setWordWrap(boolean value)](#setWordWrap-boolean-) | Задает логическое значение, указывающее перенос слов в методах AddText. |
| [setWrapMode(int value)](#setWrapMode-int-) | Устанавливает алгоритм переноса слов. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfFileMend() {#PdfFileMend--}
```
public PdfFileMend()
```


Конструктор.

### PdfFileMend(String inputFileName, String outputFileName) {#PdfFileMend-java.lang.String-java.lang.String-}
```
public PdfFileMend(String inputFileName, String outputFileName)
```


Конструктор.

Obsolete("Использовать конструктор без адресата")

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputFileName | java.lang.String | Введите имя файла PDF. |
| outputFileName | java.lang.String | Выходное имя файла PDF. |

### PdfFileMend(InputStream inputStream, OutputStream outputStream) {#PdfFileMend-java.io.InputStream-java.io.OutputStream-}
```
public PdfFileMend(InputStream inputStream, OutputStream outputStream)
```


Конструктор. Obsolete("Использовать конструктор без адресата")

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | java.io.InputStream | Входной поток PDF. |
| outputStream | java.io.OutputStream | Выходной PDF-поток. |

### PdfFileMend(System.IO.Stream inputStream, System.IO.Stream outputStream) {#PdfFileMend-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public PdfFileMend(System.IO.Stream inputStream, System.IO.Stream outputStream)
```


Конструктор.

Obsolete("Использовать конструктор без адресата")

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputStream | com.aspose.ms.System.IO.Stream | Входной поток PDF. |
| outputStream | com.aspose.ms.System.IO.Stream | Выходной PDF-поток. |

### PdfFileMend(IDocument document) {#PdfFileMend-com.aspose.pdf.IDocument-}
```
public PdfFileMend(IDocument document)
```


Инициализирует новый объект PdfFileMend на основе документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ пдф. |

### PdfFileMend(IDocument document, String outputFileName) {#PdfFileMend-com.aspose.pdf.IDocument-java.lang.String-}
```
public PdfFileMend(IDocument document, String outputFileName)
```


Инициализирует новый объект PdfFileMend на основе документа.

Obsolete("Использовать конструктор без адресата")

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ пдф. |
| outputFileName | java.lang.String | Выходное имя файла PDF. |

### PdfFileMend(IDocument document, System.IO.Stream outputStream) {#PdfFileMend-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-}
```
public PdfFileMend(IDocument document, System.IO.Stream outputStream)
```


Инициализирует новый объект PdfFileMend на основе документа.

Obsolete("Использовать конструктор без адресата")

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Документ пдф. |
| outputStream | com.aspose.ms.System.IO.Stream | Выходной PDF-поток. |

### addImage(InputStream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY) {#addImage-java.io.InputStream-int-float-float-float-float-}
```
public boolean addImage(InputStream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)
```


Добавляет изображение на указанную страницу PDF-документа по указанным координатам.

--------------------

```
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
 InputStream stream = new FileInputStream("picture.jpg"))
 mendor.addImage(stream, 1, 10, 10, 100, 100);
 mendor.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageStream | java.io.InputStream | Входной поток изображений. |
| pageNum | int | Номер страницы, на которую будет помещено изображение. |
| lowerLeftX | float | Нижний левый x прямоугольника изображения. |
| lowerLeftY | float | Нижний левый угол y прямоугольника изображения. |
| upperRightX | float | Верхний правый x прямоугольника изображения. |
| upperRightY | float | Верхний правый угол y прямоугольника изображения. |

**Возвращает:**
boolean - True, если успех false, в противном случае.
### addImage(InputStream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, CompositingParameters compositingParameters) {#addImage-java.io.InputStream-int-float-float-float-float-com.aspose.pdf.CompositingParameters-}
```
public boolean addImage(InputStream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```


Добавляет изображение на указанную страницу PDF-документа по указанным координатам.

--------------------

```
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
 InputStream stream = new FileInputStream("picture.jpg"))
 mendor.addImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
 mendor.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageStream | java.io.InputStream | Входной поток изображений. |
| pageNum | int | Номер страницы, на которую будет помещено изображение. |
| lowerLeftX | float | Нижний левый x прямоугольника изображения. |
| lowerLeftY | float | Нижний левый угол y прямоугольника изображения. |
| upperRightX | float | Верхний правый x прямоугольника изображения. |
| upperRightY | float | Верхний правый угол y прямоугольника изображения. |
| compositingParameters | [CompositingParameters](../../com.aspose.pdf/compositingparameters) | Параметры компоновки графики для изображения. |

**Возвращает:**
boolean - True, если успех false, в противном случае.
### addImage(InputStream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY) {#addImage-java.io.InputStream-int---float-float-float-float-}
```
public boolean addImage(InputStream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)
```


Добавляет изображение на указанные страницы документа PDF в указанных координатах.

--------------------

```
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
 InputStream stream = new FileInputStream("picture.jpg")
     mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100);
 mendor.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageStream | java.io.InputStream | Входной поток изображений. |
| pageNums | int[] | Количество страниц, которые получат изображение. |
| lowerLeftX | float | Нижний левый x прямоугольника изображения. |
| lowerLeftY | float | Нижний левый угол y прямоугольника изображения. |
| upperRightX | float | Верхний правый x прямоугольника изображения. |
| upperRightY | float | Верхний правый угол y прямоугольника изображения. |

**Возвращает:**
boolean - True, если успех false, в противном случае.
### addImage(InputStream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, CompositingParameters compositingParameters) {#addImage-java.io.InputStream-int---float-float-float-float-com.aspose.pdf.CompositingParameters-}
```
public boolean addImage(InputStream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```


Добавляет изображение на указанные страницы документа PDF в указанных координатах.

--------------------

```
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
 InputStream stream = new FileInputStream("picture.jpg")
     mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
 mendor.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageStream | java.io.InputStream | Входной поток изображений. |
| pageNums | int[] | Количество страниц, которые получат изображение. |
| lowerLeftX | float | Нижний левый x прямоугольника изображения. |
| lowerLeftY | float | Нижний левый угол y прямоугольника изображения. |
| upperRightX | float | Верхний правый x прямоугольника изображения. |
| upperRightY | float | Верхний правый угол y прямоугольника изображения. |
| compositingParameters | [CompositingParameters](../../com.aspose.pdf/compositingparameters) | Параметры компоновки графики для изображений. |

**Возвращает:**
boolean - True, если успех false, в противном случае.
### addImage(String imageName, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY) {#addImage-java.lang.String-int-float-float-float-float-}
```
public boolean addImage(String imageName, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)
```


Добавляет изображение на указанную страницу PDF-документа по указанным координатам.

--------------------

```
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
 mendor.addImage("picture.jpg", 1, 10, 10, 100, 100);
 mendor.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageName | java.lang.String | Путь к входному файлу изображения. |
| pageNum | int | Номер страницы, на которую будет помещено изображение. |
| lowerLeftX | float | Нижний левый x прямоугольника изображения. |
| lowerLeftY | float | Нижний левый угол y прямоугольника изображения. |
| upperRightX | float | Верхний правый x прямоугольника изображения. |
| upperRightY | float | Верхний правый угол y прямоугольника изображения. |

**Возвращает:**
boolean - True, если успех false, в противном случае.
### addImage(String imageName, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, CompositingParameters compositingParameters) {#addImage-java.lang.String-int-float-float-float-float-com.aspose.pdf.CompositingParameters-}
```
public boolean addImage(String imageName, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```


Добавляет изображение на указанную страницу PDF-документа по указанным координатам.

--------------------

```
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
 mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
 mendor.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageName | java.lang.String | Путь к входному файлу изображения. |
| pageNum | int | Номер страницы, на которую будет помещено изображение. |
| lowerLeftX | float | Нижний левый x прямоугольника изображения. |
| lowerLeftY | float | Нижний левый угол y прямоугольника изображения. |
| upperRightX | float | Верхний правый x прямоугольника изображения. |
| upperRightY | float | Верхний правый угол y прямоугольника изображения. |
| compositingParameters | [CompositingParameters](../../com.aspose.pdf/compositingparameters) | Параметры компоновки графики для изображений. |

**Возвращает:**
boolean - True, если успех false, в противном случае.
### addImage(String imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY) {#addImage-java.lang.String-int---float-float-float-float-}
```
public boolean addImage(String imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)
```


Добавляет изображение на указанные страницы документа PDF в указанных координатах.

--------------------

```
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
 mendor.addImage("picture.jpg", 1, 10, 10, 100, 100);
 mendor.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageName | java.lang.String | Путь к входному файлу изображения. |
| pageNums | int[] | Количество страниц, которые получат изображение. |
| lowerLeftX | float | Нижний левый x прямоугольника изображения. |
| lowerLeftY | float | Нижний левый угол y прямоугольника изображения. |
| upperRightX | float | Верхний правый x прямоугольника изображения. |
| upperRightY | float | Верхний правый угол y прямоугольника изображения. |

**Возвращает:**
boolean - True, если успех false, в противном случае.
### addImage(String imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, CompositingParameters compositingParameters) {#addImage-java.lang.String-int---float-float-float-float-com.aspose.pdf.CompositingParameters-}
```
public boolean addImage(String imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```


Добавляет изображение на указанные страницы документа PDF в указанных координатах.

--------------------

```
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
 mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
 mendor.close();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| imageName | java.lang.String | Путь к входному файлу изображения. |
| pageNums | int[] | Количество страниц, которые получат изображение. |
| lowerLeftX | float | Нижний левый x прямоугольника изображения. |
| lowerLeftY | float | Нижний левый угол y прямоугольника изображения. |
| upperRightX | float | Верхний правый x прямоугольника изображения. |
| upperRightY | float | Верхний правый угол y прямоугольника изображения. |
| compositingParameters | [CompositingParameters](../../com.aspose.pdf/compositingparameters) | Параметры компоновки графики для изображений. |

**Возвращает:**
boolean - True, если успех false, в противном случае.
### addText(FormattedText text, int pageNum, float lowerLeftX, float lowerLeftY) {#addText-com.aspose.pdf.facades.FormattedText-int-float-float-}
```
public boolean addText(FormattedText text, int pageNum, float lowerLeftX, float lowerLeftY)
```


Не реализованы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | Объект форматированного текста. |
| pageNum | int | Номер страницы. |
| lowerLeftX | float | Нижняя левая координата X. |
| lowerLeftY | float | Нижняя левая координата Y. |

**Возвращает:**
boolean - True, если текст был успешно добавлен.
### addText(FormattedText text, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY) {#addText-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
```
public boolean addText(FormattedText text, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)
```


Не реализованы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | Объект форматированного текста. |
| pageNum | int | Номер страницы. |
| lowerLeftX | float | Нижняя левая координата X. |
| lowerLeftY | float | Нижняя левая координата Y. |
| upperRightX | float | Верхняя правая координата X. |
| upperRightY | float | Верхняя правая координата Y. |

**Возвращает:**
boolean - True, если текст был успешно добавлен.
### addText(FormattedText text, Integer[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY) {#addText-com.aspose.pdf.facades.FormattedText-java.lang.Integer---float-float-float-float-}
```
public boolean addText(FormattedText text, Integer[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)
```


Не реализованы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | Объект форматированного текста. |
| pageNums | java.lang.Integer[] | Массив номеров страниц. |
| lowerLeftX | float | Нижняя левая координата X. |
| lowerLeftY | float | Нижняя левая координата Y. |
| upperRightX | float | Верхняя правая координата X. |
| upperRightY | float | Верхняя правая координата Y. |

**Возвращает:**
boolean - True, если текст был успешно добавлен.
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


Закрывает объект PdfFileMend.

### dispose() {#dispose--}
```
public void dispose()
```


Закрывает объект PdfFileMend. Этот метод устарел, вместо него используйте close().

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


Получает документ, над которым работает PdfFileMend.

**Возвращает:**
[IDocument](../../com.aspose.pdf/idocument) - Объект IDocument
### getInputFile() {#getInputFile--}
```
public String getInputFile()
```


Получает входной файл.

**Возвращает:**
java.lang.String — строковое значение
### getInputStream() {#getInputStream--}
```
public InputStream getInputStream()
```


Получает входной поток.

**Возвращает:**
java.io.InputStream — входной поток.
### getOutputFile() {#getOutputFile--}
```
public String getOutputFile()
```


Получает выходной файл.

**Возвращает:**
java.lang.String — строковое значение
### getOutputStream() {#getOutputStream--}
```
public OutputStream getOutputStream()
```


Получает выходной поток.

**Возвращает:**
java.io.OutputStream — поток вывода.
### getTextPositioningMode() {#getTextPositioningMode--}
```
public int getTextPositioningMode()
```


Получает стратегию позиционирования текста. PositioningMode Режим по умолчанию — Legacy.

**Возвращает:**
int — элемент PositioningMode
### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Получает алгоритм переноса слов.

**Возвращает:**
int - значение WordWrapMode
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


Сохраняет документ PDF в указанный файл.

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

### setInputFile(String value) {#setInputFile-java.lang.String-}
```
public void setInputFile(String value)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setInputStream(InputStream value) {#setInputStream-java.io.InputStream-}
```
public void setInputStream(InputStream value)
```


Устанавливает входной поток.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.io.InputStream | входной поток. |

### setOutputFile(String value) {#setOutputFile-java.lang.String-}
```
public void setOutputFile(String value)
```


Устанавливает выходной файл.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setOutputStream(OutputStream value) {#setOutputStream-java.io.OutputStream-}
```
public void setOutputStream(OutputStream value)
```


Этот метод устарел. Используйте метод Save(outputStream) для получения результатов фасада.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.io.OutputStream | выходной поток. |

### setTextPositioningMode(int value) {#setTextPositioningMode-int-}
```
public void setTextPositioningMode(int value)
```


Задает стратегию позиционирования текста. PositioningMode Режим по умолчанию — Legacy.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент PositioningMode |

### setWordWrap(boolean value) {#setWordWrap-boolean-}
```
public void setWordWrap(boolean value)
```


Задает логическое значение, указывающее перенос слов в методах AddText. Если значение равно true, текст в FormattedText будет переноситься по словам. По умолчанию значение равно false.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Устанавливает алгоритм переноса слов.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент WordWrapMode |

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
