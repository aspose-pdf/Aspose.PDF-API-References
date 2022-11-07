---
title: StampAnnotation
second_title: Aspose.PDF for Java API Reference
description: Represents rubber stamp annotation.
type: docs
weight: 273
url: /java/com.aspose.pdf/stampannotation/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.MarkupAnnotation](../../com.aspose.pdf/markupannotation)
```
public final class StampAnnotation extends MarkupAnnotation
```

Represents rubber stamp annotation. This type of annotation displays text or graphics intended to look as if they were stamped on the page with a rubber stamp.

--------------------

> ```
> Next code snippet demonstrates how to add 2 stamps into the first pdf document page.
>   Input document comes from inFile and changes are saved into the outFile.
>   The first stamp has icon NotForPublicRelease and the second comes with image from rubber.jpg.
>   
>   Document document = new Document(inFile);
>   StampAnnotation stamp1 = new StampAnnotation(StampIcon.NotForPublicRelease);
>  	stamp1.setRect ( new Rectangle(100, 100, 120, 120))
>  	document.getPages().get(1).getAnnotations().add(stamp1);
>   StampAnnotation stamp2 = new StampAnnotation(new FileStream("rubber.jpg", FileMode.Open));
>  	stamp2.setRect ( new Rectangle(200, 200, 220, 220))
>  	document.getPages().get(1).getAnnotations().add(stamp2);
>   document.save(outFile);
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [StampAnnotation(Page page, Rectangle rect)](#StampAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Creates new Stamp annotation on the specified page. |
## Methods

| Method | Description |
| --- | --- |
| [writeXfdf(System.Xml.XmlWriter writer)](#writeXfdf-com.aspose.ms.System.Xml.XmlWriter-) |  |
| [getIcon()](#getIcon--) | Gets or sets icon for rubber stamp. |
| [setIcon(int value)](#setIcon-int-) |  |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Acepts  AnnotationSelector  visitor when browsing annotation collection. |
| [getImage()](#getImage--) | Gets or sets image of the annotation. |
| [setImage(InputStream value)](#setImage-java.io.InputStream-) |  |
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

### writeXfdf(System.Xml.XmlWriter writer) {#writeXfdf-com.aspose.ms.System.Xml.XmlWriter-}
```
public void writeXfdf(System.Xml.XmlWriter writer)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| writer | com.aspose.ms.System.Xml.XmlWriter |  |

### getIcon() {#getIcon--}
```
public int getIcon()
```


Gets or sets icon for rubber stamp.

**Returns:**
int
### setIcon(int value) {#setIcon-int-}
```
public void setIcon(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Acepts  AnnotationSelector  visitor when browsing annotation collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) |  |

### getImage() {#getImage--}
```
public InputStream getImage()
```


Gets or sets image of the annotation.

**Returns:**
java.io.InputStream
### setImage(InputStream value) {#setImage-java.io.InputStream-}
```
public void setImage(InputStream value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.InputStream |  |

