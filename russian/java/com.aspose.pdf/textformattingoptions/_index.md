---
title: TextFormattingOptions
second_title: Aspose.PDF для справки по Java API
description: Представляет параметры форматирования текста
type: docs
weight: 371
url: /ru/java/com.aspose.pdf/textformattingoptions/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.TextOptions](../../com.aspose.pdf/textoptions)
```
public final class TextFormattingOptions extends TextOptions
```

Представляет параметры форматирования текста
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TextFormattingOptions(int wrapMode)](#TextFormattingOptions-int-) | Инициализирует новый экземпляр объекта TextFormattingOptions для указанного режима переноса слов. |
| [TextFormattingOptions()](#TextFormattingOptions--) | Инициализирует новый экземпляр объекта TextFormattingOptions с неопределенным режимом переноса слов. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirstLineIndent()](#getFirstLineIndent--) | Получает или задает значение отступа первой строки. |
| [getHyphenSymbol()](#getHyphenSymbol--) | Получает или задает символ дефиса, который используется в процессе расстановки переносов. |
| [getLineSpacing()](#getLineSpacing--) | Получает режим межстрочного интервала. |
| [getSubsequentLinesIndent()](#getSubsequentLinesIndent--) | Получает или задает значение отступа последующих строк. |
| [getWrapMode()](#getWrapMode--) | Получает режим переноса слов. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFirstLineIndent(float value)](#setFirstLineIndent-float-) | Получает или задает значение отступа первой строки. |
| [setHyphenSymbol(String value)](#setHyphenSymbol-java.lang.String-) | Получает или задает символ дефиса, который используется в процессе расстановки переносов. |
| [setLineSpacing(int value)](#setLineSpacing-int-) | Устанавливает межстрочный интервал. |
| [setSubsequentLinesIndent(float value)](#setSubsequentLinesIndent-float-) | Получает или задает значение отступа последующих строк. |
| [setWrapMode(int value)](#setWrapMode-int-) | Устанавливает режим переноса слов. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextFormattingOptions(int wrapMode) {#TextFormattingOptions-int-}
```
public TextFormattingOptions(int wrapMode)
```


Инициализирует новый экземпляр объекта TextFormattingOptions для указанного режима переноса слов.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| wrapMode | int | Режим переноса слов. |

### TextFormattingOptions() {#TextFormattingOptions--}
```
public TextFormattingOptions()
```


Инициализирует новый экземпляр объекта TextFormattingOptions с неопределенным режимом переноса слов.

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


Получает или задает значение отступа первой строки.

**Возвращает:**
float - плавающее значение
### getHyphenSymbol() {#getHyphenSymbol--}
```
public final String getHyphenSymbol()
```


Получает или задает символ дефиса, который используется в процессе расстановки переносов.

--------------------

Чтобы исключить рисование дефиса (при сохранении процедуры переноса), установите пустую строку string.Empty для HyphenSymbol.

**Возвращает:**
java.lang.String — строковое значение
### getLineSpacing() {#getLineSpacing--}
```
public int getLineSpacing()
```


Получает режим межстрочного интервала. Значение по умолчанию — LineSpacingMode.FontSize.

**Возвращает:**
интервал - целочисленное значение
### getSubsequentLinesIndent() {#getSubsequentLinesIndent--}
```
public float getSubsequentLinesIndent()
```


Получает или задает значение отступа последующих строк.

**Возвращает:**
float - плавающее значение
### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Получает режим переноса слов. Значение по умолчанию — WordWrapMode.NoWrap.

**Возвращает:**
int - значение WordWrapMode
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




### setFirstLineIndent(float value) {#setFirstLineIndent-float-}
```
public final void setFirstLineIndent(float value)
```


Получает или задает значение отступа первой строки.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | плавающее значение |

### setHyphenSymbol(String value) {#setHyphenSymbol-java.lang.String-}
```
public final void setHyphenSymbol(String value)
```


Получает или задает символ дефиса, который используется в процессе расстановки переносов.

--------------------

Чтобы исключить рисование дефиса (при сохранении процедуры переноса), установите пустую строку string.Empty для HyphenSymbol.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | значение Строковое значение |

### setLineSpacing(int value) {#setLineSpacing-int-}
```
public void setLineSpacing(int value)
```


Устанавливает межстрочный интервал. Значение по умолчанию — LineSpacingMode.FontSize.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

### setSubsequentLinesIndent(float value) {#setSubsequentLinesIndent-float-}
```
public void setSubsequentLinesIndent(float value)
```


Получает или задает значение отступа последующих строк.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | плавающее значение |

### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Устанавливает режим переноса слов. Значение по умолчанию — WordWrapMode.NoWrap.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение WordWrapMode |

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
