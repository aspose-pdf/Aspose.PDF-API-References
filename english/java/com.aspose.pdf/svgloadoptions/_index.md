---
title: SvgLoadOptions
second_title: Aspose.PDF for Java API Reference
description: Represents options for loading/importing SVG file into pdf document.
type: docs
weight: 4700
url: /java/com.aspose.pdf/svgloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.SvgLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.SvgLoadOptions

```
public final class SvgLoadOptions extends LoadOptions
```

Represents options for loading/importing SVG file into pdf document.

## Constructors

| Constructor | Description |
| --- | --- |
| [SvgLoadOptions](#SvgLoadOptions--) | Creates {@code SvgLoadOptions} object. |

## Methods

| Method | Description |
| --- | --- |
| [getConversionEngine](#getConversionEngine--) | Allows select conversion engine that will be in use during conversion. Currently new engine is in B-testing stage, so this value by default set to ConversionEngines.LegacyEngine |
| [getPageInfo](#getPageInfo--) | Gets page info that should be applied during loading of document. |
| [isAdjustPageSize](#isAdjustPageSize--) | Adust pdf page size to svg size |
| [setAdjustPageSize](#setAdjustPageSize-boolean-) | Adust pdf page size to svg size |
| [setConversionEngine](#setConversionEngine-int-) | Allows select conversion engine that will be in use during conversion. Currently new engine is in B-testing stage, so this value by default set to ConversionEngines.LegacyEngine |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Sets page info that should be applied during loading of document. |

### SvgLoadOptions {#SvgLoadOptions--}
```
public SvgLoadOptions()
```

Creates {@code SvgLoadOptions} object.

### getConversionEngine {#getConversionEngine--}
```
public int getConversionEngine()
```

Allows select conversion engine that will be in use during conversion. Currently new engine is in B-testing stage, so this value by default set to ConversionEngines.LegacyEngine

**Returns:**
ConversionEngines element @see ConversionEngines

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

Gets page info that should be applied during loading of document.

**Returns:**
PageInfo object

### isAdjustPageSize {#isAdjustPageSize--}
```
public boolean isAdjustPageSize()
```

Adust pdf page size to svg size

**Returns:**
boolean value

### setAdjustPageSize {#setAdjustPageSize-boolean-}
```
public void setAdjustPageSize(boolean value)
```

Adust pdf page size to svg size

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setConversionEngine {#setConversionEngine-int-}
```
public void setConversionEngine(int conversionEngine)
```

Allows select conversion engine that will be in use during conversion. Currently new engine is in B-testing stage, so this value by default set to ConversionEngines.LegacyEngine

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| conversionEngine |  | ConversionEngines element @see ConversionEngines |

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
Sets page info that should be applied during loading of document.
