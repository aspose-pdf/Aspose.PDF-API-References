---
title: TextBuilder
second_title: Aspose.PDF для справки по Java API
description: Добавляет текстовый объект на страницу Pdf.
type: docs
weight: 364
url: /ru/java/com.aspose.pdf/textbuilder/
---
**Наследование:**
java.lang.Object
```
public final class TextBuilder
```

Добавляет текстовый объект на страницу Pdf.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TextBuilder(Page page)](#TextBuilder-com.aspose.pdf.Page-) | Инициализирует новый экземпляр класса TextBuilder для страницы Pdf. |
| [TextBuilder(Page page, BaseOperatorCollection operatorCollection)](#TextBuilder-com.aspose.pdf.Page-com.aspose.pdf.BaseOperatorCollection-) | Инициализирует новый экземпляр класса TextBuilder для страницы Pdf. |
## Методы

| Метод | Описание |
| --- | --- |
| [appendParagraph(TextParagraph textParagraph)](#appendParagraph-com.aspose.pdf.TextParagraph-) | Добавляет текстовый абзац на страницу Pdf. |
| [appendParagraph(TextParagraph textParagraph, int rotation)](#appendParagraph-com.aspose.pdf.TextParagraph-int-) | Добавляет абзац с поворотом |
| [appendText(TextFragment textFragment)](#appendText-com.aspose.pdf.TextFragment-) | Добавляет текстовый фрагмент на страницу Pdf |
| [appendText(List<TextFragment> textFragments)](#appendText-java.util.List-com.aspose.pdf.TextFragment--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getSegmenter()](#getSegmenter--) | Получает объект TextSegmenter |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextBuilder(Page page) {#TextBuilder-com.aspose.pdf.Page-}
```
public TextBuilder(Page page)
```


Инициализирует новый экземпляр класса TextBuilder для страницы Pdf.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Объект страницы.

--------------------

TextBuilder позволяет добавлять текстовые объекты к страницам Pdf.|

### TextBuilder(Page page, BaseOperatorCollection operatorCollection) {#TextBuilder-com.aspose.pdf.Page-com.aspose.pdf.BaseOperatorCollection-}
```
public TextBuilder(Page page, BaseOperatorCollection operatorCollection)
```


Инициализирует новый экземпляр класса TextBuilder для страницы Pdf.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Объект страницы. |
| operatorCollection | [BaseOperatorCollection](../../com.aspose.pdf/baseoperatorcollection) | Коллекция оператора. |

### appendParagraph(TextParagraph textParagraph) {#appendParagraph-com.aspose.pdf.TextParagraph-}
```
public void appendParagraph(TextParagraph textParagraph)
```


Добавляет текстовый абзац на страницу Pdf.

--------------------

```
The example demonstrates how to create text paragraph object and append it to the Pdf page.
 
 Document doc = new Document(inFile);
 Page page = (Page)doc.getPages().get(1);
 // create text paragraph
 TextParagraph paragraph = new TextParagraph();
            
 // set the paragraph rectangle
 paragraph.setRectangle ( new Rectangle(100, 600, 200, 700));
 // set word wrapping options
 paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords);
 // append string lines
 paragraph.appendLine("the quick brown fox jumps over the lazy dog");
 paragraph.appendLine("line2");
 paragraph.appendLine("line3");
 // append the paragraph to the Pdf page with the TextBuilder
 TextBuilder textBuilder = new TextBuilder(page);
 textBuilder.appendParagraph(paragraph);
 // save Pdf document
 doc.save(outFile);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| textParagraph | [TextParagraph](../../com.aspose.pdf/textparagraph) | Объект текстового абзаца. |

### appendParagraph(TextParagraph textParagraph, int rotation) {#appendParagraph-com.aspose.pdf.TextParagraph-int-}
```
public void appendParagraph(TextParagraph textParagraph, int rotation)
```


Добавляет абзац с поворотом

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| textParagraph | [TextParagraph](../../com.aspose.pdf/textparagraph) | Объект TextParagraph |
| rotation | int | целое значение |

### appendText(TextFragment textFragment) {#appendText-com.aspose.pdf.TextFragment-}
```
public void appendText(TextFragment textFragment)
```


Добавляет текстовый фрагмент на страницу Pdf

--------------------

```
The example demonstrates how to create text fragment object, customize it's text segments and append it to the Pdf page.
 
 Document doc = new Document(inFile);
 Page page = (Page)doc.getPages().get(1);
 // create text fragment
 TextFragment tf = new TextFragment("main text");
 tf.Position = new Position(100, 600);
 // set it's text properties
 tf.getTextState().setFontSize ( 5);
 tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman"));
 tf.getTextState().setBackgroundColor ( Color.GREY);
 tf.getTextState().setForegroundColor ( Color.Red);
 // add one more segment to text fragment's Segments collection
 TextSegment segment2 = new TextSegment();
 segment2.setText ( "another segment");
 tf.getSegments.add(segment2);
 // create TextBuilder object
 TextBuilder builder = new TextBuilder(page);
 // append the text fragment to the Pdf page
 builder.appendText(tf);
 //save document
 doc.save(outFile);
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| textFragment | [TextFragment](../../com.aspose.pdf/textfragment) | Текстовый фрагмент объекта. |

### appendText(List<TextFragment> textFragments) {#appendText-java.util.List-com.aspose.pdf.TextFragment--}
```
public final void appendText(List<TextFragment> textFragments)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| textFragments | java.util.List<com.aspose.pdf.TextFragment> |  |

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
### getSegmenter() {#getSegmenter--}
```
public TextSegmenter getSegmenter()
```


Получает объект TextSegmenter

**Возвращает:**
[TextSegmenter](../../com.aspose.pdf.engine.commondata.text.segmenting/textsegmenter) - Объект TextSegmenter
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
