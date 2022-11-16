---
title: TextParagraph
second_title: Aspose.PDF для справки по Java API
description: Представляет текстовые абзацы как многострочный текстовый объект.
type: docs
weight: 380
url: /ru/java/com.aspose.pdf/textparagraph/
---
**Наследование:**
java.lang.Object
```
public final class TextParagraph
```

Представляет текстовые абзацы как многострочный текстовый объект.

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
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TextParagraph()](#TextParagraph--) | Создает объект TextParagraph. |
## Методы

| Метод | Описание |
| --- | --- |
| [appendLine(TextFragment line)](#appendLine-com.aspose.pdf.TextFragment-) | Добавляет текстовую строку с параметрами состояния текста. |
| [appendLine(TextFragment line, TextState textState)](#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-) | Добавляет текстовую строку с параметрами состояния текста. |
| [appendLine(TextFragment line, TextState textState, float lineSpacing)](#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-float-) | Добавляет текстовую строку с параметрами состояния текста |
| [appendLine(String line)](#appendLine-java.lang.String-) | Добавляет текстовую строку |
| [appendLine(String line, TextState textState)](#appendLine-java.lang.String-com.aspose.pdf.TextState-) | Добавляет текстовую строку с параметрами состояния текста. |
| [appendLine(String line, TextState textState, float lineSpacing)](#appendLine-java.lang.String-com.aspose.pdf.TextState-float-) | Добавляет текстовую строку с параметрами состояния текста |
| [appendLine(String line, float lineSpacing)](#appendLine-java.lang.String-float-) | Добавляет текстовую строку. |
| [beginEdit()](#beginEdit--) | Начинает редактирование TextParagraph. |
| [endEdit()](#endEdit--) | Завершает редактирование TextParagraph. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirstLineIndent()](#getFirstLineIndent--) | Получает или задает значение отступа последующих строк. |
| [getFormattingOptions()](#getFormattingOptions--) | Получает параметры форматирования. |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Получает горизонтальное выравнивание для текста внутри прямоугольника абзаца. |
| [getHyphenSymbol()](#getHyphenSymbol--) | Получает символ дефиса, используемый в процессе расстановки переносов. |
| [getMargin()](#getMargin--) | Получает прокладку. |
| [getPosition()](#getPosition--) | Получает позицию абзаца. |
| [getRectangle()](#getRectangle--) | Получает прямоугольник абзаца. |
| [getRotation()](#getRotation--) | Получает или задает угол поворота в градусах. |
| [getSubsequentLinesIndent()](#getSubsequentLinesIndent--) | Получает значение отступа последующих строк. |
| [getTextRectangle()](#getTextRectangle--) | Получает прямоугольник текста, помещенного в абзац. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Получает вертикальное выравнивание текста внутри Rectangle абзаца. |
| [hashCode()](#hashCode--) |  |
| [isJustify()](#isJustify--) | Получает значение, выровнен ли текст. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | Устанавливает цвет фона для текстового абзаца. |
| [setBackgroundMode(int value)](#setBackgroundMode-int-) | Установить фоновый режим для текстового абзаца |
| [setFirstLineIndent(float value)](#setFirstLineIndent-float-) | Получает или задает значение отступа последующих строк. |
| [setFormattingOptions(TextFormattingOptions value)](#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-) | Устанавливает параметры форматирования. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Устанавливает горизонтальное выравнивание для текста внутри прямоугольника абзаца. |
| [setHyphenSymbol(String value)](#setHyphenSymbol-java.lang.String-) | Устанавливает символ дефиса, который используется в процессе переноса. |
| [setJustify(boolean value)](#setJustify-boolean-) | Устанавливает значение, выравнивается ли текст. |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | Устанавливает отступ. |
| [setMatrix(Matrix value)](#setMatrix-com.aspose.pdf.Matrix-) | Задает поворот абзаца. |
| [setOldCodeCompatibilityMode(boolean value)](#setOldCodeCompatibilityMode-boolean-) | Установить режим совместимости со старым кодом |
| [setPosition(Position value)](#setPosition-com.aspose.pdf.Position-) | Устанавливает позицию абзаца. |
| [setRectangle(Rectangle value)](#setRectangle-com.aspose.pdf.Rectangle-) | Задает прямоугольник абзаца. |
| [setRotation(double value)](#setRotation-double-) | Получает или задает угол поворота в градусах. |
| [setSubsequentLinesIndent(float value)](#setSubsequentLinesIndent-float-) | Устанавливает значение отступа последующих строк. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Устанавливает вертикальное выравнивание текста внутри Rectangle абзаца. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextParagraph() {#TextParagraph--}
```
public TextParagraph()
```


Создает объект TextParagraph.

### appendLine(TextFragment line) {#appendLine-com.aspose.pdf.TextFragment-}
```
public void appendLine(TextFragment line)
```


Добавляет текстовую строку с параметрами состояния текста.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| line | [TextFragment](../../com.aspose.pdf/textfragment) | Текст новой строки. |

### appendLine(TextFragment line, TextState textState) {#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-}
```
public void appendLine(TextFragment line, TextState textState)
```


Добавляет текстовую строку с параметрами состояния текста.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| line | [TextFragment](../../com.aspose.pdf/textfragment) | Текст новой строки. |
| textState | [TextState](../../com.aspose.pdf/textstate) | Текстовое состояние новой строки. |

### appendLine(TextFragment line, TextState textState, float lineSpacing) {#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-float-}
```
public void appendLine(TextFragment line, TextState textState, float lineSpacing)
```


Добавляет текстовую строку с параметрами состояния текста

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| line | [TextFragment](../../com.aspose.pdf/textfragment) | Текст новой строки. |
| textState | [TextState](../../com.aspose.pdf/textstate) | Текстовое состояние новой строки. |
| lineSpacing | float | Дополнительный интервал (0,0 по умолчанию и соответствует высоте строки текста по умолчанию). Значение интервала добавляется к межстрочному интервалу по умолчанию для конкретной строки, поэтому вы можете указать 12,0, чтобы получить пустую строку ПОСЛЕ текстовой строки, нарисованной шрифтом 12pt. |

### appendLine(String line) {#appendLine-java.lang.String-}
```
public void appendLine(String line)
```


Добавляет текстовую строку

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| line | java.lang.String | Текст новой строки. |

### appendLine(String line, TextState textState) {#appendLine-java.lang.String-com.aspose.pdf.TextState-}
```
public void appendLine(String line, TextState textState)
```


Добавляет текстовую строку с параметрами состояния текста.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| line | java.lang.String | Текст новой строки. |
| textState | [TextState](../../com.aspose.pdf/textstate) | Текстовое состояние новой строки. |

### appendLine(String line, TextState textState, float lineSpacing) {#appendLine-java.lang.String-com.aspose.pdf.TextState-float-}
```
public void appendLine(String line, TextState textState, float lineSpacing)
```


Добавляет текстовую строку с параметрами состояния текста

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| line | java.lang.String | Текст новой строки. |
| textState | [TextState](../../com.aspose.pdf/textstate) | Текстовое состояние новой строки. |
| lineSpacing | float | Дополнительный интервал (0,0 по умолчанию и соответствует высоте строки текста по умолчанию). Значение интервала добавляется к межстрочному интервалу по умолчанию для конкретной строки, поэтому вы можете указать 12,0, чтобы получить пустую строку ПОСЛЕ текстовой строки, нарисованной шрифтом 12pt. |

### appendLine(String line, float lineSpacing) {#appendLine-java.lang.String-float-}
```
public void appendLine(String line, float lineSpacing)
```


Добавляет текстовую строку.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| line | java.lang.String | Текст новой строки. |
| lineSpacing | float | Дополнительный интервал (0,0 по умолчанию и соответствует высоте строки текста по умолчанию). Значение интервала добавляется к межстрочному интервалу по умолчанию для конкретной строки, поэтому вы можете указать 12,0, чтобы получить пустую строку ПОСЛЕ текстовой строки, нарисованной шрифтом 12pt. |

### beginEdit() {#beginEdit--}
```
public void beginEdit()
```


Начинает редактирование TextParagraph.

Улучшает производительность заполнения TextParagraph. Любой расчет макета приостанавливается до тех пор, пока не будет вызван метод EndEdit.

Обратите внимание, что вызов метода не может быть вложенным.

### endEdit() {#endEdit--}
```
public void endEdit()
```


Завершает редактирование TextParagraph.

Улучшает производительность заполнения TextParagraph. Любой расчет макета приостанавливается до тех пор, пока не будет вызван метод EndEdit.

Обратите внимание, что вызов метода не может быть вложенным.

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
### getFirstLineIndent() {#getFirstLineIndent--}
```
public final float getFirstLineIndent()
```


Получает или задает значение отступа последующих строк. Если задано ненулевое значение, оно имеет преимущество перед значением FormattingOptions.SubsequentLinesIndent.

**Возвращает:**
float - плавающее значение
### getFormattingOptions() {#getFormattingOptions--}
```
public TextFormattingOptions getFormattingOptions()
```


Получает параметры форматирования.

**Возвращает:**
[TextFormattingOptions](../../com.aspose.pdf/textformattingoptions) - Объект TextFormattingOptions
### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


Получает горизонтальное выравнивание для текста внутри прямоугольника абзаца.

HorizontalAlignment.None равно HorizontalAlignment.Left.

**Возвращает:**
int - значение HorizontalAlignment
### getHyphenSymbol() {#getHyphenSymbol--}
```
public String getHyphenSymbol()
```


Получает символ дефиса, используемый в процессе расстановки переносов.

Символ дефиса по умолчанию «-». Чтобы исключить рисование дефиса (при сохранении процедуры переноса), установите пустую строку string.Empty для HyphenSymbol.

**Возвращает:**
java.lang.String — строковое значение
### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


Получает прокладку.

**Возвращает:**
[MarginInfo](../../com.aspose.pdf/margininfo) - значение MarginInfo
### getPosition() {#getPosition--}
```
public Position getPosition()
```


Получает позицию абзаца.

**Возвращает:**
[Position](../../com.aspose.pdf/position) - Значение позиции
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Получает прямоугольник абзаца.

**Возвращает:**
[Rectangle](../../com.aspose.pdf/rectangle) - Прямоугольный объект
### getRotation() {#getRotation--}
```
public double getRotation()
```


Получает или задает угол поворота в градусах.

**Возвращает:**
двойное - двойное значение
### getSubsequentLinesIndent() {#getSubsequentLinesIndent--}
```
public float getSubsequentLinesIndent()
```


Получает значение отступа последующих строк.

**Возвращает:**
float - плавающее значение
### getTextRectangle() {#getTextRectangle--}
```
public Rectangle getTextRectangle()
```


Получает прямоугольник текста, помещенного в абзац.

**Возвращает:**
[Rectangle](../../com.aspose.pdf/rectangle) - Прямоугольный объект
### getVerticalAlignment() {#getVerticalAlignment--}
```
public int getVerticalAlignment()
```


Получает вертикальное выравнивание текста внутри Rectangle абзаца.

**Возвращает:**
int — значение вертикального выравнивания
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isJustify() {#isJustify--}
```
public boolean isJustify()
```


Получает значение, выровнен ли текст.

**Возвращает:**
boolean - логическое значение
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.pdf.Color-}
```
public void setBackgroundColor(Color value)
```


Устанавливает цвет фона для текстового абзаца.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Цвет объекта |

### setBackgroundMode(int value) {#setBackgroundMode-int-}
```
public void setBackgroundMode(int value)
```


Установить фоновый режим для текстового абзаца

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setFirstLineIndent(float value) {#setFirstLineIndent-float-}
```
public final void setFirstLineIndent(float value)
```


Получает или задает значение отступа последующих строк. Если задано ненулевое значение, оно имеет преимущество перед значением FormattingOptions.SubsequentLinesIndent.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | плавающее значение |

### setFormattingOptions(TextFormattingOptions value) {#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-}
```
public void setFormattingOptions(TextFormattingOptions value)
```


Устанавливает параметры форматирования.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextFormattingOptions](../../com.aspose.pdf/textformattingoptions) | Объект TextFormattingOptions |

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```


Устанавливает горизонтальное выравнивание для текста внутри прямоугольника абзаца.

HorizontalAlignment.None равно HorizontalAlignment.Left.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение HorizontalAlignment |

### setHyphenSymbol(String value) {#setHyphenSymbol-java.lang.String-}
```
public void setHyphenSymbol(String value)
```


Устанавливает символ дефиса, который используется в процессе переноса.

Символ дефиса по умолчанию «-». Чтобы исключить рисование дефиса (при сохранении процедуры переноса), установите пустую строку string.Empty для HyphenSymbol.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setJustify(boolean value) {#setJustify-boolean-}
```
public void setJustify(boolean value)
```


Устанавливает значение, выравнивается ли текст.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public void setMargin(MarginInfo value)
```


Устанавливает отступ.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | Значение MarginInfo |

### setMatrix(Matrix value) {#setMatrix-com.aspose.pdf.Matrix-}
```
public void setMatrix(Matrix value)
```


Задает поворот абзаца.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.pdf/matrix) | Матрица объекта |

### setOldCodeCompatibilityMode(boolean value) {#setOldCodeCompatibilityMode-boolean-}
```
public void setOldCodeCompatibilityMode(boolean value)
```


Установить режим совместимости со старым кодом

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setPosition(Position value) {#setPosition-com.aspose.pdf.Position-}
```
public void setPosition(Position value)
```


Устанавливает позицию абзаца.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Position](../../com.aspose.pdf/position) | Значение позиции |

### setRectangle(Rectangle value) {#setRectangle-com.aspose.pdf.Rectangle-}
```
public void setRectangle(Rectangle value)
```


Задает прямоугольник абзаца.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | Прямоугольный объект |

### setRotation(double value) {#setRotation-double-}
```
public void setRotation(double value)
```


Получает или задает угол поворота в градусах.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

### setSubsequentLinesIndent(float value) {#setSubsequentLinesIndent-float-}
```
public void setSubsequentLinesIndent(float value)
```


Устанавливает значение отступа последующих строк.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | плавающее значение |

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int value)
```


Устанавливает вертикальное выравнивание текста внутри Rectangle абзаца.

VerticalAlignment.None равно VerticalAlignment.Bottom.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение вертикального выравнивания |

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
