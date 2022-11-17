---
title: TableElementCollection
second_title: Aspose.PDF для справки по Java API
description: Представляет набор элементов, взятых из существующей таблицы.
type: docs
weight: 355
url: /ru/java/com.aspose.pdf/tableelementcollection/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
java.lang.Iterable
```
public final class TableElementCollection<T1> implements Iterable<T1>
```

Представляет набор элементов, взятых из существующей таблицы.

 T : экземпляр типа, реализующего ITableElement. 
## Методы

| Метод | Описание |
| --- | --- |
| [addItem(ITableElement element)](#addItem-com.aspose.pdf.ITableElement-) | Добавляет элемент текстового фрагмента по указанному индексу. |
| [clear()](#clear--) | Удаляет все элементы из коллекции. |
| [containsItem(T1 item)](#containsItem-T1-) | Определяет, содержит ли коллекция определенное значение. |
| [copyToTArray(T1[] array, int index)](#copyToTArray-T1---int-) | Копирует всю коллекцию в совместимый одномерный массив, начиная с указанного индекса целевого массива. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getSyncRoot()](#getSyncRoot--) | Получает объект, который можно использовать для синхронизации доступа к коллекции. |
| [get_Item(int index)](#get-Item-int-) | Получает элемент текстового фрагмента по указанному индексу. |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | Получает значение, указывающее, доступна ли коллекция только для чтения |
| [isSynchronized()](#isSynchronized--) | Получает значение, указывающее, является ли доступ к коллекции синхронизированным (потокобезопасным). |
| [iterator()](#iterator--) | Возвращает перечислитель для всей коллекции. |
| [iterator_Rename_Namesake()](#iterator-Rename-Namesake--) | Возвращает перечислитель для всей коллекции. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeItem(T1 item)](#removeItem-T1-) | Удаляет указанный элемент из коллекции. |
| [size()](#size--) | Получает количество элементов таблицы, фактически содержащихся в коллекции. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addItem(ITableElement element) {#addItem-com.aspose.pdf.ITableElement-}
```
public void addItem(ITableElement element)
```


Добавляет элемент текстового фрагмента по указанному индексу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [ITableElement](../../com.aspose.pdf/itableelement) | Экземпляр ITableElement |

### clear() {#clear--}
```
public void clear()
```


Удаляет все элементы из коллекции.

### containsItem(T1 item) {#containsItem-T1-}
```
public boolean containsItem(T1 item)
```


Определяет, содержит ли коллекция определенное значение.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | T1 | Объект, который нужно найти в коллекции |

**Возвращает:**
boolean - true, если элемент найден в коллекции; в противном случае ложно.
### copyToTArray(T1[] array, int index) {#copyToTArray-T1---int-}
```
public void copyToTArray(T1[] array, int index)
```


Копирует всю коллекцию в совместимый одномерный массив, начиная с указанного индекса целевого массива.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | T1[] | Массив объектов, которые будут скопированы. |
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
java.lang.Object — объект SyncRoot
### get_Item(int index) {#get-Item-int-}
```
public T1 get_Item(int index)
```


Получает элемент текстового фрагмента по указанному индексу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Указатель в коллекции. |

**Возвращает:**
T1 - объект элемента таблицы.
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
public System.Collections.IEnumerator<T1> iterator()
```


Возвращает перечислитель для всей коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.IEnumerator<T1> - Объект перечислителя.
### iterator_Rename_Namesake() {#iterator-Rename-Namesake--}
```
public System.Collections.IEnumerator iterator_Rename_Namesake()
```


Возвращает перечислитель для всей коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.IEnumerator — объект перечислителя.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeItem(T1 item) {#removeItem-T1-}
```
public boolean removeItem(T1 item)
```


Удаляет указанный элемент из коллекции.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | T1 | Объект для удаления |

**Возвращает:**
boolean - true, если элемент был удален из коллекции; в противном случае ложно.
### size() {#size--}
```
public int size()
```


Получает количество элементов таблицы, фактически содержащихся в коллекции.

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
