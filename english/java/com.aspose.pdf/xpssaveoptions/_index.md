---
title: XpsSaveOptions
second_title: Aspose.PDF for Java API Reference
description: Save options for export to Xps format
type: docs
weight: 426
url: /java/com.aspose.pdf/xpssaveoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.SaveOptions](../../com.aspose.pdf/saveoptions), [com.aspose.pdf.UnifiedSaveOptions](../../com.aspose.pdf/unifiedsaveoptions)

**All Implemented Interfaces:**
[com.aspose.pdf.IPipelineOptions](../../com.aspose.pdf/ipipelineoptions)
```
public class XpsSaveOptions extends UnifiedSaveOptions implements IPipelineOptions
```

Save options for export to Xps format
## Constructors

| Constructor | Description |
| --- | --- |
| [XpsSaveOptions()](#XpsSaveOptions--) | Constructor |
## Methods

| Method | Description |
| --- | --- |
| [getSaveTransparentTexts()](#getSaveTransparentTexts--) | Indicates whether to preserve transparent (OCR'ed) text. |
| [setSaveTransparentTexts(boolean value)](#setSaveTransparentTexts-boolean-) | Indicates whether to preserve transparent (OCR'ed) text. |
| [getBatchSize()](#getBatchSize--) | Defines batch size if batched conversion is applicable to source and destination formats pair. |
| [setBatchSize(int value)](#setBatchSize-int-) | Defines batch size if batched conversion is applicable to source and destination formats pair. |
### XpsSaveOptions() {#XpsSaveOptions--}
```
public XpsSaveOptions()
```


Constructor

### getSaveTransparentTexts() {#getSaveTransparentTexts--}
```
public final boolean getSaveTransparentTexts()
```


Indicates whether to preserve transparent (OCR'ed) text.

**Returns:**
boolean - boolean value
### setSaveTransparentTexts(boolean value) {#setSaveTransparentTexts-boolean-}
```
public final void setSaveTransparentTexts(boolean value)
```


Indicates whether to preserve transparent (OCR'ed) text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

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

