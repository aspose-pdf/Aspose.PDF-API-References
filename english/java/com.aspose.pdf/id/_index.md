---
title: Id
second_title: Aspose.PDF for Java API Reference
description: Represents file identifier structure.
type: docs
weight: 165
url: /java/com.aspose.pdf/id/
---
**Inheritance:**
java.lang.Object
```
public class Id
```

Represents file identifier structure.

--------------------

```
Document doc = new Document("example.pdf");
 String original = doc.getId().getOriginal();
 String modified = doc.getId().getModified();
```
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getModified()](#getModified--) | Changing identifier based on the document's contents at the time it was last updated. |
| [getOriginal()](#getOriginal--) | Permanent identifier based on the contents of the document at the time it was originally created. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getModified() {#getModified--}
```
public String getModified()
```


Changing identifier based on the document's contents at the time it was last updated.

**Returns:**
java.lang.String - String value
### getOriginal() {#getOriginal--}
```
public String getOriginal()
```


Permanent identifier based on the contents of the document at the time it was originally created.

**Returns:**
java.lang.String - String value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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

