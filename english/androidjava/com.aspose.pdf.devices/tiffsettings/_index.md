---
title: TiffSettings
second_title: Aspose.PDF for Java API Reference
description: This class represents settings for importing pdf to Tiff.
type: docs
weight: 28
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
| [getCoordinateType()](#getCoordinateType--) | Get or sets the page coordinate type (Media/Crop boxes). |
| [setCoordinateType(int value)](#setCoordinateType-int-) |  |
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
| skipBlankPages | boolean | if set to  true  need to skip blank pages. |

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

### getMargins() {#getMargins--}
```
public Margins getMargins()
```


Gets the margins.

**Returns:**
[Margins](../../com.aspose.pdf.devices/margins)
### getSkipBlankPages() {#getSkipBlankPages--}
```
public boolean getSkipBlankPages()
```


Gets a value indicating whether to skip blank pages.

Value:  true  if need to skip blank pages; otherwise,  false .

--------------------

Default value is false

**Returns:**
boolean
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
| value | boolean |  |

### getCompression() {#getCompression--}
```
public int getCompression()
```


Gets the type of the compression.

Value: The type of the compression.

--------------------

Default value is CompressionType.LZW

**Returns:**
int
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
| value | int |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Gets the color depth.

Value: The color depth.

--------------------

Default value is ColorDepth.Default

**Returns:**
int
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
| value | int |  |

### getShape() {#getShape--}
```
public int getShape()
```


Gets the type of the shape.

Value: The type of the shape.

--------------------

Default value is ShapeType.None

**Returns:**
int
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
| value | int |  |

### getBrightness() {#getBrightness--}
```
public float getBrightness()
```


Get value boundary of the transformation of colors in white and black. This parameter can be applied with EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle or ColorDepth.Format1bpp == 1

Value: Value of brightness should be in the range from 0 to 1. By default value is equal to 0.33f

**Returns:**
float
### setBrightness(float value) {#setBrightness-float-}
```
public void setBrightness(float value)
```


Set value boundary of the transformation of colors in white and black. This parameter can be applied with EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle or ColorDepth.Format1bpp == 1

Value: Value of brightness should be in the range from 0 to 1. By default value is equal to 0.33f

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getCoordinateType() {#getCoordinateType--}
```
public int getCoordinateType()
```


Get or sets the page coordinate type (Media/Crop boxes). CropBox value is used by default.

**Returns:**
int
### setCoordinateType(int value) {#setCoordinateType-int-}
```
public void setCoordinateType(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

