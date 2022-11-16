---
title: TextSegmentCollection
second_title: Aspose.PDF для справки по Java API
description: Представляет коллекцию текстовых сегментов
type: docs
weight: 387
url: /ru/java/com.aspose.pdf/textsegmentcollection/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
java.lang.Iterable
```
public final class TextSegmentCollection implements Iterable<TextSegment>
```

Представляет коллекцию текстовых сегментов
## Методы

| Метод | Описание |
| --- | --- |
| [add(TextSegment segment)](#add-com.aspose.pdf.TextSegment-) | Добавляет элемент текстового сегмента по указанному индексу. |
| [clear()](#clear--) | Удаляет все элементы из коллекции. |
| [contains(TextSegment item)](#contains-com.aspose.pdf.TextSegment-) | Определяет, содержит ли коллекция определенное значение. |
| [copyTo(TextSegment[] array, int index)](#copyTo-com.aspose.pdf.TextSegment---int-) | Копирует всю коллекцию в совместимый одномерный массив, начиная с указанного индекса целевого массива. |
| [delete(int index)](#delete-int-) | Удаляет элемент текстового сегмента по указанному индексу. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getSyncRoot()](#getSyncRoot--) | Получает объект, который можно использовать для синхронизации доступа к коллекции. |
| [get_Item(int index)](#get-Item-int-) | Получает элемент текстового сегмента по указанному индексу. |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | Получает значение, указывающее, доступна ли коллекция только для чтения |
| [isSynchronized()](#isSynchronized--) | Получает значение, указывающее, является ли доступ к коллекции синхронизированным (потокобезопасным). |
| [iterator()](#iterator--) | Возвращает перечислитель для всей коллекции. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(TextSegment item)](#remove-com.aspose.pdf.TextSegment-) | Удаляет указанный элемент из коллекции. |
| [size()](#size--) | Получает количество элементов объекта TextSegment, фактически содержащихся в коллекции. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(TextSegment segment) {#add-com.aspose.pdf.TextSegment-}
```
public void add(TextSegment segment)
```


Добавляет элемент текстового сегмента по указанному индексу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| segment | [TextSegment](../../com.aspose.pdf/textsegment) | Объект текстового сегмента |

### clear() {#clear--}
```
public void clear()
```


Удаляет все элементы из коллекции.

### contains(TextSegment item) {#contains-com.aspose.pdf.TextSegment-}
```
public boolean contains(TextSegment item)
```


Определяет, содержит ли коллекция определенное значение.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [TextSegment](../../com.aspose.pdf/textsegment) | Объект, который нужно найти в коллекции |

**Возвращает:**
boolean - true, если элемент найден в коллекции; в противном случае ложно.
### copyTo(TextSegment[] array, int index) {#copyTo-com.aspose.pdf.TextSegment---int-}
```
public void copyTo(TextSegment[] array, int index)
```


Копирует всю коллекцию в совместимый одномерный массив, начиная с указанного индекса целевого массива.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | [TextSegment\[\]](../../com.aspose.pdf/textsegment) | Массив объектов, которые будут скопированы. |
| index | int | Начальный индекс, с которого будет запущено копирование. |

### delete(int index) {#delete-int-}
```
public void delete(int index)
```


Удаляет элемент текстового сегмента по указанному индексу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | целое значение |

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


Получает объект, который можно использовать для синхронизации доступа к коллекции.

**Возвращает:**
java.lang.Object — элемент объекта
### get_Item(int index) {#get-Item-int-}
```
public TextSegment get_Item(int index)
```


Получает элемент текстового сегмента по указанному индексу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Указатель в коллекции. |

**Возвращает:**
[TextSegment](../../com.aspose.pdf/textsegment) - Объект TextSegment.
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


Получает значение, указывающее, доступна ли коллекция только для чтения

**Возвращает:**
boolean - логическое значение
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Получает значение, указывающее, является ли доступ к коллекции синхронизированным (потокобезопасным).

**Возвращает:**
boolean - логическое значение
### iterator() {#iterator--}
```
public Iterator<TextSegment> iterator()
```


Возвращает перечислитель для всей коллекции.

**Возвращает:**
java.util.Iterator<com.aspose.pdf.TextSegment> — объект перечислителя.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(TextSegment item) {#remove-com.aspose.pdf.TextSegment-}
```
public boolean remove(TextSegment item)
```


Удаляет указанный элемент из коллекции.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [TextSegment](../../com.aspose.pdf/textsegment) | Объект для удаления |

**Возвращает:**
boolean - true, если элемент был удален из коллекции; в противном случае ложно.
### size() {#size--}
```
public int size()
```


Получает количество элементов объекта TextSegment, фактически содержащихся в коллекции.

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
