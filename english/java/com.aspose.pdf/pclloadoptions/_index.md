---
title: PclLoadOptions
second_title: Aspose.PDF for Java API Reference
description: Represents options for loadingimport PCL file into pdf document.
type: docs
weight: 273
url: /java/com.aspose.pdf/pclloadoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.LoadOptions](../../com.aspose.pdf/loadoptions)

**All Implemented Interfaces:**
[com.aspose.pdf.IPipelineOptions](../../com.aspose.pdf/ipipelineoptions)
```
public final class PclLoadOptions extends LoadOptions implements IPipelineOptions
```

Represents options for loading(import) PCL file into pdf document.
## Constructors

| Constructor | Description |
| --- | --- |
| [PclLoadOptions()](#PclLoadOptions--) | Creates  PclLoadOptions  object. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBatchSize()](#getBatchSize--) | Defines batch size if batched conversion is applicable to source and destination formats pair. |
| [getClass()](#getClass--) |  |
| [getConversionEngine()](#getConversionEngine--) | Defines conversion engine that will be used for conversion |
| [getExceptions()](#getExceptions--) | List of conversion errors. |
| [getLoadFormat()](#getLoadFormat--) | Represents file format which  LoadOptions  describes. |
| [getWarningHandler()](#getWarningHandler--) | Callback to handle any warnings generated. |
| [hashCode()](#hashCode--) |  |
| [isSupressErrors()](#isSupressErrors--) | Gets or sets boolean value which indicates will PCL conversion errors should be supressed. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBatchSize(int value)](#setBatchSize-int-) | Defines batch size if batched conversion is applicable to source and destination formats pair. |
| [setConversionEngine(int conversionEngine)](#setConversionEngine-int-) | Defines conversion engine that will be used for conversion |
| [setSupressErrors(boolean supressErrors)](#setSupressErrors-boolean-) | Gets or sets boolean value which indicates will PCL conversion errors should be supressed. |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Callback to handle any warnings generated. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PclLoadOptions() {#PclLoadOptions--}
```
public PclLoadOptions()
```


Creates  PclLoadOptions  object.

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
### getBatchSize() {#getBatchSize--}
```
public final int getBatchSize()
```


Defines batch size if batched conversion is applicable to source and destination formats pair.

**Returns:**
int - int value
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


Defines conversion engine that will be used for conversion

**Returns:**
int - ConversionEngines element
### getExceptions() {#getExceptions--}
```
public List<Exception> getExceptions()
```


List of conversion errors.

**Returns:**
java.util.List<java.lang.Exception> - List of Exceptions
### getLoadFormat() {#getLoadFormat--}
```
public LoadFormat getLoadFormat()
```


Represents file format which  LoadOptions  describes.

**Returns:**
[LoadFormat](../../com.aspose.pdf/loadformat) - LoadFormat element
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
### isSupressErrors() {#isSupressErrors--}
```
public boolean isSupressErrors()
```


Gets or sets boolean value which indicates will PCL conversion errors should be supressed.

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




### setBatchSize(int value) {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```


Defines batch size if batched conversion is applicable to source and destination formats pair.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setConversionEngine(int conversionEngine) {#setConversionEngine-int-}
```
public void setConversionEngine(int conversionEngine)
```


Defines conversion engine that will be used for conversion

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| conversionEngine | int | ConversionEngines element |

### setSupressErrors(boolean supressErrors) {#setSupressErrors-boolean-}
```
public void setSupressErrors(boolean supressErrors)
```


Gets or sets boolean value which indicates will PCL conversion errors should be supressed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| supressErrors | boolean | boolean value |

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

