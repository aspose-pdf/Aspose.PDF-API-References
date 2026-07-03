---
title: PDF3DAnnotation
second_title: Aspose.PDF for Java API Reference
description: Class PDF3DAnnotation. This class cannot be inherited. @see Annotation
type: docs
weight: 3560
url: /java/com.aspose.pdf/pdf3dannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PDF3DAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PDF3DAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PDF3DAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class PDF3DAnnotation extends Annotation
```

Class PDF3DAnnotation. This class cannot be inherited. @see Annotation

## Constructors

| Constructor | Description |
| --- | --- |
| [PDF3DAnnotation](#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-) | Initializes a new instance of the {@code PDF3DAnnotation} class. |
| [PDF3DAnnotation](#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-com.aspose.pdf.PDF3DActivation-) | Initializes a new instance of the {@code PDF3DAnnotation} class. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor for annotation processing. |
| [clearImagePreview](#clearImagePreview--) | Clears the image preview. |
| [getAnnotationType](#getAnnotationType--) | Gets type of annotation. Value: The type of the annotation. |
| [getContent](#getContent--) | Gets or sets the content. Value: The content. |
| [getImagePreview](#getImagePreview--) | Gets the image preview. |
| [getLightingScheme](#getLightingScheme--) | Gets the lighting scheme. Value: The lighting scheme. |
| [getPdf3DArtwork](#getPdf3DArtwork--) | Gets the 3D Artwork. Value: The PDF3 d artwork. |
| [getRenderMode](#getRenderMode--) | Gets the render mode. Value: The render mode. |
| [getViewArray](#getViewArray--) | Gets the view array. Value: The view array. |
| [setContent](#setContent-com.aspose.pdf.PDF3DContent-) | Gets or sets the content. Value: The content. |
| [setDefaultViewIndex](#setDefaultViewIndex-int-) | Sets the index of the default view. |
| [setImagePreview](#setImagePreview-java.io.InputStream-) | Sets the image preview. |
| [setImagePreview](#setImagePreview-java.lang.String-) | Sets the image preview. |

### PDF3DAnnotation {#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-}
Initializes a new instance of the {@code PDF3DAnnotation} class.

### PDF3DAnnotation {#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-com.aspose.pdf.PDF3DActivation-}
Initializes a new instance of the {@code PDF3DAnnotation} class.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepts visitor for annotation processing.

### clearImagePreview {#clearImagePreview--}
```
public void clearImagePreview()
```

Clears the image preview.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Gets type of annotation. Value: The type of the annotation.

**Returns:**
int value

### getContent {#getContent--}
```
public PDF3DContent getContent()
```

Gets or sets the content. Value: The content.

**Returns:**
PDF3DContent object

### getImagePreview {#getImagePreview--}
```
public InputStream getImagePreview()
```

Gets the image preview.

**Returns:**
Image preview as stream.

### getLightingScheme {#getLightingScheme--}
```
public PDF3DLightingScheme getLightingScheme()
```

Gets the lighting scheme. Value: The lighting scheme.

**Returns:**
PDF3DLightingScheme object

### getPdf3DArtwork {#getPdf3DArtwork--}
```
public PDF3DArtwork getPdf3DArtwork()
```

Gets the 3D Artwork. Value: The PDF3 d artwork.

**Returns:**
PDF3DArtwork object

### getRenderMode {#getRenderMode--}
```
public PDF3DRenderMode getRenderMode()
```

Gets the render mode. Value: The render mode.

**Returns:**
PDF3DRenderMode object

### getViewArray {#getViewArray--}
```
public PDF3DViewArray getViewArray()
```

Gets the view array. Value: The view array.

**Returns:**
PDF3DViewArray object

### setContent {#setContent-com.aspose.pdf.PDF3DContent-}
Gets or sets the content. Value: The content.

### setDefaultViewIndex {#setDefaultViewIndex-int-}
```
public void setDefaultViewIndex(int index)
```

Sets the index of the default view.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | The default view index. |

### setImagePreview {#setImagePreview-java.io.InputStream-}
Sets the image preview.

### setImagePreview {#setImagePreview-java.lang.String-}
Sets the image preview.
