---
title: TextFragmentCollection
second_title: Aspose.PDF для справки по Java API
description: Представляет коллекцию текстовых фрагментов
type: docs
weight: 374
url: /ru/java/com.aspose.pdf/textfragmentcollection/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
java.lang.Iterable
```
public final class TextFragmentCollection implements Iterable<TextFragment>
```

Представляет коллекцию текстовых фрагментов
## Методы

| Метод | Описание |
| --- | --- |
| [add(TextFragment fragment)](#add-com.aspose.pdf.TextFragment-) | Добавляет элемент текстового фрагмента по указанному индексу. |
| [clear()](#clear--) | Удаляет все элементы из коллекции. |
| [contains(TextFragment item)](#contains-com.aspose.pdf.TextFragment-) | Определяет, содержит ли коллекция определенное значение. |
| [copyTo(TextFragment[] array, int index)](#copyTo-com.aspose.pdf.TextFragment---int-) | Копирует всю коллекцию в совместимый одномерный массив, начиная с указанного индекса целевого массива. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getSyncRoot()](#getSyncRoot--) | Получает объект, который можно использовать для синхронизации доступа к коллекции. |
| [get_Item(int index)](#get-Item-int-) | Получает элемент текстового фрагмента по указанному индексу. |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | Получает значение, указывающее, доступна ли коллекция только для чтения |
| [isSynchronized()](#isSynchronized--) | Получает значение, указывающее, является ли доступ к коллекции синхронизированным (потокобезопасным). |
| [iterator()](#iterator--) | Возвращает перечислитель для всей коллекции. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(TextFragment item)](#remove-com.aspose.pdf.TextFragment-) | Удаляет указанный элемент из коллекции. |
| [size()](#size--) | Получает количество элементов объекта TextFragment, фактически содержащихся в коллекции. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(TextFragment fragment) {#add-com.aspose.pdf.TextFragment-}
```
public void add(TextFragment fragment)
```


Добавляет элемент текстового фрагмента по указанному индексу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fragment | [TextFragment](../../com.aspose.pdf/textfragment) | Добавляемый элемент объекта TextFragment. |

### clear() {#clear--}
```
public void clear()
```


Удаляет все элементы из коллекции.

### contains(TextFragment item) {#contains-com.aspose.pdf.TextFragment-}
```
public boolean contains(TextFragment item)
```


Определяет, содержит ли коллекция определенное значение.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [TextFragment](../../com.aspose.pdf/textfragment) | Объект, который нужно найти в коллекции |

**Возвращает:**
boolean - true, если элемент найден в коллекции; в противном случае ложно.
### copyTo(TextFragment[] array, int index) {#copyTo-com.aspose.pdf.TextFragment---int-}
```
public void copyTo(TextFragment[] array, int index)
```


Копирует всю коллекцию в совместимый одномерный массив, начиная с указанного индекса целевого массива.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | [TextFragment\[\]](../../com.aspose.pdf/textfragment) | Массив объектов, которые будут скопированы. |
| index | int | Начальный индекс, с которого будет запущено копирование. |

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
public TextFragment get_Item(int index)
```


Получает элемент текстового фрагмента по указанному индексу.

 Индекс должен быть в диапазоне[1..n], где n равно количеству фрагментов текста.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Указатель в коллекции. |

**Возвращает:**
[TextFragment](../../com.aspose.pdf/textfragment) - Объект TextFragment.
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
public Iterator<TextFragment> iterator()
```


Возвращает перечислитель для всей коллекции.

**Возвращает:**
java.util.Iterator<com.aspose.pdf.TextFragment> — объект перечислителя.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(TextFragment item) {#remove-com.aspose.pdf.TextFragment-}
```
public boolean remove(TextFragment item)
```


Удаляет указанный элемент из коллекции.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [TextFragment](../../com.aspose.pdf/textfragment) | Объект для удаления |

**Возвращает:**
boolean - true, если элемент был удален из коллекции; в противном случае ложно.
### size() {#size--}
```
public int size()
```


Получает количество элементов объекта TextFragment, фактически содержащихся в коллекции.

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
