---
title: SvgLoadOptions
second_title: Aspose.PDF for Java API Reference
description: Represents options for loading/importing SVG file into pdf document.
type: docs
weight: 344
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
| [getConversionEngine()](#getConversionEngine--) | Allows select conversion engine that will be in use during conversion. |
| [setConversionEngine(int conversionEngine)](#setConversionEngine-int-) | Allows select conversion engine that will be in use during conversion. |
| [getPageInfo()](#getPageInfo--) | Gets page info that should be applied during loading of document. |
| [setPageInfo(PageInfo value)](#setPageInfo-com.aspose.pdf.PageInfo-) | Sets page info that should be applied during loading of document. |
| [isAdjustPageSize()](#isAdjustPageSize--) | Adust pdf page size to svg size |
| [setAdjustPageSize(boolean value)](#setAdjustPageSize-boolean-) | Adust pdf page size to svg size |
### SvgLoadOptions() {#SvgLoadOptions--}
```
public SvgLoadOptions()
```


Creates  SvgLoadOptions  object.

### getConversionEngine() {#getConversionEngine--}
```
public int getConversionEngine()
```


Allows select conversion engine that will be in use during conversion. Currently new engine is in B-testing stage, so this value by default set to ConversionEngines.LegacyEngine

**Returns:**
int - ConversionEngines element
### setConversionEngine(int conversionEngine) {#setConversionEngine-int-}
```
public void setConversionEngine(int conversionEngine)
```


Allows select conversion engine that will be in use during conversion. Currently new engine is in B-testing stage, so this value by default set to ConversionEngines.LegacyEngine

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| conversionEngine | int | ConversionEngines element |

### getPageInfo() {#getPageInfo--}
```
public PageInfo getPageInfo()
```


Gets page info that should be applied during loading of document. NOTE that this parameter only works when ConversionEngine == ConversionEngines.NewEngine

**Returns:**
[PageInfo](../../com.aspose.pdf/pageinfo) - PageInfo object
### setPageInfo(PageInfo value) {#setPageInfo-com.aspose.pdf.PageInfo-}
```
public void setPageInfo(PageInfo value)
```


Sets page info that should be applied during loading of document. NOTE that this parameter only works when ConversionEngine == ConversionEngines.NewEngine

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PageInfo](../../com.aspose.pdf/pageinfo) | PageInfo object |

### isAdjustPageSize() {#isAdjustPageSize--}
```
public boolean isAdjustPageSize()
```


Adust pdf page size to svg size

**Returns:**
boolean - boolean value
### setAdjustPageSize(boolean value) {#setAdjustPageSize-boolean-}
```
public void setAdjustPageSize(boolean value)
```


Adust pdf page size to svg size

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

