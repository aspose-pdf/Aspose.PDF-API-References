---
title: StampAnnotation
second_title: Aspose.PDF for Java API Reference
description: Represents rubber stamp annotation.
type: docs
weight: 336
url: /java/com.aspose.pdf/stampannotation/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.MarkupAnnotation](../../com.aspose.pdf/markupannotation)
```
public final class StampAnnotation extends MarkupAnnotation
```

Represents rubber stamp annotation. This type of annotation displays text or graphics intended to look as if they were stamped on the page with a rubber stamp.

--------------------

```
Next code snippet demonstrates how to add 2 stamps into the first pdf document page.
  Input document comes from inFile and changes are saved into the outFile.
  The first stamp has icon NotForPublicRelease and the second comes with image from rubber.jpg.
 
  Document document = new Document(inFile);
  StampAnnotation stamp1 = new StampAnnotation(StampIcon.NotForPublicRelease);
 	stamp1.setRect ( new Rectangle(100, 100, 120, 120))
 	document.getPages().get(1).getAnnotations().add(stamp1);
  StampAnnotation stamp2 = new StampAnnotation(new FileStream("rubber.jpg", FileMode.Open));
 	stamp2.setRect ( new Rectangle(200, 200, 220, 220))
 	document.getPages().get(1).getAnnotations().add(stamp2);
  document.save(outFile);
```
## Constructors

| Constructor | Description |
| --- | --- |
| [StampAnnotation(IDocument document)](#StampAnnotation-com.aspose.pdf.IDocument-) | Constructor |
| [StampAnnotation(Page page, Rectangle rect)](#StampAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Creates new Stamp annotation on the specified page. |
## Methods

| Method | Description |
| --- | --- |
| [getIcon()](#getIcon--) | Gets icon for rubber stamp. |
| [setIcon(int value)](#setIcon-int-) | Sets icon for rubber stamp. |
| [getAnnotationType()](#getAnnotationType--) | Gets type of annotation. |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Acepts  AnnotationSelector  visitor when browsing annotation collection. |
| [getImage()](#getImage--) | Gets image of the annotation. |
| [setImage(InputStream value)](#setImage-java.io.InputStream-) | Sets image of the annotation. |
| [setBase64SVGImage(String base64Svg)](#setBase64SVGImage-java.lang.String-) | Sets SVG image of the annotation in Base64 string. |
### StampAnnotation(IDocument document) {#StampAnnotation-com.aspose.pdf.IDocument-}
```
public StampAnnotation(IDocument document)
```


Constructor

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Document where annotation will be created. |

### StampAnnotation(Page page, Rectangle rect) {#StampAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public StampAnnotation(Page page, Rectangle rect)
```


Creates new Stamp annotation on the specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The document's page where annotation should be created. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | The annotation rectangle, defining the location of the annotation on the page. |

### getIcon() {#getIcon--}
```
public int getIcon()
```


Gets icon for rubber stamp.

**Returns:**
int - StampIcon value
### setIcon(int value) {#setIcon-int-}
```
public void setIcon(int value)
```


Sets icon for rubber stamp.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | StampIcon value |

### getAnnotationType() {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```


Gets type of annotation.

**Returns:**
[AnnotationType](../../com.aspose.pdf/annotationtype) - AnnotationType element
### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Acepts  AnnotationSelector  visitor when browsing annotation collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | Visitor object. |

### getImage() {#getImage--}
```
public InputStream getImage()
```


Gets image of the annotation.

**Returns:**
java.io.InputStream - InputStream object
### setImage(InputStream value) {#setImage-java.io.InputStream-}
```
public void setImage(InputStream value)
```


Sets image of the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.InputStream | InputStream object |

### setBase64SVGImage(String base64Svg) {#setBase64SVGImage-java.lang.String-}
```
public void setBase64SVGImage(String base64Svg)
```


Sets SVG image of the annotation in Base64 string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| base64Svg | java.lang.String | String of base64 svg image |

