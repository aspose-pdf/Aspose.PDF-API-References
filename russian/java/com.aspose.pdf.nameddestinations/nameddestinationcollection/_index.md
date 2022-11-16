---
title: NamedDestinationCollection
second_title: Aspose.PDF для справки по Java API
description: Класс представляет собой совокупность всех адресатов дерева имен, отображающего строки имен на адресаты, см. 12.3.2.3 Именованные адресаты и 7.7.4 Словарь имен в документе pdf.
type: docs
weight: 10
url: /ru/java/com.aspose.pdf.nameddestinations/nameddestinationcollection/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.pdf.nameddestinations.INamedDestinationCollection](../../com.aspose.pdf.nameddestinations/inameddestinationcollection)
```
public class NamedDestinationCollection implements INamedDestinationCollection
```

Класс представляет собой набор всех адресатов (дерево имен, отображающее строки имен на адресаты (см. 12.3.2.3, «Именованные адресаты») и (см. 7.7.4, «Словарь имен»)) в документе pdf.
## Методы

| Метод | Описание |
| --- | --- |
| [add(String name, IAppointment appointment)](#add-java.lang.String-com.aspose.pdf.IAppointment-) | Добавить новый именованный пункт назначения. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getNames()](#getNames--) | Список названий пунктов назначения. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Получает или задает встречу по ее имени. |
| [hashCode()](#hashCode--) |  |
| [isEmpty()](#isEmpty--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String name)](#remove-java.lang.String-) | Удалить названный пункт назначения. |
| [set_Item(String name, IAppointment value)](#set-Item-java.lang.String-com.aspose.pdf.IAppointment-) | Получает или задает встречу по ее имени. |
| [size()](#size--) | Количество именованных направлений. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(String name, IAppointment appointment) {#add-java.lang.String-com.aspose.pdf.IAppointment-}
```
public void add(String name, IAppointment appointment)
```


Добавить новый именованный пункт назначения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Название пункта назначения. |
| appointment | [IAppointment](../../com.aspose.pdf/iappointment) | Назначение добавить. |

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
### getNames() {#getNames--}
```
public String[] getNames()
```


Список названий пунктов назначения.

**Возвращает:**
java.lang.String[]
### get_Item(String name) {#get-Item-java.lang.String-}
```
public IAppointment get_Item(String name)
```


Получает или задает встречу по ее имени.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Название встречи. |

**Возвращает:**
[IAppointment](../../com.aspose.pdf/iappointment) - Appoitnemt
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




### remove(String name) {#remove-java.lang.String-}
```
public void remove(String name)
```


Удалить названный пункт назначения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя адресата для удаления. |

### set_Item(String name, IAppointment value) {#set-Item-java.lang.String-com.aspose.pdf.IAppointment-}
```
public void set_Item(String name, IAppointment value)
```


Получает или задает встречу по ее имени.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Название встречи. |
| value | [IAppointment](../../com.aspose.pdf/iappointment) | Appoitnemt экземпляр |

### size() {#size--}
```
public int size()
```


Количество именованных направлений.

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
