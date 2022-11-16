---
title: FontSourceCollection
second_title: Aspose.PDF для справки по Java API
description: Представляет коллекцию источников шрифтов.
type: docs
weight: 12
url: /ru/java/com.aspose.pdf.text/fontsourcecollection/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
java.lang.Iterable
```
public final class FontSourceCollection implements Iterable<FontSource>
```

Представляет коллекцию источников шрифтов.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FontSourceCollection()](#FontSourceCollection--) | Инициализирует объект коллекции |
## Поля

| Поле | Описание |
| --- | --- |
| [CollectionChanged](#CollectionChanged) | Событие CollectionChanged |
## Методы

| Метод | Описание |
| --- | --- |
| [add(FontSource fontSource)](#add-com.aspose.pdf.FontSource-) | Добавляет в коллекцию новый исходный объект шрифта. |
| [clear()](#clear--) | Очищает коллекцию источников шрифтов. |
| [contains(FontSource item)](#contains-com.aspose.pdf.FontSource-) | Определяет, находится ли элемент в коллекции. |
| [copyTo(FontSource[] array, int index)](#copyTo-com.aspose.pdf.FontSource---int-) | Копирует всю коллекцию в совместимый одномерный массив, начиная с указанного индекса целевого массива. |
| [delete(FontSource fontSource)](#delete-com.aspose.pdf.FontSource-) | Удаляет исходный элемент шрифта. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getItem(int index)](#getItem-int-) | Получает элемент шрифта по указанному индексу. |
| [getSyncRoot()](#getSyncRoot--) | Получает объект, который можно использовать для синхронизации доступа к коллекции. |
| [hashCode()](#hashCode--) |  |
| [isSynchronized()](#isSynchronized--) | Получает значение, указывающее, является ли доступ к коллекции синхронизированным (потокобезопасным). |
| [iterator()](#iterator--) | Возвращает перечислитель для всей коллекции. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(FontSource item)](#remove-com.aspose.pdf.FontSource-) | Удаляет исходный элемент шрифта. |
| [size()](#size--) | Получает количество элементов объекта Font, фактически содержащихся в коллекции. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FontSourceCollection() {#FontSourceCollection--}
```
public FontSourceCollection()
```


Инициализирует объект коллекции

### CollectionChanged {#CollectionChanged}
```
public final PdfEvent<System.EventHandler> CollectionChanged
```


Событие CollectionChanged

### add(FontSource fontSource) {#add-com.aspose.pdf.FontSource-}
```
public void add(FontSource fontSource)
```


Добавляет в коллекцию новый исходный объект шрифта.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontSource | [FontSource](../../com.aspose.pdf/fontsource) | Источник шрифта. |

### clear() {#clear--}
```
public void clear()
```


Очищает коллекцию источников шрифтов.

### contains(FontSource item) {#contains-com.aspose.pdf.FontSource-}
```
public boolean contains(FontSource item)
```


Определяет, находится ли элемент в коллекции.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [FontSource](../../com.aspose.pdf/fontsource) | Объект FontSource для поиска. |

**Возвращает:**
boolean - True - если элемент найден; в противном случае ложно.
### copyTo(FontSource[] array, int index) {#copyTo-com.aspose.pdf.FontSource---int-}
```
public void copyTo(FontSource[] array, int index)
```


Копирует всю коллекцию в совместимый одномерный массив, начиная с указанного индекса целевого массива.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | [FontSource\[\]](../../com.aspose.pdf/fontsource) | Массив объектов, которые будут скопированы. |
| index | int | Начальный индекс, с которого будет запущено копирование. |

### delete(FontSource fontSource) {#delete-com.aspose.pdf.FontSource-}
```
public void delete(FontSource fontSource)
```


Удаляет исходный элемент шрифта.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontSource | [FontSource](../../com.aspose.pdf/fontsource) | Объект FontSource, который будет удален. |

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
### getItem(int index) {#getItem-int-}
```
public FontSource getItem(int index)
```


Получает элемент шрифта по указанному индексу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Указатель в коллекции. |

**Возвращает:**
[FontSource](../../com.aspose.pdf/fontsource) - Исходный объект шрифта.
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Получает объект, который можно использовать для синхронизации доступа к коллекции.

**Возвращает:**
java.lang.Object — элемент объекта
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Получает значение, указывающее, является ли доступ к коллекции синхронизированным (потокобезопасным).

**Возвращает:**
boolean - логическое значение
### iterator() {#iterator--}
```
public System.Collections.IEnumerator iterator()
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




### remove(FontSource item) {#remove-com.aspose.pdf.FontSource-}
```
public boolean remove(FontSource item)
```


Удаляет исходный элемент шрифта.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [FontSource](../../com.aspose.pdf/fontsource) | Объект FontSource, который будет удален. |

**Возвращает:**
boolean - True - если элемент найден; в противном случае ложно.
### size() {#size--}
```
public int size()
```


Получает количество элементов объекта Font, фактически содержащихся в коллекции.

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
