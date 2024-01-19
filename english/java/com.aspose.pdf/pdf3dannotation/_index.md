---
title: PDF3DAnnotation
second_title: Aspose.PDF for Java API Reference
description: Class PDF3DAnnotation.
type: docs
weight: 244
url: /java/com.aspose.pdf/pdf3dannotation/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation)
```
public final class PDF3DAnnotation extends Annotation
```

Class PDF3DAnnotation. This class cannot be inherited.
## Constructors

| Constructor | Description |
| --- | --- |
| [PDF3DAnnotation(Page page, Rectangle rect, PDF3DArtwork pdf3DArtwork)](#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-) | Initializes a new instance of the  PDF3DAnnotation  class. |
| [PDF3DAnnotation(Page page, Rectangle rect, PDF3DArtwork pdf3DArtwork, int activation)](#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-int-) | Initializes a new instance of the  PDF3DAnnotation  class. |
## Methods

| Method | Description |
| --- | --- |
| [getPdf3DArtwork()](#getPdf3DArtwork--) | Gets the 3D Artwork. |
| [getLightingScheme()](#getLightingScheme--) | Gets the lighting scheme. |
| [getContent()](#getContent--) | Gets or sets the content. |
| [setContent(PDF3DContent value)](#setContent-com.aspose.pdf.PDF3DContent-) | Gets or sets the content. |
| [getRenderMode()](#getRenderMode--) | Gets the render mode. |
| [setDefaultViewIndex(int index)](#setDefaultViewIndex-int-) | Sets the index of the default view. |
| [getViewArray()](#getViewArray--) | Gets the view array. |
| [getAnnotationType()](#getAnnotationType--) | Gets type of annotation. |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor for annotation processing. |
| [setImagePreview(String filename)](#setImagePreview-java.lang.String-) | Sets the image preview. |
| [setImagePreview(InputStream image)](#setImagePreview-java.io.InputStream-) | Sets the image preview. |
| [clearImagePreview()](#clearImagePreview--) | Clears the image preview. |
| [getImagePreview()](#getImagePreview--) | Gets the image preview. |
### PDF3DAnnotation(Page page, Rectangle rect, PDF3DArtwork pdf3DArtwork) {#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-}
```
public PDF3DAnnotation(Page page, Rectangle rect, PDF3DArtwork pdf3DArtwork)
```


Initializes a new instance of the  PDF3DAnnotation  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The page. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | The rectangle. |
| pdf3DArtwork | [PDF3DArtwork](../../com.aspose.pdf/pdf3dartwork) | The 3D Artwork. |

### PDF3DAnnotation(Page page, Rectangle rect, PDF3DArtwork pdf3DArtwork, int activation) {#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-int-}
```
public PDF3DAnnotation(Page page, Rectangle rect, PDF3DArtwork pdf3DArtwork, int activation)
```


Initializes a new instance of the  PDF3DAnnotation  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The page. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | The rectangle. |
| pdf3DArtwork | [PDF3DArtwork](../../com.aspose.pdf/pdf3dartwork) | The 3D Artwork. |
| activation | int | The activation mode. |

### getPdf3DArtwork() {#getPdf3DArtwork--}
```
public PDF3DArtwork getPdf3DArtwork()
```


Gets the 3D Artwork.

Value: The PDF3 d artwork.

**Returns:**
[PDF3DArtwork](../../com.aspose.pdf/pdf3dartwork) - PDF3DArtwork object
### getLightingScheme() {#getLightingScheme--}
```
public PDF3DLightingScheme getLightingScheme()
```


Gets the lighting scheme.

Value: The lighting scheme.

**Returns:**
[PDF3DLightingScheme](../../com.aspose.pdf/pdf3dlightingscheme) - PDF3DLightingScheme object
### getContent() {#getContent--}
```
public PDF3DContent getContent()
```


Gets or sets the content.

Value: The content.

**Returns:**
[PDF3DContent](../../com.aspose.pdf/pdf3dcontent) - PDF3DContent object
### setContent(PDF3DContent value) {#setContent-com.aspose.pdf.PDF3DContent-}
```
public void setContent(PDF3DContent value)
```


Gets or sets the content.

Value: The content.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PDF3DContent](../../com.aspose.pdf/pdf3dcontent) | PDF3DContent object |

### getRenderMode() {#getRenderMode--}
```
public PDF3DRenderMode getRenderMode()
```


Gets the render mode.

Value: The render mode.

**Returns:**
[PDF3DRenderMode](../../com.aspose.pdf/pdf3drendermode) - PDF3DRenderMode object
### setDefaultViewIndex(int index) {#setDefaultViewIndex-int-}
```
public void setDefaultViewIndex(int index)
```


Sets the index of the default view.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The default view index. |

### getViewArray() {#getViewArray--}
```
public PDF3DViewArray getViewArray()
```


Gets the view array.

Value: The view array.

**Returns:**
[PDF3DViewArray](../../com.aspose.pdf/pdf3dviewarray) - PDF3DViewArray object
### getAnnotationType() {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```


Gets type of annotation.

Value: The type of the annotation.

**Returns:**
[AnnotationType](../../com.aspose.pdf/annotationtype)
### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Accepts visitor for annotation processing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | AnnotationSelector object. |

### setImagePreview(String filename) {#setImagePreview-java.lang.String-}
```
public void setImagePreview(String filename)
```


Sets the image preview.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filename | java.lang.String | The image preview filename. |

### setImagePreview(InputStream image) {#setImagePreview-java.io.InputStream-}
```
public void setImagePreview(InputStream image)
```


Sets the image preview.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | java.io.InputStream | The image stream. |

### clearImagePreview() {#clearImagePreview--}
```
public void clearImagePreview()
```


Clears the image preview.

### getImagePreview() {#getImagePreview--}
```
public InputStream getImagePreview()
```


Gets the image preview.

**Returns:**
java.io.InputStream - Image preview as stream.
