---
title: PageLabelCollection
second_title: Aspose.PDF for Java API Reference
description: Class represeingting page label collection.
type: docs
weight: 263
url: /java/com.aspose.pdf/pagelabelcollection/
---
**Inheritance:**
java.lang.Object
```
public class PageLabelCollection
```

Class represeingting page label collection.
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLabel(int pageIndex)](#getLabel-int-) | Gets page label by page index (page index is started from 0). |
| [getPages()](#getPages--) | Gets page indexes in collection. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeLabel(int pageIndex)](#removeLabel-int-) | Remove label by page index (page index is started from 0). |
| [toString()](#toString--) |  |
| [updateLabel(int pageIndex, PageLabel pageLabel)](#updateLabel-int-com.aspose.pdf.PageLabel-) | Update label for given page index (page index is started from 0). |
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
### getLabel(int pageIndex) {#getLabel-int-}
```
public PageLabel getLabel(int pageIndex)
```


Gets page label by page index (page index is started from 0).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageIndex | int | Index of the page. |

**Returns:**
[PageLabel](../../com.aspose.pdf/pagelabel) - Page label for specified page index or null if page label does not exist.
### getPages() {#getPages--}
```
public int[] getPages()
```


Gets page indexes in collection.

**Returns:**
int[] - Array of integers which contains indexes of the pages.
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




### removeLabel(int pageIndex) {#removeLabel-int-}
```
public boolean removeLabel(int pageIndex)
```


Remove label by page index (page index is started from 0).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageIndex | int | Index of page where label must be deleted. |

**Returns:**
boolean - true if operation was executed successfully.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateLabel(int pageIndex, PageLabel pageLabel) {#updateLabel-int-com.aspose.pdf.PageLabel-}
```
public void updateLabel(int pageIndex, PageLabel pageLabel)
```


Update label for given page index (page index is started from 0).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageIndex | int | Index of page to change lable of the page. |
| pageLabel | [PageLabel](../../com.aspose.pdf/pagelabel) | New label of the page. |

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

