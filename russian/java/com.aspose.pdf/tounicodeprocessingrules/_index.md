---
title: ToUnicodeProcessingRules
second_title: Aspose.PDF для справки по Java API
description: Этот класс описывает правила, которые можно использовать для устранения ошибки Adobe Preflight. Текст не может быть сопоставлен с Unicode.
type: docs
weight: 392
url: /ru/java/com.aspose.pdf/tounicodeprocessingrules/
---
**Наследование:**
java.lang.Object
```
public class ToUnicodeProcessingRules
```

Этот класс описывает правила, которые можно использовать для устранения ошибки Adobe Preflight «Текст не может быть сопоставлен с Unicode».
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ToUnicodeProcessingRules()](#ToUnicodeProcessingRules--) | Конструктор |
| [ToUnicodeProcessingRules(boolean removeSpaces)](#ToUnicodeProcessingRules-boolean-) | Конструктор |
| [ToUnicodeProcessingRules(boolean removeSpaces, boolean mapNonLinkedUnicodesOnSpace)](#ToUnicodeProcessingRules-boolean-boolean-) | Конструктор |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMapNonLinkedSymbolsOnSpace()](#getMapNonLinkedSymbolsOnSpace--) | Некоторые шрифты не предоставляют информацию об юникодах для некоторых текстовых символов. |
| [getRemoveSpacesFromCMapNames()](#getRemoveSpacesFromCMapNames--) | Некоторые шрифты имеют карты кодов символов ToUnicode с пробелами в именах. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMapNonLinkedSymbolsOnSpace(boolean value)](#setMapNonLinkedSymbolsOnSpace-boolean-) | Некоторые шрифты не предоставляют информацию об юникодах для некоторых текстовых символов. |
| [setRemoveSpacesFromCMapNames(boolean value)](#setRemoveSpacesFromCMapNames-boolean-) | Некоторые шрифты имеют карты кодов символов ToUnicode с пробелами в именах. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ToUnicodeProcessingRules() {#ToUnicodeProcessingRules--}
```
public ToUnicodeProcessingRules()
```


Конструктор

### ToUnicodeProcessingRules(boolean removeSpaces) {#ToUnicodeProcessingRules-boolean-}
```
public ToUnicodeProcessingRules(boolean removeSpaces)
```


Конструктор

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| removeSpaces | boolean | устанавливает флаг RemoveSpacesFromCMapNames |

### ToUnicodeProcessingRules(boolean removeSpaces, boolean mapNonLinkedUnicodesOnSpace) {#ToUnicodeProcessingRules-boolean-boolean-}
```
public ToUnicodeProcessingRules(boolean removeSpaces, boolean mapNonLinkedUnicodesOnSpace)
```


Конструктор

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| removeSpaces | boolean | устанавливает флаг RemoveSpacesFromCMapNames |
| mapNonLinkedUnicodesOnSpace | boolean | устанавливает флаг MapNonLinkedSymbolsOnSpace |

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
### getMapNonLinkedSymbolsOnSpace() {#getMapNonLinkedSymbolsOnSpace--}
```
public boolean getMapNonLinkedSymbolsOnSpace()
```


Некоторые шрифты не предоставляют информацию об юникодах для некоторых текстовых символов. Это отсутствие информации вызывает ошибку «Текст не может быть сопоставлен с Unicode». Используйте этот флаг для сопоставления несвязанных символов с «пробелом» юникода (код 32).

**Возвращает:**
boolean - логическое значение
### getRemoveSpacesFromCMapNames() {#getRemoveSpacesFromCMapNames--}
```
public boolean getRemoveSpacesFromCMapNames()
```


Некоторые шрифты имеют карты кодов символов ToUnicode с пробелами в именах. Эти пробелы могут вызывать ошибки при отображении текста Unicode. Этот флаг указывает на удаление пробелов из имен карт кодов символов ToUnicode. По умолчанию ложь.

**Возвращает:**
boolean - логическое значение
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




### setMapNonLinkedSymbolsOnSpace(boolean value) {#setMapNonLinkedSymbolsOnSpace-boolean-}
```
public void setMapNonLinkedSymbolsOnSpace(boolean value)
```


Некоторые шрифты не предоставляют информацию об юникодах для некоторых текстовых символов. Это отсутствие информации вызывает ошибку «Текст не может быть сопоставлен с Unicode». Используйте этот флаг для сопоставления несвязанных символов с «пробелом» юникода (код 32).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setRemoveSpacesFromCMapNames(boolean value) {#setRemoveSpacesFromCMapNames-boolean-}
```
public void setRemoveSpacesFromCMapNames(boolean value)
```


Некоторые шрифты имеют карты кодов символов ToUnicode с пробелами в именах. Эти пробелы могут вызывать ошибки при отображении текста Unicode. Этот флаг указывает на удаление пробелов из имен карт кодов символов ToUnicode. По умолчанию ложь.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

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
