---
title: TextAbsorber
second_title: Aspose.PDF для справки по Java API
description: Представляет объект-поглотитель текста.
type: docs
weight: 360
url: /ru/java/com.aspose.pdf/textabsorber/
---
**Наследование:**
java.lang.Object
```
public class TextAbsorber
```

Представляет объект-поглотитель текста. Выполняет извлечение текста и предоставляет доступ к результату через объект TextAbsorber.Text.

--------------------

```
The example demonstrates how to extract text on the first PDF document page.
 
 // открыть документ
 Document doc = new Document(inFile);
 // создать объект TextAbsorber для извлечения текста
 TextAbsorber absorber = new TextAbsorber();
 // принять поглотитель для первой страницы
 doc.getPages().get(1).accept(absorber);
 // получить извлеченный текст
 String extractedText = absorber.getText();
```

--------------------

Объект TextAbsorber используется для извлечения текста из документа Pdf или страницы документа.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TextAbsorber()](#TextAbsorber--) | Инициализирует новый экземпляр TextAbsorber. |
| [TextAbsorber(TextExtractionOptions extractionOptions)](#TextAbsorber-com.aspose.pdf.TextExtractionOptions-) | Инициализирует новый экземпляр TextAbsorber с параметрами извлечения. |
| [TextAbsorber(TextExtractionOptions extractionOptions, TextSearchOptions textSearchOptions)](#TextAbsorber-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextSearchOptions-) | Инициализирует новый экземпляр TextAbsorber с параметрами извлечения и поиска текста. |
| [TextAbsorber(TextSearchOptions textSearchOptions)](#TextAbsorber-com.aspose.pdf.TextSearchOptions-) | Инициализирует новый экземпляр TextAbsorber с параметрами текстового поиска. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getErrors()](#getErrors--) | Список объектов TextExtractionError. |
| [getExtractionOptions()](#getExtractionOptions--) | Получает параметры извлечения текста. |
| [getText()](#getText--) | Получает извлеченный текст, который TextAbsorber извлекает из документа или страницы PDF. |
| [getTextSearchOptions()](#getTextSearchOptions--) | Получает параметры поиска текста. |
| [hasErrors()](#hasErrors--) | Значение указывает, были ли обнаружены ошибки при извлечении текста. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setExtractionOptions(TextExtractionOptions value)](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | Задает параметры извлечения текста. |
| [setTextSearchOptions(TextSearchOptions value)](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Задает параметры поиска текста. |
| [toString()](#toString--) |  |
| [visit(IDocument pdf)](#visit-com.aspose.pdf.IDocument-) | Извлекает текст из указанного документа |
| [visit(Page page)](#visit-com.aspose.pdf.Page-) | Извлекает текст на указанной странице |
| [visit(XForm form)](#visit-com.aspose.pdf.XForm-) | Извлекает текст из указанной формы XForm. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextAbsorber() {#TextAbsorber--}
```
public TextAbsorber()
```


Инициализирует новый экземпляр TextAbsorber.

--------------------

```
The example demonstrates how to extract text from all pages of the PDF document.
 
 // открыть документ
 Document doc = new Document(inFile);
 // создать объект TextAbsorber для извлечения текста
 TextAbsorber absorber = new TextAbsorber();
 // принять поглотитель для всех страниц документа
 doc.getPages().accept(absorber);
 // получить извлеченный текст
 String extractedText = absorber.getText();
```

--------------------

Выполняет извлечение текста и предоставляет доступ к извлеченному тексту через объект TextAbsorber.Text.

### TextAbsorber(TextExtractionOptions extractionOptions) {#TextAbsorber-com.aspose.pdf.TextExtractionOptions-}
```
public TextAbsorber(TextExtractionOptions extractionOptions)
```


Инициализирует новый экземпляр TextAbsorber с параметрами извлечения.

--------------------

```
The example demonstrates how to extract text from all pages of the PDF document.
 
 // открыть документ
 Document doc = new Document(inFile);
 // создать объект TextAbsorber для извлечения текста с форматированием
 TextAbsorber absorber = new TextAbsorber(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure));
 // принять поглотитель для всех страниц документа
 doc.getPages().accept(absorber);
 // получить извлеченный текст
 String extractedText = absorber.getText();
```

--------------------

Выполняет извлечение текста и предоставляет доступ к извлеченному тексту через объект TextAbsorber.Text.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| extractionOptions | [TextExtractionOptions](../../com.aspose.pdf/textextractionoptions) | Параметры извлечения текста

 --------------------|

### TextAbsorber(TextExtractionOptions extractionOptions, TextSearchOptions textSearchOptions) {#TextAbsorber-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextSearchOptions-}
```
public TextAbsorber(TextExtractionOptions extractionOptions, TextSearchOptions textSearchOptions)
```


Инициализирует новый экземпляр TextAbsorber с параметрами извлечения и поиска текста.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| extractionOptions | [TextExtractionOptions](../../com.aspose.pdf/textextractionoptions) | Параметры извлечения текста |
| textSearchOptions | [TextSearchOptions](../../com.aspose.pdf/textsearchoptions) | Параметры текстового поиска

--------------------

Выполняет извлечение текста и предоставляет доступ к извлеченному тексту через объект TextAbsorber.Text.|

### TextAbsorber(TextSearchOptions textSearchOptions) {#TextAbsorber-com.aspose.pdf.TextSearchOptions-}
```
public TextAbsorber(TextSearchOptions textSearchOptions)
```


Инициализирует новый экземпляр TextAbsorber с параметрами текстового поиска.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| textSearchOptions | [TextSearchOptions](../../com.aspose.pdf/textsearchoptions) | Параметры текстового поиска

--------------------

Выполняет извлечение текста и предоставляет доступ к извлеченному тексту через объект TextAbsorber.Text.|

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
### getErrors() {#getErrors--}
```
public List<TextExtractionError> getErrors()
```


Список объектов TextExtractionError. Он содержит информацию об ошибках, обнаруженных при извлечении текста. Поиск ошибок будет производиться, только если TextSearchOptions.LogTextExtractionErrors = true; И это может снизить производительность.

**Возвращает:**
java.util.List<com.aspose.pdf.TextExtractionError> — Список объектов TextExtractionError
### getExtractionOptions() {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```


Получает параметры извлечения текста.

--------------------

```
The example demonstrates how to set Pure text formatting mode and perform text extraction.
 
 // открыть документ
 Document doc = new Document(inFile);
 // создать объект TextAbsorber для извлечения текста с форматированием
 TextAbsorber absorber = new TextAbsorber();
 // установить режим форматирования чистого текста
 absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure));
 // принять поглотитель для всех страниц документа
 doc.getPages().accept(absorber);
 // получить извлеченный текст
 String extractedText = absorber.getText();
```

--------------------

Позволяет определить режим форматирования текста TextExtractionOptions во время извлечения. Режим по умолчанию — TextExtractionOptions.TextFormattingMode.Pure. 

**Возвращает:**
[TextExtractionOptions](../../com.aspose.pdf/textextractionoptions) - Значение TextExtractionOptions
### getText() {#getText--}
```
public String getText()
```


Получает извлеченный текст, который TextAbsorber извлекает из документа или страницы PDF.

**Возвращает:**
java.lang.String — строковое значение

--------------------

```
The example demonstrates how to extract text from all pages of the PDF document.
 
 // открыть документ
 Document doc = new Document(inFile);
 // создать объект TextAbsorber для извлечения текста
 TextAbsorber absorber = new TextAbsorber();
 // принять поглотитель для всех страниц документа
 doc.getPages().accept(absorber);
 // получить извлеченный текст
 String extractedText = absorber.getText();
```
### getTextSearchOptions() {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```


Получает параметры поиска текста.

Позволяет определить прямоугольник, ограничивающий извлекаемый текст. По умолчанию прямоугольник пустой. Это означает, что границы страницы определяют только область извлечения текста.

**Возвращает:**
[TextSearchOptions](../../com.aspose.pdf/textsearchoptions) - Значение TextSearchOptions
### hasErrors() {#hasErrors--}
```
public boolean hasErrors()
```


Значение указывает, были ли обнаружены ошибки при извлечении текста. Поиск ошибок будет производиться, только если TextSearchOptions.LogTextExtractionErrors = true; И это может снизить производительность.

**Возвращает:**
boolean - логическое значение
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




### setExtractionOptions(TextExtractionOptions value) {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
```
public void setExtractionOptions(TextExtractionOptions value)
```


Задает параметры извлечения текста.

--------------------

```
The example demonstrates how to set Pure text formatting mode and perform text extraction.
 
 // открыть документ
 Document doc = new Document(inFile);
 // создать объект TextAbsorber для извлечения текста с форматированием
 TextAbsorber absorber = new TextAbsorber();
 // установить режим форматирования чистого текста
 absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure));
 // принять поглотитель для всех страниц документа
 doc.getPages().accept(absorber);
 // получить извлеченный текст
 String extractedText = absorber.getText();
```

--------------------

Позволяет определить режим форматирования текста TextExtractionOptions во время извлечения. Режим по умолчанию — TextExtractionOptions.TextFormattingMode.Pure. 

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextExtractionOptions](../../com.aspose.pdf/textextractionoptions) | Значение TextExtractionOptions |

### setTextSearchOptions(TextSearchOptions value) {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
```
public void setTextSearchOptions(TextSearchOptions value)
```


Задает параметры поиска текста.

Позволяет определить прямоугольник, ограничивающий извлекаемый текст. По умолчанию прямоугольник пустой. Это означает, что границы страницы определяют только область извлечения текста.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextSearchOptions](../../com.aspose.pdf/textsearchoptions) | Значение TextSearchOptions |

### toString() {#toString--}
```
public String toString()
```




**Возвращает:**
java.lang.String
### visit(IDocument pdf) {#visit-com.aspose.pdf.IDocument-}
```
public void visit(IDocument pdf)
```


Извлекает текст из указанного документа

--------------------

```
The example demonstrates how to extract text on PDF document.
 
 // открыть документ
 Document doc = new Document(inFile);
 // создать объект TextAbsorber для извлечения текста
 TextAbsorber absorber = new TextAbsorber();
 // принять поглотитель для всех страниц документа
 absorber.visit(doc);
 // получить извлеченный текст
 String extractedText = absorber.getText();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| pdf | [IDocument](../../com.aspose.pdf/idocument) | Pdf объект документа. |

### visit(Page page) {#visit-com.aspose.pdf.Page-}
```
public void visit(Page page)
```


Извлекает текст на указанной странице

--------------------

```
The example demonstrates how to extract text on the first PDF document page.
 
 // открыть документ
 Document doc = new Document(inFile);
 // создать объект TextAbsorber для извлечения текста
 TextAbsorber absorber = new TextAbsorber();
 // принять поглотитель для всех страниц документа
 absorber.visit(doc.getPages(1));
 // получить извлеченный текст
 String extractedText = absorber.getText();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Объект страницы документа Pdf. |

### visit(XForm form) {#visit-com.aspose.pdf.XForm-}
```
public void visit(XForm form)
```


Извлекает текст из указанной формы XForm.

--------------------

```
The example demonstrates how to extract text on the first PDF document page.
 
  // открыть документ
  Document doc = new Document(inFile);
  
  // создать объект TextAbsorber для извлечения текста
  TextAbsorber absorber = new TextAbsorber();
   
  // принять поглотитель для всех страниц документа
  absorber.visit(doc.Pages().get(1).getResources().getForms().get("Xform1"));
     
  // получить извлеченный текст
  String extractedText = absorber.getText();
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| form | [XForm](../../com.aspose.pdf/xform) | Объект формы PDF. |

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
