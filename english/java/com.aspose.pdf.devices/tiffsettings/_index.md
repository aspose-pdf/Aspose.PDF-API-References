---
title: TiffSettings
second_title: Aspose.PDF for Java API Reference
description: This class represents settings for importing pdf to Tiff.
type: docs
weight: 30
url: /java/com.aspose.pdf.devices/tiffsettings/
---
**Inheritance:**
java.lang.Object
```
public final class TiffSettings
```

This class represents settings for importing pdf to Tiff.
## Constructors

| Constructor | Description |
| --- | --- |
| [TiffSettings()](#TiffSettings--) | Initializes a new instance of the  TiffSettings  class. |
| [TiffSettings(int compressionType)](#TiffSettings-int-) | Initializes a new instance of the  TiffSettings  class. |
| [TiffSettings(Margins margins)](#TiffSettings-com.aspose.pdf.devices.Margins-) | Initializes a new instance of the  TiffSettings  class. |
| [TiffSettings(int compressionType, int colorDepth, Margins margins)](#TiffSettings-int-int-com.aspose.pdf.devices.Margins-) | Initializes a new instance of the  TiffSettings  class. |
| [TiffSettings(int compressionType, int colorDepth, Margins margins, boolean skipBlankPages)](#TiffSettings-int-int-com.aspose.pdf.devices.Margins-boolean-) | Initializes a new instance of the  TiffSettings  class. |
| [TiffSettings(int compressionType, int colorDepth, Margins margins, boolean skipBlankPages, int shapeType)](#TiffSettings-int-int-com.aspose.pdf.devices.Margins-boolean-int-) | Initializes a new instance of the  TiffSettings  class. |
| [TiffSettings(boolean skipBlankPages)](#TiffSettings-boolean-) | Initializes a new instance of the  TiffSettings  class. |
## Methods

| Method | Description |
| --- | --- |
| [getIndexedConversionType()](#getIndexedConversionType--) | Gets the IndexedConversionType. |
| [setIndexedConversionType(int value)](#setIndexedConversionType-int-) | Sets the IndexedConversionType. |
| [getMargins()](#getMargins--) | Gets the margins. |
| [getSkipBlankPages()](#getSkipBlankPages--) | Gets a value indicating whether to skip blank pages. |
| [setSkipBlankPages(boolean value)](#setSkipBlankPages-boolean-) | Sets a value indicating whether to skip blank pages. |
| [getCompression()](#getCompression--) | Gets the type of the compression. |
| [setCompression(int value)](#setCompression-int-) | Sets the type of the compression. |
| [getDepth()](#getDepth--) | Gets the color depth. |
| [setDepth(int value)](#setDepth-int-) | Gets the color depth. |
| [getShape()](#getShape--) | Gets the type of the shape. |
| [setShape(int value)](#setShape-int-) | Sets the type of the shape. |
| [getBrightness()](#getBrightness--) | Get value boundary of the transformation of colors in white and black. |
| [setBrightness(float value)](#setBrightness-float-) | Set value boundary of the transformation of colors in white and black. |
| [getCoordinateType()](#getCoordinateType--) | Gets the page coordinate type (Media/Crop boxes). |
| [setCoordinateType(int value)](#setCoordinateType-int-) | Sets the page coordinate type (Media/Crop boxes). |
| [isUseAlternativeImageEngine()](#isUseAlternativeImageEngine--) | Gets a flag determines whether alternative imaging engine is used or not. |
| [setUseAlternativeImageEngine(boolean useAlternativeImageEngine)](#setUseAlternativeImageEngine-boolean-) | Sets a flag determines whether alternative imaging engine is used or not. |
### TiffSettings() {#TiffSettings--}
```
public TiffSettings()
```


Initializes a new instance of the  TiffSettings  class.

### TiffSettings(int compressionType) {#TiffSettings-int-}
```
public TiffSettings(int compressionType)
```


Initializes a new instance of the  TiffSettings  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| compressionType | int | Type of the compression. |

### TiffSettings(Margins margins) {#TiffSettings-com.aspose.pdf.devices.Margins-}
```
public TiffSettings(Margins margins)
```


Initializes a new instance of the  TiffSettings  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| margins | [Margins](../../com.aspose.pdf.devices/margins) | The margins. |

### TiffSettings(int compressionType, int colorDepth, Margins margins) {#TiffSettings-int-int-com.aspose.pdf.devices.Margins-}
```
public TiffSettings(int compressionType, int colorDepth, Margins margins)
```


Initializes a new instance of the  TiffSettings  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| compressionType | int | Type of the compression. |
| colorDepth | int | The color depth. |
| margins | [Margins](../../com.aspose.pdf.devices/margins) | The margins. |

### TiffSettings(int compressionType, int colorDepth, Margins margins, boolean skipBlankPages) {#TiffSettings-int-int-com.aspose.pdf.devices.Margins-boolean-}
```
public TiffSettings(int compressionType, int colorDepth, Margins margins, boolean skipBlankPages)
```


Initializes a new instance of the  TiffSettings  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| compressionType | int | Type of the compression. |
| colorDepth | int | The color depth. |
| margins | [Margins](../../com.aspose.pdf.devices/margins) | The margins. |
| skipBlankPages | boolean | if set to  true  need to skip blank pages |

### TiffSettings(int compressionType, int colorDepth, Margins margins, boolean skipBlankPages, int shapeType) {#TiffSettings-int-int-com.aspose.pdf.devices.Margins-boolean-int-}
```
public TiffSettings(int compressionType, int colorDepth, Margins margins, boolean skipBlankPages, int shapeType)
```


Initializes a new instance of the  TiffSettings  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| compressionType | int | Type of the compression. |
| colorDepth | int | The color depth. |
| margins | [Margins](../../com.aspose.pdf.devices/margins) | The margins. |
| skipBlankPages | boolean | if set to  true  need to skip blank pages. |
| shapeType | int | Type of the shape. |

### TiffSettings(boolean skipBlankPages) {#TiffSettings-boolean-}
```
public TiffSettings(boolean skipBlankPages)
```


Initializes a new instance of the  TiffSettings  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| skipBlankPages | boolean | if set to  true  [skip blank pages]. |

### getIndexedConversionType() {#getIndexedConversionType--}
```
public int getIndexedConversionType()
```


Gets the IndexedConversionType. Default value is Simple.

**Returns:**
int - IndexedConversionType element
### setIndexedConversionType(int value) {#setIndexedConversionType-int-}
```
public void setIndexedConversionType(int value)
```


Sets the IndexedConversionType.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | IndexedConversionType element |

### getMargins() {#getMargins--}
```
public Margins getMargins()
```


Gets the margins.

**Returns:**
[Margins](../../com.aspose.pdf.devices/margins) - Margins object
### getSkipBlankPages() {#getSkipBlankPages--}
```
public boolean getSkipBlankPages()
```


Gets a value indicating whether to skip blank pages.

Value:  true  if need to skip blank pages; otherwise,  false .

--------------------

Default value is false

**Returns:**
boolean - boolean value
### setSkipBlankPages(boolean value) {#setSkipBlankPages-boolean-}
```
public void setSkipBlankPages(boolean value)
```


Sets a value indicating whether to skip blank pages.

Value:  true  if need to skip blank pages; otherwise,  false .

--------------------

Default value is false

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getCompression() {#getCompression--}
```
public int getCompression()
```


Gets the type of the compression.

Value: The type of the compression.

--------------------

Default value is CompressionType.LZW

**Returns:**
int - CompressionType element
### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Sets the type of the compression.

Value: The type of the compression.

--------------------

Default value is CompressionType.LZW

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | CompressionType element |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Gets the color depth.

Value: The color depth.

--------------------

Default value is ColorDepth.Default

**Returns:**
int - ColorDepth element
### setDepth(int value) {#setDepth-int-}
```
public void setDepth(int value)
```


Gets the color depth.

Value: The color depth.

--------------------

Default value is ColorDepth.Default

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ColorDepth element |

### getShape() {#getShape--}
```
public int getShape()
```


Gets the type of the shape.

Value: The type of the shape.

--------------------

Default value is ShapeType.None

**Returns:**
int - ShapeType element
### setShape(int value) {#setShape-int-}
```
public void setShape(int value)
```


Sets the type of the shape.

Value: The type of the shape.

--------------------

Default value is ShapeType.None

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ShapeType element |

### getBrightness() {#getBrightness--}
```
public float getBrightness()
```


Get value boundary of the transformation of colors in white and black. This parameter can be applied with EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle or ColorDepth.Format1bpp == 1

**Returns:**
float - float value of brightness should be in the range from 0 to 1. By default value is equal to 0.33f
### setBrightness(float value) {#setBrightness-float-}
```
public void setBrightness(float value)
```


Set value boundary of the transformation of colors in white and black. This parameter can be applied with EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle or ColorDepth.Format1bpp == 1

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | : Value of brightness should be in the range from 0 to 1. By default value is equal to 0.33f |

### getCoordinateType() {#getCoordinateType--}
```
public int getCoordinateType()
```


Gets the page coordinate type (Media/Crop boxes). CropBox value is used by default.

**Returns:**
int - PageCoordinateType value
### setCoordinateType(int value) {#setCoordinateType-int-}
```
public void setCoordinateType(int value)
```


Sets the page coordinate type (Media/Crop boxes). CropBox value is used by default.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | PageCoordinateType |

### isUseAlternativeImageEngine() {#isUseAlternativeImageEngine--}
```
public boolean isUseAlternativeImageEngine()
```


Gets a flag determines whether alternative imaging engine is used or not. True value is used by default for Linux OS. For Windows OS default value is false.

**Returns:**
boolean - boolean value
### setUseAlternativeImageEngine(boolean useAlternativeImageEngine) {#setUseAlternativeImageEngine-boolean-}
```
public void setUseAlternativeImageEngine(boolean useAlternativeImageEngine)
```


Sets a flag determines whether alternative imaging engine is used or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| useAlternativeImageEngine | boolean | boolean value |

