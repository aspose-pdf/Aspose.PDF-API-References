---
title: OutlineCollection
second_title: Aspose.PDF для справки по Java API
description: Представляет иерархию структуры документа.
type: docs
weight: 239
url: /ru/java/com.aspose.pdf/outlinecollection/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.Outlines](../../com.aspose.pdf/outlines)
```
public final class OutlineCollection extends Outlines
```

Представляет иерархию структуры документа.
## Методы

| Метод | Описание |
| --- | --- |
| [add(OutlineItemCollection outline)](#add-com.aspose.pdf.OutlineItemCollection-) | Добавляет элемент контура в коллекцию. |
| [clear()](#clear--) | Удаляет все элементы из коллекции. |
| [contains(OutlineItemCollection item)](#contains-com.aspose.pdf.OutlineItemCollection-) | Пока не поддерживается. |
| [copyTo(OutlineItemCollection[] array, int index)](#copyTo-com.aspose.pdf.OutlineItemCollection---int-) | Копирует элементы структуры в System.Array, начиная с определенного индекса System.Array. |
| [delete()](#delete--) | Удаляет все элементы структуры из структуры документа. |
| [delete(String name)](#delete-java.lang.String-) | Удаляет элемент структуры с указанным заголовком из структуры документа. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirst()](#getFirst--) | Получает элемент структуры, представляющий первый элемент верхнего уровня в структуре. |
| [getLast()](#getLast--) | Получает элемент структуры, представляющий последний элемент верхнего уровня в структуре. |
| [getSyncRoot()](#getSyncRoot--) | Получает объект, который можно использовать для синхронизации доступа к этой коллекции. |
| [getVisibleCount()](#getVisibleCount--) | Количество — это сумма количества видимых элементов структуры потомков на всех уровнях. |
| [get_Item(int index)](#get-Item-int-) | Получает элемент схемы из коллекции по индексу. |
| [hasNext()](#hasNext--) |  |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | Получает значение, указывающее, доступна ли коллекция только для чтения. |
| [isSynchronized()](#isSynchronized--) | Получает значение, указывающее, является ли доступ к этой коллекции синхронизированным (потокобезопасным). |
| [iterator()](#iterator--) | Возвращает перечислитель, который выполняет итерацию по коллекции. |
| [iterator_Rename_Namesake()](#iterator-Rename-Namesake--) |  |
| [next()](#next--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(OutlineItemCollection item)](#remove-com.aspose.pdf.OutlineItemCollection-) | Пока не поддерживается. |
| [remove(int index)](#remove-int-) | Удалить элемент по индексу. |
| [size()](#size--) | Получает общее количество элементов структуры (закладок) на всех уровнях структуры документа. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(OutlineItemCollection outline) {#add-com.aspose.pdf.OutlineItemCollection-}
```
public void add(OutlineItemCollection outline)
```


Добавляет элемент контура в коллекцию.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| outline | [OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) | Добавляемый элемент схемы. |

### clear() {#clear--}
```
public void clear()
```


Удаляет все элементы из коллекции.

### contains(OutlineItemCollection item) {#contains-com.aspose.pdf.OutlineItemCollection-}
```
public boolean contains(OutlineItemCollection item)
```


Пока не поддерживается.

Проверяет, содержит ли коллекция данный элемент.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) | Объект, который нужно найти в коллекции |

**Возвращает:**
boolean - логическое значение True - если элемент найден; в противном случае ложно.
### copyTo(OutlineItemCollection[] array, int index) {#copyTo-com.aspose.pdf.OutlineItemCollection---int-}
```
public void copyTo(OutlineItemCollection[] array, int index)
```


Копирует элементы структуры в System.Array, начиная с определенного индекса System.Array.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | [OutlineItemCollection\[\]](../../com.aspose.pdf/outlineitemcollection) | Одномерный System.Array, который является местом назначения. Должен иметь индексацию с отсчетом от нуля. |
| index | int | Отсчитываемый от нуля индекс в массиве, с которого начинается копирование. |

### delete() {#delete--}
```
public void delete()
```


Удаляет все элементы структуры из структуры документа.

### delete(String name) {#delete-java.lang.String-}
```
public void delete(String name)
```


Удаляет элемент структуры с указанным заголовком из структуры документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Название элемента схемы, которое нужно удалить |

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
### getFirst() {#getFirst--}
```
public OutlineItemCollection getFirst()
```


Получает элемент структуры, представляющий первый элемент верхнего уровня в структуре.

**Возвращает:**
[OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) - Объект OutlineItemCollection
### getLast() {#getLast--}
```
public OutlineItemCollection getLast()
```


Получает элемент структуры, представляющий последний элемент верхнего уровня в структуре.

**Возвращает:**
[OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) - Объект OutlineItemCollection
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Получает объект, который можно использовать для синхронизации доступа к этой коллекции.

**Возвращает:**
java.lang.Object — Объект для синхронизации
### getVisibleCount() {#getVisibleCount--}
```
public int getVisibleCount()
```


Количество — это сумма количества видимых элементов структуры потомков на всех уровнях. Примечание: пожалуйста, не путайте с Count, который является числом предметов в коллекции.

**Возвращает:**
инт
### get_Item(int index) {#get-Item-int-}
```
public OutlineItemCollection get_Item(int index)
```


Получает элемент схемы из коллекции по индексу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс запрашиваемого элемента. |

**Возвращает:**
[OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) - Объект OutlineItemCollection
### hasNext() {#hasNext--}
```
public boolean hasNext()
```




**Возвращает:**
логический
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


Получает значение, указывающее, доступна ли коллекция только для чтения.

**Возвращает:**
boolean - логическое значение
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Получает значение, указывающее, является ли доступ к этой коллекции синхронизированным (потокобезопасным).

**Возвращает:**
boolean - логическое значение
### iterator() {#iterator--}
```
public Iterator<OutlineItemCollection> iterator()
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
### next() {#next--}
```
public OutlineItemCollection next()
```




**Возвращает:**
[OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection)
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
public boolean remove(OutlineItemCollection item)
```


Пока не поддерживается.

Всегда выдает исключение

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) | Объект, который нужно найти в коллекции |

**Возвращает:**
boolean - логическое значение True - если элемент удален; в противном случае ложно.
### remove(int index) {#remove-int-}
```
public final void remove(int index)
```


Удалить элемент по индексу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс удаляемого элемента. |

### size() {#size--}
```
public int size()
```


Получает общее количество элементов структуры (закладок) на всех уровнях структуры документа.

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
