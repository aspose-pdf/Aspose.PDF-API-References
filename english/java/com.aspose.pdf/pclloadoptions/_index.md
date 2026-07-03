---
title: PclLoadOptions
second_title: Aspose.PDF for Java API Reference
description: Represents options for loading(import) PCL file into pdf document.
type: docs
weight: 3530
url: /java/com.aspose.pdf/pclloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.PclLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.PclLoadOptions

**All Implemented Interfaces:**
IPipelineOptions

```
public final class PclLoadOptions extends LoadOptions implements IPipelineOptions
```

Represents options for loading(import) PCL file into pdf document.

## Constructors

| Constructor | Description |
| --- | --- |
| [PclLoadOptions](#PclLoadOptions--) | Creates {@code PclLoadOptions} object. |

## Methods

| Method | Description |
| --- | --- |
| [getBatchSize](#getBatchSize--) | Defines batch size if batched conversion is applicable to source and destination formats pair. |
| [getConversionEngine](#getConversionEngine--) | Defines conversion engine that will be used for conversion |
| [getExceptions](#getExceptions--) | List of conversion errors. |
| [isSupressErrors](#isSupressErrors--) | Gets or sets boolean value which indicates will PCL conversion errors should be supressed. |
| [setBatchSize](#setBatchSize-int-) | Defines batch size if batched conversion is applicable to source and destination formats pair. |
| [setConversionEngine](#setConversionEngine-int-) | Defines conversion engine that will be used for conversion |
| [setSupressErrors](#setSupressErrors-boolean-) | Gets or sets boolean value which indicates will PCL conversion errors should be supressed. |

### PclLoadOptions {#PclLoadOptions--}
```
public PclLoadOptions()
```

Creates {@code PclLoadOptions} object.

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

Defines batch size if batched conversion is applicable to source and destination formats pair.

**Returns:**
int value

### getConversionEngine {#getConversionEngine--}
```
public int getConversionEngine()
```

Defines conversion engine that will be used for conversion

**Returns:**
ConversionEngines element @see ConversionEngines

### getExceptions {#getExceptions--}
```
public List < Exception > getExceptions()
```

List of conversion errors.

**Returns:**
List of Exceptions

### isSupressErrors {#isSupressErrors--}
```
public boolean isSupressErrors()
```

Gets or sets boolean value which indicates will PCL conversion errors should be supressed.

**Returns:**
boolean value

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

Defines batch size if batched conversion is applicable to source and destination formats pair.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setConversionEngine {#setConversionEngine-int-}
```
public void setConversionEngine(int conversionEngine)
```

Defines conversion engine that will be used for conversion

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| conversionEngine |  | ConversionEngines element @see ConversionEngines |

### setSupressErrors {#setSupressErrors-boolean-}
```
public void setSupressErrors(boolean supressErrors)
```

Gets or sets boolean value which indicates will PCL conversion errors should be supressed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| supressErrors |  | boolean value |
