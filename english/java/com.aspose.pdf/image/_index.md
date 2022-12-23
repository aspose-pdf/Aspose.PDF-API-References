---
title: Image
second_title: Aspose.PDF for Java API Reference
description: Represents image.
type: docs
weight: 167
url: /java/com.aspose.pdf/image/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph)
```
public final class Image extends BaseParagraph
```

Represents image.
## Constructors

| Constructor | Description |
| --- | --- |
| [Image()](#Image--) | default constructor |
## Methods

| Method | Description |
| --- | --- |
| [getFile()](#getFile--) | Gets the image file. |
| [setFile(String value)](#setFile-java.lang.String-) | Sets the image file. |
| [getFixWidth()](#getFixWidth--) | Gets the image width. |
| [setFixWidth(double value)](#setFixWidth-double-) | Sets the image width. |
| [getFixHeight()](#getFixHeight--) | Gets the image height. |
| [setFixHeight(double value)](#setFixHeight-double-) | Sets the image height. |
| [getFileType()](#getFileType--) | Gets the image file type. |
| [setFileType(int value)](#setFileType-int-) | Sets the image file type. |
| [getImageScale()](#getImageScale--) | Gets the image scale. |
| [setImageScale(double value)](#setImageScale-double-) | Sets the image scale. |
| [getImageStream()](#getImageStream--) | Gets the image stream. |
| [setImageStream(InputStream value)](#setImageStream-java.io.InputStream-) | Sets the image stream. |
| [isApplyResolution()](#isApplyResolution--) | Gets or sets a boolean value that indicates whether the image use resolution during generation |
| [setApplyResolution(boolean value)](#setApplyResolution-boolean-) | Gets or sets a boolean value that indicates whether the image use resolution during generation |
| [isBlackWhite()](#isBlackWhite--) | Gets a boolean value that indicates whether the image is forced to be black-and-white. |
| [setBlackWhite(boolean value)](#setBlackWhite-boolean-) | Sets a boolean value that indicates whether the image is forced to be black-and-white. |
| [getTitle()](#getTitle--) | Gets a string value that indicates the title of the image. |
| [setTitle(TextFragment value)](#setTitle-com.aspose.pdf.TextFragment-) | Sets a string value that indicates the title of the image. |
| [getMimeType(System.Drawing.Image i)](#getMimeType-com.aspose.ms.System.Drawing.Image-) | Returns mime type for image. |
| [convertToJpeg(InputStream value)](#convertToJpeg-java.io.InputStream-) | Try to convert to stream with bmp/png/gif/tiff image to stream with JPG format image. |
| [deepClone()](#deepClone--) | Clone the image. |
| [setBufferedImage(BufferedImage value)](#setBufferedImage-java.awt.image.BufferedImage-) | Sets the java awt image. |
| [getBufferedImage()](#getBufferedImage--) | Gets the java awt image. |
| [setBlackWhiteForGrayScale(boolean blackWhiteForGrayScale)](#setBlackWhiteForGrayScale-boolean-) | Try to detect and use 1bpp encoding for grayscale images. |
| [isBlackWhiteForGrayScale()](#isBlackWhiteForGrayScale--) | Try to detect and use 1bpp encoding for grayscale images Default value == FALSE |
### Image() {#Image--}
```
public Image()
```


default constructor

### getFile() {#getFile--}
```
public String getFile()
```


Gets the image file.

**Returns:**
java.lang.String - String value
### setFile(String value) {#setFile-java.lang.String-}
```
public void setFile(String value)
```


Sets the image file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getFixWidth() {#getFixWidth--}
```
public double getFixWidth()
```


Gets the image width.

**Returns:**
double - double value
### setFixWidth(double value) {#setFixWidth-double-}
```
public void setFixWidth(double value)
```


Sets the image width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getFixHeight() {#getFixHeight--}
```
public double getFixHeight()
```


Gets the image height.

**Returns:**
double - double value
### setFixHeight(double value) {#setFixHeight-double-}
```
public void setFixHeight(double value)
```


Sets the image height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getFileType() {#getFileType--}
```
public int getFileType()
```


Gets the image file type.

**Returns:**
int - int value
### setFileType(int value) {#setFileType-int-}
```
public void setFileType(int value)
```


Sets the image file type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### getImageScale() {#getImageScale--}
```
public double getImageScale()
```


Gets the image scale.

**Returns:**
double - double value
### setImageScale(double value) {#setImageScale-double-}
```
public void setImageScale(double value)
```


Sets the image scale.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getImageStream() {#getImageStream--}
```
public InputStream getImageStream()
```


Gets the image stream.

**Returns:**
java.io.InputStream - InputStream object
### setImageStream(InputStream value) {#setImageStream-java.io.InputStream-}
```
public void setImageStream(InputStream value)
```


Sets the image stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.InputStream | InputStream value |

### isApplyResolution() {#isApplyResolution--}
```
public boolean isApplyResolution()
```


Gets or sets a boolean value that indicates whether the image use resolution during generation

**Returns:**
boolean - boolean value
### setApplyResolution(boolean value) {#setApplyResolution-boolean-}
```
public void setApplyResolution(boolean value)
```


Gets or sets a boolean value that indicates whether the image use resolution during generation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isBlackWhite() {#isBlackWhite--}
```
public boolean isBlackWhite()
```


Gets a boolean value that indicates whether the image is forced to be black-and-white. If TIFF image of CCITT subformat is used, this property must be set to true.

**Returns:**
boolean - boolean value
### setBlackWhite(boolean value) {#setBlackWhite-boolean-}
```
public void setBlackWhite(boolean value)
```


Sets a boolean value that indicates whether the image is forced to be black-and-white. If TIFF image of CCITT subformat is used, this property must be set to true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getTitle() {#getTitle--}
```
public TextFragment getTitle()
```


Gets a string value that indicates the title of the image.

**Returns:**
[TextFragment](../../com.aspose.pdf/textfragment) - TextFragment value
### setTitle(TextFragment value) {#setTitle-com.aspose.pdf.TextFragment-}
```
public void setTitle(TextFragment value)
```


Sets a string value that indicates the title of the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextFragment](../../com.aspose.pdf/textfragment) | TextFragment value |

### getMimeType(System.Drawing.Image i) {#getMimeType-com.aspose.ms.System.Drawing.Image-}
```
public static String getMimeType(System.Drawing.Image i)
```


Returns mime type for image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| i | com.aspose.ms.System.Drawing.Image | Image object/ |

**Returns:**
java.lang.String - Mime type as string if found; otherwise, "image/unknown" value.
### convertToJpeg(InputStream value) {#convertToJpeg-java.io.InputStream-}
```
public static InputStream convertToJpeg(InputStream value)
```


Try to convert to stream with bmp/png/gif/tiff image to stream with JPG format image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.InputStream | InputStream instance |

**Returns:**
java.io.InputStream - InputStream instance
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clone the image.

**Returns:**
java.lang.Object - The cloned object
### setBufferedImage(BufferedImage value) {#setBufferedImage-java.awt.image.BufferedImage-}
```
public void setBufferedImage(BufferedImage value)
```


Sets the java awt image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.image.BufferedImage | BufferedImage object |

### getBufferedImage() {#getBufferedImage--}
```
public BufferedImage getBufferedImage()
```


Gets the java awt image.

**Returns:**
java.awt.image.BufferedImage - BufferedImage object
### setBlackWhiteForGrayScale(boolean blackWhiteForGrayScale) {#setBlackWhiteForGrayScale-boolean-}
```
public void setBlackWhiteForGrayScale(boolean blackWhiteForGrayScale)
```


Try to detect and use 1bpp encoding for grayscale images. Default value == FALSE

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| blackWhiteForGrayScale | boolean | boolean value |

### isBlackWhiteForGrayScale() {#isBlackWhiteForGrayScale--}
```
public boolean isBlackWhiteForGrayScale()
```


Try to detect and use 1bpp encoding for grayscale images Default value == FALSE

**Returns:**
boolean - boolean value
