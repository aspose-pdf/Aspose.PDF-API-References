---
title: PdfActionCollection
second_title: Aspose.PDF для справки по Java API
description: Класс описывает список действий.
type: docs
weight: 276
url: /ru/java/com.aspose.pdf/pdfactioncollection/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
java.lang.Iterable
```
public class PdfActionCollection implements Iterable<PdfAction>
```

Класс описывает список действий.
## Методы

| Метод | Описание |
| --- | --- |
| [add(PdfAction action)](#add-com.aspose.pdf.PdfAction-) | Добавить действие в список действий. |
| [delete(int index)](#delete-int-) | Удалить действие по индексу. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Получает количество действий. |
| [get_Item(int index)](#get-Item-int-) | Получает действие по его индексу. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Получает перечислитель. |
| [iterator_Rename_Namesake()](#iterator-Rename-Namesake--) | Внутренний метод |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(PdfAction action) {#add-com.aspose.pdf.PdfAction-}
```
public void add(PdfAction action)
```


Добавить действие в список действий.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| action | [PdfAction](../../com.aspose.pdf/pdfaction) | Экземпляр PdfAction Добавляемое действие. |

### delete(int index) {#delete-int-}
```
public void delete(int index)
```


Удалить действие по индексу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс действий по удалению. |

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
### getCount() {#getCount--}
```
public int getCount()
```


Получает количество действий.

**Возвращает:**
интервал - целочисленное значение
### get_Item(int index) {#get-Item-int-}
```
public PdfAction get_Item(int index)
```


Получает действие по его индексу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Значение индекса действия. |

**Возвращает:**
[PdfAction](../../com.aspose.pdf/pdfaction) - индекс PdfAction, если он найден; иначе бросает
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<PdfAction> iterator()
```


Получает перечислитель.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.pdf.PdfAction> — перечислитель PDfAction.
### iterator_Rename_Namesake() {#iterator-Rename-Namesake--}
```
public System.Collections.IEnumerator<PdfAction> iterator_Rename_Namesake()
```


Внутренний метод

**Возвращает:**
com.aspose.ms.System.Collections.IEnumerator<com.aspose.pdf.PdfAction> — внутренний объект.
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
