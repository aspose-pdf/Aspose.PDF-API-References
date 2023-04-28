---
title: LoadOptions
second_title: Aspose.PDF for Java API Reference
description: LoadOptions type holds level of abstraction on individual load options
type: docs
weight: 201
url: /java/com.aspose.pdf/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class LoadOptions
```

LoadOptions type holds level of abstraction on individual load options
## Constructors

| Constructor | Description |
| --- | --- |
| [LoadOptions()](#LoadOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getWarningHandler()](#getWarningHandler--) | Callback to handle any warnings generated. |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Callback to handle any warnings generated. |
| [getLoadFormat()](#getLoadFormat--) | Represents file format which  LoadOptions  describes. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


### getWarningHandler() {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```


Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease.

**Returns:**
[WarningCallback](../../com.aspose.pdf/warningcallback) - IWarningCallback value
### setWarningHandler(WarningCallback value) {#setWarningHandler-com.aspose.pdf.WarningCallback-}
```
public void setWarningHandler(WarningCallback value)
```


Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [WarningCallback](../../com.aspose.pdf/warningcallback) | IWarningCallback value |

### getLoadFormat() {#getLoadFormat--}
```
public LoadFormat getLoadFormat()
```


Represents file format which  LoadOptions  describes.

**Returns:**
[LoadFormat](../../com.aspose.pdf/loadformat) - LoadFormat element
