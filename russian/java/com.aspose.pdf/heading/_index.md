---
title: Heading
second_title: Aspose.PDF для справки по Java API
description: Представляет заголовок.
type: docs
weight: 151
url: /ru/java/com.aspose.pdf/heading/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.TextFragment](../../com.aspose.pdf/textfragment)
```
public final class Heading extends TextFragment
```

Представляет заголовок.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Heading()](#Heading--) | Только для внутреннего использования |
| [Heading(int level)](#Heading-int-) | Инициализирует новый экземпляр класса Cell. |
## Методы

| Метод | Описание |
| --- | --- |
| [cloneWithSegments()](#cloneWithSegments--) | Клонируйте заголовок со всеми сегментами. |
| [deepClone()](#deepClone--) | Клонируйте заголовок. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBaselinePosition()](#getBaselinePosition--) | Получает текстовую позицию для текста, представленного объектом TextFragment. |
| [getClass()](#getClass--) |  |
| [getDestinationPage()](#getDestinationPage--) | Получает целевую страницу. |
| [getEndNote()](#getEndNote--) | Получает примечание в конце абзаца. |
| [getFootNote()](#getFootNote--) | Получает сноску абзаца. |
| [getForm()](#getForm--) | Получает объект формы, содержащий TextFragment
Значение может быть нулевым, если объект TextFragment не принадлежит форме. |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Получает горизонтальное выравнивание текстового фрагмента. |
| [getHyperlink()](#getHyperlink--) | Получает гиперссылку фрагмента (для генератора pdf). |
| [getLevel()](#getLevel--) | Получает уровень. |
| [getMargin()](#getMargin--) | Получает внешнее поле для абзаца (для создания pdf) |
| [getPage()](#getPage--) | Получает страницу, содержащую TextFragment
Значение может быть нулевым, если объект TextFragment не принадлежит ни одной странице. |
| [getPosition()](#getPosition--) | Получает текстовую позицию для текста, представленного объектом TextFragment. |
| [getRectangle()](#getRectangle--) | Получает прямоугольник TextFragment |
| [getReplaceOptions()](#getReplaceOptions--) | Получает параметры замены текста. |
| [getSegments()](#getSegments--) | Получает текстовые сегменты для текущего TextFragment . |
| [getStartNumber()](#getStartNumber--) | Получает начальный номер заголовка. |
| [getStyle()](#getStyle--) | Получает или задает стиль. |
| [getText()](#getText--) | Получает строковый текстовый объект, который представляет объект TextFragment. |
| [getTextState()](#getTextState--) | Получает или задает состояние текста для текста, который представляет объект TextFragment. |
| [getTocPage()](#getTocPage--) | Получает страницу, содержащую этот заголовок. |
| [getTop()](#getTop--) | Получает верхнюю Y этих заголовков (для внутреннего использования). |
| [getUserLabel()](#getUserLabel--) | Получает или задает метку пользователя. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Получает вертикальное выравнивание текстового фрагмента. |
| [getWrapLinesCount()](#getWrapLinesCount--) | Получает количество строк переноса для этого абзаца (только для создания PDF) |
| [getZIndex()](#getZIndex--) | Получает значение int, указывающее Z-порядок графика. |
| [hashCode()](#hashCode--) |  |
| [isAutoSequence()](#isAutoSequence--) | Получает заголовок должен нумероваться автоматически. |
| [isFirstParagraphInColumn()](#isFirstParagraphInColumn--) | Получает или задает логическое значение, указывающее, будет ли этот абзац находиться в следующем столбце. |
| [isInLineParagraph()](#isInLineParagraph--) | Получает абзац встроенным. |
| [isInList()](#isInList--) | Получает, что заголовок должен быть в списке toc. |
| [isInNewPage()](#isInNewPage--) | Получает логическое значение, которое принудительно генерирует этот абзац на новой странице. |
| [isKeptWithNext()](#isKeptWithNext--) | Получает логическое значение, указывающее, остается ли текущий абзац на той же странице, что и следующий абзац. |
| [isolateTextSegments(int startIndex, int length)](#isolateTextSegments-int-int-) | Получает TextSegment (s), представляющие указанную часть текста TextFragment. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSequence(boolean value)](#setAutoSequence-boolean-) | устанавливает, что заголовок должен быть пронумерован автоматически. |
| [setBaselinePosition(Position value)](#setBaselinePosition-com.aspose.pdf.Position-) | Устанавливает текстовую позицию для текста, представленного объектом TextFragment. |
| [setDestinationPage(Page value)](#setDestinationPage-com.aspose.pdf.Page-) | устанавливает целевую страницу. |
| [setEndNote(Note value)](#setEndNote-com.aspose.pdf.Note-) | Устанавливает примечание конца абзаца. |
| [setFirstParagraphInColumn(boolean value)](#setFirstParagraphInColumn-boolean-) | Получает или задает логическое значение, указывающее, будет ли этот абзац находиться в следующем столбце. |
| [setFootNote(Note value)](#setFootNote-com.aspose.pdf.Note-) | Устанавливает сноску абзаца. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Устанавливает горизонтальное выравнивание текстового фрагмента. |
| [setHyperlink(Hyperlink value)](#setHyperlink-com.aspose.pdf.Hyperlink-) | Устанавливает гиперссылку фрагмента |
| [setInLineParagraph(boolean value)](#setInLineParagraph-boolean-) | Устанавливает абзац встроенным. |
| [setInList(boolean value)](#setInList-boolean-) | устанавливает, что заголовок должен быть в списке toc. |
| [setInNewPage(boolean value)](#setInNewPage-boolean-) | Устанавливает логическое значение, которое принудительно генерирует этот абзац на новой странице. |
| [setKeptWithNext(boolean value)](#setKeptWithNext-boolean-) | Задает логическое значение, указывающее, остается ли текущий абзац на той же странице вместе со следующим абзацем. |
| [setLevel(int value)](#setLevel-int-) | устанавливает уровень. |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | Устанавливает внешнее поле для абзаца (для создания pdf) |
| [setMarkedContentProperties(String name, int id)](#setMarkedContentProperties-java.lang.String-int-) |  |
| [setPosition(Position value)](#setPosition-com.aspose.pdf.Position-) | Устанавливает текстовую позицию для текста, представленного объектом TextFragment. |
| [setRectangle(Rectangle value)](#setRectangle-com.aspose.pdf.Rectangle-) | Получает прямоугольник TextFragment |
| [setSegments(TextSegmentCollection value)](#setSegments-com.aspose.pdf.TextSegmentCollection-) | Представлять метод setSegments |
| [setStartNumber(int value)](#setStartNumber-int-) | Получает начальный номер заголовка. |
| [setStyle(int value)](#setStyle-int-) | устанавливает или устанавливает стиль. |
| [setText(String value)](#setText-java.lang.String-) | Задает строковый текстовый объект, который представляет объект TextFragment. |
| [setTocPage(Page value)](#setTocPage-com.aspose.pdf.Page-) | Задает страницу, содержащую этот заголовок. |
| [setTop(double value)](#setTop-double-) | устанавливает верхний Y этих заголовков (для внутреннего использования). |
| [setUserLabel(TextSegment value)](#setUserLabel-com.aspose.pdf.TextSegment-) | Получает или задает метку пользователя. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Устанавливает вертикальное выравнивание текстового фрагмента. |
| [setWrapLinesCount(int value)](#setWrapLinesCount-int-) | Устанавливает количество строк переноса для этого абзаца (только для создания pdf) |
| [setZIndex(int value)](#setZIndex-int-) | Задает значение int, указывающее Z-порядок графика. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Heading() {#Heading--}
```
public Heading()
```


Только для внутреннего использования

### Heading(int level) {#Heading-int-}
```
public Heading(int level)
```


Инициализирует новый экземпляр класса Cell.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| level | int | Уровень заголовков. |

### cloneWithSegments() {#cloneWithSegments--}
```
public Object cloneWithSegments()
```


Клонируйте заголовок со всеми сегментами.

**Возвращает:**
java.lang.Object — клонированный объект
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Клонируйте заголовок.

**Возвращает:**
java.lang.Object — клонированный объект
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


Получает текстовую позицию для текста, представленного объектом TextFragment. YIndent структуры Position представляет базовую координату текстового фрагмента.

**Возвращает:**
[Position](../../com.aspose.pdf/position) - Значение позиции
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getDestinationPage() {#getDestinationPage--}
```
public Page getDestinationPage()
```


Получает целевую страницу.

**Возвращает:**
[Page](../../com.aspose.pdf/page) - Страница назначения.
### getEndNote() {#getEndNote--}
```
public Note getEndNote()
```


Получает примечание в конце абзаца (только для создания PDF-файла).

**Возвращает:**
[Note](../../com.aspose.pdf/note) - Примечание значение
### getFootNote() {#getFootNote--}
```
public Note getFootNote()
```


Получает примечание к абзацу (только для создания PDF-файла).

**Возвращает:**
[Note](../../com.aspose.pdf/note) - Примечание значение
### getForm() {#getForm--}
```
public XForm getForm()
```


Получает объект формы, содержащий TextFragment
Значение может быть нулевым, если объект TextFragment не принадлежит форме.

**Возвращает:**
[XForm](../../com.aspose.pdf/xform) - Значение X-формы
### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


Получает горизонтальное выравнивание текстового фрагмента.

**Возвращает:**
int - значение HorizontalAlignment
### getHyperlink() {#getHyperlink--}
```
public Hyperlink getHyperlink()
```


Получает гиперссылку фрагмента (для генератора pdf).

**Возвращает:**
[Hyperlink](../../com.aspose.pdf/hyperlink) - гиперссылка на фрагмент (для генератора pdf).
### getLevel() {#getLevel--}
```
public int getLevel()
```


Получает уровень.

**Возвращает:**
int - Уровень заголовка.
### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


Получает внешнее поле для абзаца (для создания pdf)

**Возвращает:**
[MarginInfo](../../com.aspose.pdf/margininfo) - значение MarginInfo
### getPage() {#getPage--}
```
public Page getPage()
```


Получает страницу, содержащую TextFragment
Значение может быть нулевым, если объект TextFragment не принадлежит ни одной странице.

**Возвращает:**
[Page](../../com.aspose.pdf/page) - Объект страницы
### getPosition() {#getPosition--}
```
public Position getPosition()
```


Получает текстовую позицию для текста, представленного объектом TextFragment.

**Возвращает:**
[Position](../../com.aspose.pdf/position) - Значение позиции

--------------------

```
The example demonstrates how to view placement of a text, represented by ```
TextFragment
``` object.

   // Open document
   Document doc = new Document("D:\\Tests\\input.pdf");

   // Create TextFragmentAbsorber object to find all "hello world" text occurrences
   TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

   // Accept the absorber for first page
   doc.getPages().get(1).accept(absorber);

   // View text and placement info of first text occurrence
   TextFragment firstOccurrence = absorber.getTextFragments().get_Item(1);

   System.out.println("fragment text: " + firstOccurrence.getText()));
   System.out.println("fragment X indent: "+ firstOccurrence.getPosition().getXIndent()));
   System.out.println("fragment Y indent: "+ firstOccurrence.getPosition().getYIndent()));
```
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Получает прямоугольник TextFragment

**Возвращает:**
[Rectangle](../../com.aspose.pdf/rectangle) - Прямоугольный объект
### getReplaceOptions() {#getReplaceOptions--}
```
public final TextReplaceOptions getReplaceOptions()
```


Получает параметры замены текста. Опции определяют поведение при замене текста фрагмента на более короткий/длинный.

**Возвращает:**
[TextReplaceOptions](../../com.aspose.pdf/textreplaceoptions) - Экземпляр TextReplaceOptions
### getSegments() {#getSegments--}
```
public TextSegmentCollection getSegments()
```


Получает текстовые сегменты для текущего TextFragment .

**Возвращает:**
[TextSegmentCollection](../../com.aspose.pdf/textsegmentcollection) - Значение TextSegmentCollection

--------------------

```
The example demonstrates how to navigate all ```
TextSegment
``` objects inside ```
TextFragment
```.

  // Open document
  Document doc = new Document("D:\\Tests\\input.pdf");

  // Create TextFragmentAbsorber object to find all "hello world" text occurrences
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

  // Accept the absorber for first page
  doc.getPages().get(1).accept(absorber);

  // Navigate all text segments and out their text and placement info
  for (TextSegment segment : (```
Iterable
```)absorber.getTextFragments().get_Item(1).getSegments())
  {
      System.out.println("segment text: "+ segment.getText()));
      System.out.println("segment X indent: "+ segment.getPosition().getXIndent()));
      System.out.println("segment Y indent: "+ segment.getPosition().getYIndent()));
  }
```

--------------------

В двух словах, объекты TextSegment являются дочерними элементами объекта TextFragment. Опытные пользователи могут напрямую обращаться к сегментам для выполнения более сложных сценариев редактирования текста. Подробности смотрите в описании объекта TextFragment.
### getStartNumber() {#getStartNumber--}
```
public int getStartNumber()
```


Получает начальный номер заголовка.

**Возвращает:**
int — значение: начальный номер.
### getStyle() {#getStyle--}
```
public int getStyle()
```


Получает или задает стиль.

**Возвращает:**
int - Стиль заголовка.
### getText() {#getText--}
```
public String getText()
```


Получает строковый текстовый объект, который представляет объект TextFragment.

**Возвращает:**
java.lang.String — строковое значение

--------------------

```
The example demonstrates how to search a text and replace first occurrence represented with ```

  TextFragment
``` object .

  // Open document
  Document doc = new Document("D:\\Tests\\input.pdf");

  // Create TextFragmentAbsorber object to find all "hello world" text occurrences
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

  // Accept the absorber for first page
  doc.getPages().get(1).accept(absorber);

  // Change font of the first text occurrence
  absorber.getTextFragments().get_Item(1).setText ( "hi world");

  // Save document
  doc.save("D:\\Tests\\output.pdf");
```
### getTextState() {#getTextState--}
```
public TextFragmentState getTextState()
```


Получает или задает состояние текста для текста, который представляет объект TextFragment.

**Возвращает:**
[TextFragmentState](../../com.aspose.pdf/textfragmentstate) - Объект TextFragmentState

--------------------

```
The example demonstrates how to change text color and font size of the text with ```
TextState
``` object.

  // Open document
  Document doc = new Document("D:\\Tests\\input.pdf");

  // Create TextFragmentAbsorber object to find all "hello world" text occurrences
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

  // Accept the absorber for first page
  doc.getPages().get(1).accept(absorber);

  // Change foreground color of the first text occurrence
  absorber.getTextFragments().get_Item(1).getTextState().setForegroundColor(Color.RED);

  // Change font size of the first text occurrence
  absorber.getTextFragments().get_Item(1).getTextState().setFontSize ( 15);

  // Save document
  doc.save("D:\\Tests\\output.pdf");
```

--------------------

Предоставляет возможность изменить следующие свойства текста: Font FontSize FontStyle ForegroundColor BackgroundColor
### getTocPage() {#getTocPage--}
```
public Page getTocPage()
```


Получает страницу, содержащую этот заголовок.

**Возвращает:**
[Page](../../com.aspose.pdf/page) - Страница.
### getTop() {#getTop--}
```
public double getTop()
```


Получает верхнюю Y этих заголовков (для внутреннего использования).

**Возвращает:**
double - Верхнее значение Y
### getUserLabel() {#getUserLabel--}
```
public TextSegment getUserLabel()
```


Получает или задает метку пользователя.

**Возвращает:**
[TextSegment](../../com.aspose.pdf/textsegment) - Объект TextSegment
### getVerticalAlignment() {#getVerticalAlignment--}
```
public int getVerticalAlignment()
```


Получает вертикальное выравнивание текстового фрагмента.

**Возвращает:**
интервал - целочисленное значение
### getWrapLinesCount() {#getWrapLinesCount--}
```
public int getWrapLinesCount()
```


Получает количество строк переноса для этого абзаца (только для создания PDF)

**Возвращает:**
интервал - целочисленное значение
### getZIndex() {#getZIndex--}
```
public int getZIndex()
```


Получает значение int, указывающее Z-порядок графика. График с большим ZIndex будет размещен над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещен за текстом на странице.

**Возвращает:**
интервал - целочисленное значение
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isAutoSequence() {#isAutoSequence--}
```
public boolean isAutoSequence()
```


Получает заголовок должен нумероваться автоматически.

**Возвращает:**
логическое значение — IsAutoSequens.
### isFirstParagraphInColumn() {#isFirstParagraphInColumn--}
```
public boolean isFirstParagraphInColumn()
```


Получает или задает логическое значение, указывающее, будет ли этот абзац находиться в следующем столбце. Значение по умолчанию — false. (для генерации pdf)

**Возвращает:**
boolean - логическое значение
### isInLineParagraph() {#isInLineParagraph--}
```
public boolean isInLineParagraph()
```


Получает абзац встроенным. Значение по умолчанию — false. (для генерации pdf)

**Возвращает:**
boolean - логическое значение
### isInList() {#isInList--}
```
public boolean isInList()
```


Получает, что заголовок должен быть в списке toc.

**Возвращает:**
логическое значение — IsInList.
### isInNewPage() {#isInNewPage--}
```
public boolean isInNewPage()
```


Получает логическое значение, которое принудительно генерирует этот абзац на новой странице. Значение по умолчанию — false. (для генерации pdf)

**Возвращает:**
boolean - логическое значение
### isKeptWithNext() {#isKeptWithNext--}
```
public boolean isKeptWithNext()
```


Получает логическое значение, указывающее, остается ли текущий абзац на той же странице, что и следующий абзац. Значение по умолчанию — false. (для генерации pdf)

**Возвращает:**
boolean - логическое значение
### isolateTextSegments(int startIndex, int length) {#isolateTextSegments-int-int-}
```
public TextSegmentCollection isolateTextSegments(int startIndex, int length)
```


Получает TextSegment (s), представляющие указанную часть текста TextFragment.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| startIndex | int | Позиция в тексте, с которой будут начинаться новые TextSegment(s). |
| length | int | Длина текста, который будет изолирован в TextSegment (s). |

**Возвращает:**
[TextSegmentCollection](../../com.aspose.pdf/textsegmentcollection) - TextSegmentCollection, содержащая текстовые сегменты, представляющие текстовую подстроку, начинающуюся с указанной позиции и имеющую указанную длину.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAutoSequence(boolean value) {#setAutoSequence-boolean-}
```
public void setAutoSequence(boolean value)
```


устанавливает, что заголовок должен быть пронумерован автоматически.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | IsAutoSequens. |

### setBaselinePosition(Position value) {#setBaselinePosition-com.aspose.pdf.Position-}
```
public void setBaselinePosition(Position value)
```


Устанавливает текстовую позицию для текста, представленного объектом TextFragment. YIndent структуры Position представляет базовую координату текстового фрагмента.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Position](../../com.aspose.pdf/position) | Значение позиции |

### setDestinationPage(Page value) {#setDestinationPage-com.aspose.pdf.Page-}
```
public void setDestinationPage(Page value)
```


устанавливает целевую страницу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Page](../../com.aspose.pdf/page) | Страница назначения. |

### setEndNote(Note value) {#setEndNote-com.aspose.pdf.Note-}
```
public void setEndNote(Note value)
```


Устанавливает примечание в конце абзаца (только для создания PDF-файлов).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Note](../../com.aspose.pdf/note) | Примечание значение |

### setFirstParagraphInColumn(boolean value) {#setFirstParagraphInColumn-boolean-}
```
public void setFirstParagraphInColumn(boolean value)
```


Получает или задает логическое значение, указывающее, будет ли этот абзац находиться в следующем столбце. Значение по умолчанию — false. (для генерации pdf)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setFootNote(Note value) {#setFootNote-com.aspose.pdf.Note-}
```
public void setFootNote(Note value)
```


Устанавливает сноску к абзацу (только для создания PDF-файлов).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Note](../../com.aspose.pdf/note) | Примечание значение |

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```


Устанавливает горизонтальное выравнивание текстового фрагмента.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение HorizontalAlignment |

### setHyperlink(Hyperlink value) {#setHyperlink-com.aspose.pdf.Hyperlink-}
```
public void setHyperlink(Hyperlink value)
```


Устанавливает гиперссылку фрагмента

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Hyperlink](../../com.aspose.pdf/hyperlink) |  |

### setInLineParagraph(boolean value) {#setInLineParagraph-boolean-}
```
public void setInLineParagraph(boolean value)
```


Устанавливает абзац встроенным. Значение по умолчанию — false. (для генерации pdf)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setInList(boolean value) {#setInList-boolean-}
```
public void setInList(boolean value)
```


устанавливает, что заголовок должен быть в списке toc.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | IsInList. |

### setInNewPage(boolean value) {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```


Устанавливает логическое значение, которое принудительно генерирует этот абзац на новой странице. Значение по умолчанию — false. (для генерации pdf)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setKeptWithNext(boolean value) {#setKeptWithNext-boolean-}
```
public final void setKeptWithNext(boolean value)
```


Задает логическое значение, указывающее, остается ли текущий абзац на той же странице вместе со следующим абзацем. Значение по умолчанию — false. (для генерации pdf)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setLevel(int value) {#setLevel-int-}
```
public void setLevel(int value)
```


устанавливает уровень.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Уровень заголовка. |

### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public void setMargin(MarginInfo value)
```


Устанавливает внешнее поле для абзаца (для создания pdf)

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | Объект MarginInfo |

### setMarkedContentProperties(String name, int id) {#setMarkedContentProperties-java.lang.String-int-}
```
public void setMarkedContentProperties(String name, int id)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String |  |
| id | int |  |

### setPosition(Position value) {#setPosition-com.aspose.pdf.Position-}
```
public void setPosition(Position value)
```


Устанавливает текстовую позицию для текста, представленного объектом TextFragment.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Position](../../com.aspose.pdf/position) | Значение позиции

--------------------

```
The example demonstrates how to view placement of a text, represented by ```

                       TextFragment
```
                       object.

                        // Open document
                        Document doc = new Document("D:\\Tests\\input.pdf");

                        // Create TextFragmentAbsorber object to find all "hello world" text occurrences
                        TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

                        // Accept the absorber for first page
                        doc.getPages().get(1).accept(absorber);

                        // View text and placement info of first text occurrence
                        TextFragment firstOccurrence = absorber.getTextFragments().get_Item(1);

                        System.out.println("fragment text: " + firstOccurrence.getText()));
                        System.out.println("fragment X indent: "+ firstOccurrence.getPosition().getXIndent()));
                        System.out.println("fragment Y indent: "+ firstOccurrence.getPosition().getYIndent()));
``` |

### setRectangle(Rectangle value) {#setRectangle-com.aspose.pdf.Rectangle-}
```
public void setRectangle (значение прямоугольника)
```


Gets rectangle of the TextFragment

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle instance |

### setSegments(TextSegmentCollection value) {#setSegments-com.aspose.pdf.TextSegmentCollection-}
```
public void setSegments (значение TextSegmentCollection)
```


Represent setSegments method

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextSegmentCollection](../../com.aspose.pdf/textsegmentcollection) | TextSegmentCollection value |

### setStartNumber(int value) {#setStartNumber-int-}
```
public void setStartNumber (значение int)
```


Gets the heading start number.

Value: The startNumber.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The startNumber. |

### setStyle(int value) {#setStyle-int-}
```
public void setStyle (значение int)
```


sets or sets style.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The heading style. |

### setText(String value) {#setText-java.lang.String-}
```
public void setText (строковое значение)
```


Sets  string  text object that the  TextFragment  object represents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value

--------------------

```
В примере показано, как искать текст и заменять первое вхождение, представленное с помощью
                       ```
Фрагмент текста
``` object .

                       // Open document
                       Document doc = new Document("D:\\Tests\\input.pdf");

                       // Create TextFragmentAbsorber object to find all "hello world" text occurrences
                       TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

                       // Accept the absorber for first page
                       doc.getPages().get(1).accept(absorber);

                       // Change font of the first text occurrence
                       absorber.getTextFragments().get_Item(1).setText ( "hi world");

                       // Save document
                       doc.save("D:\\Tests\\output.pdf");
``` |

### setTocPage(Page value) {#setTocPage-com.aspose.pdf.Page-}
```
public void setTocPage (значение страницы)
```


Sets the page that contains this heading.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Page](../../com.aspose.pdf/page) | The page. |

### setTop(double value) {#setTop-double-}
```
public void setTop (двойное значение)
```


sets the top Y of this headings(for internal use).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The top Y value |

### setUserLabel(TextSegment value) {#setUserLabel-com.aspose.pdf.TextSegment-}
```
public void setUserLabel (значение TextSegment)
```


Gets or sets user label.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextSegment](../../com.aspose.pdf/textsegment) | TextSegment object |

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment (целое значение)
```


Sets a vertical alignment of text fragment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setWrapLinesCount(int value) {#setWrapLinesCount-int-}
```
public void setWrapLinesCount (целое значение)
```


Sets wrap lines count for this paragraph(for pdf generation only)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setZIndex(int value) {#setZIndex-int-}
```
public void setZIndex (значение int)
```


Sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

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