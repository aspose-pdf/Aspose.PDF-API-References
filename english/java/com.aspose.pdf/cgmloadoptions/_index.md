---
title: CgmLoadOptions
second_title: Aspose.PDF for Java API Reference
description: Contains options for loading/importing CGM file into pdf document.
type: docs
weight: 55
url: /java/com.aspose.pdf/cgmloadoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.LoadOptions](../../com.aspose.pdf/loadoptions)
```
public final class CgmLoadOptions extends LoadOptions
```

Contains options for loading/importing CGM file into pdf document.
## Constructors

| Constructor | Description |
| --- | --- |
| [CgmLoadOptions()](#CgmLoadOptions--) | Creates default load options for converting CGM file into pdf document. |
| [CgmLoadOptions(Dimension2D pageSize)](#CgmLoadOptions-java.awt.geom.Dimension2D-) | Creates load options with defined  pageSize . |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLoadFormat()](#getLoadFormat--) | Represents file format which  LoadOptions  describes. |
| [getPageSize()](#getPageSize--) | Gets output page size for import. |
| [getWarningHandler()](#getWarningHandler--) | Callback to handle any warnings generated. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Callback to handle any warnings generated. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CgmLoadOptions() {#CgmLoadOptions--}
```
public CgmLoadOptions()
```


Creates default load options for converting CGM file into pdf document. Default pdf page size - A4 300dpi 2480 X 3508.

### CgmLoadOptions(Dimension2D pageSize) {#CgmLoadOptions-java.awt.geom.Dimension2D-}
```
public CgmLoadOptions(Dimension2D pageSize)
```


Creates load options with defined  pageSize .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | java.awt.geom.Dimension2D | Defines pdf page width and height. |

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
### getLoadFormat() {#getLoadFormat--}
```
public LoadFormat getLoadFormat()
```


Represents file format which  LoadOptions  describes.

**Returns:**
[LoadFormat](../../com.aspose.pdf/loadformat) - LoadFormat element
### getPageSize() {#getPageSize--}
```
public Dimension2D getPageSize()
```


Gets output page size for import.

**Returns:**
java.awt.geom.Dimension2D - Dimension2D object
### getWarningHandler() {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```


Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease.

**Returns:**
[WarningCallback](../../com.aspose.pdf/warningcallback) - IWarningCallback value
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




### setWarningHandler(WarningCallback value) {#setWarningHandler-com.aspose.pdf.WarningCallback-}
```
public void setWarningHandler(WarningCallback value)
```


Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [WarningCallback](../../com.aspose.pdf/warningcallback) | IWarningCallback value |

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

