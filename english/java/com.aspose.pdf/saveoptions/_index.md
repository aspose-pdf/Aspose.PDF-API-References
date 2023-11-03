---
title: SaveOptions
second_title: Aspose.PDF for Java API Reference
description: SaveOptions type hold level of abstraction on individual save options
type: docs
weight: 321
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
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Callback to handle any warnings generated. |
| [getSaveFormat()](#getSaveFormat--) | Format of data save. |
| [isCloseResponse()](#isCloseResponse--) | Gets boolean value which indicates will Response object be closed after document saved into response. |
| [setCloseResponse(boolean value)](#setCloseResponse-boolean-) | Sets boolean value which indicates will Response object be closed after document saved into response. |
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


### getWarningHandler() {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```


Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease.

**Returns:**
[WarningCallback](../../com.aspose.pdf/warningcallback) - IWarningCallback value
### setWarningHandler(WarningCallback value) {#setWarningHandler-com.aspose.pdf.WarningCallback-}
```
public void setWarningHandler(WarningCallback value)
```


Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [WarningCallback](../../com.aspose.pdf/warningcallback) | IWarningCallback value |

### getSaveFormat() {#getSaveFormat--}
```
public SaveFormat getSaveFormat()
```


Format of data save.

**Returns:**
[SaveFormat](../../com.aspose.pdf/saveformat) - SaveFormat value
### isCloseResponse() {#isCloseResponse--}
```
public boolean isCloseResponse()
```


Gets boolean value which indicates will Response object be closed after document saved into response.

**Returns:**
boolean - boolean value
### setCloseResponse(boolean value) {#setCloseResponse-boolean-}
```
public void setCloseResponse(boolean value)
```


Sets boolean value which indicates will Response object be closed after document saved into response.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

