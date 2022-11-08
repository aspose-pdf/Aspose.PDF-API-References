---
title: SvgLoadOptions
second_title: Aspose.PDF for Java API Reference
description: Represents options for loading/importing SVG file into pdf document.
type: docs
weight: 343
url: /java/com.aspose.pdf/svgloadoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.LoadOptions](../../com.aspose.pdf/loadoptions)
```
public final class SvgLoadOptions extends LoadOptions
```

Represents options for loading/importing SVG file into pdf document.
## Constructors

| Constructor | Description |
| --- | --- |
| [SvgLoadOptions()](#SvgLoadOptions--) | Creates  SvgLoadOptions  object. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getConversionEngine()](#getConversionEngine--) | Allows select conversion engine that will be in use during conversion. |
| [getLoadFormat()](#getLoadFormat--) | Represents file format which  LoadOptions  describes. |
| [getPageInfo()](#getPageInfo--) | Gets page info that should be applied during loading of document. |
| [getWarningHandler()](#getWarningHandler--) | Callback to handle any warnings generated. |
| [hashCode()](#hashCode--) |  |
| [isAdjustPageSize()](#isAdjustPageSize--) | Adust pdf page size to svg size |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAdjustPageSize(boolean value)](#setAdjustPageSize-boolean-) | Adust pdf page size to svg size |
| [setConversionEngine(int conversionEngine)](#setConversionEngine-int-) | Allows select conversion engine that will be in use during conversion. |
| [setPageInfo(PageInfo value)](#setPageInfo-com.aspose.pdf.PageInfo-) | Sets page info that should be applied during loading of document. |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Callback to handle any warnings generated. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SvgLoadOptions() {#SvgLoadOptions--}
```
public SvgLoadOptions()
```


Creates  SvgLoadOptions  object.

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
### getConversionEngine() {#getConversionEngine--}
```
public int getConversionEngine()
```


Allows select conversion engine that will be in use during conversion. Currently new engine is in B-testing stage, so this value by default set to ConversionEngines.LegacyEngine

**Returns:**
int - ConversionEngines element
### getLoadFormat() {#getLoadFormat--}
```
public LoadFormat getLoadFormat()
```


Represents file format which  LoadOptions  describes.

**Returns:**
[LoadFormat](../../com.aspose.pdf/loadformat) - LoadFormat element
### getPageInfo() {#getPageInfo--}
```
public PageInfo getPageInfo()
```


Gets page info that should be applied during loading of document. NOTE that this parameter only works when ConversionEngine == ConversionEngines.NewEngine

**Returns:**
[PageInfo](../../com.aspose.pdf/pageinfo) - PageInfo object
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
### isAdjustPageSize() {#isAdjustPageSize--}
```
public boolean isAdjustPageSize()
```


Adust pdf page size to svg size

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




### setAdjustPageSize(boolean value) {#setAdjustPageSize-boolean-}
```
public void setAdjustPageSize(boolean value)
```


Adust pdf page size to svg size

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setConversionEngine(int conversionEngine) {#setConversionEngine-int-}
```
public void setConversionEngine(int conversionEngine)
```


Allows select conversion engine that will be in use during conversion. Currently new engine is in B-testing stage, so this value by default set to ConversionEngines.LegacyEngine

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| conversionEngine | int | ConversionEngines element |

### setPageInfo(PageInfo value) {#setPageInfo-com.aspose.pdf.PageInfo-}
```
public void setPageInfo(PageInfo value)
```


Sets page info that should be applied during loading of document. NOTE that this parameter only works when ConversionEngine == ConversionEngines.NewEngine

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PageInfo](../../com.aspose.pdf/pageinfo) | PageInfo object |

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

