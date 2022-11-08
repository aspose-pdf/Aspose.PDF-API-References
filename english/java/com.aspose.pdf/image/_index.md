---
title: Image
second_title: Aspose.PDF for Java API Reference
description: Represents image.
type: docs
weight: 166
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
| [convertToJpeg(InputStream value)](#convertToJpeg-java.io.InputStream-) | Try to convert to stream with bmp/png/gif/tiff image to stream with JPG format image. |
| [deepClone()](#deepClone--) | Clone the image. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBufferedImage()](#getBufferedImage--) | Gets the java awt image. |
| [getClass()](#getClass--) |  |
| [getFile()](#getFile--) | Gets the image file. |
| [getFileType()](#getFileType--) | Gets the image file type. |
| [getFixHeight()](#getFixHeight--) | Gets the image height. |
| [getFixWidth()](#getFixWidth--) | Gets the image width. |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Gets a horizontal alignment of paragraph |
| [getHyperlink()](#getHyperlink--) | Gets the fragment hyperlink(for pdf generator). |
| [getImageScale()](#getImageScale--) | Gets the image scale. |
| [getImageStream()](#getImageStream--) | Gets the image stream. |
| [getMargin()](#getMargin--) | Gets a outer margin for paragraph (for pdf generation) |
| [getMimeType(System.Drawing.Image i)](#getMimeType-com.aspose.ms.System.Drawing.Image-) | Returns mime type for image. |
| [getTitle()](#getTitle--) | Gets a string value that indicates the title of the image. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Gets a vertical alignment of paragraph |
| [getZIndex()](#getZIndex--) | Gets an int value that indicates the Z-order of the graph. |
| [hashCode()](#hashCode--) |  |
| [isApplyResolution()](#isApplyResolution--) | Gets or sets a boolean value that indicates whether the image use resolution during generation |
| [isBlackWhite()](#isBlackWhite--) | Gets a boolean value that indicates whether the image is forced to be black-and-white. |
| [isBlackWhiteForGrayScale()](#isBlackWhiteForGrayScale--) | Try to detect and use 1bpp encoding for grayscale images Default value == FALSE |
| [isFirstParagraphInColumn()](#isFirstParagraphInColumn--) | Gets or sets a bool value that indicates whether this paragraph will be at next column. |
| [isInLineParagraph()](#isInLineParagraph--) | Gets a paragraph is inline. |
| [isInNewPage()](#isInNewPage--) | Gets a bool value that force this paragraph generates at new page. |
| [isKeptWithNext()](#isKeptWithNext--) | Gets a boolean value that indicates whether current paragraph remains in the same page along with next paragraph. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setApplyResolution(boolean value)](#setApplyResolution-boolean-) | Gets or sets a boolean value that indicates whether the image use resolution during generation |
| [setBlackWhite(boolean value)](#setBlackWhite-boolean-) | Sets a boolean value that indicates whether the image is forced to be black-and-white. |
| [setBlackWhiteForGrayScale(boolean blackWhiteForGrayScale)](#setBlackWhiteForGrayScale-boolean-) | Try to detect and use 1bpp encoding for grayscale images. |
| [setBufferedImage(BufferedImage value)](#setBufferedImage-java.awt.image.BufferedImage-) | Sets the java awt image. |
| [setFile(String value)](#setFile-java.lang.String-) | Sets the image file. |
| [setFileType(int value)](#setFileType-int-) | Sets the image file type. |
| [setFirstParagraphInColumn(boolean value)](#setFirstParagraphInColumn-boolean-) | Gets or sets a bool value that indicates whether this paragraph will be at next column. |
| [setFixHeight(double value)](#setFixHeight-double-) | Sets the image height. |
| [setFixWidth(double value)](#setFixWidth-double-) | Sets the image width. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Sets a horizontal alignment of paragraph |
| [setHyperlink(Hyperlink value)](#setHyperlink-com.aspose.pdf.Hyperlink-) | Sets hyperlink(for pdf generator). |
| [setImageScale(double value)](#setImageScale-double-) | Sets the image scale. |
| [setImageStream(InputStream value)](#setImageStream-java.io.InputStream-) | Sets the image stream. |
| [setInLineParagraph(boolean value)](#setInLineParagraph-boolean-) | Sets a paragraph is inline. |
| [setInNewPage(boolean value)](#setInNewPage-boolean-) | Sets a boolean value that force this paragraph generates at new page. |
| [setKeptWithNext(boolean value)](#setKeptWithNext-boolean-) | Sets a boolean value that indicates whether current paragraph remains in the same page along with next paragraph. |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | Sets a outer margin for paragraph (for pdf generation) |
| [setTitle(TextFragment value)](#setTitle-com.aspose.pdf.TextFragment-) | Sets a string value that indicates the title of the image. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Sets a vertical alignment of paragraph |
| [setZIndex(int value)](#setZIndex-int-) | Sets a int value that indicates the Z-order of the graph. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Image() {#Image--}
```
public Image()
```


default constructor

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
### getBufferedImage() {#getBufferedImage--}
```
public BufferedImage getBufferedImage()
```


Gets the java awt image.

**Returns:**
java.awt.image.BufferedImage - BufferedImage object
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFile() {#getFile--}
```
public String getFile()
```


Gets the image file.

**Returns:**
java.lang.String - String value
### getFileType() {#getFileType--}
```
public int getFileType()
```


Gets the image file type.

**Returns:**
int - int value
### getFixHeight() {#getFixHeight--}
```
public double getFixHeight()
```


Gets the image height.

**Returns:**
double - double value
### getFixWidth() {#getFixWidth--}
```
public double getFixWidth()
```


Gets the image width.

**Returns:**
double - double value
### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


Gets a horizontal alignment of paragraph

**Returns:**
int - HorizontalAlignment value
### getHyperlink() {#getHyperlink--}
```
public Hyperlink getHyperlink()
```


Gets the fragment hyperlink(for pdf generator).

**Returns:**
[Hyperlink](../../com.aspose.pdf/hyperlink) - the fragment hyperlink(for pdf generator).
### getImageScale() {#getImageScale--}
```
public double getImageScale()
```


Gets the image scale.

**Returns:**
double - double value
### getImageStream() {#getImageStream--}
```
public InputStream getImageStream()
```


Gets the image stream.

**Returns:**
java.io.InputStream - InputStream object
### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


Gets a outer margin for paragraph (for pdf generation)

**Returns:**
[MarginInfo](../../com.aspose.pdf/margininfo) - MarginInfo value
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
### getTitle() {#getTitle--}
```
public TextFragment getTitle()
```


Gets a string value that indicates the title of the image.

**Returns:**
[TextFragment](../../com.aspose.pdf/textfragment) - TextFragment value
### getVerticalAlignment() {#getVerticalAlignment--}
```
public int getVerticalAlignment()
```


Gets a vertical alignment of paragraph

**Returns:**
int - VerticalAlignment element
### getZIndex() {#getZIndex--}
```
public int getZIndex()
```


Gets an int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page.

**Returns:**
int - int value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isApplyResolution() {#isApplyResolution--}
```
public boolean isApplyResolution()
```


Gets or sets a boolean value that indicates whether the image use resolution during generation

**Returns:**
boolean - boolean value
### isBlackWhite() {#isBlackWhite--}
```
public boolean isBlackWhite()
```


Gets a boolean value that indicates whether the image is forced to be black-and-white. If TIFF image of CCITT subformat is used, this property must be set to true.

**Returns:**
boolean - boolean value
### isBlackWhiteForGrayScale() {#isBlackWhiteForGrayScale--}
```
public boolean isBlackWhiteForGrayScale()
```


Try to detect and use 1bpp encoding for grayscale images Default value == FALSE

**Returns:**
boolean - boolean value
### isFirstParagraphInColumn() {#isFirstParagraphInColumn--}
```
public boolean isFirstParagraphInColumn()
```


Gets or sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation)

**Returns:**
boolean - boolean value
### isInLineParagraph() {#isInLineParagraph--}
```
public boolean isInLineParagraph()
```


Gets a paragraph is inline. Default is false.(for pdf generation)

**Returns:**
boolean - boolean value
### isInNewPage() {#isInNewPage--}
```
public boolean isInNewPage()
```


Gets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation)

**Returns:**
boolean - boolean value
### isKeptWithNext() {#isKeptWithNext--}
```
public boolean isKeptWithNext()
```


Gets a boolean value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation)

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




### setApplyResolution(boolean value) {#setApplyResolution-boolean-}
```
public void setApplyResolution(boolean value)
```


Gets or sets a boolean value that indicates whether the image use resolution during generation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setBlackWhite(boolean value) {#setBlackWhite-boolean-}
```
public void setBlackWhite(boolean value)
```


Sets a boolean value that indicates whether the image is forced to be black-and-white. If TIFF image of CCITT subformat is used, this property must be set to true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setBlackWhiteForGrayScale(boolean blackWhiteForGrayScale) {#setBlackWhiteForGrayScale-boolean-}
```
public void setBlackWhiteForGrayScale(boolean blackWhiteForGrayScale)
```


Try to detect and use 1bpp encoding for grayscale images. Default value == FALSE

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| blackWhiteForGrayScale | boolean | boolean value |

### setBufferedImage(BufferedImage value) {#setBufferedImage-java.awt.image.BufferedImage-}
```
public void setBufferedImage(BufferedImage value)
```


Sets the java awt image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.image.BufferedImage | BufferedImage object |

### setFile(String value) {#setFile-java.lang.String-}
```
public void setFile(String value)
```


Sets the image file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### setFileType(int value) {#setFileType-int-}
```
public void setFileType(int value)
```


Sets the image file type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setFirstParagraphInColumn(boolean value) {#setFirstParagraphInColumn-boolean-}
```
public void setFirstParagraphInColumn(boolean value)
```


Gets or sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setFixHeight(double value) {#setFixHeight-double-}
```
public void setFixHeight(double value)
```


Sets the image height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### setFixWidth(double value) {#setFixWidth-double-}
```
public void setFixWidth(double value)
```


Sets the image width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```


Sets a horizontal alignment of paragraph

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | HorizontalAlignment value |

### setHyperlink(Hyperlink value) {#setHyperlink-com.aspose.pdf.Hyperlink-}
```
public void setHyperlink(Hyperlink value)
```


Sets hyperlink(for pdf generator).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Hyperlink](../../com.aspose.pdf/hyperlink) | hyperlink(for pdf generator). |

### setImageScale(double value) {#setImageScale-double-}
```
public void setImageScale(double value)
```


Sets the image scale.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### setImageStream(InputStream value) {#setImageStream-java.io.InputStream-}
```
public void setImageStream(InputStream value)
```


Sets the image stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.InputStream | InputStream value |

### setInLineParagraph(boolean value) {#setInLineParagraph-boolean-}
```
public void setInLineParagraph(boolean value)
```


Sets a paragraph is inline. Default is false.(for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setInNewPage(boolean value) {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```


Sets a boolean value that force this paragraph generates at new page. Default is false.(for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setKeptWithNext(boolean value) {#setKeptWithNext-boolean-}
```
public final void setKeptWithNext(boolean value)
```


Sets a boolean value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public void setMargin(MarginInfo value)
```


Sets a outer margin for paragraph (for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo object |

### setTitle(TextFragment value) {#setTitle-com.aspose.pdf.TextFragment-}
```
public void setTitle(TextFragment value)
```


Sets a string value that indicates the title of the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextFragment](../../com.aspose.pdf/textfragment) | TextFragment value |

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int value)
```


Sets a vertical alignment of paragraph

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | VerticalAlignment element |

### setZIndex(int value) {#setZIndex-int-}
```
public void setZIndex(int value)
```


Sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

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

