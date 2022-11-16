---
title: Outlines
second_title: Aspose.PDF для справки по Java API
description: Класс описывает набор контуров.
type: docs
weight: 241
url: /ru/java/com.aspose.pdf/outlines/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
java.lang.Iterable
```
public abstract class Outlines implements Iterable<OutlineItemCollection>
```

Класс описывает набор контуров.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Outlines()](#Outlines--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [add(OutlineItemCollection item)](#add-com.aspose.pdf.OutlineItemCollection-) | Добавляет элемент контура в коллекцию. |
| [clear()](#clear--) | Удаляет все элементы из коллекции. |
| [contains(OutlineItemCollection item)](#contains-com.aspose.pdf.OutlineItemCollection-) | Всегда выдает NotImplementedException. |
| [copyTo(OutlineItemCollection[] array, int arrayIndex)](#copyTo-com.aspose.pdf.OutlineItemCollection---int-) | Копирует записи структуры в System.Array, начиная с определенного индекса System.Array. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getVisibleCount()](#getVisibleCount--) | Получает общее количество элементов структуры на всех уровнях иерархии структуры документа. |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | Получает значение, указывающее, доступна ли коллекция только для чтения. |
| [iterator()](#iterator--) | Возвращает перечислитель, который выполняет итерацию по коллекции. |
| [iterator_Rename_Namesake()](#iterator-Rename-Namesake--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(OutlineItemCollection item)](#remove-com.aspose.pdf.OutlineItemCollection-) | Удалить элемент коллекции контуров. |
| [size()](#size--) | Получает счет. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Outlines() {#Outlines--}
```
public Outlines()
```


### add(OutlineItemCollection item) {#add-com.aspose.pdf.OutlineItemCollection-}
```
public abstract void add(OutlineItemCollection item)
```


Добавляет элемент контура в коллекцию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) | Добавляемый элемент схемы. |

### clear() {#clear--}
```
public abstract void clear()
```


Удаляет все элементы из коллекции.

### contains(OutlineItemCollection item) {#contains-com.aspose.pdf.OutlineItemCollection-}
```
public abstract boolean contains(OutlineItemCollection item)
```


Всегда выдает NotImplementedException.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) | Объект, который нужно найти в коллекции |

**Возвращает:**
boolean - логическое значение True - если элемент найден; в противном случае ложно.
### copyTo(OutlineItemCollection[] array, int arrayIndex) {#copyTo-com.aspose.pdf.OutlineItemCollection---int-}
```
public abstract void copyTo(OutlineItemCollection[] array, int arrayIndex)
```


Копирует записи структуры в System.Array, начиная с определенного индекса System.Array.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | [OutlineItemCollection\[\]](../../com.aspose.pdf/outlineitemcollection) | Одномерный System.Array, который является местом назначения. Должен иметь индексацию с отсчетом от нуля. |
| arrayIndex | int | Отсчитываемый от нуля индекс в массиве, с которого начинается копирование. |

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
### getVisibleCount() {#getVisibleCount--}
```
public abstract int getVisibleCount()
```


Получает общее количество элементов структуры на всех уровнях иерархии структуры документа.

**Возвращает:**
интервал - целочисленное значение
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isReadOnly() {#isReadOnly--}
```
public abstract boolean isReadOnly()
```


Получает значение, указывающее, доступна ли коллекция только для чтения.

**Возвращает:**
boolean - логическое значение
### iterator() {#iterator--}
```
public abstract Iterator<OutlineItemCollection> iterator()
```


Возвращает перечислитель, который выполняет итерацию по коллекции.

**Возвращает:**
java.util.Iterator<com.aspose.pdf.OutlineItemCollection> — объект System.Collections.IEnumerator, который можно использовать для перебора коллекции.
### iterator_Rename_Namesake() {#iterator-Rename-Namesake--}
```
public final System.Collections.IEnumerator iterator_Rename_Namesake()
```




**Возвращает:**
com.aspose.ms.System.Collections.IEnumerator
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(OutlineItemCollection item) {#remove-com.aspose.pdf.OutlineItemCollection-}
```
public abstract boolean remove(OutlineItemCollection item)
```


Удалить элемент коллекции контуров.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) | Элемент для удаления. |

**Возвращает:**
boolean - логическое значение True - если элемент удален; в противном случае ложно.
### size() {#size--}
```
public abstract int size()
```


Получает счет.

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
