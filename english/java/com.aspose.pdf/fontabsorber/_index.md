---
title: FontAbsorber
second_title: Aspose.PDF for Java API Reference
description: Represents an absorber object of fonts.
type: docs
weight: 131
url: /java/com.aspose.pdf/fontabsorber/
---
**Inheritance:**
java.lang.Object
```
public class FontAbsorber
```

Represents an absorber object of fonts. Performs search for fonts and provides access to search results via  FontAbsorber.Fonts  collection.
## Constructors

| Constructor | Description |
| --- | --- |
| [FontAbsorber()](#FontAbsorber--) | Initializes a new instance of the  FontAbsorber  that performs search for fonts of the document. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFonts()](#getFonts--) | Gets collection of search occurrences that are presented with  Font  objects. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [visit(Document pdf)](#visit-com.aspose.pdf.Document-) | Performs search on the specified document. |
| [visit(Document pdf, int startPage, int pageCount)](#visit-com.aspose.pdf.Document-int-int-) | Performs search in the specified range of pages of the document. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FontAbsorber() {#FontAbsorber--}
```
public FontAbsorber()
```


Initializes a new instance of the  FontAbsorber  that performs search for fonts of the document.

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
### getFonts() {#getFonts--}
```
public FontCollection getFonts()
```


Gets collection of search occurrences that are presented with  Font  objects.

**Returns:**
[FontCollection](../../com.aspose.pdf/fontcollection) - FontCollection object
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
### visit(Document pdf) {#visit-com.aspose.pdf.Document-}
```
public void visit(Document pdf)
```


Performs search on the specified document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdf | [Document](../../com.aspose.pdf/document) | Pdf pocument object. |

### visit(Document pdf, int startPage, int pageCount) {#visit-com.aspose.pdf.Document-int-int-}
```
public void visit(Document pdf, int startPage, int pageCount)
```


Performs search in the specified range of pages of the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdf | [Document](../../com.aspose.pdf/document) | Pdf pocument object. |
| startPage | int | Pdf pocument start page. |
| pageCount | int | Pdf document page count |

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

