---
title: ActionCollection
second_title: Aspose.PDF для справки по Java API
description: Коллекция действий
type: docs
weight: 14
url: /ru/java/com.aspose.pdf/actioncollection/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
java.lang.Iterable
```
public final class ActionCollection implements Iterable<PdfAction>
```

Коллекция действий
## Методы

| Метод | Описание |
| --- | --- |
| [add(PdfAction action)](#add-com.aspose.pdf.PdfAction-) | Добавляет новое действие в коллекцию. |
| [clear()](#clear--) | Очистить коллекцию. |
| [contains(PdfAction item)](#contains-com.aspose.pdf.PdfAction-) | Пока не поддерживается. |
| [copyTo(PdfAction[] array, int index)](#copyTo-com.aspose.pdf.PdfAction---int-) | Копирует массив действий в коллекцию. |
| [delete()](#delete--) | Удалить все действия. |
| [delete(int index)](#delete-int-) | Удаляет действие из коллекции по индексу. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getSyncRoot()](#getSyncRoot--) | Получает объект синхронизации. |
| [get_Item(int index)](#get-Item-int-) | Получает действие по его индексу. |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | Возвращает true, если коллекция доступна только для чтения. |
| [isSynchronized()](#isSynchronized--) | Возвращает true, если объект синхронизирован. |
| [iterator()](#iterator--) | Возвращает перечислитель для коллекции. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(PdfAction item)](#remove-com.aspose.pdf.PdfAction-) | \* Пока не поддерживается. |
| [size()](#size--) | Количество действий над коллекцией. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(PdfAction action) {#add-com.aspose.pdf.PdfAction-}
```
public void add(PdfAction action)
```


Добавляет новое действие в коллекцию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| action | [PdfAction](../../com.aspose.pdf/pdfaction) | Действие, которое следует добавить. |

### clear() {#clear--}
```
public void clear()
```


Очистить коллекцию.

### contains(PdfAction item) {#contains-com.aspose.pdf.PdfAction-}
```
public boolean contains(PdfAction item)
```


Пока не поддерживается.

Возвращает true, если данный элемент присутствует в коллекции.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [PdfAction](../../com.aspose.pdf/pdfaction) | Экземпляр PdfAction Не реализован. |

**Возвращает:**
boolean - логическое значение Элемент для поиска.
### copyTo(PdfAction[] array, int index) {#copyTo-com.aspose.pdf.PdfAction---int-}
```
public void copyTo(PdfAction[] array, int index)
```


Копирует массив действий в коллекцию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | [PdfAction\[\]](../../com.aspose.pdf/pdfaction) | Массив действий, которые необходимо скопировать в коллекцию. |
| index | int | Индекс, начиная с которого будет скопирован массив. |

### delete() {#delete--}
```
public void delete()
```


Удалить все действия.

### delete(int index) {#delete-int-}
```
public void delete(int index)
```


Удаляет действие из коллекции по индексу.

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
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Получает объект синхронизации.

**Возвращает:**
java.lang.Object — значение объекта
### get_Item(int index) {#get-Item-int-}
```
public PdfAction get_Item(int index)
```


Получает действие по его индексу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс действия. |

**Возвращает:**
[PdfAction](../../com.aspose.pdf/pdfaction) - Восстановленное действие.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Возвращает true, если коллекция доступна только для чтения.

**Возвращает:**
boolean - логическое значение
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Возвращает true, если объект синхронизирован.

**Возвращает:**
boolean - логическое значение
### iterator() {#iterator--}
```
public System.Collections.IEnumerator<PdfAction> iterator()
```


Возвращает перечислитель для коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.IEnumerator<com.aspose.pdf.PdfAction> — перечислитель коллекций.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(PdfAction item) {#remove-com.aspose.pdf.PdfAction-}
```
public boolean remove(PdfAction item)
```


\* Пока не поддерживается.

Удаляет предмет из коллекции.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [PdfAction](../../com.aspose.pdf/pdfaction) | Элемент для удаления. |

**Возвращает:**
boolean - логическое значение Не реализовано.
### size() {#size--}
```
public int size()
```


Количество действий над коллекцией.

**Возвращает:**
интервал - целочисленное значение
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
