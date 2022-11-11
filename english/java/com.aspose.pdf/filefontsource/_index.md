---
title: FileFontSource
second_title: Aspose.PDF for Java API Reference
description: Represents single font file source.
type: docs
weight: 112
url: /java/com.aspose.pdf/filefontsource/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.FontSource](../../com.aspose.pdf/fontsource)
```
public final class FileFontSource extends FontSource
```

Represents single font file source.
## Constructors

| Constructor | Description |
| --- | --- |
| [FileFontSource(String filePath)](#FileFontSource-java.lang.String-) | Initializes a new instance of  FileFontSource  class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Check if font file source objects are equal. |
| [getClass()](#getClass--) |  |
| [getFilePath()](#getFilePath--) | Path to the font file. |
| [hashCode()](#hashCode--) | Returns a hash code value for the object. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFilePath(String value)](#setFilePath-java.lang.String-) | Path to the font file. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FileFontSource(String filePath) {#FileFontSource-java.lang.String-}
```
public FileFontSource(String filePath)
```


Initializes a new instance of  FileFontSource  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Path to the font file. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Check if font file source objects are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Font file source object which will be compared. |

**Returns:**
boolean - True if both objects are font file sources targeted to the same file.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


Path to the font file.

**Returns:**
java.lang.String - String value
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code value for the object. This method is supported for the benefit of hash tables such as those provided by java.util.HashMap.

The general contract of  hashCode  is:

 *  Whenever it is invoked on the same object more than once during an execution of a Java application, the  hashCode  method must consistently return the same integer, provided no information used in  equals  comparisons on the object is modified. This integer need not remain consistent from one execution of an application to another execution of the same application.
 *  If two objects are equal according to the  equals(Object)  method, then calling the  hashCode  method on each of the two objects must produce the same integer result.
 *  It is *not* required that if two objects are unequal according to the java.lang.Object\#equals(java.lang.Object).equals(java.lang.Object) method, then calling the  hashCode  method on each of the two objects must produce distinct integer results. However, the programmer should be aware that producing distinct integer results for unequal objects may improve the performance of hash tables.

As much as is reasonably practical, the hashCode method defined by class  Object  does return distinct integers for distinct objects. (This is typically implemented by converting the internal address of the object into an integer, but this implementation technique is not required by the Java TM programming language.)

**Returns:**
int - a hash code value for this object.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setFilePath(String value) {#setFilePath-java.lang.String-}
```
public void setFilePath(String value)
```


Path to the font file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

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

