---
title: StampAnnotation
linktitle: StampAnnotation
second_title: Aspose.PDF for Java API Reference
description: <p> Represents rubber stamp annotation. This type of annotation displays text or graphics intended to look as if they were stamped on the page with a rubber stamp. </p> <hr>.
type: docs
weight: 4630
url: /java/com.aspose.pdf/stampannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.StampAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.StampAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.StampAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.StampAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class StampAnnotation extends MarkupAnnotation
```

<p> Represents rubber stamp annotation. This type of annotation displays text or graphics intended to look as if they were stamped on the page with a rubber stamp. </p> <hr> <pre> Next code snippet demonstrates how to add 2 stamps into the first pdf document page. Input document comes from inFile and changes are saved into the outFile. The first stamp has icon NotForPublicRelease and the second comes with image from rubber.jpg. Document document = new Document(inFile); StampAnnotation stamp1 = new StampAnnotation(StampIcon.NotForPublicRelease); stamp1.setRect ( new Rectangle(100, 100, 120, 120)) document.getPages().get(1).getAnnotations().add(stamp1); StampAnnotation stamp2 = new StampAnnotation(new FileStream("rubber.jpg", FileMode.Open)); stamp2.setRect ( new Rectangle(200, 200, 220, 220)) document.getPages().get(1).getAnnotations().add(stamp2); document.save(outFile); </pre>

## Constructors

| Constructor | Description |
| --- | --- |
| [StampAnnotation](#StampAnnotation-com.aspose.pdf.IDocument-) | Constructor |
| [StampAnnotation](#StampAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Creates new Stamp annotation on the specified page. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Acepts {@code AnnotationSelector} visitor when browsing annotation collection. |
| [clear](#clear--) | Clear static instances |
| [getAnnotationType](#getAnnotationType--) | Gets type of annotation. |
| [getIcon](#getIcon--) | Gets icon for rubber stamp. |
| [getImage](#getImage--) | Gets image of the annotation. |
| [setBase64SVGImage](#setBase64SVGImage-java.lang.String-) | Sets SVG image of the annotation in Base64 string. |
| [setIcon](#setIcon-com.aspose.pdf.StampIcon-) | Sets icon for rubber stamp. |
| [setImage](#setImage-java.io.InputStream-) | Sets image of the annotation. |

### StampAnnotation {#StampAnnotation-com.aspose.pdf.IDocument-}
Constructor

### StampAnnotation {#StampAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Creates new Stamp annotation on the specified page.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Acepts {@code AnnotationSelector} visitor when browsing annotation collection.

### clear {#clear--}
```
public static void clear()
```

Clear static instances

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Gets type of annotation.

**Returns:**
AnnotationType element @see AnnotationType

### getIcon {#getIcon--}
```
public StampIcon getIcon()
```

Gets icon for rubber stamp.

**Returns:**
StampIcon value

### getImage {#getImage--}
```
public InputStream getImage()
```

Gets image of the annotation.

**Returns:**
InputStream object

### setBase64SVGImage {#setBase64SVGImage-java.lang.String-}
Sets SVG image of the annotation in Base64 string.

### setIcon {#setIcon-com.aspose.pdf.StampIcon-}
Sets icon for rubber stamp.

### setImage {#setImage-java.io.InputStream-}
Sets image of the annotation.
