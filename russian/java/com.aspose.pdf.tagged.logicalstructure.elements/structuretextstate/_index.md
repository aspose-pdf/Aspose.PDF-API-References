---
title: StructureTextState
second_title: Aspose.PDF для справки по Java API
description: Представляет параметры состояния текста для элементов текстовой структуры и TaggedContent ITextElement ITaggedContent
type: docs
weight: 19
url: /ru/java/com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate/
---
**Наследование:**
java.lang.Object
```
public class StructureTextState
```

Представляет параметры состояния текста для элементов текстовой структуры и TaggedContent (ITextElement, ITaggedContent).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [StructureTextState()](#StructureTextState--) | Конструктор по умолчанию |
## Методы

| Метод | Описание |
| --- | --- |
| [createTextState()](#createTextState--) | Создать текстовое состояние |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | Получает или задает цвет фона текста. |
| [getCharacterSpacing()](#getCharacterSpacing--) | Получает или задает межсимвольный интервал в тексте. |
| [getClass()](#getClass--) |  |
| [getFont()](#getFont--) | Получает или задает шрифт текста. |
| [getFontSize()](#getFontSize--) | Получает или задает размер шрифта текста. |
| [getFontStyle()](#getFontStyle--) | Получает или задает стиль шрифта текста. |
| [getForegroundColor()](#getForegroundColor--) | Получает или задает цвет переднего плана текста. |
| [getHorizontalScaling()](#getHorizontalScaling--) | Получает или задает горизонтальное масштабирование текста. |
| [getLineSpacing()](#getLineSpacing--) | Получает или задает межстрочный интервал текста. |
| [getMarginInfo()](#getMarginInfo--) | Получает или задает поле для элемента блочной структуры. |
| [getStrikeOut()](#getStrikeOut--) | Получает или задает зачеркивание текста. |
| [getSubscript()](#getSubscript--) | Получает или задает нижний индекс текста. |
| [getSuperscript()](#getSuperscript--) | Получает или задает верхний индекс текста. |
| [getUnderline()](#getUnderline--) | Получает или задает подчеркивание текста. |
| [getWordSpacing()](#getWordSpacing--) | Получает или задает интервал между словами в тексте. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | Получает или задает цвет фона текста. |
| [setCharacterSpacing(Float value)](#setCharacterSpacing-java.lang.Float-) | Получает или задает межсимвольный интервал в тексте. |
| [setFont(Font value)](#setFont-com.aspose.pdf.Font-) | Получает или задает шрифт текста. |
| [setFontSize(Float value)](#setFontSize-java.lang.Float-) | Получает или задает размер шрифта текста. |
| [setFontStyle(Integer value)](#setFontStyle-java.lang.Integer-) | Получает или задает стиль шрифта текста. |
| [setForegroundColor(Color value)](#setForegroundColor-com.aspose.pdf.Color-) | Получает или задает цвет переднего плана текста. |
| [setHorizontalScaling(Float value)](#setHorizontalScaling-java.lang.Float-) | Получает или задает горизонтальное масштабирование текста. |
| [setLineSpacing(Float value)](#setLineSpacing-java.lang.Float-) | Получает или задает межстрочный интервал текста. |
| [setMarginInfo(MarginInfo value)](#setMarginInfo-com.aspose.pdf.MarginInfo-) | Получает или задает поле для элемента блочной структуры. |
| [setStrikeOut(Boolean value)](#setStrikeOut-java.lang.Boolean-) | Получает или задает зачеркивание текста. |
| [setSubscript(Boolean value)](#setSubscript-java.lang.Boolean-) | Получает или задает нижний индекс текста. |
| [setSuperscript(Boolean value)](#setSuperscript-java.lang.Boolean-) | Получает или задает верхний индекс текста. |
| [setUnderline(Boolean value)](#setUnderline-java.lang.Boolean-) | Получает или задает подчеркивание текста. |
| [setWordSpacing(Float value)](#setWordSpacing-java.lang.Float-) | Получает или задает интервал между словами в тексте. |
| [toString()](#toString--) |  |
| [update(StructureTextState structureTextState)](#update-com.aspose.pdf.tagged.logicalstructure.elements.StructureTextState-) | Обновить элементы |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StructureTextState() {#StructureTextState--}
```
public StructureTextState()
```


Конструктор по умолчанию

### createTextState() {#createTextState--}
```
public final TextState createTextState()
```


Создать текстовое состояние

**Возвращает:**
[TextState](../../com.aspose.pdf/textstate) - Экземпляр TextState
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
public final Color getBackgroundColor()
```


Получает или задает цвет фона текста.

Может быть нулевым. Используйте null для наследования свойства BackgroundColor от родительского элемента структуры.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - Цветной экземпляр
### getCharacterSpacing() {#getCharacterSpacing--}
```
public final Float[] getCharacterSpacing()
```


Получает или задает межсимвольный интервал в тексте.

Может быть нулевым. Используйте null для наследования свойства CharacterSpacing от родительского элемента структуры.

**Возвращает:**
java.lang.Float[- Массив с плавающей запятой
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getFont() {#getFont--}
```
public final Font getFont()
```


Получает или задает шрифт текста.

Может быть нулевым. Используйте null для наследования свойства Font от родительского элемента структуры.

**Возвращает:**
[Font](../../com.aspose.pdf/font) - Экземпляр шрифта
### getFontSize() {#getFontSize--}
```
public final Float[] getFontSize()
```


Получает или задает размер шрифта текста.

Может быть нулевым. Используйте null для наследования свойства FontSize от родительского элемента структуры.

**Возвращает:**
java.lang.Float[- Массив с плавающей запятой
### getFontStyle() {#getFontStyle--}
```
public final Integer[] getFontStyle()
```


Получает или задает стиль шрифта текста.

Может быть нулевым. Используйте null для наследования свойства FontStyle от родительского элемента структуры.

**Возвращает:**
java.lang.Integer[] - Целочисленный массив
### getForegroundColor() {#getForegroundColor--}
```
public final Color getForegroundColor()
```


Получает или задает цвет переднего плана текста.

Может быть нулевым. Используйте null для наследования свойства ForegroundColor от родительского элемента структуры.

**Возвращает:**
[Color](../../com.aspose.pdf/color) - Цветной экземпляр
### getHorizontalScaling() {#getHorizontalScaling--}
```
public final Float[] getHorizontalScaling()
```


Получает или задает горизонтальное масштабирование текста.

Может быть нулевым. Используйте null, чтобы наследовать свойство HorizontalScaling от родительского элемента структуры.

**Возвращает:**
java.lang.Float[- Массив с плавающей запятой
### getLineSpacing() {#getLineSpacing--}
```
public final Float[] getLineSpacing()
```


Получает или задает межстрочный интервал текста.

Может быть нулевым. Используйте null для наследования свойства LineSpacing от родительского элемента структуры.

**Возвращает:**
java.lang.Float[- Массив с плавающей запятой
### getMarginInfo() {#getMarginInfo--}
```
public final MarginInfo getMarginInfo()
```


Получает или задает поле для элемента блочной структуры.

**Возвращает:**
[MarginInfo](../../com.aspose.pdf/margininfo) - Экземпляр MarginInfo
### getStrikeOut() {#getStrikeOut--}
```
public final Boolean[] getStrikeOut()
```


Получает или задает зачеркивание текста.

Может быть нулевым. Используйте null для наследования свойства StrikeOut от родительского элемента структуры.

**Возвращает:**
java.lang.Boolean[] - Логический массив
### getSubscript() {#getSubscript--}
```
public final Boolean[] getSubscript()
```


Получает или задает нижний индекс текста.

Может быть нулевым. Используйте null для наследования свойства Subscript от родительского элемента структуры.

**Возвращает:**
java.lang.Boolean[] - Логический массив
### getSuperscript() {#getSuperscript--}
```
public final Boolean[] getSuperscript()
```


Получает или задает верхний индекс текста.

Может быть нулевым. Используйте null для наследования свойства Superscript от родительского элемента структуры.

**Возвращает:**
java.lang.Boolean[] - Логический массив
### getUnderline() {#getUnderline--}
```
public final Boolean[] getUnderline()
```


Получает или задает подчеркивание текста.

Может быть нулевым. Используйте null для наследования свойства Underline от родительского элемента структуры.

**Возвращает:**
java.lang.Boolean[] - Логический массив
### getWordSpacing() {#getWordSpacing--}
```
public final Float[] getWordSpacing()
```


Получает или задает интервал между словами в тексте.

Может быть нулевым. Используйте null для наследования свойства WordSpacing от родительского элемента структуры.

**Возвращает:**
java.lang.Float[- Массив с плавающей запятой
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




### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.pdf.Color-}
```
public final void setBackgroundColor(Color value)
```


Получает или задает цвет фона текста.

Может быть нулевым. Используйте null для наследования свойства BackgroundColor от родительского элемента структуры.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Экземпляр цвета |

### setCharacterSpacing(Float value) {#setCharacterSpacing-java.lang.Float-}
```
public final void setCharacterSpacing(Float value)
```


Получает или задает межсимвольный интервал в тексте.

Может быть нулевым. Используйте null для наследования свойства CharacterSpacing от родительского элемента структуры.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Float | Плавающее значение |

### setFont(Font value) {#setFont-com.aspose.pdf.Font-}
```
public final void setFont(Font value)
```


Получает или задает шрифт текста.

Может быть нулевым. Используйте null для наследования свойства Font от родительского элемента структуры.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Font](../../com.aspose.pdf/font) | Экземпляр шрифта |

### setFontSize(Float value) {#setFontSize-java.lang.Float-}
```
public final void setFontSize(Float value)
```


Получает или задает размер шрифта текста.

Может быть нулевым. Используйте null для наследования свойства FontSize от родительского элемента структуры.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Float | Плавающее значение |

### setFontStyle(Integer value) {#setFontStyle-java.lang.Integer-}
```
public final void setFontStyle(Integer value)
```


Получает или задает стиль шрифта текста.

Может быть нулевым. Используйте null для наследования свойства FontStyle от родительского элемента структуры.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Integer | Значение элемента FontStyle |

### setForegroundColor(Color value) {#setForegroundColor-com.aspose.pdf.Color-}
```
public final void setForegroundColor(Color value)
```


Получает или задает цвет переднего плана текста.

Может быть нулевым. Используйте null для наследования свойства ForegroundColor от родительского элемента структуры.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Экземпляр цвета |

### setHorizontalScaling(Float value) {#setHorizontalScaling-java.lang.Float-}
```
public final void setHorizontalScaling(Float value)
```


Получает или задает горизонтальное масштабирование текста.

Может быть нулевым. Используйте null, чтобы наследовать свойство HorizontalScaling от родительского элемента структуры.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Float | Плавающее значение |

### setLineSpacing(Float value) {#setLineSpacing-java.lang.Float-}
```
public final void setLineSpacing(Float value)
```


Получает или задает межстрочный интервал текста.

Может быть нулевым. Используйте null для наследования свойства LineSpacing от родительского элемента структуры.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Float | Плавающее значение |

### setMarginInfo(MarginInfo value) {#setMarginInfo-com.aspose.pdf.MarginInfo-}
```
public final void setMarginInfo(MarginInfo value)
```


Получает или задает поле для элемента блочной структуры.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | Экземпляр MarginInfo |

### setStrikeOut(Boolean value) {#setStrikeOut-java.lang.Boolean-}
```
public final void setStrikeOut(Boolean value)
```


Получает или задает зачеркивание текста.

Может быть нулевым. Используйте null для наследования свойства StrikeOut от родительского элемента структуры.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Boolean | Логическое значение |

### setSubscript(Boolean value) {#setSubscript-java.lang.Boolean-}
```
public final void setSubscript(Boolean value)
```


Получает или задает нижний индекс текста.

Может быть нулевым. Используйте null для наследования свойства Subscript от родительского элемента структуры.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Boolean | Логическое значение |

### setSuperscript(Boolean value) {#setSuperscript-java.lang.Boolean-}
```
public final void setSuperscript(Boolean value)
```


Получает или задает верхний индекс текста.

Может быть нулевым. Используйте null для наследования свойства Superscript от родительского элемента структуры.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Boolean | Логическое значение |

### setUnderline(Boolean value) {#setUnderline-java.lang.Boolean-}
```
public final void setUnderline(Boolean value)
```


Получает или задает подчеркивание текста.

Может быть нулевым. Используйте null для наследования свойства Underline от родительского элемента структуры.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Boolean | Логическое значение |

### setWordSpacing(Float value) {#setWordSpacing-java.lang.Float-}
```
public final void setWordSpacing(Float value)
```


Получает или задает интервал между словами в тексте.

Может быть нулевым. Используйте null для наследования свойства WordSpacing от родительского элемента структуры.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Float | Плавающее значение |

### toString() {#toString--}
```
public String toString()
```




**Возвращает:**
java.lang.String
### update(StructureTextState structureTextState) {#update-com.aspose.pdf.tagged.logicalstructure.elements.StructureTextState-}
```
public final void update(StructureTextState structureTextState)
```


Обновить элементы

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| structureTextState | [StructureTextState](../../com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate) | Экземпляр StructureTextState |

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
