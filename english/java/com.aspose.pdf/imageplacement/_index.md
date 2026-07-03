---
title: ImagePlacement
second_title: Aspose.PDF for Java API Reference
description: <p> Represents characteristics of an image placed to Pdf document page. </p> <hr> <pre> The example demonstrates how to find images on the first PDF document page and get images.
type: docs
weight: 2330
url: /java/com.aspose.pdf/imageplacement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ImagePlacement

```
public final class ImagePlacement extends Object
```

<p> Represents characteristics of an image placed to Pdf document page. </p> <hr> <pre> The example demonstrates how to find images on the first PDF document page and get images as bitmaps with visible dimensions. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Retrieve images with visible dimensions for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { BufferedImage scaledImage; ByteArrayOutputStream imageStream = new ByteArrayOutputStream()) // Retrieve image from resources imagePlacement.getImage().save(imageStream, ImageFormatInternal.Png); BufferedImage resourceImage = (BufferedImage) ImageIO.read(imageStream); // Create new bitmap with actual dimensions scaledImage = new BufferedImage(resourceImage, (int)imagePlacement.getRectangle().getWidth(), (int)imagePlacement.getRectangle().getHeight()); } </pre> <hr> <p> When an image is placed to a page it may have dimensions other than physical dimensions defined in {@code Resources}. The object {@code ImagePlacement} is intended to provide such information like dimensions, resolution and so on. </p>

## Methods

| Method | Description |
| --- | --- |
| [getCompositingParameters](#getCompositingParameters--) | Gets compositing parameters of graphics state active for the image placed to the page. |
| [getImage](#getImage--) | Gets related XImage resource object. |
| [getMatrix](#getMatrix--) | Current transformation matrix for this image. |
| [getOperator](#getOperator--) | Operator used for displaying the image. |
| [getPage](#getPage--) | Gets the page containing the image. |
| [getRectangle](#getRectangle--) | Gets rectangle of the Image. |
| [getResolution](#getResolution--) | Gets resolution of the Image. |
| [getRotation](#getRotation--) | Gets rotation angle of the Image. |
| [hide](#hide--) | Delete image from the page. |
| [replace](#replace-java.io.InputStream-) | Replace image in collection with another image. |
| [save](#save-java.io.OutputStream-) | Saves image with corresponding transformations: scaling, rotation and resolution. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.ImageType-) | Saves image with corresponding transformations: scaling, rotation and resolution. |

### getCompositingParameters {#getCompositingParameters--}
```
public CompositingParameters getCompositingParameters()
```

Gets compositing parameters of graphics state active for the image placed to the page.

**Returns:**
CompositingParameters object

### getImage {#getImage--}
```
public XImage getImage()
```

Gets related XImage resource object.

**Returns:**
XImage object

### getMatrix {#getMatrix--}
```
public Matrix getMatrix()
```

Current transformation matrix for this image.

**Returns:**
Matrix object

### getOperator {#getOperator--}
```
public final Operator getOperator()
```

Operator used for displaying the image.

**Returns:**
Operator instance

### getPage {#getPage--}
```
public Page getPage()
```

Gets the page containing the image.

**Returns:**
Page object

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Gets rectangle of the Image.

**Returns:**
Rectangle object

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

Gets resolution of the Image.

**Returns:**
Resolution object

### getRotation {#getRotation--}
```
public float getRotation()
```

Gets rotation angle of the Image.

**Returns:**
int value

### hide {#hide--}
```
public final void hide()
```

Delete image from the page.

### replace {#replace-java.io.InputStream-}
Replace image in collection with another image.

### save {#save-java.io.OutputStream-}
Saves image with corresponding transformations: scaling, rotation and resolution.

### save {#save-java.io.OutputStream-com.aspose.pdf.ImageType-}
Saves image with corresponding transformations: scaling, rotation and resolution.
