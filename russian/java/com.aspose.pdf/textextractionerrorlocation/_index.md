---
title: TextExtractionErrorLocation
second_title: Aspose.PDF для справки по Java API
description: Представляет место в документе PDF, где появилась ошибка извлечения текста.
type: docs
weight: 369
url: /ru/java/com.aspose.pdf/textextractionerrorlocation/
---
**Наследование:**
java.lang.Object
```
public final class TextExtractionErrorLocation
```

Представляет место в документе PDF, где появилась ошибка извлечения текста.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFontUsedKey()](#getFontUsedKey--) | Ключ (имя) объекта PDF Font, который используется для отображения оператора, вызывающего ошибку извлечения текста. |
| [getFormKey()](#getFormKey--) | Ключ (имя) объекта PDF Form XObject, в котором находится ошибка извлечения текста потока содержимого. |
| [getObjectType()](#getObjectType--) | Тип объекта PDF (Страница или xForm), в котором находится ошибка извлечения текста из потока содержимого. |
| [getOperatorIndex()](#getOperatorIndex--) | Индекс текста, показывающего оператор в потоке содержимого (наборе операторов), который вызывает ошибку извлечения текста. |
| [getOperatorString()](#getOperatorString--) | Текст, показывающий оператор, вызывающий ошибку извлечения текста. |
| [getPageNumber()](#getPageNumber--) | Номер страницы документа, на которой обнаружена ошибка извлечения текста. |
| [getPath()](#getPath--) | Расположение документа PDF, в котором возникла ошибка извлечения текста. |
| [getTextStartPoint()](#getTextStartPoint--) | Ключ (имя) объекта PDF Font, который используется для отображения оператора, вызывающего ошибку извлечения текста. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Возвращает строковое представление. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getFontUsedKey() {#getFontUsedKey--}
```
public String getFontUsedKey()
```


Ключ (имя) объекта PDF Font, который используется для отображения оператора, вызывающего ошибку извлечения текста.

**Возвращает:**
java.lang.String — строковое значение
### getFormKey() {#getFormKey--}
```
public String getFormKey()
```


Ключ (имя) объекта PDF Form XObject, в котором находится ошибка извлечения текста потока содержимого. Не пусто, если ObjectType == 'xForm'.

**Возвращает:**
java.lang.String — строковое значение
### getObjectType() {#getObjectType--}
```
public String getObjectType()
```


Тип объекта PDF (Страница или xForm), в котором находится ошибка извлечения текста из потока содержимого.

**Возвращает:**
java.lang.String — строковое значение
### getOperatorIndex() {#getOperatorIndex--}
```
public int getOperatorIndex()
```


Индекс текста, показывающего оператор в потоке содержимого (наборе операторов), который вызывает ошибку извлечения текста.

**Возвращает:**
интервал - целочисленное значение
### getOperatorString() {#getOperatorString--}
```
public String getOperatorString()
```


Текст, показывающий оператор, вызывающий ошибку извлечения текста.

**Возвращает:**
java.lang.String — строковое значение
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Номер страницы документа, на которой обнаружена ошибка извлечения текста.

**Возвращает:**
интервал - целочисленное значение
### getPath() {#getPath--}
```
public String getPath()
```


Расположение документа PDF, в котором возникла ошибка извлечения текста.

**Возвращает:**
java.lang.String — строковое значение
### getTextStartPoint() {#getTextStartPoint--}
```
public Point getTextStartPoint()
```


Ключ (имя) объекта PDF Font, который используется для отображения оператора, вызывающего ошибку извлечения текста.

**Возвращает:**
[Point](../../com.aspose.pdf/point) - экземпляр точки
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


Возвращает строковое представление.

**Возвращает:**
java.lang.String — строковое представление.
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
