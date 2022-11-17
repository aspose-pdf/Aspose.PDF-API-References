---
title: TextParagraphAbsorber
second_title: Aspose.PDF для справки по Java API
description: Представляет объект-поглотитель текстовых абзацев.
type: docs
weight: 381
url: /ru/java/com.aspose.pdf/textparagraphabsorber/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.TextAbsorber](../../com.aspose.pdf/textabsorber)
```
public final class TextParagraphAbsorber extends TextAbsorber
```

Представляет объект-поглотитель текстовых абзацев. Выполняет текстовый поиск и предоставляет доступ к результатам поиска через коллекцию TextParagraphAbsorber.TextParagraphs.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TextParagraphAbsorber(Rectangle[] rectangles)](#TextParagraphAbsorber-com.aspose.pdf.Rectangle---) | Инициализирует новый экземпляр TextParagraphAbsorber с коллекцией прямоугольников. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getErrors()](#getErrors--) | Список объектов TextExtractionError. |
| [getExtractionOptions()](#getExtractionOptions--) | Получает параметры извлечения текста. |
| [getRectangles()](#getRectangles--) | Получает прямоугольники, используемые TextParagraphAbsorber для поиска текстовых абзацев в документе или странице PDF. |
| [getText()](#getText--) | Получает извлеченный текст, который TextAbsorber извлекает из документа или страницы PDF. |
| [getTextParagraphs()](#getTextParagraphs--) | Получает коллекцию вхождений поиска, представленных объектами TextParagraph. |
| [getTextSearchOptions()](#getTextSearchOptions--) | Получает параметры поиска текста. |
| [hasErrors()](#hasErrors--) | Значение указывает, были ли обнаружены ошибки при извлечении текста. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setExtractionOptions(TextExtractionOptions value)](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | Задает параметры извлечения текста. |
| [setRectangles(Rectangle[] value)](#setRectangles-com.aspose.pdf.Rectangle---) | Задает прямоугольники, используемые TextParagraphAbsorber для поиска текстовых абзацев в документе или странице PDF. |
| [setTextParagraphs(TextParagraphCollection value)](#setTextParagraphs-com.aspose.pdf.TextParagraphCollection-) | Задает коллекцию вхождений поиска, представленных объектами TextParagraph. |
| [setTextSearchOptions(TextSearchOptions value)](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Задает параметры поиска текста. |
| [toString()](#toString--) |  |
| [visit(IDocument pdf)](#visit-com.aspose.pdf.IDocument-) | Извлекает текст из указанного документа |
| [visit(Page page)](#visit-com.aspose.pdf.Page-) | Выполняет поиск на указанной странице. |
| [visit(XForm form)](#visit-com.aspose.pdf.XForm-) | Извлекает текст из указанной формы XForm. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextParagraphAbsorber(Rectangle[] rectangles) {#TextParagraphAbsorber-com.aspose.pdf.Rectangle---}
```
public TextParagraphAbsorber(Rectangle[] rectangles)
```


Инициализирует новый экземпляр TextParagraphAbsorber с коллекцией прямоугольников.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangles | [Rectangle\[\]](../../com.aspose.pdf/rectangle) | Прямоугольники абзацев.

--------------------

 Поглотитель будет искать текст и возвращать абзацы, соответствующие прямоугольникам.|

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
### getRectangles() {#getRectangles--}
```
public Rectangle[] getRectangles()
```


Получает прямоугольники, используемые TextParagraphAbsorber для поиска текстовых абзацев в документе или странице PDF.

**Возвращает:**
com.aspose.pdf.Прямоугольник[] - массив прямоугольников
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
### getTextParagraphs() {#getTextParagraphs--}
```
public TextParagraphCollection getTextParagraphs()
```


Получает коллекцию вхождений поиска, представленных объектами TextParagraph.

**Возвращает:**
[TextParagraphCollection](../../com.aspose.pdf/textparagraphcollection) - Значение TextParagraphCollection
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

### setRectangles(Rectangle[] value) {#setRectangles-com.aspose.pdf.Rectangle---}
```
public void setRectangles(Rectangle[] value)
```


Задает прямоугольники, используемые TextParagraphAbsorber для поиска текстовых абзацев в документе или странице PDF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.pdf/rectangle) | прямоугольный массив |

### setTextParagraphs(TextParagraphCollection value) {#setTextParagraphs-com.aspose.pdf.TextParagraphCollection-}
```
public void setTextParagraphs(TextParagraphCollection value)
```


Задает коллекцию вхождений поиска, представленных объектами TextParagraph.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextParagraphCollection](../../com.aspose.pdf/textparagraphcollection) | Значение TextParagraphCollection |

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


Выполняет поиск на указанной странице.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Объект страницы |

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
