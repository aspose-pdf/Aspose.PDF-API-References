---
title: PdfEvent
second_title: Aspose.PDF для справки по Java API
description: Класс, представляющий события
type: docs
weight: 277
url: /ru/java/com.aspose.pdf/pdfevent/
---
**Наследование:**
java.lang.Object
```
public abstract class PdfEvent<T>
```

Класс, представляющий события
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfEvent()](#PdfEvent--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [add(T delegate)](#add-T-) | Добавьте еще одного делегата. |
| [assign(T delegate)](#assign-T-) | Добавить только текущего делегата, сняв остальные. |
| [clear()](#clear--) | Очистить список делегатов |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [isEmpty()](#isEmpty--) | Возвращает true, если список обработчиков пуст. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(T delegate)](#remove-T-) | Удалить делегата из списка |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfEvent() {#PdfEvent--}
```
public PdfEvent()
```


### add(T delegate) {#add-T-}
```
public final void add(T delegate)
```


Добавьте еще одного делегата.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| delegate | T | Объект обработчиков |

### assign(T delegate) {#assign-T-}
```
public final void assign(T delegate)
```


Добавить только текущего делегата, сняв остальные.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| delegate | T | Объект обработчиков |

### clear() {#clear--}
```
public final void clear()
```


Очистить список делегатов

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
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Возвращает true, если список обработчиков пуст.

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




### remove(T delegate) {#remove-T-}
```
public final void remove(T delegate)
```


Удалить делегата из списка

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| delegate | T | Объект обработчиков |

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
