---
title: TextSegment
second_title: Aspose.PDF для справки по Java API
description: Представляет сегмент текста Pdf.
type: docs
weight: 386
url: /ru/java/com.aspose.pdf/textsegment/
---
**Наследование:**
java.lang.Object
```
public final class TextSegment
```

Представляет сегмент текста Pdf.

--------------------

```
The example demonstrates how to change text color and font size of the text with ```
TextState
``` object of
  ```
Текстовый сегмент
``` object.


  // Open document
  Document doc = new Document("D:\\Tests\\input.pdf");

  // Create TextFragmentAbsorber object to find all "hello world" text occurrences
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

  // Accept the absorber for first page
  doc.getPages().get(1).accept(absorber);

  // Change foreground color of the first text segment of the first text occurrence
  absorber.getTextFragments().get(1).getSegments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED);
  // Change font size of the first text segment of the first text occurrence
  absorber.getTextFragments().get(1).getSegments().get_Item(1).getTextState().setFontSize ( 15);

  // Save document
  doc.save("D:\\Tests\\output.pdf");
```

--------------------

```
In a few words, ```
TextSegment
``` objects are children of ```
TextFragment
``` object.

 In details:

 Text of pdf document in ```
Aspose.Pdf
``` is represented by two basic objects:
 ```
Фрагмент текста
``` and ```
Текстовый сегмент
``` The differences between them is mostly
 context-dependent. Let's consider following scenario. User searches text "hello world" to operate
 with it, change it's properties, look etc.


  Document doc = new Document(docFile);
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  doc.getPages().get(1).accept(absorber);
```

