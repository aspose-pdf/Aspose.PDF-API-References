---
title: INamedDestinationCollection
second_title: Aspose.PDF для справки по Java API
описание: Коллекция именованных направлений.
тип: документы
вес: 11
URL-адрес: /java/com.aspose.pdf.nameddestinations/inameddestinationcollection/
---```
открытый интерфейс INamedDestinationCollection
```

Collection of Named Destinations.
## Methods

| Method | Description |
| --- | --- |
| [add(String name, IAppointment appointment)](#add-java.lang.String-com.aspose.pdf.IAppointment-) | Adds new named destination. |
| [getNames()](#getNames--) | Gets array of names of the destinations. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Gets destination by its name. |
| [remove(String name)](#remove-java.lang.String-) | Removes destination by its name. |
| [set_Item(String name, IAppointment value)](#set-Item-java.lang.String-com.aspose.pdf.IAppointment-) | Sets destination by its name. |
| [size()](#size--) | Returns count of the destinations. |
### add(String name, IAppointment appointment) {#add-java.lang.String-com.aspose.pdf.IAppointment-}
```
public abstract void add (имя строки, назначение IAppointment)
```


Adds new named destination.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | String value |
| appointment | [IAppointment](../../com.aspose.pdf/iappointment) | IAppointment instance |

### getNames() {#getNames--}
```
общедоступная абстрактная строка[] получитьИмена()
```


Gets array of names of the destinations.

**Returns:**
java.lang.String[] - Array of String values
### get_Item(String name) {#get-Item-java.lang.String-}
```
открытый абстрактный IAppointment get_Item (имя строки)
```


Gets destination by its name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | String value |

**Returns:**
[IAppointment](../../com.aspose.pdf/iappointment) - IAppointment instance Destination object.
### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove (строковое имя)
```


Removes destination by its name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | String value |

### set_Item(String name, IAppointment value) {#set-Item-java.lang.String-com.aspose.pdf.IAppointment-}
```
public abstract void set_Item (имя строки, значение IAppointment)
```


Sets destination by its name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | String value |
| value | [IAppointment](../../com.aspose.pdf/iappointment) | IAppointment instance Destination object. |

### size() {#size--}
```
публичный абстрактный размер int()
```


Returns count of the destinations.

**Returns:**
int - int value