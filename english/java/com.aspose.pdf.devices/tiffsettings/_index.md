---
title: TiffSettings
linktitle: TiffSettings
second_title: Aspose.PDF for Java API Reference
description: This class represents settings for importing pdf to Tiff.
type: docs
weight: 220
url: /java/com.aspose.pdf.devices/tiffsettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.TiffSettings

```
public final class TiffSettings extends Object
```

This class represents settings for importing pdf to Tiff.

## Constructors

| Constructor | Description |
| --- | --- |
| [TiffSettings](#TiffSettings--) | Initializes a new instance of the {@code TiffSettings} class. |
| [TiffSettings](#TiffSettings-boolean-) | Initializes a new instance of the {@code TiffSettings} class. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.ColorDepth-) | Initializes a new instance of the {@code TiffSettings} class. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-) | Initializes a new instance of the {@code TiffSettings} class. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-) | Initializes a new instance of the {@code TiffSettings} class. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-) | Initializes a new instance of the {@code TiffSettings} class. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-com.aspose.pdf.devices.ShapeType-) | Initializes a new instance of the {@code TiffSettings} class. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.Margins-) | Initializes a new instance of the {@code TiffSettings} class. |

## Methods

| Method | Description |
| --- | --- |
| [getBrightness](#getBrightness--) | Get value boundary of the transformation of colors in white and black. This parameter can be applied with EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle or ColorDepth.Format1bpp == 1 |
| [getCompression](#getCompression--) | <p> Gets the type of the compression. </p> Value: The type of the compression. <hr> <p> Default value is CompressionType.LZW </p> |
| [getCoordinateType](#getCoordinateType--) | Gets the page coordinate type (Media/Crop boxes). CropBox value is used by default. |
| [getDepth](#getDepth--) | <p> Gets the color depth. </p> Value: The color depth. <hr> <p> Default value is ColorDepth.Default </p> |
| [getIndexedConversionType](#getIndexedConversionType--) | Gets the IndexedConversionType. Default value is Simple. |
| [getMargins](#getMargins--) | Gets the margins. |
| [getShape](#getShape--) | <p> Gets the type of the shape. </p> Value: The type of the shape. <hr> <p> Default value is ShapeType.None </p> |
| [getSkipBlankPages](#getSkipBlankPages--) | <p> Gets a value indicating whether to skip blank pages. </p> Value: {@code true} if need to skip blank pages; otherwise, {@code false}. <hr> <p> Default value is false </p> |
| [isUseAlternativeImageEngine](#isUseAlternativeImageEngine--) | Gets a flag determines whether alternative imaging engine is used or not. True value is used by default for Linux OS. For Windows OS default value is false. |
| [setBrightness](#setBrightness-float-) | Set value boundary of the transformation of colors in white and black. This parameter can be applied with EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle or ColorDepth.Format1bpp == 1 |
| [setCompression](#setCompression-com.aspose.pdf.devices.CompressionType-) | <p> Sets the type of the compression. </p> Value: The type of the compression. <hr> <p> Default value is CompressionType.LZW </p> |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | Sets the page coordinate type (Media/Crop boxes). CropBox value is used by default. |
| [setDepth](#setDepth-com.aspose.pdf.devices.ColorDepth-) | <p> Gets the color depth. </p> Value: The color depth. <hr> <p> Default value is ColorDepth.Default </p> |
| [setIndexedConversionType](#setIndexedConversionType-int-) | Sets the IndexedConversionType. |
| [setShape](#setShape-com.aspose.pdf.devices.ShapeType-) | <p> Sets the type of the shape. </p> Value: The type of the shape. <hr> <p> Default value is ShapeType.None </p> |
| [setSkipBlankPages](#setSkipBlankPages-boolean-) | <p> Sets a value indicating whether to skip blank pages. </p> Value: {@code true} if need to skip blank pages; otherwise, {@code false}. <hr> <p> Default value is false </p> |
| [setUseAlternativeImageEngine](#setUseAlternativeImageEngine-boolean-) | Sets a flag determines whether alternative imaging engine is used or not. |

### TiffSettings {#TiffSettings--}
```
public TiffSettings()
```

Initializes a new instance of the {@code TiffSettings} class.

### TiffSettings {#TiffSettings-boolean-}
```
public TiffSettings(boolean skipBlankPages)
```

Initializes a new instance of the {@code TiffSettings} class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| skipBlankPages |  | if set to {@code true} [skip blank pages]. |

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.ColorDepth-}
Initializes a new instance of the {@code TiffSettings} class.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-}
Initializes a new instance of the {@code TiffSettings} class.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-}
Initializes a new instance of the {@code TiffSettings} class.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-}
Initializes a new instance of the {@code TiffSettings} class.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-com.aspose.pdf.devices.ShapeType-}
Initializes a new instance of the {@code TiffSettings} class.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.Margins-}
Initializes a new instance of the {@code TiffSettings} class.

### getBrightness {#getBrightness--}
```
public float getBrightness()
```

Get value boundary of the transformation of colors in white and black. This parameter can be applied with EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle or ColorDepth.Format1bpp == 1

**Returns:**
float value of brightness should be in the range from 0 to 1. By default value is equal to 0.33f

### getCompression {#getCompression--}
```
public CompressionType getCompression()
```

<p> Gets the type of the compression. </p> Value: The type of the compression. <hr> <p> Default value is CompressionType.LZW </p>

**Returns:**
CompressionType element @see CompressionType

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

Gets the page coordinate type (Media/Crop boxes). CropBox value is used by default.

**Returns:**
PageCoordinateType value @see PageCoordinateType

### getDepth {#getDepth--}
```
public ColorDepth getDepth()
```

<p> Gets the color depth. </p> Value: The color depth. <hr> <p> Default value is ColorDepth.Default </p>

**Returns:**
ColorDepth element @see ColorDepth

### getIndexedConversionType {#getIndexedConversionType--}
```
public int getIndexedConversionType()
```

Gets the IndexedConversionType. Default value is Simple.

**Returns:**
IndexedConversionType element @see IndexedConversionType

### getMargins {#getMargins--}
```
public Margins getMargins()
```

Gets the margins.

**Returns:**
Margins object

### getShape {#getShape--}
```
public ShapeType getShape()
```

<p> Gets the type of the shape. </p> Value: The type of the shape. <hr> <p> Default value is ShapeType.None </p>

**Returns:**
ShapeType element @see ShapeType

### getSkipBlankPages {#getSkipBlankPages--}
```
public boolean getSkipBlankPages()
```

<p> Gets a value indicating whether to skip blank pages. </p> Value: {@code true} if need to skip blank pages; otherwise, {@code false}. <hr> <p> Default value is false </p>

**Returns:**
boolean value

### isUseAlternativeImageEngine {#isUseAlternativeImageEngine--}
```
public boolean isUseAlternativeImageEngine()
```

Gets a flag determines whether alternative imaging engine is used or not. True value is used by default for Linux OS. For Windows OS default value is false.

**Returns:**
boolean value

### setBrightness {#setBrightness-float-}
```
public void setBrightness(float value)
```

Set value boundary of the transformation of colors in white and black. This parameter can be applied with EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle or ColorDepth.Format1bpp == 1

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | : Value of brightness should be in the range from 0 to 1. By default value is equal to 0.33f |

### setCompression {#setCompression-com.aspose.pdf.devices.CompressionType-}
<p> Sets the type of the compression. </p> Value: The type of the compression. <hr> <p> Default value is CompressionType.LZW </p>

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
Sets the page coordinate type (Media/Crop boxes). CropBox value is used by default.

### setDepth {#setDepth-com.aspose.pdf.devices.ColorDepth-}
<p> Gets the color depth. </p> Value: The color depth. <hr> <p> Default value is ColorDepth.Default </p>

### setIndexedConversionType {#setIndexedConversionType-int-}
```
public void setIndexedConversionType(int value)
```

Sets the IndexedConversionType.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | IndexedConversionType element @see IndexedConversionType |

### setShape {#setShape-com.aspose.pdf.devices.ShapeType-}
<p> Sets the type of the shape. </p> Value: The type of the shape. <hr> <p> Default value is ShapeType.None </p>

### setSkipBlankPages {#setSkipBlankPages-boolean-}
```
public void setSkipBlankPages(boolean value)
```

<p> Sets a value indicating whether to skip blank pages. </p> Value: {@code true} if need to skip blank pages; otherwise, {@code false}. <hr> <p> Default value is false </p>

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setUseAlternativeImageEngine {#setUseAlternativeImageEngine-boolean-}
```
public void setUseAlternativeImageEngine(boolean useAlternativeImageEngine)
```

Sets a flag determines whether alternative imaging engine is used or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| useAlternativeImageEngine |  | boolean value |
