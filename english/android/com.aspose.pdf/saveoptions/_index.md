---
title: SaveOptions
second_title: Aspose.PDF for Java API Reference
description: SaveOptions type hold level of abstraction on individual save options
type: docs
weight: 258
url: /java/com.aspose.pdf/saveoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class SaveOptions
```

SaveOptions type hold level of abstraction on individual save options
## Constructors

| Constructor | Description |
| --- | --- |
| [SaveOptions()](#SaveOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getWarningHandler()](#getWarningHandler--) | Callback to handle any warnings generated. |
| [setWarningHandler(IWarningCallback value)](#setWarningHandler-com.aspose.pdf.IWarningCallback-) |  |
| [getSaveFormat()](#getSaveFormat--) | Format of data save. |
| [getCloseResponse()](#getCloseResponse--) | Gets or sets boolean value which indicates will Response object be closed after document saved into response. |
| [setCloseResponse(boolean value)](#setCloseResponse-boolean-) |  |
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


### getWarningHandler() {#getWarningHandler--}
```
public IWarningCallback getWarningHandler()
```


Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease.

**Returns:**
[IWarningCallback](../../com.aspose.pdf/iwarningcallback)
### setWarningHandler(IWarningCallback value) {#setWarningHandler-com.aspose.pdf.IWarningCallback-}
```
public void setWarningHandler(IWarningCallback value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.pdf/iwarningcallback) |  |

### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


Format of data save.

**Returns:**
int
### getCloseResponse() {#getCloseResponse--}
```
public boolean getCloseResponse()
```


Gets or sets boolean value which indicates will Response object be closed after document saved into response.

**Returns:**
boolean
### setCloseResponse(boolean value) {#setCloseResponse-boolean-}
```
public void setCloseResponse(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

