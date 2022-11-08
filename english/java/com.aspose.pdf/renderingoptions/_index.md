---
title: RenderingOptions
second_title: Aspose.PDF for Java API Reference
description: Represents rendering options
type: docs
weight: 304
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
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeOptimization()](#getBarcodeOptimization--) | Gets barcode optimization mode. |
| [getClass()](#getClass--) |  |
| [getConvertFontsToUnicodeTTF()](#getConvertFontsToUnicodeTTF--) | Indicates that all fonts will be converted to TTF unicode versions. |
| [getDefaultFontName()](#getDefaultFontName--) | Gets/sets the default name of font used to substitute of missing fonts. |
| [getHeightExtraUnits()](#getHeightExtraUnits--) | Gets or sets a value used to increase or decrease the width of rectangle for AppendRectangle operator. |
| [getIgnoreResourceFontErrors()](#getIgnoreResourceFontErrors--) | Gets or sets indication that errors related to absence of font will be ignored. |
| [getInterpolationHighQuality()](#getInterpolationHighQuality--) | Gets or sets high quality mode for interpolation. |
| [getMaxFontsCacheSize()](#getMaxFontsCacheSize--) | Maximum count of fonts in fonts cache. |
| [getMaxSymbolsCacheSize()](#getMaxSymbolsCacheSize--) | Maximum count of symbols in symbol cache. |
| [getOptimizeDimensions()](#getOptimizeDimensions--) | Gets or sets optimize dimensions mode. |
| [getScaleImagesToFitPageWidth()](#getScaleImagesToFitPageWidth--) | Gets or sets a values used to scale all images on the page to fit page's width. |
| [getSystemFontsNativeRendering()](#getSystemFontsNativeRendering--) | Gets a mode where system fonts are rendered natively |
| [getUseFontHinting()](#getUseFontHinting--) | Usage of this flag turn on font hinting mechanism. |
| [getUseNewImagingEngine()](#getUseNewImagingEngine--) | Gets a flag determines whether new imaging engine is used or not. |
| [getWidthExtraUnits()](#getWidthExtraUnits--) | Gets or sets a value used to increase or decrease the width of rectangle for AppendRectangle operator. |
| [hashCode()](#hashCode--) |  |
| [isTryToSkipDocumentErrors()](#isTryToSkipDocumentErrors--) | Gets a value used to skip errors during processing pdf file |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarcodeOptimization(boolean value)](#setBarcodeOptimization-boolean-) | Sets barcode optimization mode. |
| [setConvertFontsToUnicodeTTF(boolean value)](#setConvertFontsToUnicodeTTF-boolean-) | Indicates that all fonts will be converted to TTF unicode versions. |
| [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | Gets/sets the default name of font used to substitute of missing fonts. |
| [setHeightExtraUnits(float value)](#setHeightExtraUnits-float-) | Gets or sets a value used to increase or decrease the width of rectangle for AppendRectangle operator. |
| [setIgnoreResourceFontErrors(boolean value)](#setIgnoreResourceFontErrors-boolean-) | Gets or sets indication that errors related to absence of font will be ignored. |
| [setInterpolationHighQuality(boolean value)](#setInterpolationHighQuality-boolean-) | Gets or sets high quality mode for interpolation. |
| [setMaxFontsCacheSize(int value)](#setMaxFontsCacheSize-int-) | Maximum count of fonts in fonts cache. |
| [setMaxSymbolsCacheSize(int value)](#setMaxSymbolsCacheSize-int-) | Maximum count of symbols in symbol cache. |
| [setOptimizeDimensions(boolean value)](#setOptimizeDimensions-boolean-) | Gets or sets optimize dimensions mode. |
| [setScaleImagesToFitPageWidth(boolean value)](#setScaleImagesToFitPageWidth-boolean-) | Gets or sets a values used to scale all images on the page to fit page's width. |
| [setSystemFontsNativeRendering(boolean value)](#setSystemFontsNativeRendering-boolean-) | Sets a mode where system fonts are rendered natively |
| [setTryToSkipDocumentErrors(boolean value)](#setTryToSkipDocumentErrors-boolean-) | Sets a value used to skip errors during processing pdf file |
| [setUseFontHinting(boolean value)](#setUseFontHinting-boolean-) | Usage of this flag turn on font hinting mechanism. |
| [setUseNewImagingEngine(boolean value)](#setUseNewImagingEngine-boolean-) | Sets a flag determines whether new imaging engine is used or not. |
| [setWidthExtraUnits(float value)](#setWidthExtraUnits-float-) | Gets or sets a value used to increase or decrease the width of rectangle for AppendRectangle operator. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RenderingOptions() {#RenderingOptions--}
```
public RenderingOptions()
```


Initializes new instance of the  RenderingOptions  object.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBarcodeOptimization() {#getBarcodeOptimization--}
```
public boolean getBarcodeOptimization()
```


Gets barcode optimization mode.

**Returns:**
boolean - boolean value
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConvertFontsToUnicodeTTF() {#getConvertFontsToUnicodeTTF--}
```
public boolean getConvertFontsToUnicodeTTF()
```


Indicates that all fonts will be converted to TTF unicode versions. That is useful for compatibility reasons and to optimize font usage, cause every new TTF font will have not all the symbols from source font, but only symbols which are used in text.

**Returns:**
boolean - boolean value
### getDefaultFontName() {#getDefaultFontName--}
```
public final String getDefaultFontName()
```


Gets/sets the default name of font used to substitute of missing fonts.

**Returns:**
java.lang.String - String value
### getHeightExtraUnits() {#getHeightExtraUnits--}
```
public final float getHeightExtraUnits()
```


Gets or sets a value used to increase or decrease the width of rectangle for AppendRectangle operator.

**Returns:**
float - float value
### getIgnoreResourceFontErrors() {#getIgnoreResourceFontErrors--}
```
public final boolean getIgnoreResourceFontErrors()
```


Gets or sets indication that errors related to absence of font will be ignored. true - means that errors of absence of font will be ignored. Text segments that refer to incorrect resources will be skipped during processing. false by default

**Returns:**
boolean - boolean value
### getInterpolationHighQuality() {#getInterpolationHighQuality--}
```
public boolean getInterpolationHighQuality()
```


Gets or sets high quality mode for interpolation.

**Returns:**
boolean - boolean value
### getMaxFontsCacheSize() {#getMaxFontsCacheSize--}
```
public int getMaxFontsCacheSize()
```


Maximum count of fonts in fonts cache. Default value is 10.

**Returns:**
int - int value
### getMaxSymbolsCacheSize() {#getMaxSymbolsCacheSize--}
```
public int getMaxSymbolsCacheSize()
```


Maximum count of symbols in symbol cache. Default value is 100.

**Returns:**
int - int value
### getOptimizeDimensions() {#getOptimizeDimensions--}
```
public final boolean getOptimizeDimensions()
```


Gets or sets optimize dimensions mode.

**Returns:**
boolean - boolean value
### getScaleImagesToFitPageWidth() {#getScaleImagesToFitPageWidth--}
```
public boolean getScaleImagesToFitPageWidth()
```


Gets or sets a values used to scale all images on the page to fit page's width.

**Returns:**
boolean - boolean value
### getSystemFontsNativeRendering() {#getSystemFontsNativeRendering--}
```
public boolean getSystemFontsNativeRendering()
```


Gets a mode where system fonts are rendered natively

**Returns:**
boolean - boolean value
### getUseFontHinting() {#getUseFontHinting--}
```
public boolean getUseFontHinting()
```


Usage of this flag turn on font hinting mechanism. Font hinting is the use of mathematical instructions to adjust the display of an outline font. In some cases turning this flag on may solve problems with text legibility. At current moment usage of this flag could give effect only for TTF fonts, if these fonts are used in source document.

**Returns:**
boolean - boolean value
### getUseNewImagingEngine() {#getUseNewImagingEngine--}
```
public boolean getUseNewImagingEngine()
```


Gets a flag determines whether new imaging engine is used or not.

**Returns:**
boolean - boolean value
### getWidthExtraUnits() {#getWidthExtraUnits--}
```
public float getWidthExtraUnits()
```


Gets or sets a value used to increase or decrease the width of rectangle for AppendRectangle operator.

**Returns:**
float - float value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isTryToSkipDocumentErrors() {#isTryToSkipDocumentErrors--}
```
public boolean isTryToSkipDocumentErrors()
```


Gets a value used to skip errors during processing pdf file

**Returns:**
boolean - boolean value
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBarcodeOptimization(boolean value) {#setBarcodeOptimization-boolean-}
```
public void setBarcodeOptimization(boolean value)
```


Sets barcode optimization mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setConvertFontsToUnicodeTTF(boolean value) {#setConvertFontsToUnicodeTTF-boolean-}
```
public void setConvertFontsToUnicodeTTF(boolean value)
```


Indicates that all fonts will be converted to TTF unicode versions. That is useful for compatibility reasons and to optimize font usage, cause every new TTF font will have not all the symbols from source font, but only symbols which are used in text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setDefaultFontName(String value) {#setDefaultFontName-java.lang.String-}
```
public final void setDefaultFontName(String value)
```


Gets/sets the default name of font used to substitute of missing fonts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setHeightExtraUnits(float value) {#setHeightExtraUnits-float-}
```
public final void setHeightExtraUnits(float value)
```


Gets or sets a value used to increase or decrease the width of rectangle for AppendRectangle operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | float value |

### setIgnoreResourceFontErrors(boolean value) {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```


Gets or sets indication that errors related to absence of font will be ignored. true - means that errors of absence of font will be ignored. Text segments that refer to incorrect resources will be skipped during processing. false by default

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setInterpolationHighQuality(boolean value) {#setInterpolationHighQuality-boolean-}
```
public void setInterpolationHighQuality(boolean value)
```


Gets or sets high quality mode for interpolation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setMaxFontsCacheSize(int value) {#setMaxFontsCacheSize-int-}
```
public void setMaxFontsCacheSize(int value)
```


Maximum count of fonts in fonts cache. Default value is 10.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setMaxSymbolsCacheSize(int value) {#setMaxSymbolsCacheSize-int-}
```
public void setMaxSymbolsCacheSize(int value)
```


Maximum count of symbols in symbol cache. Default value is 100.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setOptimizeDimensions(boolean value) {#setOptimizeDimensions-boolean-}
```
public final void setOptimizeDimensions(boolean value)
```


Gets or sets optimize dimensions mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setScaleImagesToFitPageWidth(boolean value) {#setScaleImagesToFitPageWidth-boolean-}
```
public void setScaleImagesToFitPageWidth(boolean value)
```


Gets or sets a values used to scale all images on the page to fit page's width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setSystemFontsNativeRendering(boolean value) {#setSystemFontsNativeRendering-boolean-}
```
public void setSystemFontsNativeRendering(boolean value)
```


Sets a mode where system fonts are rendered natively

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setTryToSkipDocumentErrors(boolean value) {#setTryToSkipDocumentErrors-boolean-}
```
public void setTryToSkipDocumentErrors(boolean value)
```


Sets a value used to skip errors during processing pdf file

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setUseFontHinting(boolean value) {#setUseFontHinting-boolean-}
```
public void setUseFontHinting(boolean value)
```


Usage of this flag turn on font hinting mechanism. Font hinting is the use of mathematical instructions to adjust the display of an outline font. In some cases turning this flag on may solve problems with text legibility. At current moment usage of this flag could give effect only for TTF fonts, if these fonts are used in source document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setUseNewImagingEngine(boolean value) {#setUseNewImagingEngine-boolean-}
```
public void setUseNewImagingEngine(boolean value)
```


Sets a flag determines whether new imaging engine is used or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setWidthExtraUnits(float value) {#setWidthExtraUnits-float-}
```
public void setWidthExtraUnits(float value)
```


Gets or sets a value used to increase or decrease the width of rectangle for AppendRectangle operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | float value |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

