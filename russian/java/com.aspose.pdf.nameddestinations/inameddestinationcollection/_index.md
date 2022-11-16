---
title: INamedDestinationCollection
second_title: Aspose.PDF для справки по Java API
description: Коллекция именованных направлений.
type: docs
weight: 11
url: /ru/java/com.aspose.pdf.nameddestinations/inameddestinationcollection/
---
```
public interface INamedDestinationCollection
```

Коллекция именованных направлений.
## Методы

| Метод | Описание |
| --- | --- |
| [add(String name, IAppointment appointment)](#add-java.lang.String-com.aspose.pdf.IAppointment-) | Добавляет новый именованный пункт назначения. |
| [getNames()](#getNames--) | Получает массив имен пунктов назначения. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Получает пункт назначения по его имени. |
| [remove(String name)](#remove-java.lang.String-) | Удаляет пункт назначения по его имени. |
| [set_Item(String name, IAppointment value)](#set-Item-java.lang.String-com.aspose.pdf.IAppointment-) | Устанавливает пункт назначения по его имени. |
| [size()](#size--) | Возвращает количество пунктов назначения. |
### add(String name, IAppointment appointment) {#add-java.lang.String-com.aspose.pdf.IAppointment-}
```
public abstract void add(String name, IAppointment appointment)
```


Добавляет новый именованный пункт назначения.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Строковое значение |
| appointment | [IAppointment](../../com.aspose.pdf/iappointment) | Экземпляр IAppointment |

### getNames() {#getNames--}
```
public abstract String[] getNames()
```


Получает массив имен пунктов назначения.

**Возвращает:**
java.lang.String[] — массив строковых значений
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract IAppointment get_Item(String name)
```


Получает пункт назначения по его имени.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Строковое значение |

**Возвращает:**
[IAppointment](../../com.aspose.pdf/iappointment) - Объект назначения экземпляра IAppointment.
### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```


Удаляет пункт назначения по его имени.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Строковое значение |

### set_Item(String name, IAppointment value) {#set-Item-java.lang.String-com.aspose.pdf.IAppointment-}
```
public abstract void set_Item(String name, IAppointment value)
```


Устанавливает пункт назначения по его имени.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Строковое значение |
| value | [IAppointment](../../com.aspose.pdf/iappointment) | Экземпляр IAppointment Целевой объект. |

### size() {#size--}
```
public abstract int size()
```


Возвращает количество пунктов назначения.

**Возвращает:**
интервал - целочисленное значение