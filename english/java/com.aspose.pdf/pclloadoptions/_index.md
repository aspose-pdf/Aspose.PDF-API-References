---
title: PclLoadOptions
second_title: Aspose.PDF for Java API Reference
description: Represents options for loadingimport PCL file into pdf document.
type: docs
weight: 272
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
| [getConversionEngine()](#getConversionEngine--) | Defines conversion engine that will be used for conversion |
| [setConversionEngine(int conversionEngine)](#setConversionEngine-int-) | Defines conversion engine that will be used for conversion |
| [isSupressErrors()](#isSupressErrors--) | Gets or sets boolean value which indicates will PCL conversion errors should be supressed. |
| [setSupressErrors(boolean supressErrors)](#setSupressErrors-boolean-) | Gets or sets boolean value which indicates will PCL conversion errors should be supressed. |
| [getExceptions()](#getExceptions--) | List of conversion errors. |
| [getBatchSize()](#getBatchSize--) | Defines batch size if batched conversion is applicable to source and destination formats pair. |
| [setBatchSize(int value)](#setBatchSize-int-) | Defines batch size if batched conversion is applicable to source and destination formats pair. |
### PclLoadOptions() {#PclLoadOptions--}
```
public PclLoadOptions()
```


Creates  PclLoadOptions  object.

### getConversionEngine() {#getConversionEngine--}
```
public int getConversionEngine()
```


Defines conversion engine that will be used for conversion

**Returns:**
int - ConversionEngines element
### setConversionEngine(int conversionEngine) {#setConversionEngine-int-}
```
public void setConversionEngine(int conversionEngine)
```


Defines conversion engine that will be used for conversion

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| conversionEngine | int | ConversionEngines element |

### isSupressErrors() {#isSupressErrors--}
```
public boolean isSupressErrors()
```


Gets or sets boolean value which indicates will PCL conversion errors should be supressed.

**Returns:**
boolean - boolean value
### setSupressErrors(boolean supressErrors) {#setSupressErrors-boolean-}
```
public void setSupressErrors(boolean supressErrors)
```


Gets or sets boolean value which indicates will PCL conversion errors should be supressed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| supressErrors | boolean | boolean value |

### getExceptions() {#getExceptions--}
```
public List<Exception> getExceptions()
```


List of conversion errors.

**Returns:**
java.util.List<java.lang.Exception> - List of Exceptions
### getBatchSize() {#getBatchSize--}
```
public final int getBatchSize()
```


Defines batch size if batched conversion is applicable to source and destination formats pair.

**Returns:**
int - int value
### setBatchSize(int value) {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```


Defines batch size if batched conversion is applicable to source and destination formats pair.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

