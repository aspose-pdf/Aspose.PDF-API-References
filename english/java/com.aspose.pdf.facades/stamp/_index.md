---
title: Stamp
second_title: Aspose.PDF for Java API Reference
description: Class represeting stamp.
type: docs
weight: 59
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
| [bindImage(InputStream image)](#bindImage-java.io.InputStream-) | Sets image which will be used as stamp. |
| [bindImage(String imageFile)](#bindImage-java.lang.String-) | Sets image as a stamp. |
| [bindLogo(FormattedText formattedText)](#bindLogo-com.aspose.pdf.facades.FormattedText-) | Sets text as stamp. |
| [bindPdf(InputStream pdfStream, int pageNumber)](#bindPdf-java.io.InputStream-int-) | Sets PDF file and number of page which will be used as stamp. |
| [bindPdf(String pdfFile, int pageNumber)](#bindPdf-java.lang.String-int-) | Sets PDF file and number of page which will be used as stamp. |
| [bindTextState(TextState textState)](#bindTextState-com.aspose.pdf.TextState-) | Sets text state of stamp text. |
| [close()](#close--) | Closes this instance |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendingSpace()](#getBlendingSpace--) | Gets a BlendingColorSpace value that defines a color space that is used to perform transparency and blending operations on the page. |
| [getClass()](#getClass--) |  |
| [getOpacity()](#getOpacity--) | Gets opacity of the stamp. |
| [getPageNumber()](#getPageNumber--) | Gets page number. |
| [getPages()](#getPages--) | Gets array with numbers of pages which will be affected by stamp. |
| [getQuality()](#getQuality--) | Gets quality of image stamp in percent. |
| [getRotation()](#getRotation--) | Gets rotation of the stamp in degrees. |
| [getStampId()](#getStampId--) | Gets identifier of stamp. |
| [hashCode()](#hashCode--) |  |
| [isBackground()](#isBackground--) | Gets background status. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackground(boolean value)](#setBackground-boolean-) | Sets background status. |
| [setBlendingSpace(int value)](#setBlendingSpace-int-) | Sets a BlendingColorSpace value that defines a color space that is used to perform transparency and blending operations on the page. |
| [setImageSize(float width, float height)](#setImageSize-float-float-) | Sets size of image stamp. |
| [setOpacity(float value)](#setOpacity-float-) | Sets opacity of the stamp. |
| [setOrigin(float originX, float originY)](#setOrigin-float-float-) | Sets position on page where stamp will be placed. |
| [setPageNumber(int value)](#setPageNumber-int-) | Sets page number. |
| [setPages(int[] value)](#setPages-int---) | Sets array with numbers of pages which will be affected by stamp. |
| [setQuality(int value)](#setQuality-int-) | Sets quality of image stamp in percent. |
| [setRotation(float value)](#setRotation-float-) | Gets or sets rotation of the stamp in degrees. |
| [setStampId(int value)](#setStampId-int-) | Sets identifier of stamp. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Stamp() {#Stamp--}
```
public Stamp()
```


Constructor for Stamp object.

### bindImage(InputStream image) {#bindImage-java.io.InputStream-}
```
public void bindImage(InputStream image)
```


Sets image which will be used as stamp.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | java.io.InputStream | Stream which contains image data. |

### bindImage(String imageFile) {#bindImage-java.lang.String-}
```
public void bindImage(String imageFile)
```


Sets image as a stamp.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
 Stamp stamp = new Stamp();
 stamp.bindImage("image.jpg");
 fileStamp.addStamp(stamp);
 fileStamp.close();
```

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

### bindPdf(InputStream pdfStream, int pageNumber) {#bindPdf-java.io.InputStream-int-}
```
public void bindPdf(InputStream pdfStream, int pageNumber)
```


Sets PDF file and number of page which will be used as stamp.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
 Stamp stamp = new Stamp();
 //First page will be used as stamp.
 InputStream stream = new FileInputStream("stamp.pdf");
 stamp.bindPdf(stream, 1);
 fileStamp.addStamp(stamp);
 fileStamp.close();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdfStream | java.io.InputStream | Stream which contains PDF document. |
| pageNumber | int | Page index of the document whihc will be used as stamp. |

### bindPdf(String pdfFile, int pageNumber) {#bindPdf-java.lang.String-int-}
```
public void bindPdf(String pdfFile, int pageNumber)
```


Sets PDF file and number of page which will be used as stamp.

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
 Stamp stamp = new Stamp();
 //First page will be used as stamp.
 stamp.bindPdf("stamp.pdf", 1);
 stamp.isBackground (true);
 fileStamp.addStamp(stamp);
 fileStamp.close();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdfFile | java.lang.String | Path to PDF file. |
| pageNumber | int | Number of page in PDF file |

### bindTextState(TextState textState) {#bindTextState-com.aspose.pdf.TextState-}
```
public void bindTextState(TextState textState)
```


Sets text state of stamp text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| textState | [TextState](../../com.aspose.pdf/textstate) | TextState object which specifies text properties. |

### close() {#close--}
```
public void close()
```


Closes this instance

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
### getBlendingSpace() {#getBlendingSpace--}
```
public int getBlendingSpace()
```


Gets a BlendingColorSpace value that defines a color space that is used to perform transparency and blending operations on the page.

**Returns:**
int - int value
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Gets opacity of the stamp.

**Returns:**
float - float value
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Gets page number.

**Returns:**
int - int value
### getPages() {#getPages--}
```
public int[] getPages()
```


Gets array with numbers of pages which will be affected by stamp.

**Returns:**
int[] - int array
### getQuality() {#getQuality--}
```
public int getQuality()
```


Gets quality of image stamp in percent. Valiued values 0..100%.

**Returns:**
int - int value
### getRotation() {#getRotation--}
```
public float getRotation()
```


Gets rotation of the stamp in degrees.

**Returns:**
float - float value
### getStampId() {#getStampId--}
```
public int getStampId()
```


Gets identifier of stamp.

**Returns:**
int - int value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isBackground() {#isBackground--}
```
public boolean isBackground()
```


Gets background status. If true stamp will be placed as background of the spamped page. By default is set to false.

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




### setBackground(boolean value) {#setBackground-boolean-}
```
public void setBackground(boolean value)
```


Sets background status. If true stamp will be placed as background of the spamped page. By default is set to false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setBlendingSpace(int value) {#setBlendingSpace-int-}
```
public void setBlendingSpace(int value)
```


Sets a BlendingColorSpace value that defines a color space that is used to perform transparency and blending operations on the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setImageSize(float width, float height) {#setImageSize-float-float-}
```
public void setImageSize(float width, float height)
```


Sets size of image stamp. Image will be scaled according to the specified values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | float | Image width. |
| height | float | Image height. |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Sets opacity of the stamp.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | float value |

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

### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


Sets page number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setPages(int[] value) {#setPages-int---}
```
public void setPages(int[] value)
```


Sets array with numbers of pages which will be affected by stamp. If Pages = null all pages of the document are affected.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] | int array

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
 Stamp stamp = new com.aspose.pdf.facades.Stamp();
 stamp.bindLogo(new FormattedText(text));
 //put stamp only on 1st, 4th and 6th page.
 stamp.setPages(new int[] { 1, 4, 6 });
 fileStamp.addStamp(stamp);
 fileStamp.close();
``` |

### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


Sets quality of image stamp in percent. Valiued values 0..100%.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setRotation(float value) {#setRotation-float-}
```
public void setRotation(float value)
```


Gets or sets rotation of the stamp in degrees.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | float value

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
 Stamp stamp = new Stamp();
 stamp.bindLogo(new FormattedText("STAMP"));
 stamp.setRotation(90);
 fileStamp.addStamp(stamp);
 fileStamp.close();
``` |

### setStampId(int value) {#setStampId-int-}
```
public void setStampId(int value)
```


Sets identifier of stamp.

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

