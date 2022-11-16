---
title: ReplaceTextStrategy
second_title: Aspose.PDF для справки по Java API
description: Этот класс содержит параметры, определяющие поведение PdfContentEditor при выполнении операции ReplaceText.
type: docs
weight: 57
url: /ru/java/com.aspose.pdf.facades/replacetextstrategy/
---
**Наследование:**
java.lang.Object
```
public final class ReplaceTextStrategy
```

Этот класс содержит параметры, определяющие поведение PdfContentEditor при выполнении операции ReplaceText.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ReplaceTextStrategy()](#ReplaceTextStrategy--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getNoCharacterBehavior()](#getNoCharacterBehavior--) | Действие, которое выполняется, когда для измененного текста не найден подходящий шрифт (Сбросить исключение / Заменить другой шрифт / Заменить в любом случае). |
| [getReplaceScope()](#getReplaceScope--) | Объем операции замены (заменить первое вхождение или заменить все вхождения). |
| [hashCode()](#hashCode--) |  |
| [isRegularExpressionUsed()](#isRegularExpressionUsed--) | Если false, искомая строка представляет собой простой текст. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setNoCharacterBehavior(int value)](#setNoCharacterBehavior-int-) | Действие, которое выполняется, когда для измененного текста не найден подходящий шрифт (Сбросить исключение / Заменить другой шрифт / Заменить в любом случае). |
| [setRegularExpressionUsed(boolean value)](#setRegularExpressionUsed-boolean-) | Если false, искомая строка представляет собой простой текст. |
| [setReplaceScope(int value)](#setReplaceScope-int-) | Объем операции замены (заменить первое вхождение или заменить все вхождения). |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ReplaceTextStrategy() {#ReplaceTextStrategy--}
```
public ReplaceTextStrategy()
```


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
### getNoCharacterBehavior() {#getNoCharacterBehavior--}
```
public int getNoCharacterBehavior()
```


Действие, которое выполняется, когда для измененного текста не найден подходящий шрифт (Сбросить исключение / Заменить другой шрифт / Заменить в любом случае).

**Возвращает:**
int - значение NoCharacterAction.
### getReplaceScope() {#getReplaceScope--}
```
public int getReplaceScope()
```


Объем операции замены (заменить первое вхождение или заменить все вхождения).

**Возвращает:**
int — элемент области видимости
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isRegularExpressionUsed() {#isRegularExpressionUsed--}
```
public boolean isRegularExpressionUsed()
```


Если false, искомая строка представляет собой простой текст. Если true, искомая строка является регулярным выражением.

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




### setNoCharacterBehavior(int value) {#setNoCharacterBehavior-int-}
```
public void setNoCharacterBehavior(int value)
```


Действие, которое выполняется, когда для измененного текста не найден подходящий шрифт (Сбросить исключение / Заменить другой шрифт / Заменить в любом случае).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение NoCharacterAction. |

### setRegularExpressionUsed(boolean value) {#setRegularExpressionUsed-boolean-}
```
public void setRegularExpressionUsed(boolean value)
```


Если false, искомая строка представляет собой простой текст. Если true, искомая строка является регулярным выражением.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | логическое значение |

### setReplaceScope(int value) {#setReplaceScope-int-}
```
public void setReplaceScope(int value)
```


Объем операции замены (заменить первое вхождение или заменить все вхождения).

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | целое значение |

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
