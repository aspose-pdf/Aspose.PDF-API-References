---
title: RenderingOptions
second_title: Aspose.PDF for Java API Reference
description: Represents rendering options
type: docs
weight: 248
url: /java/com.aspose.pdf/renderingoptions/
---
**Inheritance:**
java.lang.Object
```
public final class RenderingOptions
```

Represents rendering options
## Constructors

| Constructor | Description |
| --- | --- |
| [RenderingOptions()](#RenderingOptions--) | Initializes new instance of the  RenderingOptions  object. |
## Methods

| Method | Description |
| --- | --- |
| [getBarcodeOptimization()](#getBarcodeOptimization--) | Gets barcode optimization mode. |
| [setBarcodeOptimization(boolean value)](#setBarcodeOptimization-boolean-) | Sets barcode optimization mode. |
| [getOptimizeDimensions()](#getOptimizeDimensions--) | Gets or sets optimize dimensions mode. |
| [setOptimizeDimensions(boolean value)](#setOptimizeDimensions-boolean-) | Gets or sets optimize dimensions mode. |
| [getSystemFontsNativeRendering()](#getSystemFontsNativeRendering--) | Gets a mode where system fonts are rendered natively |
| [setSystemFontsNativeRendering(boolean value)](#setSystemFontsNativeRendering-boolean-) | Sets a mode where system fonts are rendered natively |
| [getUseNewImagingEngine()](#getUseNewImagingEngine--) | Gets a flag determines whether new imaging engine is used or not. |
| [setUseNewImagingEngine(boolean value)](#setUseNewImagingEngine-boolean-) | Sets a flag determines whether new imaging engine is used or not. |
| [getWidthExtraUnits()](#getWidthExtraUnits--) | Gets or sets a value used to increase or decrease the width of rectangle for AppendRectangle operator. |
| [setWidthExtraUnits(float value)](#setWidthExtraUnits-float-) | Gets or sets a value used to increase or decrease the width of rectangle for AppendRectangle operator. |
| [getConvertFontsToUnicodeTTF()](#getConvertFontsToUnicodeTTF--) | Indicates that all fonts will be converted to TTF unicode versions. |
| [setConvertFontsToUnicodeTTF(boolean value)](#setConvertFontsToUnicodeTTF-boolean-) | Indicates that all fonts will be converted to TTF unicode versions. |
| [getUseFontHinting()](#getUseFontHinting--) | Usage of this flag turn on font hinting mechanism. |
| [setUseFontHinting(boolean value)](#setUseFontHinting-boolean-) | Usage of this flag turn on font hinting mechanism. |
| [getScaleImagesToFitPageWidth()](#getScaleImagesToFitPageWidth--) | Gets or sets a values used to scale all images on the page to fit page's width. |
| [setScaleImagesToFitPageWidth(boolean value)](#setScaleImagesToFitPageWidth-boolean-) | Gets or sets a values used to scale all images on the page to fit page's width. |
| [getInterpolationHighQuality()](#getInterpolationHighQuality--) | Gets or sets high Quality mode for interpolation. |
| [setInterpolationHighQuality(boolean value)](#setInterpolationHighQuality-boolean-) | Gets or sets high Quality mode for interpolation. |
| [getMaxFontsCacheSize()](#getMaxFontsCacheSize--) | Maximum count of fonts in fonts cache. |
| [setMaxFontsCacheSize(int value)](#setMaxFontsCacheSize-int-) | Maximum count of fonts in fonts cache. |
| [getMaxSymbolsCacheSize()](#getMaxSymbolsCacheSize--) | Maximum count of symbols in symbol cache. |
| [setMaxSymbolsCacheSize(int value)](#setMaxSymbolsCacheSize-int-) | Maximum count of symbols in symbol cache. |
| [getDefaultFontName()](#getDefaultFontName--) | Gets/sets the default name of font used to substitute of missing fonts. |
| [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | Gets/sets the default name of font used to substitute of missing fonts. |
### RenderingOptions() {#RenderingOptions--}
```
public RenderingOptions()
```


Initializes new instance of the  RenderingOptions  object.

### getBarcodeOptimization() {#getBarcodeOptimization--}
```
public boolean getBarcodeOptimization()
```


Gets barcode optimization mode.

**Returns:**
boolean - boolean value
### setBarcodeOptimization(boolean value) {#setBarcodeOptimization-boolean-}
```
public void setBarcodeOptimization(boolean value)
```


Sets barcode optimization mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getOptimizeDimensions() {#getOptimizeDimensions--}
```
public final boolean getOptimizeDimensions()
```


Gets or sets optimize dimensions mode.

**Returns:**
boolean - boolean value
### setOptimizeDimensions(boolean value) {#setOptimizeDimensions-boolean-}
```
public final void setOptimizeDimensions(boolean value)
```


Gets or sets optimize dimensions mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getSystemFontsNativeRendering() {#getSystemFontsNativeRendering--}
```
public boolean getSystemFontsNativeRendering()
```


Gets a mode where system fonts are rendered natively

**Returns:**
boolean - boolean value
### setSystemFontsNativeRendering(boolean value) {#setSystemFontsNativeRendering-boolean-}
```
public void setSystemFontsNativeRendering(boolean value)
```


Sets a mode where system fonts are rendered natively

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getUseNewImagingEngine() {#getUseNewImagingEngine--}
```
public boolean getUseNewImagingEngine()
```


Gets a flag determines whether new imaging engine is used or not.

**Returns:**
boolean - boolean value
### setUseNewImagingEngine(boolean value) {#setUseNewImagingEngine-boolean-}
```
public void setUseNewImagingEngine(boolean value)
```


Sets a flag determines whether new imaging engine is used or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getWidthExtraUnits() {#getWidthExtraUnits--}
```
public float getWidthExtraUnits()
```


Gets or sets a value used to increase or decrease the width of rectangle for AppendRectangle operator.

**Returns:**
float - float value
### setWidthExtraUnits(float value) {#setWidthExtraUnits-float-}
```
public void setWidthExtraUnits(float value)
```


Gets or sets a value used to increase or decrease the width of rectangle for AppendRectangle operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | float value |

### getConvertFontsToUnicodeTTF() {#getConvertFontsToUnicodeTTF--}
```
public boolean getConvertFontsToUnicodeTTF()
```


Indicates that all fonts will be converted to TTF unicode versions. That is useful for compatibility reasons and to optimize font usage, cause every new TTF font will have not all the symbols from source font, but only symbols which are used in text.

**Returns:**
boolean - boolean value
### setConvertFontsToUnicodeTTF(boolean value) {#setConvertFontsToUnicodeTTF-boolean-}
```
public void setConvertFontsToUnicodeTTF(boolean value)
```


Indicates that all fonts will be converted to TTF unicode versions. That is useful for compatibility reasons and to optimize font usage, cause every new TTF font will have not all the symbols from source font, but only symbols which are used in text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getUseFontHinting() {#getUseFontHinting--}
```
public boolean getUseFontHinting()
```


Usage of this flag turn on font hinting mechanism. Font hinting is the use of mathematical instructions to adjust the display of an outline font. In some cases turning this flag on may solve problems with text legibility. At current moment usage of this flag could give effect only for TTF fonts, if these fonts are used in source document.

**Returns:**
boolean - boolean value
### setUseFontHinting(boolean value) {#setUseFontHinting-boolean-}
```
public void setUseFontHinting(boolean value)
```


Usage of this flag turn on font hinting mechanism. Font hinting is the use of mathematical instructions to adjust the display of an outline font. In some cases turning this flag on may solve problems with text legibility. At current moment usage of this flag could give effect only for TTF fonts, if these fonts are used in source document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getScaleImagesToFitPageWidth() {#getScaleImagesToFitPageWidth--}
```
public boolean getScaleImagesToFitPageWidth()
```


Gets or sets a values used to scale all images on the page to fit page's width.

**Returns:**
boolean - boolean value
### setScaleImagesToFitPageWidth(boolean value) {#setScaleImagesToFitPageWidth-boolean-}
```
public void setScaleImagesToFitPageWidth(boolean value)
```


Gets or sets a values used to scale all images on the page to fit page's width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getInterpolationHighQuality() {#getInterpolationHighQuality--}
```
public boolean getInterpolationHighQuality()
```


Gets or sets high Quality mode for interpolation.

**Returns:**
boolean - boolean value
### setInterpolationHighQuality(boolean value) {#setInterpolationHighQuality-boolean-}
```
public void setInterpolationHighQuality(boolean value)
```


Gets or sets high Quality mode for interpolation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getMaxFontsCacheSize() {#getMaxFontsCacheSize--}
```
public int getMaxFontsCacheSize()
```


Maximum count of fonts in fonts cache. Default value is 10.

**Returns:**
int - int value
### setMaxFontsCacheSize(int value) {#setMaxFontsCacheSize-int-}
```
public void setMaxFontsCacheSize(int value)
```


Maximum count of fonts in fonts cache. Default value is 10.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### getMaxSymbolsCacheSize() {#getMaxSymbolsCacheSize--}
```
public int getMaxSymbolsCacheSize()
```


Maximum count of symbols in symbol cache. Default value is 100.

**Returns:**
int - int value
### setMaxSymbolsCacheSize(int value) {#setMaxSymbolsCacheSize-int-}
```
public void setMaxSymbolsCacheSize(int value)
```


Maximum count of symbols in symbol cache. Default value is 100.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### getDefaultFontName() {#getDefaultFontName--}
```
public final String getDefaultFontName()
```


Gets/sets the default name of font used to substitute of missing fonts.

**Returns:**
java.lang.String - String value
### setDefaultFontName(String value) {#setDefaultFontName-java.lang.String-}
```
public final void setDefaultFontName(String value)
```


Gets/sets the default name of font used to substitute of missing fonts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

