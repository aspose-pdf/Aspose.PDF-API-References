---
title: Stamp
second_title: Aspose.PDF for Java API Reference
description: Class represeting stamp.
type: docs
weight: 51
url: /java/com.aspose.pdf.facades/stamp/
---
**Inheritance:**
java.lang.Object
```
public final class Stamp
```

Class represeting stamp.
## Constructors

| Constructor | Description |
| --- | --- |
| [Stamp()](#Stamp--) | Constructor for Stamp object. |
## Methods

| Method | Description |
| --- | --- |
| [getStampId()](#getStampId--) | Gets or sets identifier of stamp. |
| [setStampId(int value)](#setStampId-int-) |  |
| [getOpacity()](#getOpacity--) | Gets opacity of the stamp. |
| [setOpacity(float value)](#setOpacity-float-) | Sets opacity of the stamp. |
| [getPageNumber()](#getPageNumber--) | Gets page number. |
| [setPageNumber(int value)](#setPageNumber-int-) | Sets page number. |
| [getPages()](#getPages--) | Gets array with numbers of pages which will be affected by stamp. |
| [setPages(int[] value)](#setPages-int---) | Sets array with numbers of pages which will be affected by stamp. |
| [getRotation()](#getRotation--) | Gets rotation of the stamp in degrees. |
| [setRotation(float value)](#setRotation-float-) | Gets or sets rotation of the stamp in degrees. |
| [isBackground()](#isBackground--) | Gets background status. |
| [isBackground(boolean value)](#isBackground-boolean-) | Sets background status. |
| [getBlendingSpace()](#getBlendingSpace--) | Gets a BlendingColorSpace value that defines a color space that is used to perform transparency and blending operations on the page. |
| [setBlendingSpace(int value)](#setBlendingSpace-int-) | Sets a BlendingColorSpace value that defines a color space that is used to perform transparency and blending operations on the page. |
| [bindPdf(String pdfFile, int pageNumber)](#bindPdf-java.lang.String-int-) | Sets PDF file and number of page which will be used as stamp. |
| [bindPdf(System.IO.Stream pdfStream, int pageNumber)](#bindPdf-com.aspose.ms.System.IO.Stream-int-) | Sets PDF file and number of page which will be used as stamp. |
| [bindImage(String imageFile)](#bindImage-java.lang.String-) | Sets image as a stamp. |
| [bindLogo(FormattedText formattedText)](#bindLogo-com.aspose.pdf.facades.FormattedText-) | Sets text as stamp. |
| [setOrigin(float originX, float originY)](#setOrigin-float-float-) | Sets position on page where stamp will be placed. |
| [close()](#close--) |  |
### Stamp() {#Stamp--}
```
public Stamp()
```


Constructor for Stamp object.

### getStampId() {#getStampId--}
```
public int getStampId()
```


Gets or sets identifier of stamp.

**Returns:**
int
### setStampId(int value) {#setStampId-int-}
```
public void setStampId(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Gets opacity of the stamp.

**Returns:**
float
### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Sets opacity of the stamp.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Gets page number.

**Returns:**
int
### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


Sets page number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPages() {#getPages--}
```
public int[] getPages()
```


Gets array with numbers of pages which will be affected by stamp.

**Returns:**
int[]
### setPages(int[] value) {#setPages-int---}
```
public void setPages(int[] value)
```


Sets array with numbers of pages which will be affected by stamp. If Pages = null all pages of the document are affected.

--------------------

> ```
> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
>  Stamp stamp = new com.aspose.pdf.facades.Stamp();
>  stamp.bindLogo(new FormattedText(text));
>  //put stamp only on 1st, 4th and 6th page.
>  stamp.setPages(new int[] { 1, 4, 6 });
>  fileStamp.addStamp(stamp);
>  fileStamp.close();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] |  |

### getRotation() {#getRotation--}
```
public float getRotation()
```


Gets rotation of the stamp in degrees.

**Returns:**
float
### setRotation(float value) {#setRotation-float-}
```
public void setRotation(float value)
```


Gets or sets rotation of the stamp in degrees.

--------------------

> ```
> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
>  Stamp stamp = new Stamp();
>  stamp.bindLogo(new FormattedText("STAMP"));
>  stamp.setRotation(90);
>  fileStamp.addStamp(stamp);
>  fileStamp.close();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### isBackground() {#isBackground--}
```
public boolean isBackground()
```


Gets background status. If true stamp will be placed as background of the spamped page. By default is set to false.

**Returns:**
boolean
### isBackground(boolean value) {#isBackground-boolean-}
```
public void isBackground(boolean value)
```


Sets background status. If true stamp will be placed as background of the spamped page. By default is set to false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getBlendingSpace() {#getBlendingSpace--}
```
public int getBlendingSpace()
```


Gets a BlendingColorSpace value that defines a color space that is used to perform transparency and blending operations on the page.

**Returns:**
int
### setBlendingSpace(int value) {#setBlendingSpace-int-}
```
public void setBlendingSpace(int value)
```


Sets a BlendingColorSpace value that defines a color space that is used to perform transparency and blending operations on the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### bindPdf(String pdfFile, int pageNumber) {#bindPdf-java.lang.String-int-}
```
public void bindPdf(String pdfFile, int pageNumber)
```


Sets PDF file and number of page which will be used as stamp.

--------------------

> ```
> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
>  Stamp stamp = new Stamp();
>  //First page will be used as stamp.
>  stamp.bindPdf("stamp.pdf", 1);
>  stamp.isBackground = true;
>  fileStamp.addStamp(stamp);
>  fileStamp.close();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdfFile | java.lang.String | Path to PDF file. |
| pageNumber | int | Number of page in PDF file |

### bindPdf(System.IO.Stream pdfStream, int pageNumber) {#bindPdf-com.aspose.ms.System.IO.Stream-int-}
```
public void bindPdf(System.IO.Stream pdfStream, int pageNumber)
```


Sets PDF file and number of page which will be used as stamp.

--------------------

> ```
> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
>  Stamp stamp = new Stamp();
>  //First page will be used as stamp.
>  Stream stream = new FileInputStream("stamp.pdf", FileMode.Open, FileAccess.Read);
>  stamp.bindPdf(stream, 1);
>  fileStamp.AddStamp(stamp);
>  fileStamp.Close();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdfStream | com.aspose.ms.System.IO.Stream | Stream which contains PDF document. |
| pageNumber | int | Page index of the document whihc will be used as stamp. |

### bindImage(String imageFile) {#bindImage-java.lang.String-}
```
public void bindImage(String imageFile)
```


Sets image as a stamp.

--------------------

> ```
> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
>  Stamp stamp = new Stamp();
>  stamp.bindImage("image.jpg");
>  fileStamp.addStamp(stamp);
>  fileStamp.close();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageFile | java.lang.String | Image file name and path. |

### bindLogo(FormattedText formattedText) {#bindLogo-com.aspose.pdf.facades.FormattedText-}
```
public void bindLogo(FormattedText formattedText)
```


Sets text as stamp.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | FormattedText object which specifies text and text properties. |

### setOrigin(float originX, float originY) {#setOrigin-float-float-}
```
public void setOrigin(float originX, float originY)
```


Sets position on page where stamp will be placed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| originX | float | X coordinate of the stamp. |
| originY | float | Y coordinate of the stamp. |

### close() {#close--}
```
public void close()
```




