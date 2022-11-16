---
title: NamedAction
second_title: Aspose.PDF для справки по Java API
description: Представляет именованные действия, которые должны поддерживать приложения для просмотра PDF.
type: docs
weight: 225
url: /ru/java/com.aspose.pdf/namedaction/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.PdfAction](../../com.aspose.pdf/pdfaction)
```
public final class NamedAction extends PdfAction
```

Представляет именованные действия, которые должны поддерживать приложения для просмотра PDF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [NamedAction(int action)](#NamedAction-int-) | Конструктор для класса Named Action. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | Получает действие, которое необходимо выполнить. |
| [getNext()](#getNext--) | Следующие действия по порядку. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setName(String value)](#setName-java.lang.String-) | Устанавливает действие, которое необходимо выполнить. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NamedAction(int action) {#NamedAction-int-}
```
public NamedAction(int action)
```


Конструктор для класса Named Action.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| action | int | Действие, для которого создан этот объект. |

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
### getName() {#getName--}
```
public String getName()
```


Получает действие, которое необходимо выполнить.

**Возвращает:**
java.lang.String — строковое значение
### getNext() {#getNext--}
```
public ActionCollection getNext()
```


Следующие действия по порядку.

**Возвращает:**
[ActionCollection](../../com.aspose.pdf/actioncollection) - Объект ActionCollection
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




### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Устанавливает действие, которое необходимо выполнить.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение |

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
