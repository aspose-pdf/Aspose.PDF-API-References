---
title: DestinationCollection
second_title: Aspose.PDF для справки по Java API
description: Класс представляет собой совокупность всех адресатов дерева имен, отображающего строки имен на адресаты, см. 12.3.2.3 Именованные адресаты и 7.7.4 Словарь имен в документе pdf.
type: docs
weight: 84
url: /ru/java/com.aspose.pdf/destinationcollection/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
java.lang.Iterable
```
public final class DestinationCollection implements Iterable<System.Collections.Generic.KeyValuePair<String,Object>>
```

Класс представляет собой набор всех адресатов (дерево имен, отображающее строки имен на адресаты (см. 12.3.2.3, «Именованные адресаты») и (см. 7.7.4, «Словарь имен»)) в документе pdf.
## Методы

| Метод | Описание |
| --- | --- |
| [add(System.Collections.Generic.KeyValuePair<String,Object> item)](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-java.lang.Object--) | Добавляет указанный элемент. |
| [clear()](#clear--) | Коллекция доступна только для чтения. |
| [contains(System.Collections.Generic.KeyValuePair<String,Object> value)](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-java.lang.Object--) | Определяет, содержит ли этот экземпляр объект. |
| [copyTo(System.Collections.Generic.KeyValuePair<String,Object>[] array, int arrayIndex)](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-java.lang.Object----int-) | Копирует элементы коллекции в массив, начиная с определенного индекса массива. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExplicitDestination(String destinameName, boolean useCache)](#getExplicitDestination-java.lang.String-boolean-) | Возвращает явное место назначения по имени. |
| [getPageNumber(String destinameName, boolean useCache)](#getPageNumber-java.lang.String-boolean-) | Возвращает номер страницы назначения по имени. |
| [get_Item(int index)](#get-Item-int-) | Получает целевой объект по индексу. |
| [hashCode()](#hashCode--) |  |
| [indexOf(System.Collections.Generic.KeyValuePair<String,Object> value)](#indexOf-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-java.lang.Object--) | Возвращает индекс назначения в коллекции. |
| [isReadOnly()](#isReadOnly--) | Получает значение, указывающее, доступна ли коллекция только для чтения. |
| [iterator()](#iterator--) | Возвращает перечислитель. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(System.Collections.Generic.KeyValuePair<String,Object> item)](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-java.lang.Object--) | Удаляет указанный элемент. |
| [size()](#size--) | Получает количество элементов, содержащихся в коллекции. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(System.Collections.Generic.KeyValuePair<String,Object> item) {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-java.lang.Object--}
```
public void add(System.Collections.Generic.KeyValuePair<String,Object> item)
```


Добавляет указанный элемент. Коллекция доступна только для чтения. Всегда выдает исключение NotSupportedException.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object> | Предмет. |

### clear() {#clear--}
```
public void clear()
```


Коллекция доступна только для чтения. Всегда выдает исключение NotSupportedException.

### contains(System.Collections.Generic.KeyValuePair<String,Object> value) {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-java.lang.Object--}
```
public boolean contains(System.Collections.Generic.KeyValuePair<String,Object> value)
```


Определяет, содержит ли этот экземпляр объект.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object> | Значение, которое нужно найти. |

**Возвращает:**
 логическое значение - верно, если[ содержит][указанное значение]; в противном случае ложь.
### copyTo(System.Collections.Generic.KeyValuePair<String,Object>[] array, int arrayIndex) {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-java.lang.Object----int-}
```
public void copyTo(System.Collections.Generic.KeyValuePair<String,Object>[] array, int arrayIndex)
```


Копирует элементы коллекции в массив, начиная с определенного индекса массива.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object>[] | Одномерный массив, который является местом назначения элементов, скопированных из коллекции. |
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
### getExplicitDestination(String destinameName, boolean useCache) {#getExplicitDestination-java.lang.String-boolean-}
```
public ExplicitDestination getExplicitDestination(String destinameName, boolean useCache)
```


Возвращает явное место назначения по имени.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| destinameName | java.lang.String | Название пункта назначения. |
| useCache | boolean | Определяет, используется ли кэшированная версия коллекции. |

**Возвращает:**
[ExplicitDestination](../../com.aspose.pdf/explicitdestination) Объект ExplicitDestination для пункта назначения найден; в противном случае ноль.
### getPageNumber(String destinameName, boolean useCache) {#getPageNumber-java.lang.String-boolean-}
```
public int getPageNumber(String destinameName, boolean useCache)
```


Возвращает номер страницы назначения по имени.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| destinameName | java.lang.String | Название пункта назначения. |
| useCache | boolean | Определяет, используется ли кэшированная версия коллекции. |

**Возвращает:**
int - Номер страницы, если место назначения найдено; иначе -1.
### get_Item(int index) {#get-Item-int-}
```
public System.Collections.Generic.KeyValuePair<String,Object> get_Item(int index)
```


Получает целевой объект по индексу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс получателя. |

**Возвращает:**
[KeyValuePair](../../com.aspose.ms.system.collections.generic/keyvaluepair) - Назначения.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### indexOf(System.Collections.Generic.KeyValuePair<String,Object> value) {#indexOf-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-java.lang.Object--}
```
public int indexOf(System.Collections.Generic.KeyValuePair<String,Object> value)
```


Возвращает индекс назначения в коллекции.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object> | Значение, которое нужно найти. |

**Возвращает:**
int — индекс назначения в коллекции.
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Получает значение, указывающее, доступна ли коллекция только для чтения.

**Возвращает:**
boolean - логическое значение
### iterator() {#iterator--}
```
public System.Collections.IEnumerator<System.Collections.Generic.KeyValuePair<String,Object>> iterator()
```


Возвращает перечислитель.

**Возвращает:**
com.aspose.ms.System.Collections.IEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object>> — перечислитель.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(System.Collections.Generic.KeyValuePair<String,Object> item) {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-java.lang.Object--}
```
public boolean remove(System.Collections.Generic.KeyValuePair<String,Object> item)
```


Удаляет указанный элемент. Коллекция доступна только для чтения. Всегда выдает исключение NotSupportedException.

еще не поддерживается.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object> | Предмет. |

**Возвращает:**
boolean - логическое значение
### size() {#size--}
```
public int size()
```


Получает количество элементов, содержащихся в коллекции.

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
