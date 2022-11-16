---
title: TextState
second_title: Aspose.PDF для справки по Java API
description: Представляет текстовое состояние текста
type: docs
weight: 389
url: /ru/java/com.aspose.pdf/textstate/
---
**Наследование:**
java.lang.Object
```
public class TextState
```

Представляет текстовое состояние текста
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TextState()](#TextState--) | Создает текстовый объект состояния. |
| [TextState(double fontSize)](#TextState-double-) | Создает объект состояния текста с указанием размера шрифта. |
| [TextState(Color foregroundColor)](#TextState-java.awt.Color-) | Создает объект состояния текста с указанием цвета переднего плана. |
| [TextState(Color foregroundColor, double fontSize)](#TextState-java.awt.Color-double-) | Создает объект состояния текста с указанием цвета переднего плана и размера шрифта. |
| [TextState(String fontFamily)](#TextState-java.lang.String-) | Создает объект состояния текста со спецификацией семейства шрифтов. |
| [TextState(String fontFamily, boolean bold, boolean italic)](#TextState-java.lang.String-boolean-boolean-) | Создает объект состояния текста с семейством шрифтов и спецификацией стиля шрифта. |
| [TextState(String fontFamily, double fontSize)](#TextState-java.lang.String-double-) | Создает объект состояния текста с указанием семейства шрифтов и размера шрифта. |
## Поля

| Поле | Описание |
| --- | --- |
| [TabTag](#TabTag) | Вы можете поместить этот тег в текст, чтобы объявить табуляцию. |
| [TabstopDefaultValue](#TabstopDefaultValue) | Значение табуляции по умолчанию в ширине пробела шрифта по умолчанию. |
## Методы

| Метод | Описание |
| --- | --- |
| [applyChangesFrom(TextState textState)](#applyChangesFrom-com.aspose.pdf.TextState-) | Применяет настройки из другого textState |
| [calculateFontSize(String str, Rectangle rect)](#calculateFontSize-java.lang.String-com.aspose.pdf.Rectangle-) | Вычисляет размер шрифта для прямоугольника. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | Получает цвет фона текста. |
| [getCharacterSpacing()](#getCharacterSpacing--) | Получает межсимвольный интервал текста. |
| [getClass()](#getClass--) |  |
| [getFont()](#getFont--) | Получает шрифт текста. |
| [getFontSize()](#getFontSize--) | Получает размер шрифта текста. |
| [getFontStyle()](#getFontStyle--) | Устанавливает стиль шрифта текста. |
| [getForegroundColor()](#getForegroundColor--) | Получает цвет переднего плана текста. |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Выравнивает текст по горизонтали. |
| [getHorizontalScaling()](#getHorizontalScaling--) | Получает горизонтальное масштабирование текста. |
| [getLineSpacing()](#getLineSpacing--) | Получает межстрочный интервал текста. |
| [getRenderingMode()](#getRenderingMode--) | Получает или задает режим рендеринга текста. |
| [getStrikeOut()](#getStrikeOut--) | Вычеркивает текст, представленный объектом TextFragment. |
| [getStrokingColor()](#getStrokingColor--) | Получает или задает цвет переднего плана текста. |
| [getTextHeight()](#getTextHeight--) | Получает высоту текста. |
| [getWordSpacing()](#getWordSpacing--) | Получает межсловный интервал в тексте. |
| [hashCode()](#hashCode--) |  |
| [isInvisible()](#isInvisible--) | Получает или задает невидимость текста. |
| [isSubscript()](#isSubscript--) | Получает или задает нижний индекс текста. |
| [isSuperscript()](#isSuperscript--) | Получает верхний индекс текста. |
| [isUnderline()](#isUnderline--) | Получает подчеркивание текста, представленного объектом TextFragment. |
| [measureString(String str)](#measureString-java.lang.String-) | Измеряет струну. |
| [measureString(String str, boolean insideLine)](#measureString-java.lang.String-boolean-) | Измеряет струну. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | Устанавливает цвет фона текста. |
| [setCharacterSpacing(float value)](#setCharacterSpacing-float-) | Устанавливает межсимвольный интервал в тексте. |
| [setFont(Font value)](#setFont-com.aspose.pdf.Font-) | Получает шрифт текста. |
| [setFontSize(float value)](#setFontSize-float-) | Устанавливает размер шрифта текста. |
| [setFontSizeSuppressedUpdate(float value)](#setFontSizeSuppressedUpdate-float-) | Устанавливает размер шрифта текста, который необходимо отключить при обновлении. |
| [setFontStyle(int value)](#setFontStyle-int-) | Устанавливает стиль шрифта текста. |
| [setFontSuppressedUpdate(Font value)](#setFontSuppressedUpdate-com.aspose.pdf.Font-) | Получает шрифт текста, который желает отключить обновление. |
| [setForegroundColor(Color value)](#setForegroundColor-com.aspose.pdf.Color-) | Устанавливает цвет переднего плана текста. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Задает горизонтальное выравнивание текста. |
| [setHorizontalScaling(float value)](#setHorizontalScaling-float-) | Устанавливает горизонтальное масштабирование текста. |
| [setInvisible(boolean value)](#setInvisible-boolean-) | Получает или задает невидимость текста. |
| [setLineSpacing(float value)](#setLineSpacing-float-) | Устанавливает межстрочный интервал текста. |
| [setRenderingMode(int value)](#setRenderingMode-int-) | Получает или задает режим рендеринга текста. |
| [setStrikeOut(boolean value)](#setStrikeOut-boolean-) | Устанавливает зачеркивание для текста, представленного объектом TextFragment. |
| [setStrokingColor(Color value)](#setStrokingColor-com.aspose.pdf.Color-) | Получает или задает цвет переднего плана текста. |
| [setSubscript(boolean value)](#setSubscript-boolean-) | Получает или задает нижний индекс текста. |
| [setSuperscript(boolean value)](#setSuperscript-boolean-) | Устанавливает верхний индекс текста. |
| [setUnderline(boolean value)](#setUnderline-boolean-) | Устанавливает подчеркивание для текста, представленного объектом TextFragment. |
| [setWordSpacing(float value)](#setWordSpacing-float-) | Устанавливает межсловный интервал в тексте. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextState() {#TextState--}
```
public TextState()
```


Создает текстовый объект состояния.

### TextState(double fontSize) {#TextState-double-}
```
public TextState(double fontSize)
```


Создает объект состояния текста с указанием размера шрифта.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontSize | double | Размер шрифта. |

### TextState(Color foregroundColor) {#TextState-java.awt.Color-}
```
public TextState(Color foregroundColor)
```


Создает объект состояния текста с указанием цвета переднего плана.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| foregroundColor | java.awt.Color | Цвет переднего плана. |

### TextState(Color foregroundColor, double fontSize) {#TextState-java.awt.Color-double-}
```
public TextState(Color foregroundColor, double fontSize)
```


Создает объект состояния текста с указанием цвета переднего плана и размера шрифта.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| foregroundColor | java.awt.Color | Цвет переднего плана. |
| fontSize | double | Размер шрифта. |

### TextState(String fontFamily) {#TextState-java.lang.String-}
```
public TextState(String fontFamily)
```


Создает объект состояния текста со спецификацией семейства шрифтов.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontFamily | java.lang.String | Семейство шрифтов. |

### TextState(String fontFamily, boolean bold, boolean italic) {#TextState-java.lang.String-boolean-boolean-}
```
public TextState(String fontFamily, boolean bold, boolean italic)
```


Создает объект состояния текста с семейством шрифтов и спецификацией стиля шрифта.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontFamily | java.lang.String | Семейство шрифтов. |
| bold | boolean | Жирный стиль шрифта. |
| italic | boolean | Курсивный стиль шрифта. |

### TextState(String fontFamily, double fontSize) {#TextState-java.lang.String-double-}
```
public TextState(String fontFamily, double fontSize)
```


Создает объект состояния текста с указанием семейства шрифтов и размера шрифта.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontFamily | java.lang.String | Семейство шрифтов. |
| fontSize | double | Размер шрифта. |

### TabTag {#TabTag}
```
public static final String TabTag
```


Вы можете поместить этот тег в текст, чтобы объявить табуляцию.

--------------------

Это действует только в паре с TabStops.

### TabstopDefaultValue {#TabstopDefaultValue}
```
public final float TabstopDefaultValue
```


Значение табуляции по умолчанию в ширине пробела шрифта по умолчанию.

### applyChangesFrom(TextState textState) {#applyChangesFrom-com.aspose.pdf.TextState-}
```
public void applyChangesFrom(TextState textState)
```


Применяет настройки из другого textState

--------------------

Будут скопированы только те свойства, которые были изменены явно.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| textState | [TextState](../../com.aspose.pdf/textstate) | Текстовый объект состояния. |

### calculateFontSize(String str, Rectangle rect) {#calculateFontSize-java.lang.String-com.aspose.pdf.Rectangle-}
```
public double calculateFontSize(String str, Rectangle rect)
```


Вычисляет размер шрифта для прямоугольника.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | java.lang.String | Строковое значение |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Прямоугольный объект |

**Возвращает:**
двойное - двойное значение
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
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Получает цвет фона текста.

--------------------

Обратите внимание, что значение не сохраняется как текстовая характеристика в документе. Метод получения свойства BackgroundColor работает для объекта, если он был явно установлен ранее с помощью метода установки BackgroundColor для этого объекта. Свойство используется средой выполнения в контексте текущего процесса генерации/модификации.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - Значение цвета
### getCharacterSpacing() {#getCharacterSpacing--}
```
public float getCharacterSpacing()
```


Получает межсимвольный интервал текста.

**Возвращает:**
float - плавающее значение
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getFont() {#getFont--}
```
public Font getFont()
```


Получает шрифт текста.

**Возвращает:**
[Font](../../com.aspose.pdf/font) - Объект шрифта
### getFontSize() {#getFontSize--}
```
public float getFontSize()
```


Получает размер шрифта текста.

**Возвращает:**
float - плавающее значение
### getFontStyle() {#getFontStyle--}
```
public int getFontStyle()
```


Устанавливает стиль шрифта текста.

**Возвращает:**
int - элемент FontStyles
### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


Получает цвет переднего плана текста.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - Значение цвета
### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


Выравнивает текст по горизонтали.

--------------------

HorizontalAlignment.None равно HorizontalAlignment.Left. Обратите внимание, что свойство TextState.HorizontalAlignment работает только в новых сценариях генерации документов.

**Возвращает:**
int - значение HorizontalAlignment
### getHorizontalScaling() {#getHorizontalScaling--}
```
public float getHorizontalScaling()
```


Получает горизонтальное масштабирование текста.

**Возвращает:**
float - плавающее значение
### getLineSpacing() {#getLineSpacing--}
```
public float getLineSpacing()
```


Получает межстрочный интервал текста.

**Возвращает:**
float - плавающее значение

--------------------

Обратите внимание, что значение не сохраняется как текстовая характеристика в документе. Геттер свойства LineSpacing работает для объекта в случае, если он был явно установлен ранее с помощью установщика LineSpacing для этого объекта. Свойство используется средой выполнения в контексте текущего процесса генерации/модификации.
### getRenderingMode() {#getRenderingMode--}
```
public int getRenderingMode()
```


Получает или задает режим рендеринга текста.

**Возвращает:**
int — элемент TextRenderingMode
### getStrikeOut() {#getStrikeOut--}
```
public boolean getStrikeOut()
```


Вычеркивает текст, представленный объектом TextFragment.

**Возвращает:**
boolean - логическое значение
### getStrokingColor() {#getStrokingColor--}
```
public Color getStrokingColor()
```


Получает или задает цвет переднего плана текста.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - Цветной экземпляр
### getTextHeight() {#getTextHeight--}
```
public float getTextHeight()
```


Получает высоту текста.

**Возвращает:**
float - плавающее значение
### getWordSpacing() {#getWordSpacing--}
```
public float getWordSpacing()
```


Получает межсловный интервал в тексте.

**Возвращает:**
float - плавающее значение
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isInvisible() {#isInvisible--}
```
public boolean isInvisible()
```


Получает или задает невидимость текста. Это в основном отражает RenderingMode (\#getRenderingMode.getRenderingMode/\#setRenderingMode(int).setRenderingMode(int)), за исключением некоторых особых случаев (например, отсечения).

**Возвращает:**
boolean - логическое значение
### isSubscript() {#isSubscript--}
```
public boolean isSubscript()
```


Получает или задает нижний индекс текста.

**Возвращает:**
boolean - логическое значение
### isSuperscript() {#isSuperscript--}
```
public boolean isSuperscript()
```


Получает верхний индекс текста.

**Возвращает:**
boolean - логическое значение
### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


Получает подчеркивание текста, представленного объектом TextFragment.

**Возвращает:**
boolean - логическое значение
### measureString(String str) {#measureString-java.lang.String-}
```
public double measureString(String str)
```


Измеряет струну.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | java.lang.String | Струна. |

**Возвращает:**
double - Ширина строки, представленной этим текстовым состоянием.
### measureString(String str, boolean insideLine) {#measureString-java.lang.String-boolean-}
```
public double measureString(String str, boolean insideLine)
```


Измеряет струну.

--------------------

insideLine указывает, что строка не заканчивается. в случае, если измеряется часть всей строки, внутренняя строка должна быть истинной. в случае, если измеряется вся строка, значение insideLine должно быть ложным. другими словами: в случае insideLine = true учитывается только ширина символов. никакие дополнительные преобразования не учитываются в случае, если insideLine = false конец строки обрабатывается правильно - учитывается курсивное преобразование.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | java.lang.String | Строковое значение |
| insideLine | boolean | логическое значение |

**Возвращает:**
двойное - двойное значение
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


Устанавливает цвет фона текста.

--------------------

Обратите внимание, что значение не сохраняется как текстовая характеристика в документе. Метод получения свойства BackgroundColor работает для объекта, если он был явно установлен ранее с помощью метода установки BackgroundColor для этого объекта. Свойство используется средой выполнения в контексте текущего процесса генерации/модификации.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Значение цвета |

### setCharacterSpacing(float value) {#setCharacterSpacing-float-}
```
public void setCharacterSpacing(float value)
```


Устанавливает межсимвольный интервал в тексте.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | плавающее значение |

### setFont(Font value) {#setFont-com.aspose.pdf.Font-}
```
public void setFont(Font value)
```


Получает шрифт текста.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Font](../../com.aspose.pdf/font) | Объект шрифта |

### setFontSize(float value) {#setFontSize-float-}
```
public void setFontSize(float value)
```


Устанавливает размер шрифта текста.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | плавающее значение |

### setFontSizeSuppressedUpdate(float value) {#setFontSizeSuppressedUpdate-float-}
```
public void setFontSizeSuppressedUpdate(float value)
```


Устанавливает размер шрифта текста, который необходимо отключить при обновлении.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | плавающее значение |

### setFontStyle(int value) {#setFontStyle-int-}
```
public void setFontStyle(int value)
```


Устанавливает стиль шрифта текста.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение стиля шрифта |

### setFontSuppressedUpdate(Font value) {#setFontSuppressedUpdate-com.aspose.pdf.Font-}
```
public void setFontSuppressedUpdate(Font value)
```


Получает шрифт текста, который желает отключить обновление.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Font](../../com.aspose.pdf/font) | Объект шрифта |

### setForegroundColor(Color value) {#setForegroundColor-com.aspose.pdf.Color-}
```
public void setForegroundColor(Color value)
```


Устанавливает цвет переднего плана текста.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Значение цвета |

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```


Задает горизонтальное выравнивание текста.

--------------------

HorizontalAlignment.None равно HorizontalAlignment.Left. Обратите внимание, что свойство TextState.HorizontalAlignment работает только в новых сценариях генерации документов.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение HorizontalAlignment |

### setHorizontalScaling(float value) {#setHorizontalScaling-float-}
```
public void setHorizontalScaling(float value)
```


Устанавливает горизонтальное масштабирование текста.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | плавающее значение |

### setInvisible(boolean value) {#setInvisible-boolean-}
```
public void setInvisible(boolean value)
```


Получает или задает невидимость текста. Это в основном отражает RenderingMode (\#getRenderingMode.getRenderingMode/\#setRenderingMode(int).setRenderingMode(int)), за исключением некоторых особых случаев (например, отсечения).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setLineSpacing(float value) {#setLineSpacing-float-}
```
public void setLineSpacing(float value)
```


Устанавливает межстрочный интервал текста.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | плавающее значение

--------------------

 Обратите внимание, что значение не сохраняется как текстовая характеристика в документе. Геттер свойства LineSpacing работает для объекта в случае, если он был явно установлен ранее с помощью установщика LineSpacing для этого объекта. Свойство используется средой выполнения в контексте текущего процесса генерации/модификации.|

### setRenderingMode(int value) {#setRenderingMode-int-}
```
public void setRenderingMode(int value)
```


Получает или задает режим рендеринга текста.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Элемент TextRenderingMode |

### setStrikeOut(boolean value) {#setStrikeOut-boolean-}
```
public void setStrikeOut(boolean value)
```


Устанавливает зачеркивание для текста, представленного объектом TextFragment.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setStrokingColor(Color value) {#setStrokingColor-com.aspose.pdf.Color-}
```
public void setStrokingColor(Color value)
```


Получает или задает цвет переднего плана текста.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Экземпляр цвета |

### setSubscript(boolean value) {#setSubscript-boolean-}
```
public void setSubscript(boolean value)
```


Получает или задает нижний индекс текста.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setSuperscript(boolean value) {#setSuperscript-boolean-}
```
public void setSuperscript(boolean value)
```


Устанавливает верхний индекс текста.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setUnderline(boolean value) {#setUnderline-boolean-}
```
public void setUnderline(boolean value)
```


Устанавливает подчеркивание для текста, представленного объектом TextFragment.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setWordSpacing(float value) {#setWordSpacing-float-}
```
public void setWordSpacing(float value)
```


Устанавливает межсловный интервал в тексте.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | плавающее значение |

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
