---
title: PdfEvent
second_title: Aspose.PDF for Java API Reference
description: Class representing events
type: docs
weight: 277
url: /java/com.aspose.pdf/pdfevent/
---
**Inheritance:**
java.lang.Object
```
public abstract class PdfEvent<T>
```

Class representing events
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfEvent()](#PdfEvent--) |  |
## Methods

| Method | Description |
| --- | --- |
| [add(T delegate)](#add-T-) | Add one more delegate. |
| [assign(T delegate)](#assign-T-) | Add only the current delegate, clearing other. |
| [clear()](#clear--) | Clear delegate list |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [isEmpty()](#isEmpty--) | Returns true if the list of handlers is empty |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(T delegate)](#remove-T-) | Delete delegate from list |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfEvent() {#PdfEvent--}
```
public PdfEvent()
```


### add(T delegate) {#add-T-}
```
public final void add(T delegate)
```


Add one more delegate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| delegate | T | Handlers object |

### assign(T delegate) {#assign-T-}
```
public final void assign(T delegate)
```


Add only the current delegate, clearing other.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| delegate | T | Handlers object |

### clear() {#clear--}
```
public final void clear()
```


Clear delegate list

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


Returns true if the list of handlers is empty

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




### remove(T delegate) {#remove-T-}
```
public final void remove(T delegate)
```


Delete delegate from list

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| delegate | T | Handlers object |

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

