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
| [add(String name, IAppointment appointment)](#add-java.lang.String-com.aspose.pdf.IAppointment-) | Add new named destination. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getNames()](#getNames--) | List of names of the destinations. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Gets or sets appointment by its name. |
| [hashCode()](#hashCode--) |  |
| [isEmpty()](#isEmpty--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String name)](#remove-java.lang.String-) | Delete named destination. |
| [set_Item(String name, IAppointment value)](#set-Item-java.lang.String-com.aspose.pdf.IAppointment-) | Gets or sets appointment by its name. |
| [size()](#size--) | Count of named destinations. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getNames() {#getNames--}
```
public String[] getNames()
```


List of names of the destinations.

**Returns:**
java.lang.String[]
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
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```




**Returns:**
boolean - boolean value
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


Delete named destination.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the destination to delete. |

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
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

