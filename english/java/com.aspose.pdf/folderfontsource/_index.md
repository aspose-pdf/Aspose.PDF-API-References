---
title: FolderFontSource
second_title: Aspose.PDF for Java API Reference
description: Represents the folder that contains font files.
type: docs
weight: 130
url: /java/com.aspose.pdf/folderfontsource/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.FontSource](../../com.aspose.pdf/fontsource)
```
public final class FolderFontSource extends FontSource
```

Represents the folder that contains font files.
## Constructors

| Constructor | Description |
| --- | --- |
| [FolderFontSource(String folderPath)](#FolderFontSource-java.lang.String-) | Initializes a new instance of  FolderFontSource  class. |
## Methods

| Method | Description |
| --- | --- |
| [getFolderPath()](#getFolderPath--) | Path to the folder that contains font files. |
| [setFolderPath(String value)](#setFolderPath-java.lang.String-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Check if folder font source objects are equal. |
| [hashCode()](#hashCode--) | Returns a hash code value for the object. |
### FolderFontSource(String folderPath) {#FolderFontSource-java.lang.String-}
```
public FolderFontSource(String folderPath)
```


Initializes a new instance of  FolderFontSource  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderPath | java.lang.String | Path to the folder. |

### getFolderPath() {#getFolderPath--}
```
public String getFolderPath()
```


Path to the folder that contains font files.

**Returns:**
java.lang.String - String value
### setFolderPath(String value) {#setFolderPath-java.lang.String-}
```
public void setFolderPath(String value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Check if folder font source objects are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Folder font source object which will be compared. |

**Returns:**
boolean - True if both objects are folder font sources targeted to the same folder.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code value for the object. This method is supported for the benefit of hash tables such as those provided by java.util.HashMap.

The general contract of  hashCode  is:

 *  Whenever it is invoked on the same object more than once during an execution of a Java application, the  hashCode  method must consistently return the same integer, provided no information used in  equals  comparisons on the object is modified. This integer need not remain consistent from one execution of an application to another execution of the same application.
 *  If two objects are equal according to the  equals(Object)  method, then calling the  hashCode  method on each of the two objects must produce the same integer result.
 *  It is *not* required that if two objects are unequal according to the java.lang.Object\#equals(java.lang.Object)\#equals(java.lang.Object) method, then calling the  hashCode  method on each of the two objects must produce distinct integer results. However, the programmer should be aware that producing distinct integer results for unequal objects may improve the performance of hash tables.

As much as is reasonably practical, the hashCode method defined by class  Object  does return distinct integers for distinct objects. (This is typically implemented by converting the internal address of the object into an integer, but this implementation technique is not required by the JavaTM programming language.)

**Returns:**
int - a hash code value for this object.
