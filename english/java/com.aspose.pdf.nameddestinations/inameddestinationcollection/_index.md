---
title: INamedDestinationCollection
second_title: Aspose.PDF for Java API Reference
description: Collection of Named Destinations.
type: docs
weight: 11
url: /java/com.aspose.pdf.nameddestinations/inameddestinationcollection/
---```
public interface INamedDestinationCollection
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
public abstract void add(String name, IAppointment appointment)
```


Adds new named destination.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | String value |
| appointment | [IAppointment](../../com.aspose.pdf/iappointment) | IAppointment instance |

### getNames() {#getNames--}
```
public abstract String[] getNames()
```


Gets array of names of the destinations.

**Returns:**
java.lang.String[] - Array of String values
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract IAppointment get_Item(String name)
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
public abstract void remove(String name)
```


Removes destination by its name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | String value |

### set_Item(String name, IAppointment value) {#set-Item-java.lang.String-com.aspose.pdf.IAppointment-}
```
public abstract void set_Item(String name, IAppointment value)
```


Sets destination by its name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | String value |
| value | [IAppointment](../../com.aspose.pdf/iappointment) | IAppointment instance Destination object. |

### size() {#size--}
```
public abstract int size()
```


Returns count of the destinations.

**Returns:**
int - int value
