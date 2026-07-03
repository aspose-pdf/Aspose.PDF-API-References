---
title: Stamp
linktitle: Stamp
second_title: Aspose.PDF for Java API Reference
description: Class represeting stamp.
type: docs
weight: 700
url: /java/com.aspose.pdf.facades/stamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Stamp

```
public final class Stamp extends Object
```

Class represeting stamp.

## Constructors

| Constructor | Description |
| --- | --- |
| [Stamp](#Stamp--) | Constructor for Stamp object. |

## Methods

| Method | Description |
| --- | --- |
| [bindImage](#bindImage-java.io.InputStream-) | Sets image which will be used as stamp. |
| [bindImage](#bindImage-java.lang.String-) | <p> Sets image as a stamp. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); stamp.bindImage("image.jpg"); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [bindLogo](#bindLogo-com.aspose.pdf.facades.FormattedText-) | Sets text as stamp. |
| [bindPdf](#bindPdf-java.io.InputStream-int-) | <p> Sets PDF file and number of page which will be used as stamp. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //First page will be used as stamp. InputStream stream = new FileInputStream("stamp.pdf"); stamp.bindPdf(stream, 1); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [bindPdf](#bindPdf-java.lang.String-int-) | <p> Sets PDF file and number of page which will be used as stamp. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //First page will be used as stamp. stamp.bindPdf("stamp.pdf", 1); stamp.isBackground (true); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [bindTextState](#bindTextState-com.aspose.pdf.TextState-) | Sets text state of stamp text. |
| [close](#close--) | Closes this instance |
| [getBlendingSpace](#getBlendingSpace--) | Gets a BlendingColorSpace value that defines a color space that is used to perform transparency and blending operations on the page. |
| [getOpacity](#getOpacity--) | Gets opacity of the stamp. |
| [getPageNumber](#getPageNumber--) | Gets page number. |
| [getPages](#getPages--) | Gets array with numbers of pages which will be affected by stamp. |
| [getQuality](#getQuality--) | Gets quality of image stamp in percent. Valiued values 0..100%. |
| [getRotation](#getRotation--) | Gets rotation of the stamp in degrees. |
| [getStampId](#getStampId--) | Gets identifier of stamp. |
| [isBackground](#isBackground--) | Gets background status. If true stamp will be placed as background of the spamped page. By default is set to false. |
| [setBackground](#setBackground-boolean-) | Sets background status. If true stamp will be placed as background of the spamped page. By default is set to false. |
| [setBlendingSpace](#setBlendingSpace-com.aspose.pdf.facades.BlendingColorSpace-) | Sets a BlendingColorSpace value that defines a color space that is used to perform transparency and blending operations on the page. |
| [setImageSize](#setImageSize-float-float-) | Sets size of image stamp. Image will be scaled according to the specified values. |
| [setOpacity](#setOpacity-float-) | Sets opacity of the stamp. |
| [setOrigin](#setOrigin-float-float-) | Sets position on page where stamp will be placed. |
| [setPageNumber](#setPageNumber-int-) | Sets page number. |
| [setPages](#setPages-int:A-) | <p> Sets array with numbers of pages which will be affected by stamp. If Pages = null all pages of the document are affected. </p> |
| [setQuality](#setQuality-int-) | Sets quality of image stamp in percent. Valiued values 0..100%. |
| [setRotation](#setRotation-float-) | <p> Gets or sets rotation of the stamp in degrees. </p> |
| [setStampId](#setStampId-int-) | Sets identifier of stamp. |

### Stamp {#Stamp--}
```
public Stamp()
```

Constructor for Stamp object.

### bindImage {#bindImage-java.io.InputStream-}
Sets image which will be used as stamp.

### bindImage {#bindImage-java.lang.String-}
<p> Sets image as a stamp. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); stamp.bindImage("image.jpg"); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### bindLogo {#bindLogo-com.aspose.pdf.facades.FormattedText-}
Sets text as stamp.

### bindPdf {#bindPdf-java.io.InputStream-int-}
<p> Sets PDF file and number of page which will be used as stamp. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //First page will be used as stamp. InputStream stream = new FileInputStream("stamp.pdf"); stamp.bindPdf(stream, 1); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### bindPdf {#bindPdf-java.lang.String-int-}
<p> Sets PDF file and number of page which will be used as stamp. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //First page will be used as stamp. stamp.bindPdf("stamp.pdf", 1); stamp.isBackground (true); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### bindTextState {#bindTextState-com.aspose.pdf.TextState-}
Sets text state of stamp text.

### close {#close--}
```
public void close()
```

Closes this instance

### getBlendingSpace {#getBlendingSpace--}
```
public BlendingColorSpace getBlendingSpace()
```

Gets a BlendingColorSpace value that defines a color space that is used to perform transparency and blending operations on the page.

**Returns:**
int value @see BlendingColorSpace

### getOpacity {#getOpacity--}
```
public float getOpacity()
```

Gets opacity of the stamp.

**Returns:**
float value

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

Gets page number.

**Returns:**
int value

### getPages {#getPages--}
```
public int[] getPages()
```

Gets array with numbers of pages which will be affected by stamp.

**Returns:**
int array

### getQuality {#getQuality--}
```
public int getQuality()
```

Gets quality of image stamp in percent. Valiued values 0..100%.

**Returns:**
int value

### getRotation {#getRotation--}
```
public float getRotation()
```

Gets rotation of the stamp in degrees.

**Returns:**
float value

### getStampId {#getStampId--}
```
public int getStampId()
```

Gets identifier of stamp.

**Returns:**
int value

### isBackground {#isBackground--}
```
public boolean isBackground()
```

Gets background status. If true stamp will be placed as background of the spamped page. By default is set to false.

**Returns:**
boolean value

### setBackground {#setBackground-boolean-}
```
public void setBackground(boolean value)
```

Sets background status. If true stamp will be placed as background of the spamped page. By default is set to false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setBlendingSpace {#setBlendingSpace-com.aspose.pdf.facades.BlendingColorSpace-}
Sets a BlendingColorSpace value that defines a color space that is used to perform transparency and blending operations on the page.

### setImageSize {#setImageSize-float-float-}
```
public void setImageSize(float width, float height)
```

Sets size of image stamp. Image will be scaled according to the specified values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width |  | Image width. |
| height |  | Image height. |

### setOpacity {#setOpacity-float-}
```
public void setOpacity(float value)
```

Sets opacity of the stamp.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | float value |

### setOrigin {#setOrigin-float-float-}
```
public void setOrigin(float originX, float originY)
```

Sets position on page where stamp will be placed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| originX |  | X coordinate of the stamp. |
| originY |  | Y coordinate of the stamp. |

### setPageNumber {#setPageNumber-int-}
```
public void setPageNumber(int value)
```

Sets page number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setPages {#setPages-int:A-}
```
public void setPages(int[] value)
```

<p> Sets array with numbers of pages which will be affected by stamp. If Pages = null all pages of the document are affected. </p>

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int array <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new com.aspose.pdf.facades.Stamp(); stamp.bindLogo(new FormattedText(text)); //put stamp only on 1st, 4th and 6th page. stamp.setPages(new int[] { 1, 4, 6 }); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |

### setQuality {#setQuality-int-}
```
public void setQuality(int value)
```

Sets quality of image stamp in percent. Valiued values 0..100%.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setRotation {#setRotation-float-}
```
public void setRotation(float value)
```

<p> Gets or sets rotation of the stamp in degrees. </p>

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | float value <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); stamp.bindLogo(new FormattedText("STAMP")); stamp.setRotation(90); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |

### setStampId {#setStampId-int-}
```
public void setStampId(int value)
```

Sets identifier of stamp.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |
