---
title: EpubLoadOptions
second_title: Aspose.PDF for Java API Reference
description: Contains options for loading/importing EPUB file into pdf document.
type: docs
weight: 99
url: /java/com.aspose.pdf/epubloadoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.LoadOptions](../../com.aspose.pdf/loadoptions)
```
public final class EpubLoadOptions extends LoadOptions
```

Contains options for loading/importing EPUB file into pdf document.
## Constructors

| Constructor | Description |
| --- | --- |
| [EpubLoadOptions()](#EpubLoadOptions--) | Creates default load options for converting EPUB file into pdf document. |
| [EpubLoadOptions(Dimension2D pageSize)](#EpubLoadOptions-java.awt.geom.Dimension2D-) | Creates load options with specified page size. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLoadFormat()](#getLoadFormat--) | Represents file format which  LoadOptions  describes. |
| [getMargin()](#getMargin--) | Gets reference on object that represent marging info. |
| [getMarginsAreaUsageMode()](#getMarginsAreaUsageMode--) | Represents mode of usage of margins area - defines treatement of instructions (if any) of CSS of imported document related to usage of margins. |
| [getPageSize()](#getPageSize--) | Gets output page size for import. |
| [getPageSizeAdjustmentMode()](#getPageSizeAdjustmentMode--) | ATTENTION! |
| [getWarningHandler()](#getWarningHandler--) | Callback to handle any warnings generated. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | Gets reference on object that represent marging info. |
| [setMarginsAreaUsageMode(int marginsAreaUsageMode)](#setMarginsAreaUsageMode-int-) | Represents mode of usage of margins area - defines treatement of instructions (if any) of CSS of imported document related to usage of margins. |
| [setPageSizeAdjustmentMode(int pageSizeAdjustmentMode)](#setPageSizeAdjustmentMode-int-) | ATTENTION! |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Callback to handle any warnings generated. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EpubLoadOptions() {#EpubLoadOptions--}
```
public EpubLoadOptions()
```


Creates default load options for converting EPUB file into pdf document. Default pdf page size - A4 300dpi 2480 X 3508.

### EpubLoadOptions(Dimension2D pageSize) {#EpubLoadOptions-java.awt.geom.Dimension2D-}
```
public EpubLoadOptions(Dimension2D pageSize)
```


Creates load options with specified page size.

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
### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


Gets reference on object that represent marging info.

**Returns:**
[MarginInfo](../../com.aspose.pdf/margininfo) - MarginInfo object
### getMarginsAreaUsageMode() {#getMarginsAreaUsageMode--}
```
public int getMarginsAreaUsageMode()
```


Represents mode of usage of margins area - defines treatement of instructions (if any) of CSS of imported document related to usage of margins.

**Returns:**
int - MarginsAreaUsageModes value
### getPageSize() {#getPageSize--}
```
public Dimension2D getPageSize()
```


Gets output page size for import.

**Returns:**
java.awt.geom.Dimension2D - Dimension2D object
### getPageSizeAdjustmentMode() {#getPageSizeAdjustmentMode--}
```
public int getPageSizeAdjustmentMode()
```


ATTENTION! The feature implemented but did not put yet to public API since blocker issue in OSHARED layer revealed for sample document. Represents mode of usage of page size during conversion. Formats (like HTML, EPUB etc), usually have float design, so, it allows to fit required pagesize. But sometimes content has specified horizontal positions or size that does not allow put content into required page size. In such case we can define what should be done in this case (i.e when size of content does not fit required initial page size of result PDF document).

**Returns:**
int - PageSizeAdjustmentModes value
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




### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public final void setMargin(MarginInfo value)
```


Gets reference on object that represent marging info.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo object |

### setMarginsAreaUsageMode(int marginsAreaUsageMode) {#setMarginsAreaUsageMode-int-}
```
public void setMarginsAreaUsageMode(int marginsAreaUsageMode)
```


Represents mode of usage of margins area - defines treatement of instructions (if any) of CSS of imported document related to usage of margins.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| marginsAreaUsageMode | int | MarginsAreaUsageModes value |

### setPageSizeAdjustmentMode(int pageSizeAdjustmentMode) {#setPageSizeAdjustmentMode-int-}
```
public void setPageSizeAdjustmentMode(int pageSizeAdjustmentMode)
```


ATTENTION! The feature implemented but did not put yet to public API since blocker issue in OSHARED layer revealed for sample document. Represents mode of usage of page size during conversion. Formats (like HTML, EPUB etc), usually have float design, so, it allows to fit required pagesize. But sometimes content has specified horizontal positions or size that does not allow put content into required page size. In such case we can define what should be done in this case (i.e when size of content does not fit required initial page size of result PDF document).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSizeAdjustmentMode | int | PageSizeAdjustmentModes value |

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

