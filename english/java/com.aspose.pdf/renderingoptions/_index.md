---
title: RenderingOptions
linktitle: RenderingOptions
second_title: Aspose.PDF for Java API Reference
description: Represents rendering options
type: docs
weight: 4150
url: /java/com.aspose.pdf/renderingoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.RenderingOptions

```
public final class RenderingOptions extends Object
```

Represents rendering options

## Constructors

| Constructor | Description |
| --- | --- |
| [RenderingOptions](#RenderingOptions--) | Initializes new instance of the {@code RenderingOptions} object. |

## Methods

| Method | Description |
| --- | --- |
| [getAnalyzeFonts](#getAnalyzeFonts--) | Replaces fonts as necessary to ensure all characters in the text can be displayed. The font substitution algorithm follows these steps: 1. If the user explicitly sets the DefaultFontName property, check if the specified font can display the desired characters. 2. If no user-defined font is set, search through fonts added via the {@code FontRepository.Sources}. 3. Analyze the text to identify its alphabet or script and suggest font names accordingly. Attempt to locate and use these fonts from the system. 4. As a fallback, search the system for any font capable of displaying the required characters. |
| [getBarcodeOptimization](#getBarcodeOptimization--) | Gets barcode optimization mode. |
| [getConvertFontsToUnicodeTTF](#getConvertFontsToUnicodeTTF--) | Indicates that all fonts will be converted to TTF unicode versions. That is useful for compatibility reasons and to optimize font usage, cause every new TTF font will have not all the symbols from source font, but only symbols which are used in text. |
| [getDefaultFontName](#getDefaultFontName--) | Gets/sets the default name of font used to substitute of missing fonts. |
| [getHeightExtraUnits](#getHeightExtraUnits--) | Gets or sets a value used to increase or decrease the width of rectangle for AppendRectangle operator. |
| [getIgnoreResourceFontErrors](#getIgnoreResourceFontErrors--) | Gets or sets indication that errors related to absence of font will be ignored. true - means that errors of absence of font will be ignored. Text segments that refer to incorrect resources will be skipped during processing. false by default |
| [getInterpolationHighQuality](#getInterpolationHighQuality--) | Gets or sets high quality mode for interpolation. |
| [getMaxFontsCacheSize](#getMaxFontsCacheSize--) | Maximum count of fonts in fonts cache. Default value is 10. |
| [getMaxSymbolsCacheSize](#getMaxSymbolsCacheSize--) | Maximum count of symbols in symbol cache. Default value is 100. |
| [getOptimizeDimensions](#getOptimizeDimensions--) | Gets or sets optimize dimensions mode. |
| [getScaleImagesToFitPageWidth](#getScaleImagesToFitPageWidth--) | Gets or sets a values used to scale all images on the page to fit page's width. |
| [getSystemFontsNativeRendering](#getSystemFontsNativeRendering--) | Gets a mode where system fonts are rendered natively |
| [getUseFontHinting](#getUseFontHinting--) | Usage of this flag turn on font hinting mechanism. Font hinting is the use of mathematical instructions to adjust the display of an outline font. In some cases turning this flag on may solve problems with text legibility. At current moment usage of this flag could give effect only for TTF fonts, if these fonts are used in source document. |
| [getUseNewImagingEngine](#getUseNewImagingEngine--) | Gets a flag determines whether new imaging engine is used or not. |
| [getWidthExtraUnits](#getWidthExtraUnits--) | Gets or sets a value used to increase or decrease the width of rectangle for AppendRectangle operator. |
| [isTryToSkipDocumentErrors](#isTryToSkipDocumentErrors--) | Gets a value used to skip errors during processing pdf file |
| [setAnalyzeFonts](#setAnalyzeFonts-boolean-) | Replaces fonts as necessary to ensure all characters in the text can be displayed. The font substitution algorithm follows these steps: 1. If the user explicitly sets the DefaultFontName property, check if the specified font can display the desired characters. 2. If no user-defined font is set, search through fonts added via the {@code FontRepository.Sources}. 3. Analyze the text to identify its alphabet or script and suggest font names accordingly. Attempt to locate and use these fonts from the system. 4. As a fallback, search the system for any font capable of displaying the required characters. |
| [setBarcodeOptimization](#setBarcodeOptimization-boolean-) | Sets barcode optimization mode. |
| [setConvertFontsToUnicodeTTF](#setConvertFontsToUnicodeTTF-boolean-) | Indicates that all fonts will be converted to TTF unicode versions. That is useful for compatibility reasons and to optimize font usage, cause every new TTF font will have not all the symbols from source font, but only symbols which are used in text. |
| [setDefaultFontName](#setDefaultFontName-java.lang.String-) | Gets/sets the default name of font used to substitute of missing fonts. |
| [setHeightExtraUnits](#setHeightExtraUnits-float-) | Gets or sets a value used to increase or decrease the width of rectangle for AppendRectangle operator. |
| [setIgnoreResourceFontErrors](#setIgnoreResourceFontErrors-boolean-) | Gets or sets indication that errors related to absence of font will be ignored. true - means that errors of absence of font will be ignored. Text segments that refer to incorrect resources will be skipped during processing. false by default |
| [setInterpolationHighQuality](#setInterpolationHighQuality-boolean-) | Gets or sets high quality mode for interpolation. |
| [setMaxFontsCacheSize](#setMaxFontsCacheSize-int-) | Maximum count of fonts in fonts cache. Default value is 10. |
| [setMaxSymbolsCacheSize](#setMaxSymbolsCacheSize-int-) | Maximum count of symbols in symbol cache. Default value is 100. |
| [setOptimizeDimensions](#setOptimizeDimensions-boolean-) | Gets or sets optimize dimensions mode. |
| [setScaleImagesToFitPageWidth](#setScaleImagesToFitPageWidth-boolean-) | Gets or sets a values used to scale all images on the page to fit page's width. |
| [setSystemFontsNativeRendering](#setSystemFontsNativeRendering-boolean-) | Sets a mode where system fonts are rendered natively |
| [setTryToSkipDocumentErrors](#setTryToSkipDocumentErrors-boolean-) | Sets a value used to skip errors during processing pdf file |
| [setUseFontHinting](#setUseFontHinting-boolean-) | Usage of this flag turn on font hinting mechanism. Font hinting is the use of mathematical instructions to adjust the display of an outline font. In some cases turning this flag on may solve problems with text legibility. At current moment usage of this flag could give effect only for TTF fonts, if these fonts are used in source document. |
| [setUseNewImagingEngine](#setUseNewImagingEngine-boolean-) | Sets a flag determines whether new imaging engine is used or not. |
| [setWidthExtraUnits](#setWidthExtraUnits-float-) | Gets or sets a value used to increase or decrease the width of rectangle for AppendRectangle operator. |

### RenderingOptions {#RenderingOptions--}
```
public RenderingOptions()
```

Initializes new instance of the {@code RenderingOptions} object.

### getAnalyzeFonts {#getAnalyzeFonts--}
```
public final boolean getAnalyzeFonts()
```

Replaces fonts as necessary to ensure all characters in the text can be displayed. The font substitution algorithm follows these steps: 1. If the user explicitly sets the DefaultFontName property, check if the specified font can display the desired characters. 2. If no user-defined font is set, search through fonts added via the {@code FontRepository.Sources}. 3. Analyze the text to identify its alphabet or script and suggest font names accordingly. Attempt to locate and use these fonts from the system. 4. As a fallback, search the system for any font capable of displaying the required characters.

**Returns:**
boolean value

### getBarcodeOptimization {#getBarcodeOptimization--}
```
public boolean getBarcodeOptimization()
```

Gets barcode optimization mode.

**Returns:**
boolean value

### getConvertFontsToUnicodeTTF {#getConvertFontsToUnicodeTTF--}
```
public boolean getConvertFontsToUnicodeTTF()
```

Indicates that all fonts will be converted to TTF unicode versions. That is useful for compatibility reasons and to optimize font usage, cause every new TTF font will have not all the symbols from source font, but only symbols which are used in text.

**Returns:**
boolean value

### getDefaultFontName {#getDefaultFontName--}
```
public final String getDefaultFontName()
```

Gets/sets the default name of font used to substitute of missing fonts.

**Returns:**
String value

### getHeightExtraUnits {#getHeightExtraUnits--}
```
public final float getHeightExtraUnits()
```

Gets or sets a value used to increase or decrease the width of rectangle for AppendRectangle operator.

**Returns:**
float value

### getIgnoreResourceFontErrors {#getIgnoreResourceFontErrors--}
```
public final boolean getIgnoreResourceFontErrors()
```

Gets or sets indication that errors related to absence of font will be ignored. true - means that errors of absence of font will be ignored. Text segments that refer to incorrect resources will be skipped during processing. false by default

**Returns:**
boolean value

### getInterpolationHighQuality {#getInterpolationHighQuality--}
```
public boolean getInterpolationHighQuality()
```

Gets or sets high quality mode for interpolation.

**Returns:**
boolean value

### getMaxFontsCacheSize {#getMaxFontsCacheSize--}
```
public int getMaxFontsCacheSize()
```

Maximum count of fonts in fonts cache. Default value is 10.

**Returns:**
int value

### getMaxSymbolsCacheSize {#getMaxSymbolsCacheSize--}
```
public int getMaxSymbolsCacheSize()
```

Maximum count of symbols in symbol cache. Default value is 100.

**Returns:**
int value

### getOptimizeDimensions {#getOptimizeDimensions--}
```
public final boolean getOptimizeDimensions()
```

Gets or sets optimize dimensions mode.

**Returns:**
boolean value

### getScaleImagesToFitPageWidth {#getScaleImagesToFitPageWidth--}
```
@Deprecated public final boolean getScaleImagesToFitPageWidth()
```

Gets or sets a values used to scale all images on the page to fit page's width.

**Returns:**
boolean value @deprecated ScaleImagesToFitPageWidth is deprecated.

### getSystemFontsNativeRendering {#getSystemFontsNativeRendering--}
```
public boolean getSystemFontsNativeRendering()
```

Gets a mode where system fonts are rendered natively

**Returns:**
boolean value

### getUseFontHinting {#getUseFontHinting--}
```
public boolean getUseFontHinting()
```

Usage of this flag turn on font hinting mechanism. Font hinting is the use of mathematical instructions to adjust the display of an outline font. In some cases turning this flag on may solve problems with text legibility. At current moment usage of this flag could give effect only for TTF fonts, if these fonts are used in source document.

**Returns:**
boolean value

### getUseNewImagingEngine {#getUseNewImagingEngine--}
```
@Deprecated public boolean getUseNewImagingEngine()
```

Gets a flag determines whether new imaging engine is used or not.

**Returns:**
boolean value @deprecated UseNewImagingEngine is deprecated

### getWidthExtraUnits {#getWidthExtraUnits--}
```
public float getWidthExtraUnits()
```

Gets or sets a value used to increase or decrease the width of rectangle for AppendRectangle operator.

**Returns:**
float value

### isTryToSkipDocumentErrors {#isTryToSkipDocumentErrors--}
```
public boolean isTryToSkipDocumentErrors()
```

Gets a value used to skip errors during processing pdf file

**Returns:**
boolean value

### setAnalyzeFonts {#setAnalyzeFonts-boolean-}
```
public final void setAnalyzeFonts(boolean value)
```

Replaces fonts as necessary to ensure all characters in the text can be displayed. The font substitution algorithm follows these steps: 1. If the user explicitly sets the DefaultFontName property, check if the specified font can display the desired characters. 2. If no user-defined font is set, search through fonts added via the {@code FontRepository.Sources}. 3. Analyze the text to identify its alphabet or script and suggest font names accordingly. Attempt to locate and use these fonts from the system. 4. As a fallback, search the system for any font capable of displaying the required characters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setBarcodeOptimization {#setBarcodeOptimization-boolean-}
```
public void setBarcodeOptimization(boolean value)
```

Sets barcode optimization mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setConvertFontsToUnicodeTTF {#setConvertFontsToUnicodeTTF-boolean-}
```
public void setConvertFontsToUnicodeTTF(boolean value)
```

Indicates that all fonts will be converted to TTF unicode versions. That is useful for compatibility reasons and to optimize font usage, cause every new TTF font will have not all the symbols from source font, but only symbols which are used in text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setDefaultFontName {#setDefaultFontName-java.lang.String-}
Gets/sets the default name of font used to substitute of missing fonts.

### setHeightExtraUnits {#setHeightExtraUnits-float-}
```
public final void setHeightExtraUnits(float value)
```

Gets or sets a value used to increase or decrease the width of rectangle for AppendRectangle operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | float value |

### setIgnoreResourceFontErrors {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```

Gets or sets indication that errors related to absence of font will be ignored. true - means that errors of absence of font will be ignored. Text segments that refer to incorrect resources will be skipped during processing. false by default

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setInterpolationHighQuality {#setInterpolationHighQuality-boolean-}
```
public void setInterpolationHighQuality(boolean value)
```

Gets or sets high quality mode for interpolation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setMaxFontsCacheSize {#setMaxFontsCacheSize-int-}
```
public void setMaxFontsCacheSize(int value)
```

Maximum count of fonts in fonts cache. Default value is 10.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setMaxSymbolsCacheSize {#setMaxSymbolsCacheSize-int-}
```
public void setMaxSymbolsCacheSize(int value)
```

Maximum count of symbols in symbol cache. Default value is 100.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setOptimizeDimensions {#setOptimizeDimensions-boolean-}
```
public final void setOptimizeDimensions(boolean value)
```

Gets or sets optimize dimensions mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setScaleImagesToFitPageWidth {#setScaleImagesToFitPageWidth-boolean-}
```
@Deprecated public final void setScaleImagesToFitPageWidth(boolean value)
```

Gets or sets a values used to scale all images on the page to fit page's width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value @deprecated ScaleImagesToFitPageWidth is deprecated. |

### setSystemFontsNativeRendering {#setSystemFontsNativeRendering-boolean-}
```
public void setSystemFontsNativeRendering(boolean value)
```

Sets a mode where system fonts are rendered natively

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setTryToSkipDocumentErrors {#setTryToSkipDocumentErrors-boolean-}
```
public void setTryToSkipDocumentErrors(boolean value)
```

Sets a value used to skip errors during processing pdf file

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setUseFontHinting {#setUseFontHinting-boolean-}
```
public void setUseFontHinting(boolean value)
```

Usage of this flag turn on font hinting mechanism. Font hinting is the use of mathematical instructions to adjust the display of an outline font. In some cases turning this flag on may solve problems with text legibility. At current moment usage of this flag could give effect only for TTF fonts, if these fonts are used in source document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setUseNewImagingEngine {#setUseNewImagingEngine-boolean-}
```
@Deprecated public void setUseNewImagingEngine(boolean value)
```

Sets a flag determines whether new imaging engine is used or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value @deprecated UseNewImagingEngine is deprecated |

### setWidthExtraUnits {#setWidthExtraUnits-float-}
```
public void setWidthExtraUnits(float value)
```

Gets or sets a value used to increase or decrease the width of rectangle for AppendRectangle operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | float value |
