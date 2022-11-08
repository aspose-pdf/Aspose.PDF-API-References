---
title: ImagePlacement
second_title: Aspose.PDF for Java API Reference
description: Represents characteristics of an image placed to Pdf document page.
type: docs
weight: 171
url: /java/com.aspose.pdf/imageplacement/
---
**Inheritance:**
java.lang.Object
```
public final class ImagePlacement
```

Represents characteristics of an image placed to Pdf document page.

--------------------

```
The example demonstrates how to find images on the first PDF document page and get images as bitmaps with visible dimensions.
 
  
 // Open document
 Document doc = new Document("D:\\Tests\\input.pdf");
 // Create ImagePlacementAbsorber object to perform image placement search
 ImagePlacementAbsorber abs = new ImagePlacementAbsorber();
 // Accept the absorber for first page
 doc.getPages().get_Item(1).accept(abs);
 // Retrieve images with visible dimensions
 for (ImagePlacement imagePlacement : ```
(Iterable)
```abs.getImagePlacements())
 {
     BufferedImage scaledImage;
     ByteArrayOutputStream imageStream = new ByteArrayOutputStream())
     
         // Retrieve image from resources
         imagePlacement.getImage().save(imageStream, ImageFormatInternal.Png);
         BufferedImage resourceImage = (BufferedImage) ImageIO.read(imageStream);
         // Create new bitmap with actual dimensions
         scaledImage = new BufferedImage(resourceImage, (int)imagePlacement.getRectangle().getWidth(), (int)imagePlacement.getRectangle().getHeight());
     
 }
```

--------------------

When an image is placed to a page it may have dimensions other than physical dimensions defined in  Resources . The object  ImagePlacement  is intended to provide such information like dimensions, resolution and so on.
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompositingParameters()](#getCompositingParameters--) | Gets compositing parameters of graphics state active for the image placed to the page. |
| [getImage()](#getImage--) | Gets related XImage resource object. |
| [getMatrix()](#getMatrix--) | Current transformation matrix for this image. |
| [getOperator()](#getOperator--) | Operator used for displaying the image. |
| [getPage()](#getPage--) | Gets the page containing the image. |
| [getRectangle()](#getRectangle--) | Gets rectangle of the Image. |
| [getResolution()](#getResolution--) | Gets resolution of the Image. |
| [getRotation()](#getRotation--) | Gets rotation angle of the Image. |
| [hashCode()](#hashCode--) |  |
| [hide()](#hide--) | Delete image from the page. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [replace(InputStream image)](#replace-java.io.InputStream-) | Replace image in collection with another image. |
| [save(OutputStream outputStream)](#save-java.io.OutputStream-) | Saves image with corresponding transformations: scaling, rotation and resolution. |
| [save(OutputStream outputStream, ImageType format)](#save-java.io.OutputStream-com.aspose.pdf.ImageType-) | Saves image with corresponding transformations: scaling, rotation and resolution. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompositingParameters() {#getCompositingParameters--}
```
public CompositingParameters getCompositingParameters()
```


Gets compositing parameters of graphics state active for the image placed to the page.

**Returns:**
[CompositingParameters](../../com.aspose.pdf/compositingparameters) - CompositingParameters object
### getImage() {#getImage--}
```
public XImage getImage()
```


Gets related XImage resource object.

**Returns:**
[XImage](../../com.aspose.pdf/ximage) - XImage object
### getMatrix() {#getMatrix--}
```
public Matrix getMatrix()
```


Current transformation matrix for this image.

**Returns:**
[Matrix](../../com.aspose.pdf/matrix) - Matrix object
### getOperator() {#getOperator--}
```
public final Operator getOperator()
```


Operator used for displaying the image.

**Returns:**
[Operator](../../com.aspose.pdf/operator) - Operator instance
### getPage() {#getPage--}
```
public Page getPage()
```


Gets the page containing the image.

**Returns:**
[Page](../../com.aspose.pdf/page) - Page object
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Gets rectangle of the Image.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle object
### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


Gets resolution of the Image.

**Returns:**
[Resolution](../../com.aspose.pdf.devices/resolution) - Resolution object
### getRotation() {#getRotation--}
```
public float getRotation()
```


Gets rotation angle of the Image.

**Returns:**
float - int value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### hide() {#hide--}
```
public final void hide()
```


Delete image from the page.

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### replace(InputStream image) {#replace-java.io.InputStream-}
```
public void replace(InputStream image)
```


Replace image in collection with another image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | java.io.InputStream | Stream containing image data. |

### save(OutputStream outputStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream outputStream)
```


Saves image with corresponding transformations: scaling, rotation and resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Stream where image will be saved |

### save(OutputStream outputStream, ImageType format) {#save-java.io.OutputStream-com.aspose.pdf.ImageType-}
```
public void save(OutputStream outputStream, ImageType format)
```


Saves image with corresponding transformations: scaling, rotation and resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | java.io.OutputStream | Stream where image will be saved |
| format | [ImageType](../../com.aspose.pdf/imagetype) | Format which will be used for image enconding.  ImageFormat  |

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

