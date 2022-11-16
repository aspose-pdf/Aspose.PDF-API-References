---
title: DefaultAppearance
second_title: Aspose.PDF для справки по Java API
description: Описывает внешний вид по умолчанию размера и цвета текста шрифта поля.
type: docs
weight: 82
url: /ru/java/com.aspose.pdf/defaultappearance/
---
**Наследование:**
java.lang.Object
```
public final class DefaultAppearance
```

Описывает внешний вид поля по умолчанию (шрифт, размер текста и цвет).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [DefaultAppearance()](#DefaultAppearance--) | Конструктор DefaultAppearance. |
| [DefaultAppearance(IPdfDictionary engineDict)](#DefaultAppearance-com.aspose.pdf.engine.data.IPdfDictionary-) |  |
| [DefaultAppearance(IPdfPrimitive appearance)](#DefaultAppearance-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |
| [DefaultAppearance(String fontName, double fontSize, Color textColor)](#DefaultAppearance-java.lang.String-double-java.awt.Color-) | Конструктор DefaultAppearance. |
| [DefaultAppearance(Font font, double fontSize, Color textColor)](#DefaultAppearance-com.aspose.pdf.Font-double-java.awt.Color-) | Конструктор DefaultAppearance. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFont()](#getFont--) | Получает шрифт, указанный по умолчанию для текста. |
| [getFontName()](#getFontName--) | Получает имя шрифта в виде по умолчанию. |
| [getFontResourceName()](#getFontResourceName--) | Получает имя шрифта в виде по умолчанию. |
| [getFontSize()](#getFontSize--) | Получает размер шрифта по умолчанию. |
| [getText()](#getText--) | Получает список операторов PDF, представляющих внешний вид. |
| [getTextColor()](#getTextColor--) | Получает цвет текста по умолчанию. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFontName(String value)](#setFontName-java.lang.String-) | Получает имя шрифта в виде по умолчанию. |
| [setFontResourceName(String value)](#setFontResourceName-java.lang.String-) | Получает имя шрифта в виде по умолчанию. |
| [setFontSize(double value)](#setFontSize-double-) | Устанавливает размер шрифта по умолчанию. |
| [setTextColor(Color color)](#setTextColor-java.awt.Color-) | Устанавливает цвет текста по умолчанию. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DefaultAppearance() {#DefaultAppearance--}
```
public DefaultAppearance()
```


Конструктор DefaultAppearance.

### DefaultAppearance(IPdfDictionary engineDict) {#DefaultAppearance-com.aspose.pdf.engine.data.IPdfDictionary-}
```
public DefaultAppearance(IPdfDictionary engineDict)
```


**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| engineDict | [IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) |  |

### DefaultAppearance(IPdfPrimitive appearance) {#DefaultAppearance-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public DefaultAppearance(IPdfPrimitive appearance)
```


**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| appearance | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) |  |

### DefaultAppearance(String fontName, double fontSize, Color textColor) {#DefaultAppearance-java.lang.String-double-java.awt.Color-}
```
public DefaultAppearance(String fontName, double fontSize, Color textColor)
```


Конструктор DefaultAppearance.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | java.lang.String | Название шрифта. |
| fontSize | double | Размер шрифта. |
| textColor | java.awt.Color | Цвет текста. |

### DefaultAppearance(Font font, double fontSize, Color textColor) {#DefaultAppearance-com.aspose.pdf.Font-double-java.awt.Color-}
```
public DefaultAppearance(Font font, double fontSize, Color textColor)
```


Конструктор DefaultAppearance.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| font | [Font](../../com.aspose.pdf/font) | Шрифт, который будет использоваться по умолчанию. |
| fontSize | double | Размер шрифта. |
| textColor | java.awt.Color | Цвет текста. |

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
### getFont() {#getFont--}
```
public Font getFont()
```


Получает шрифт, указанный по умолчанию для текста.

**Возвращает:**
[Font](../../com.aspose.pdf/font) - Значение шрифта
### getFontName() {#getFontName--}
```
public String getFontName()
```


Получает имя шрифта в виде по умолчанию.

**Возвращает:**
java.lang.String — строковое значение
### getFontResourceName() {#getFontResourceName--}
```
public final String getFontResourceName()
```


Получает имя шрифта в виде по умолчанию.

**Возвращает:**
java.lang.String — строковое значение
### getFontSize() {#getFontSize--}
```
public double getFontSize()
```


Получает размер шрифта по умолчанию.

**Возвращает:**
двойной - размер шрифта
### getText() {#getText--}
```
public String getText()
```


Получает список операторов PDF, представляющих внешний вид.

**Возвращает:**
java.lang.String — строковое значение
### getTextColor() {#getTextColor--}
```
public Color getTextColor()
```


Получает цвет текста по умолчанию.

**Возвращает:**
[Color](../../java.awt/color) - Цвет объекта
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




### setFontName(String value) {#setFontName-java.lang.String-}
```
public void setFontName(String value)
```


Получает имя шрифта в виде по умолчанию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setFontResourceName(String value) {#setFontResourceName-java.lang.String-}
```
public final void setFontResourceName(String value)
```


Получает имя шрифта в виде по умолчанию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

### setFontSize(double value) {#setFontSize-double-}
```
public void setFontSize(double value)
```


Устанавливает размер шрифта по умолчанию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | размер шрифта |

### setTextColor(Color color) {#setTextColor-java.awt.Color-}
```
public void setTextColor(Color color)
```


Устанавливает цвет текста по умолчанию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| color | java.awt.Color | Цвет объекта |

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
