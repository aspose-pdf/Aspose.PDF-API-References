---
title: ImagePlacementAbsorber
second_title: Aspose.PDF for Java API Reference
description: Represents an absorber object of image placement objects.
type: docs
weight: 172
url: /java/com.aspose.pdf/imageplacementabsorber/
---
**Inheritance:**
java.lang.Object
```
public final class ImagePlacementAbsorber
```

Represents an absorber object of image placement objects. Performs search of image usages and provides access to search results via  ImagePlacementAbsorber.ImagePlacements  collection.

--------------------

```
The example demonstrates how to find images on the first PDF document page and get the image placement properties.


 // Open document
 Document doc = new Document("D:\\Tests\\input.pdf");
 // Create ImagePlacementAbsorber object to perform image placement search
 ImagePlacementAbsorber abs = new ImagePlacementAbsorber();
 // Accept the absorber for first page
 doc.getPages().get_Item(1).accept(abs);
 // Display image placement properties for all placements
 for (ImagePlacement imagePlacement : ```
(Iterable)
```abs.getImagePlacements())
 {
     System.out.println("image width:" + imagePlacement.getRectangle().getWidth());
     System.out.println("image height:" + imagePlacement.getRectangle().getHeight());
     System.out.println("image LLX:" + imagePlacement.getRectangle(0).getX());
     System.out.println("image LLY:" + imagePlacement.getRectangle.getY());
     System.out.println("image horizontal resolution:" + imagePlacement.getResolution().getX());
     System.out.println("image vertical resolution:" + imagePlacement.getResolution().getY());
 }
```

--------------------

The  ImagePlacementAbsorber  object is basically used in images search scenario. When the search is completed the occurrences are represented with  ImagePlacement  objects that the  ImagePlacementAbsorber.ImagePlacements  collection contains. The  ImagePlacement  object provides access to the image placement properties: dimensions, resolution etc.
## Constructors

| Constructor | Description |
| --- | --- |
| [ImagePlacementAbsorber()](#ImagePlacementAbsorber--) | Initializes new instance of the  ImagePlacementAbsorber  object. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getImagePlacements()](#getImagePlacements--) | Gets collection of image placement occurrences that are presented with  ImagePlacement  objects. |
| [hashCode()](#hashCode--) |  |
| [isReadOnlyMode()](#isReadOnlyMode--) | Gets/sets read only mode for parsing operations collection. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setReadOnlyMode(boolean value)](#setReadOnlyMode-boolean-) | Gets/sets read only mode for parsing operations collection. |
| [toString()](#toString--) |  |
| [visit(IDocument pdf)](#visit-com.aspose.pdf.IDocument-) | Performs search on the specified document. |
| [visit(Page page)](#visit-com.aspose.pdf.Page-) | Performs search on the specified page. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImagePlacementAbsorber() {#ImagePlacementAbsorber--}
```
public ImagePlacementAbsorber()
```


Initializes new instance of the  ImagePlacementAbsorber  object.

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
### getImagePlacements() {#getImagePlacements--}
```
public ImagePlacementCollection getImagePlacements()
```


Gets collection of image placement occurrences that are presented with  ImagePlacement  objects.

**Returns:**
[ImagePlacementCollection](../../com.aspose.pdf/imageplacementcollection) - ImagePlacementCollection object
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isReadOnlyMode() {#isReadOnlyMode--}
```
public final boolean isReadOnlyMode()
```


Gets/sets read only mode for parsing operations collection. It may help against out of memory exceptions.

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




### setReadOnlyMode(boolean value) {#setReadOnlyMode-boolean-}
```
public final void setReadOnlyMode(boolean value)
```


Gets/sets read only mode for parsing operations collection. It may help against out of memory exceptions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### visit(IDocument pdf) {#visit-com.aspose.pdf.IDocument-}
```
public void visit(IDocument pdf)
```


Performs search on the specified document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdf | [IDocument](../../com.aspose.pdf/idocument) | Pdf pocument object. |

### visit(Page page) {#visit-com.aspose.pdf.Page-}
```
public void visit(Page page)
```


Performs search on the specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Pdf pocument page object. |

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

