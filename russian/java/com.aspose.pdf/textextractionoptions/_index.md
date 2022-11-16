---
title: TextExtractionOptions
second_title: Aspose.PDF для справки по Java API
description: Представляет параметры извлечения текста
type: docs
weight: 370
url: /ru/java/com.aspose.pdf/textextractionoptions/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.TextOptions](../../com.aspose.pdf/textoptions)
```
public final class TextExtractionOptions extends TextOptions
```

Представляет параметры извлечения текста
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TextExtractionOptions(int formattingMode)](#TextExtractionOptions-int-) | Инициализирует новый экземпляр объекта TextExtractionOptions для указанного режима форматирования текста. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFormattingMode()](#getFormattingMode--) | Получает режим форматирования. |
| [getScaleFactor()](#getScaleFactor--) | Получает коэффициент, который будет применяться для масштабирования размера шрифта во время извлечения в чистом режиме. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFormattingMode(int value)](#setFormattingMode-int-) | Устанавливает режим форматирования. |
| [setScaleFactor(double value)](#setScaleFactor-double-) | Устанавливает коэффициент, который будет применяться для масштабирования размера шрифта при извлечении в чистом режиме. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextExtractionOptions(int formattingMode) {#TextExtractionOptions-int-}
```
public TextExtractionOptions(int formattingMode)
```


Инициализирует новый экземпляр объекта TextExtractionOptions для указанного режима форматирования текста.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| formattingMode | int | Значение режима форматирования текста. |

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
### getFormattingMode() {#getFormattingMode--}
```
public int getFormattingMode()
```


Получает режим форматирования.

**Возвращает:**
int — значение TextFormattingMode
### getScaleFactor() {#getScaleFactor--}
```
public double getScaleFactor()
```


Получает коэффициент, который будет применяться для масштабирования размера шрифта во время извлечения в чистом режиме. Установка меньшего значения приводит к большему количеству пробелов в извлеченном тексте. Значение по умолчанию 1 - без масштабирования; Установка значения на ноль позволяет алгоритму автоматически выбирать масштабирование.

**Возвращает:**
двойное - двойное значение
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




### setFormattingMode(int value) {#setFormattingMode-int-}
```
public void setFormattingMode(int value)
```


Устанавливает режим форматирования.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение TextFormattingMode |

### setScaleFactor(double value) {#setScaleFactor-double-}
```
public void setScaleFactor(double value)
```


Устанавливает коэффициент, который будет применяться для масштабирования размера шрифта при извлечении в чистом режиме. Установка меньшего значения приводит к большему количеству пробелов в извлеченном тексте (от 1 до 10). Значение по умолчанию 1 - без масштабирования; Установка значения на ноль позволяет алгоритму автоматически выбирать масштабирование.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | двойное значение |

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
