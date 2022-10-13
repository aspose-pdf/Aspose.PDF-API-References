---
title: NamedDestinationCollection
second_title: Aspose.PDF for Java API Reference
description: Class represents the collection of all destinations a name tree mapping name strings to destinations see 12.3.2.3 Named Destinations and see 7.7.4 Name Dictionary in the pdf document.
type: docs
weight: 10
url: /java/com.aspose.pdf.nameddestinations/nameddestinationcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.pdf.nameddestinations.INamedDestinationCollection](../../com.aspose.pdf.nameddestinations/inameddestinationcollection)
```
public class NamedDestinationCollection implements INamedDestinationCollection
```

Class represents the collection of all destinations (a name tree mapping name strings to destinations (see 12.3.2.3, "Named Destinations") and (see 7.7.4, "Name Dictionary")) in the pdf document.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(String name)](#get-Item-java.lang.String-) | Gets or sets appointment by its name. |
| [set_Item(String name, IAppointment value)](#set-Item-java.lang.String-com.aspose.pdf.IAppointment-) | Gets or sets appointment by its name. |
| [size()](#size--) | Count of named destinations. |
| [remove(String name)](#remove-java.lang.String-) | Delete named destination. |
| [add(String name, IAppointment appointment)](#add-java.lang.String-com.aspose.pdf.IAppointment-) | Add new named destination. |
| [getNames()](#getNames--) | List of names of the destinations. |
### get_Item(String name) {#get-Item-java.lang.String-}
```
public IAppointment get_Item(String name)
```


Gets or sets appointment by its name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the appointment. |

**Returns:**
[IAppointment](../../com.aspose.pdf/iappointment) - Appoitnemt
### set_Item(String name, IAppointment value) {#set-Item-java.lang.String-com.aspose.pdf.IAppointment-}
```
public void set_Item(String name, IAppointment value)
```


Gets or sets appointment by its name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the appointment. |
| value | [IAppointment](../../com.aspose.pdf/iappointment) | Appoitnemt instance |

### size() {#size--}
```
public int size()
```


Count of named destinations.

**Returns:**
int - int value
### remove(String name) {#remove-java.lang.String-}
```
public void remove(String name)
```


Delete named destination.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the destination to delete. |

### add(String name, IAppointment appointment) {#add-java.lang.String-com.aspose.pdf.IAppointment-}
```
public void add(String name, IAppointment appointment)
```


Add new named destination.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Destination name. |
| appointment | [IAppointment](../../com.aspose.pdf/iappointment) | Appointment to add. |

### getNames() {#getNames--}
```
public String[] getNames()
```


List of names of the destinations.

**Returns:**
java.lang.String[]
