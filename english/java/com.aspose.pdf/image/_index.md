---
title: Image
second_title: Aspose.PDF for Java API Reference
description: Represents image.
type: docs
weight: 2280
url: /java/com.aspose.pdf/image/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Image, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Image

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Image extends BaseParagraph
```

Represents image.

## Constructors

| Constructor | Description |
| --- | --- |
| [Image](#Image--) | default constructor |

## Methods

| Method | Description |
| --- | --- |
| [convertToJpeg](#convertToJpeg-java.io.InputStream-) | Try to convert to stream with bmp/png/gif/tiff image to stream with JPG format image. |
| [deepClone](#deepClone--) | Clone the image. |
| [getBitmapInfo](#getBitmapInfo--) | Gets or sets uncompressed image bytes. |
| [getBitmapSize](#getBitmapSize--) | Gets the image bitmap size. |
| [getBufferedImage](#getBufferedImage--) | Gets the java awt image. |
| [getFile](#getFile--) | Gets the image file. |
| [getFileType](#getFileType--) | Gets the image file type. |
| [getFixHeight](#getFixHeight--) | Gets the image height. |
| [getFixWidth](#getFixWidth--) | Gets the image width. |
| [getImageScale](#getImageScale--) | Gets the image scale. |
| [getImageStream](#getImageStream--) | Gets the image stream. |
| [getMimeType](#getMimeType-com.aspose.ms.System.Drawing.Image-) | Returns mime type for image. |
| [getTitle](#getTitle--) | Gets a string value that indicates the title of the image. |
| [isApplyResolution](#isApplyResolution--) | Gets or sets a boolean value that indicates whether the image use resolution during generation |
| [isBlackWhite](#isBlackWhite--) | Gets a boolean value that indicates whether the image is forced to be black-and-white. If TIFF image of CCITT subformat is used, this property must be set to true. |
| [isBlackWhiteForGrayScale](#isBlackWhiteForGrayScale--) | Try to detect and use 1bpp encoding for grayscale images Default value == FALSE |
| [setApplyResolution](#setApplyResolution-boolean-) | Gets or sets a boolean value that indicates whether the image use resolution during generation |
| [setBitmapInfo](#setBitmapInfo-com.aspose.pdf.BitmapInfo-) | Gets or sets uncompressed image bytes. |
| [setBlackWhite](#setBlackWhite-boolean-) | Sets a boolean value that indicates whether the image is forced to be black-and-white. If TIFF image of CCITT subformat is used, this property must be set to true. |
| [setBlackWhiteForGrayScale](#setBlackWhiteForGrayScale-boolean-) | Try to detect and use 1bpp encoding for grayscale images. Default value == FALSE |
| [setBufferedImage](#setBufferedImage-java.awt.image.BufferedImage-) | Sets the java awt image. |
| [setFile](#setFile-java.lang.String-) | Sets the image file. |
| [setFileType](#setFileType-com.aspose.pdf.ImageFileType-) | Sets the image file type. |
| [setFixHeight](#setFixHeight-double-) | Sets the image height. |
| [setFixWidth](#setFixWidth-double-) | Sets the image width. |
| [setImageScale](#setImageScale-double-) | Sets the image scale. |
| [setImageStream](#setImageStream-java.io.InputStream-) | Sets the image stream. |
| [setTitle](#setTitle-com.aspose.pdf.TextFragment-) | Sets a string value that indicates the title of the image. |

### Image {#Image--}
```
public Image()
```

default constructor

### convertToJpeg {#convertToJpeg-java.io.InputStream-}
Try to convert to stream with bmp/png/gif/tiff image to stream with JPG format image.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clone the image.

**Returns:**
The cloned object

### getBitmapInfo {#getBitmapInfo--}
```
public final BitmapInfo getBitmapInfo()
```

Gets or sets uncompressed image bytes.

**Returns:**
BitmapInfo instance

### getBitmapSize {#getBitmapSize--}
```
public final Rectangle getBitmapSize()
```

Gets the image bitmap size.

**Returns:**
Rectangle instance

### getBufferedImage {#getBufferedImage--}
```
public BufferedImage getBufferedImage()
```

Gets the java awt image.

**Returns:**
BufferedImage object

### getFile {#getFile--}
```
public String getFile()
```

Gets the image file.

**Returns:**
String value

### getFileType {#getFileType--}
```
public ImageFileType getFileType()
```

Gets the image file type.

**Returns:**
int value @see ImageFileType

### getFixHeight {#getFixHeight--}
```
public double getFixHeight()
```

Gets the image height.

**Returns:**
double value

### getFixWidth {#getFixWidth--}
```
public double getFixWidth()
```

Gets the image width.

**Returns:**
double value

### getImageScale {#getImageScale--}
```
public double getImageScale()
```

Gets the image scale.

**Returns:**
double value

### getImageStream {#getImageStream--}
```
public InputStream getImageStream()
```

Gets the image stream.

**Returns:**
InputStream object

### getMimeType {#getMimeType-com.aspose.ms.System.Drawing.Image-}
Returns mime type for image.

### getTitle {#getTitle--}
```
public TextFragment getTitle()
```

Gets a string value that indicates the title of the image.

**Returns:**
TextFragment value

### isApplyResolution {#isApplyResolution--}
```
public boolean isApplyResolution()
```

Gets or sets a boolean value that indicates whether the image use resolution during generation

**Returns:**
boolean value

### isBlackWhite {#isBlackWhite--}
```
public boolean isBlackWhite()
```

Gets a boolean value that indicates whether the image is forced to be black-and-white. If TIFF image of CCITT subformat is used, this property must be set to true.

**Returns:**
boolean value

### isBlackWhiteForGrayScale {#isBlackWhiteForGrayScale--}
```
public boolean isBlackWhiteForGrayScale()
```

Try to detect and use 1bpp encoding for grayscale images Default value == FALSE

**Returns:**
boolean value

### setApplyResolution {#setApplyResolution-boolean-}
```
public void setApplyResolution(boolean value)
```

Gets or sets a boolean value that indicates whether the image use resolution during generation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setBitmapInfo {#setBitmapInfo-com.aspose.pdf.BitmapInfo-}
Gets or sets uncompressed image bytes.

### setBlackWhite {#setBlackWhite-boolean-}
```
public void setBlackWhite(boolean value)
```

Sets a boolean value that indicates whether the image is forced to be black-and-white. If TIFF image of CCITT subformat is used, this property must be set to true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setBlackWhiteForGrayScale {#setBlackWhiteForGrayScale-boolean-}
```
public void setBlackWhiteForGrayScale(boolean blackWhiteForGrayScale)
```

Try to detect and use 1bpp encoding for grayscale images. Default value == FALSE

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| blackWhiteForGrayScale |  | boolean value |

### setBufferedImage {#setBufferedImage-java.awt.image.BufferedImage-}
Sets the java awt image.

### setFile {#setFile-java.lang.String-}
Sets the image file.

### setFileType {#setFileType-com.aspose.pdf.ImageFileType-}
Sets the image file type.

### setFixHeight {#setFixHeight-double-}
```
public void setFixHeight(double value)
```

Sets the image height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setFixWidth {#setFixWidth-double-}
```
public void setFixWidth(double value)
```

Sets the image width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setImageScale {#setImageScale-double-}
```
public void setImageScale(double value)
```

Sets the image scale.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setImageStream {#setImageStream-java.io.InputStream-}
Sets the image stream.

### setTitle {#setTitle-com.aspose.pdf.TextFragment-}
Sets a string value that indicates the title of the image.
