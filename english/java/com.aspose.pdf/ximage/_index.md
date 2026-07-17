---
title: XImage
linktitle: XImage
second_title: Aspose.PDF for Java API Reference
description: Class representing image X-Object.
type: docs
weight: 5610
url: /java/com.aspose.pdf/ximage/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XImage

```
public final class XImage extends Object
```

Class representing image X-Object.

## Constructors

| Constructor | Description |
| --- | --- |
| [XImage](#XImage-com.aspose.pdf.engine.data.IPdfDataStream-) | for internal usage only |

## Methods

| Method | Description |
| --- | --- |
| [addStencilMask](#addStencilMask-java.io.InputStream-) | Adds a stencil mask to the XImage. |
| [containsTransparency](#containsTransparency--) | If the image contains transparency than return true; otherwise, false. |
| [delete](#delete--) | Deletes image from the parent collection. |
| [detectColorType](#detectColorType-java.awt.image.BufferedImage-) | Returns color type of image. |
| [getAlternativeText](#getAlternativeText-com.aspose.pdf.Page-) | Returns a list of strings with Alternative Text for an XImage. |
| [getColorType](#getColorType--) | Returns color type of image. |
| [getEngineImg](#getEngineImg--) | IPdfImage object which decribes image. Internal only |
| [getFilterType](#getFilterType--) | Gets image filter type. |
| [getGrayscaled](#getGrayscaled--) | Gets grayscaled version of image. |
| [getHeight](#getHeight--) | Gets height of the image. |
| [getImage](#getImage--) | For internal use only |
| [getMetadata](#getMetadata--) | Metadata of the image. |
| [getName](#getName--) | Gets image name. Please note that if you change name of the image which has references in page contents, document may became incorrect. Please use XImage.Rename method in this case. |
| [getNameInCollection](#getNameInCollection--) | Returns the name of the image in its collection. |
| [getRawBytes](#getRawBytes--) | Returns raw bytes for the image without decoding. |
| [getRawImageData](#getRawImageData--) | Retrieves the raw image data from the source image. |
| [getRawParameters](#getRawParameters--) | Gets raw image parameters |
| [getWidth](#getWidth--) | Gets width of the image. |
| [isImage](#isImage-com.aspose.pdf.engine.data.IPdfPrimitive-) | Returns true if the primitive is an image. |
| [isImageMask](#isImageMask--) | Gets a flag indicating whether the image shall be treated as an image mask (see 8.9.6, "Masked Images"). If this flag is true, the value of BitsPerComponent shall be 1 and Mask and ColorSpace shall not be specified; unmasked areas shall bepainted using the current nonstroking colour. Default value: false. Value: True is the image is image mask. |
| [isTheSameObject](#isTheSameObject-com.aspose.pdf.XImage-) | Returns true if both images references to the same object. |
| [rename](#rename-java.lang.String-) | Renames image and replaces all references to the image with the new name |
| [replace](#replace-java.io.InputStream-) | Replaces image onto stream specified in {@code image}. * |
| [save](#save-java.io.OutputStream-) | Saves image data into stream as JPEG image. |
| [save](#save-java.io.OutputStream-float-float-) | Saves image into stream with requested format. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.ImageType-) | Saves image into stream with requested format. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.ImageType-int-) | Saves image into stream with requested format. |
| [save](#save-java.io.OutputStream-int-) | Saves image into stream with requested format with specified resolution. |
| [saveInternal](#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-) | Saves image into stream with requested format. |
| [saveInternal](#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-int-) |  |
| [saveInternal](#saveInternal-com.aspose.ms.System.IO.Stream-int-) | Saves image data into stream as JPEG image with specified resolution. |
| [setName](#setName-java.lang.String-) | Sets image name. Please note that if you change name of the image which has references in page contents, document may became incorrect. Please use XImage.Rename method in this case. |
| [toStream](#toStream--) | Returns the original image stream. |
| [toString](#toString--) | Returns a string representation XImage object properties. |
| [trySetAlternativeText](#trySetAlternativeText-java.lang.String-com.aspose.pdf.Page-) | Sets alternative text for an XImage on the page. |

### XImage {#XImage-com.aspose.pdf.engine.data.IPdfDataStream-}
for internal usage only

### addStencilMask {#addStencilMask-java.io.InputStream-}
Adds a stencil mask to the XImage.

### containsTransparency {#containsTransparency--}
```
public boolean containsTransparency()
```

If the image contains transparency than return true; otherwise, false.

**Returns:**
boolean value

### delete {#delete--}
```
public void delete()
```

Deletes image from the parent collection.

### detectColorType {#detectColorType-java.awt.image.BufferedImage-}
Returns color type of image.

### getAlternativeText {#getAlternativeText-com.aspose.pdf.Page-}
Returns a list of strings with Alternative Text for an XImage.

### getColorType {#getColorType--}
```
public ColorType getColorType()
```

Returns color type of image.

**Returns:**
The color type value.

### getEngineImg {#getEngineImg--}
```
public com.aspose.pdf.engine.data.IPdfDataStream getEngineImg()
```

IPdfImage object which decribes image. Internal only

**Returns:**
IPdfDataStream

### getFilterType {#getFilterType--}
```
public final ImageFilterType getFilterType()
```

Gets image filter type.

**Returns:**
ImageFilterType element

### getGrayscaled {#getGrayscaled--}
```
public BufferedImage getGrayscaled()
```

Gets grayscaled version of image.

**Returns:**
BufferedImage

### getHeight {#getHeight--}
```
public int getHeight()
```

Gets height of the image.

**Returns:**
int value

### getImage {#getImage--}
```
public com.aspose.ms.System.Drawing.Bitmap getImage()
```

For internal use only

**Returns:**
Image

### getMetadata {#getMetadata--}
```
public final Metadata getMetadata()
```

Metadata of the image.

**Returns:**
Metadata instance

### getName {#getName--}
```
public String getName()
```

Gets image name. Please note that if you change name of the image which has references in page contents, document may became incorrect. Please use XImage.Rename method in this case.

**Returns:**
String

### getNameInCollection {#getNameInCollection--}
```
public String getNameInCollection()
```

Returns the name of the image in its collection.

**Returns:**
Image key (name).

### getRawBytes {#getRawBytes--}
```
public byte[] getRawBytes()
```

Returns raw bytes for the image without decoding.

**Returns:**
byte array

### getRawImageData {#getRawImageData--}
```
public final byte[] getRawImageData()
```

Retrieves the raw image data from the source image.

**Returns:**
A {@link byte[]} containing the original image data.

### getRawParameters {#getRawParameters--}
```
public XImage.RawParameters getRawParameters()
```

Gets raw image parameters

**Returns:**
RawParameters instance

### getWidth {#getWidth--}
```
public int getWidth()
```

Gets width of the image.

**Returns:**
int value

### isImage {#isImage-com.aspose.pdf.engine.data.IPdfPrimitive-}
Returns true if the primitive is an image.

### isImageMask {#isImageMask--}
```
public final boolean isImageMask()
```

Gets a flag indicating whether the image shall be treated as an image mask (see 8.9.6, "Masked Images"). If this flag is true, the value of BitsPerComponent shall be 1 and Mask and ColorSpace shall not be specified; unmasked areas shall bepainted using the current nonstroking colour. Default value: false. Value: True is the image is image mask.

**Returns:**
boolean value

### isTheSameObject {#isTheSameObject-com.aspose.pdf.XImage-}
Returns true if both images references to the same object.

### rename {#rename-java.lang.String-}
Renames image and replaces all references to the image with the new name

### replace {#replace-java.io.InputStream-}
Replaces image onto stream specified in {@code image}. *

### save {#save-java.io.OutputStream-}
Saves image data into stream as JPEG image.

### save {#save-java.io.OutputStream-float-float-}
Saves image into stream with requested format.

### save {#save-java.io.OutputStream-com.aspose.pdf.ImageType-}
Saves image into stream with requested format.

### save {#save-java.io.OutputStream-com.aspose.pdf.ImageType-int-}
Saves image into stream with requested format.

### save {#save-java.io.OutputStream-int-}
Saves image into stream with requested format with specified resolution.

### saveInternal {#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-}
Saves image into stream with requested format.

### saveInternal {#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-int-}


### saveInternal {#saveInternal-com.aspose.ms.System.IO.Stream-int-}
Saves image data into stream as JPEG image with specified resolution.

### setName {#setName-java.lang.String-}
Sets image name. Please note that if you change name of the image which has references in page contents, document may became incorrect. Please use XImage.Rename method in this case.

### toStream {#toStream--}
```
public InputStream toStream()
```

Returns the original image stream.

**Returns:**
The original image stream.

### toString {#toString--}
```
public String toString()
```

Returns a string representation XImage object properties.

**Returns:**
String instance

### trySetAlternativeText {#trySetAlternativeText-java.lang.String-com.aspose.pdf.Page-}
Sets alternative text for an XImage on the page.
