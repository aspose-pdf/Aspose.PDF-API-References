---
title: XpsSaveOptions
linktitle: XpsSaveOptions
second_title: Aspose.PDF for Java API Reference
description: Save options for export to Xps format
type: docs
weight: 5770
url: /java/com.aspose.pdf/xpssaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.XpsSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.XpsSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.XpsSaveOptions

**All Implemented Interfaces:**
IPipelineOptions

```
public class XpsSaveOptions extends UnifiedSaveOptions implements IPipelineOptions
```

Save options for export to Xps format

## Constructors

| Constructor | Description |
| --- | --- |
| [XpsSaveOptions](#XpsSaveOptions--) | Constructor |

## Methods

| Method | Description |
| --- | --- |
| [getBatchSize](#getBatchSize--) | Defines batch size if batched conversion is applicable to source and destination formats pair. |
| [getDefaultFont](#getDefaultFont--) | Gets/sets the default font name. Used if the embedded font name is not found in the system. |
| [getSaveTransparentTexts](#getSaveTransparentTexts--) | Indicates whether to preserve transparent (OCR'ed) text. |
| [getUseEmbeddedTrueTypeFonts](#getUseEmbeddedTrueTypeFonts--) | Gets/sets the flag to use embedded TrueType fonts. Avoiding the use of embedded TrueType fonts can reduce conversion time. |
| [isUseNewImagingEngine](#isUseNewImagingEngine--) | Gets or sets UseNewImagingEngine option. |
| [setBatchSize](#setBatchSize-int-) | Defines batch size if batched conversion is applicable to source and destination formats pair. |
| [setDefaultFont](#setDefaultFont-java.lang.String-) | Gets/sets the default font name. Used if the embedded font name is not found in the system. |
| [setSaveTransparentTexts](#setSaveTransparentTexts-boolean-) | Indicates whether to preserve transparent (OCR'ed) text. |
| [setUseEmbeddedTrueTypeFonts](#setUseEmbeddedTrueTypeFonts-boolean-) | Gets/sets the flag to use embedded TrueType fonts. Avoiding the use of embedded TrueType fonts can reduce conversion time. |
| [setUseNewImagingEngine](#setUseNewImagingEngine-boolean-) | Gets or sets UseNewImagingEngine option. |

### XpsSaveOptions {#XpsSaveOptions--}
```
public XpsSaveOptions()
```

Constructor

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

Defines batch size if batched conversion is applicable to source and destination formats pair.

**Returns:**
int value

### getDefaultFont {#getDefaultFont--}
```
public final String getDefaultFont()
```

Gets/sets the default font name. Used if the embedded font name is not found in the system.

**Returns:**
String value

### getSaveTransparentTexts {#getSaveTransparentTexts--}
```
public final boolean getSaveTransparentTexts()
```

Indicates whether to preserve transparent (OCR'ed) text.

**Returns:**
boolean value

### getUseEmbeddedTrueTypeFonts {#getUseEmbeddedTrueTypeFonts--}
```
public final boolean getUseEmbeddedTrueTypeFonts()
```

Gets/sets the flag to use embedded TrueType fonts. Avoiding the use of embedded TrueType fonts can reduce conversion time.

**Returns:**
boolean value

### isUseNewImagingEngine {#isUseNewImagingEngine--}
```
@Deprecated public final boolean isUseNewImagingEngine()
```

Gets or sets UseNewImagingEngine option.

**Returns:**
boolean value @deprecated UseNewImagingEngine is deprecated

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

Defines batch size if batched conversion is applicable to source and destination formats pair.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setDefaultFont {#setDefaultFont-java.lang.String-}
Gets/sets the default font name. Used if the embedded font name is not found in the system.

### setSaveTransparentTexts {#setSaveTransparentTexts-boolean-}
```
public final void setSaveTransparentTexts(boolean value)
```

Indicates whether to preserve transparent (OCR'ed) text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setUseEmbeddedTrueTypeFonts {#setUseEmbeddedTrueTypeFonts-boolean-}
```
public final void setUseEmbeddedTrueTypeFonts(boolean value)
```

Gets/sets the flag to use embedded TrueType fonts. Avoiding the use of embedded TrueType fonts can reduce conversion time.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setUseNewImagingEngine {#setUseNewImagingEngine-boolean-}
```
@Deprecated public final void setUseNewImagingEngine(boolean value)
```

Gets or sets UseNewImagingEngine option.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value @deprecated UseNewImagingEngine is deprecated |