Физически представление текста в формате PDF очень сложно. Текст «hello world» может состоять из нескольких физически независимых текстовых сегментов. Текстовая модель Aspose.PDF в основном устанавливает, что объект TextFragment предоставляет единый набор логических операций над набором физических объектов TextSegment, которые представляют запрос пользователя. В сценарии текстового поиска TextFragment является логическим текстовым представлением «привет, мир», а коллекция объектов TextSegment представляет все физические сегменты, которые создают текстовый объект «привет, мир». Итак, TextFragment близок к логическому текстовому представлению. А TextSegment близок к физическому текстовому представлению. Очевидно, что каждый объект TextSegment может иметь свой собственный шрифт, цвет, свойства позиционирования. TextFragment предоставляет простой способ изменить текст с помощью его свойств: установить шрифт, установить размер шрифта, установить цвет шрифта и т. д. При этом объекты TextSegment доступны, и пользователи могут работать с объектами TextSegment независимо.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TextSegment()](#TextSegment--) | Создает объект TextSegment. |
| [TextSegment(String text)](#TextSegment-java.lang.String-) | Создает объект TextSegment. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBaselinePosition()](#getBaselinePosition--) | Получает текстовую позицию для текста, представленного объектом TextSegment. |
| [getCharacters()](#getCharacters--) | Получает коллекцию объектов CharInfo, представляющих информацию о символах в текстовом сегменте. |
| [getClass()](#getClass--) |  |
| [getEndCharIndex()](#getEndCharIndex--) | Получает индекс конечного символа текущего сегмента в сегменте оператора отображения текста (Tj, TJ). |
| [getHyperlink()](#getHyperlink--) | Получает или задает гиперссылку сегмента (для генератора PDF). |
| [getPosition()](#getPosition--) | Получает текстовую позицию для текста, представленного объектом TextSegment. |
| [getRectangle()](#getRectangle--) | Получает прямоугольник TextSegment |
| [getStartCharIndex()](#getStartCharIndex--) | Получает индекс начального символа текущего сегмента в сегменте оператора отображения текста (Tj, TJ). |
| [getText()](#getText--) | Получает строковый текстовый объект, который представляет объект TextSegment. |
| [getTextEditOptions()](#getTextEditOptions--) | Получает параметры редактирования текста. |
| [getTextState()](#getTextState--) | Получает или задает состояние текста для текста, который представляет объект TextSegment. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBaselinePosition(Position value)](#setBaselinePosition-com.aspose.pdf.Position-) | Устанавливает текстовую позицию для текста, представленного объектом TextSegment. |
| [setHyperlink(Hyperlink value)](#setHyperlink-com.aspose.pdf.Hyperlink-) | Получает или задает гиперссылку сегмента (для генератора PDF). |
| [setPosition(Position value)](#setPosition-com.aspose.pdf.Position-) | Устанавливает текстовую позицию для текста, представленного объектом TextSegment. |
| [setText(String value)](#setText-java.lang.String-) | Задает строковый текстовый объект, который представляет объект TextSegment. |
| [setTextEditOptions(TextEditOptions value)](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Задает параметры редактирования текста. |
| [setTextState(TextState value)](#setTextState-com.aspose.pdf.TextState-) | Задает состояние текста для текста, который представляет объект TextSegment. |
| [setTextSuppressedUpdate(String value)](#setTextSuppressedUpdate-java.lang.String-) | Задает строковый текстовый объект, который представляет объект TextSegment, требующий подавления обновления. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextSegment() {#TextSegment--}
```
public TextSegment()
```


Создает объект TextSegment.

--------------------

```
The example demonstrates how to create text fragment object, add a text segment to the text fragment
 collection and append it to the Pdf page.


 Document doc = new Document(inFile);
 Page page = (Page)doc.getPages().get(1);
 // create text fragment
 TextFragment tf = new TextFragment("main text");
 tf.setPosition ( new Position(100, 600));
 // set it's text properties
 tf.getTextState().setFontSize ( 5);
 tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman"));
 tf.getTextState().setBackgroundColor ( Color.GRAY);
 tf.getTextState().setForegroundColor ( Color.RED);
 // add one more segment to text fragment's Segments collection
 TextSegment segment2 = new TextSegment();
 segment2.setText ( "another segment");
 tf.getSegments().add(segment2);
 // create TextBuilder object
 TextBuilder builder = new TextBuilder(page);
 // append the text fragment to the Pdf page
 builder.appendText(tf);
 //save document
 doc.save(outFile);
```

### TextSegment(String text) {#TextSegment-java.lang.String-}
```
public TextSegment(String text)
```


Создает объект TextSegment.

```
The example demonstrates how to create text fragment object, add a text segment to the text fragment
 collection and append it to the Pdf page.

 Document doc = new Document(inFile);
 Page page = (Page)doc.getPages().get(1);
 // create text fragment
 TextFragment tf = new TextFragment("main text");
 tf.setPosition ( new Position(100, 600));
 // set it's text properties
 tf.getTextState().setFontSize ( 5);
 tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman"));
 tf.getTextState().setBackgroundColor ( Color.GRAY);
 tf.getTextState().setForegroundColor ( Color.RED);
 // add one more segment to text fragment's Segments collection
 TextSegment segment2 = new TextSegment("another segment");
 tf.getSegments().add(segment2);
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
| text | java.lang.String | Текст текстового сегмента. |

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
### getBaselinePosition() {#getBaselinePosition--}
```
public Position getBaselinePosition()
```


Получает текстовую позицию для текста, представленного объектом TextSegment. YIndent структуры Position представляет базовую координату текстового сегмента.

**Возвращает:**
[Position](../../com.aspose.pdf/position) - Значение позиции
### getCharacters() {#getCharacters--}
```
public CharInfoCollection getCharacters()
```


Получает коллекцию объектов CharInfo, представляющих информацию о символах в текстовом сегменте.

**Возвращает:**
[CharInfoCollection](../../com.aspose.pdf/charinfocollection) - Объект CharInfoCollection
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getEndCharIndex() {#getEndCharIndex--}
```
public int getEndCharIndex()
```


Получает индекс конечного символа текущего сегмента в сегменте оператора отображения текста (Tj, TJ).

**Возвращает:**
интервал - целочисленное значение
### getHyperlink() {#getHyperlink--}
```
public Hyperlink getHyperlink()
```


Получает или задает гиперссылку сегмента (для генератора PDF).

**Возвращает:**
[Hyperlink](../../com.aspose.pdf/hyperlink) - Объект гиперссылки
### getPosition() {#getPosition--}
```
public Position getPosition()
```


Получает текстовую позицию для текста, представленного объектом TextSegment.

**Возвращает:**
[Position](../../com.aspose.pdf/position) - Значение позиции
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Получает прямоугольник TextSegment

**Возвращает:**
[Rectangle](../../com.aspose.pdf/rectangle) - Прямоугольный объект
### getStartCharIndex() {#getStartCharIndex--}
```
public int getStartCharIndex()
```


Получает индекс начального символа текущего сегмента в сегменте оператора отображения текста (Tj, TJ).

**Возвращает:**
интервал - целочисленное значение
### getText() {#getText--}
```
public String getText()
```


Получает строковый текстовый объект, который представляет объект TextSegment.

**Возвращает:**
java.lang.String — строковое значение
### getTextEditOptions() {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```


Получает параметры редактирования текста. Опции определяют особое поведение, когда запрошенный символ не может быть написан шрифтом.

**Возвращает:**
[TextEditOptions](../../com.aspose.pdf/texteditoptions) - Значение TextEditOptions
### getTextState() {#getTextState--}
```
public TextState getTextState()
```


Получает или задает состояние текста для текста, который представляет объект TextSegment.

--------------------

Предоставляет возможность изменить следующие свойства текста: Font FontSize FontStyle ForegroundColor BackgroundColor

**Возвращает:**
[TextState](../../com.aspose.pdf/textstate) - Значение TextState
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




### setBaselinePosition(Position value) {#setBaselinePosition-com.aspose.pdf.Position-}
```
public void setBaselinePosition(Position value)
```


Устанавливает текстовую позицию для текста, представленного объектом TextSegment. YIndent структуры Position представляет базовую координату текстового сегмента.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Position](../../com.aspose.pdf/position) | Значение позиции |

### setHyperlink(Hyperlink value) {#setHyperlink-com.aspose.pdf.Hyperlink-}
```
public void setHyperlink(Hyperlink value)
```


Получает или задает гиперссылку сегмента (для генератора PDF).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Hyperlink](../../com.aspose.pdf/hyperlink) | Объект гиперссылки |

### setPosition(Position value) {#setPosition-com.aspose.pdf.Position-}
```
public void setPosition(Position value)
```


Устанавливает текстовую позицию для текста, представленного объектом TextSegment.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Position](../../com.aspose.pdf/position) | Значение позиции |

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Задает строковый текстовый объект, который представляет объект TextSegment.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setTextEditOptions(TextEditOptions value) {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
```
public void setTextEditOptions(TextEditOptions value)
```


Задает параметры редактирования текста. Опции определяют особое поведение, когда запрошенный символ не может быть написан шрифтом.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextEditOptions](../../com.aspose.pdf/texteditoptions) | Значение TextEditOptions |

### setTextState(TextState value) {#setTextState-com.aspose.pdf.TextState-}
```
public void setTextState(TextState value)
```


Задает состояние текста для текста, который представляет объект TextSegment.

--------------------

Предоставляет возможность изменить следующие свойства текста: Font FontSize FontStyle ForegroundColor BackgroundColor

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | Значение TextState |

### setTextSuppressedUpdate(String value) {#setTextSuppressedUpdate-java.lang.String-}
```
public void setTextSuppressedUpdate(String value)
```


Задает строковый текстовый объект, который представляет объект TextSegment, требующий подавления обновления.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

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
