---
title: FormattedText
second_title: Aspose.PDF для справки по Java API
description: Класс, представляющий форматированный текст.
type: docs
weight: 30
url: /ru/java/com.aspose.pdf.facades/formattedtext/
---
**Наследование:**
java.lang.Object
```
public final class FormattedText
```

Класс, представляющий форматированный текст. Содержит информацию о тексте и его цвете, размере, стиле.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FormattedText()](#FormattedText--) | Инициализирует форматированный текст. |
| [FormattedText(String text)](#FormattedText-java.lang.String-) | Инициализирует форматированный текст. |
| [FormattedText(String text, FontColor fontColor, int fontStyle, int encodingType, boolean embedded, float textSize)](#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-int-int-boolean-float-) | Инициализирует форматированный текст. |
| [FormattedText(String text, FontColor fontColor, int textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing)](#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-int-int-boolean-float-float-) | Инициализировать форматированный текст. |
| [FormattedText(String text, Color color, int textFont, int textEncoding, boolean embedded, float textSize)](#FormattedText-java.lang.String-java.awt.Color-int-int-boolean-float-) | Инициализирует форматированный текст. |
| [FormattedText(String text, Color textColor, int textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing)](#FormattedText-java.lang.String-java.awt.Color-int-int-boolean-float-float-) | Инициализирует форматированный текст. |
| [FormattedText(String text, FontColor textColor, FontColor backColor, int textFont, int textEncoding, boolean embedded, float textSize)](#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-com.aspose.pdf.facades.FontColor-int-int-boolean-float-) | Инициализирует форматированный текст. |
| [FormattedText(String text, FontColor textColor, FontColor backColor, int textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing)](#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-com.aspose.pdf.facades.FontColor-int-int-boolean-float-float-) | Инициализирует форматированный текст. |
| [FormattedText(String text, Color textColor, Color backColor, int textFont, int encoding, boolean embedded, float textSize)](#FormattedText-java.lang.String-java.awt.Color-java.awt.Color-int-int-boolean-float-) | Инициализирует форматированный текст. |
| [FormattedText(String text, Color textColor, Color backColor, int textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing)](#FormattedText-java.lang.String-java.awt.Color-java.awt.Color-int-int-boolean-float-float-) | Инициализирует форматированный текст. |
| [FormattedText(String text, Color textColor, Color backColor, String fontName, int textEncoding, boolean embedded, float fontSize)](#FormattedText-java.lang.String-java.awt.Color-java.awt.Color-java.lang.String-int-boolean-float-) | Инициализирует форматированный текст. |
| [FormattedText(String text, Color textColor, Color backColor)](#FormattedText-java.lang.String-java.awt.Color-java.awt.Color-) | Инициализирует форматированный текст. |
| [FormattedText(String text, Color textColor, String fontName, int textEncoding, boolean embedded, float fontSize)](#FormattedText-java.lang.String-java.awt.Color-java.lang.String-int-boolean-float-) | Инициализирует форматированный текст. |
## Методы

| Метод | Описание |
| --- | --- |
| [addNewLineText(String newLineText)](#addNewLineText-java.lang.String-) | Добавляет новую строку в объект FormattedText и задает для newLineText текст следующей строки. |
| [addNewLineText(String newLineText, float lineSpacing)](#addNewLineText-java.lang.String-float-) | Добавляет новую строку в объект FormattedText и задает для newLineText текст следующей строки. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackColor()](#getBackColor--) | Внутренний возвращает цвет |
| [getClass()](#getClass--) |  |
| [getFirstLine()](#getFirstLine--) | Получает первую строку |
| [getFont()](#getFont--) | Получает шрифт |
| [getFontSize()](#getFontSize--) | Получает размер шрифта |
| [getText()](#getText--) | Только для внутреннего использования |
| [getTextColor()](#getTextColor--) | Внутренний Получает цвет текста |
| [getTextHeight()](#getTextHeight--) | Получает высоту текста. |
| [getTextWidth()](#getTextWidth--) | Получает ширину текста. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FormattedText() {#FormattedText--}
```
public FormattedText()
```


Инициализирует форматированный текст.

### FormattedText(String text) {#FormattedText-java.lang.String-}
```
public FormattedText(String text)
```


Инициализирует форматированный текст.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст, содержащийся в FormattedText. |

### FormattedText(String text, FontColor fontColor, int fontStyle, int encodingType, boolean embedded, float textSize) {#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-int-int-boolean-float-}
```
public FormattedText(String text, FontColor fontColor, int fontStyle, int encodingType, boolean embedded, float textSize)
```


Инициализирует форматированный текст.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текстовое содержимое строки. |
| fontColor | [FontColor](../../com.aspose.pdf.facades/fontcolor) | Цвет текста. |
| fontStyle | int | Стиль текста. |
| encodingType | int | Тип кодировки (значение перечисления EncodingType). |
| embedded | boolean | Истинно, если шрифт будет встроен. |
| textSize | float | Размер текста. |

### FormattedText(String text, FontColor fontColor, int textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing) {#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-int-int-boolean-float-float-}
```
public FormattedText(String text, FontColor fontColor, int textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing)
```


Инициализировать форматированный текст.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текстовое содержимое строки. |
| fontColor | [FontColor](../../com.aspose.pdf.facades/fontcolor) | Цвет текста. |
| textFont | int | Шрифт текста. |
| textEncoding | int | Кодировка текста. |
| embedded | boolean | Истинно, если текст будет встроен. |
| textSize | float | Размер текста. |
| lineSpacing | float | Дополнительный интервал. |

### FormattedText(String text, Color color, int textFont, int textEncoding, boolean embedded, float textSize) {#FormattedText-java.lang.String-java.awt.Color-int-int-boolean-float-}
```
public FormattedText(String text, Color color, int textFont, int textEncoding, boolean embedded, float textSize)
```


Инициализирует форматированный текст.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текстовое содержимое строки. |
| color | java.awt.Color | Цвет текста. |
| textFont | int | Шрифт текста. |
| textEncoding | int | Кодировка текста. |
| embedded | boolean | Истинно, если текст будет встроен. |
| textSize | float | Размер текста. |

### FormattedText(String text, Color textColor, int textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing) {#FormattedText-java.lang.String-java.awt.Color-int-int-boolean-float-float-}
```
public FormattedText(String text, Color textColor, int textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing)
```


Инициализирует форматированный текст.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текстовое содержимое строки. |
| textColor | java.awt.Color | Цвет текста. |
| textFont | int | Шрифт текста. |
| textEncoding | int | Кодировка текста. |
| embedded | boolean | Если true шрифт будет встроен. |
| textSize | float | Размер текста. |
| lineSpacing | float | Дополнительный интервал. |

### FormattedText(String text, FontColor textColor, FontColor backColor, int textFont, int textEncoding, boolean embedded, float textSize) {#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-com.aspose.pdf.facades.FontColor-int-int-boolean-float-}
```
public FormattedText(String text, FontColor textColor, FontColor backColor, int textFont, int textEncoding, boolean embedded, float textSize)
```


Инициализирует форматированный текст.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текстовое содержимое строки. |
| textColor | [FontColor](../../com.aspose.pdf.facades/fontcolor) | Цвет текста. |
| backColor | [FontColor](../../com.aspose.pdf.facades/fontcolor) | Цвет фона. |
| textFont | int | Шрифт текста. |
| textEncoding | int | Кодировка текста. |
| embedded | boolean | Если true шрифт будет встроен. |
| textSize | float | Размер текста. |

### FormattedText(String text, FontColor textColor, FontColor backColor, int textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing) {#FormattedText-java.lang.String-com.aspose.pdf.facades.FontColor-com.aspose.pdf.facades.FontColor-int-int-boolean-float-float-}
```
public FormattedText(String text, FontColor textColor, FontColor backColor, int textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing)
```


Инициализирует форматированный текст.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текстовое содержание. |
| textColor | [FontColor](../../com.aspose.pdf.facades/fontcolor) | Цвет текста. |
| backColor | [FontColor](../../com.aspose.pdf.facades/fontcolor) | Цвет фона. |
| textFont | int | Шрифт текста. |
| textEncoding | int | Кодировка текста. |
| embedded | boolean | Если true шрифт будет встроен. |
| textSize | float | Размер текста. |
| lineSpacing | float | Дополнительный интервал. |

### FormattedText(String text, Color textColor, Color backColor, int textFont, int encoding, boolean embedded, float textSize) {#FormattedText-java.lang.String-java.awt.Color-java.awt.Color-int-int-boolean-float-}
```
public FormattedText(String text, Color textColor, Color backColor, int textFont, int encoding, boolean embedded, float textSize)
```


Инициализирует форматированный текст.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текстовое содержимое строки. |
| textColor | java.awt.Color | Цвет текста. |
| backColor | java.awt.Color | Цвет фона. |
| textFont | int | Шрифт текста. |
| encoding | int | Кодировка текста. |
| embedded | boolean | Истинно, если шрифт будет встроен. |
| textSize | float | Размер текста. |

### FormattedText(String text, Color textColor, Color backColor, int textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing) {#FormattedText-java.lang.String-java.awt.Color-java.awt.Color-int-int-boolean-float-float-}
```
public FormattedText(String text, Color textColor, Color backColor, int textFont, int textEncoding, boolean embedded, float textSize, float lineSpacing)
```


Инициализирует форматированный текст.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текстовое содержимое строки. |
| textColor | java.awt.Color | Цвет текста. |
| backColor | java.awt.Color | Цвет фона. |
| textFont | int | Шрифт текста. |
| textEncoding | int | Кодировка текста. |
| embedded | boolean | Если истинный шрифт встроен. |
| textSize | float | Размер текста. |
| lineSpacing | float | Дополнительный интервал. |

### FormattedText(String text, Color textColor, Color backColor, String fontName, int textEncoding, boolean embedded, float fontSize) {#FormattedText-java.lang.String-java.awt.Color-java.awt.Color-java.lang.String-int-boolean-float-}
```
public FormattedText(String text, Color textColor, Color backColor, String fontName, int textEncoding, boolean embedded, float fontSize)
```


Инициализирует форматированный текст.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текстовое содержание. |
| textColor | java.awt.Color | Цвет текста. |
| backColor | java.awt.Color | Цвет фона. |
| fontName | java.lang.String | Шрифт текста. |
| textEncoding | int | Кодировка текста. |
| embedded | boolean | Если true шрифт будет встроен. |
| fontSize | float | Размер текста. |

### FormattedText(String text, Color textColor, Color backColor) {#FormattedText-java.lang.String-java.awt.Color-java.awt.Color-}
```
public FormattedText(String text, Color textColor, Color backColor)
```


Инициализирует форматированный текст.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текстовое содержание. |
| textColor | java.awt.Color | Цвет текста. |
| backColor | java.awt.Color | Цвет фона. |

### FormattedText(String text, Color textColor, String fontName, int textEncoding, boolean embedded, float fontSize) {#FormattedText-java.lang.String-java.awt.Color-java.lang.String-int-boolean-float-}
```
public FormattedText(String text, Color textColor, String fontName, int textEncoding, boolean embedded, float fontSize)
```


Инициализирует форматированный текст.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текстовое содержание. |
| textColor | java.awt.Color | Цвет текста. |
| fontName | java.lang.String | Шрифт текста. |
| textEncoding | int | Кодировка текста. |
| embedded | boolean | Если true шрифт будет встроен. |
| fontSize | float | Размер текста. |

### addNewLineText(String newLineText) {#addNewLineText-java.lang.String-}
```
public void addNewLineText(String newLineText)
```


Добавляет новую строку в объект FormattedText и задает для newLineText текст следующей строки.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| newLineText | java.lang.String | Текст новой добавленной строки. |

### addNewLineText(String newLineText, float lineSpacing) {#addNewLineText-java.lang.String-float-}
```
public void addNewLineText(String newLineText, float lineSpacing)
```


Добавляет новую строку в объект FormattedText и задает для newLineText текст следующей строки.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| newLineText | java.lang.String | Текст новой добавленной строки. |
| lineSpacing | float | Расстояние между строками. |

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
### getBackColor() {#getBackColor--}
```
public System.Drawing.Color getBackColor()
```


Внутренний возвращает цвет

**Возвращает:**
[Color](../../com.aspose.ms.system.drawing/color) - Цветовой элемент
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getFirstLine() {#getFirstLine--}
```
public String getFirstLine()
```


Получает первую строку

**Возвращает:**
java.lang.String — строковое значение
### getFont() {#getFont--}
```
public Font getFont()
```


Получает шрифт

**Возвращает:**
[Font](../../com.aspose.pdf/font) - Элемент шрифта
### getFontSize() {#getFontSize--}
```
public float getFontSize()
```


Получает размер шрифта

**Возвращает:**
float - плавающее значение
### getText() {#getText--}
```
public System.Collections.Generic.List<String> getText()
```


Только для внутреннего использования

**Возвращает:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> — внутренний объект
### getTextColor() {#getTextColor--}
```
public System.Drawing.Color getTextColor()
```


Внутренний Получает цвет текста

**Возвращает:**
[Color](../../com.aspose.ms.system.drawing/color) - Цветовой элемент
### getTextHeight() {#getTextHeight--}
```
public float getTextHeight()
```


Получает высоту текста.

**Возвращает:**
float - плавающее значение
### getTextWidth() {#getTextWidth--}
```
public float getTextWidth()
```


Получает ширину текста.

**Возвращает:**
float - плавающее значение
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
