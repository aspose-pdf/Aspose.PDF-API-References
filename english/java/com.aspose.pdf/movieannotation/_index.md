---
title: MovieAnnotation
second_title: Aspose.PDF for Java API Reference
description: Represents a movie annotation that contains animated graphics and sound to be presented on the computer screen and through the speakers.
type: docs
weight: 222
url: /java/com.aspose.pdf/movieannotation/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation)

**All Implemented Interfaces:**
[com.aspose.pdf.engine.ITitledAnnotation](../../com.aspose.pdf.engine/ititledannotation)
```
public final class MovieAnnotation extends Annotation implements ITitledAnnotation
```

Represents a movie annotation that contains animated graphics and sound to be presented on the computer screen and through the speakers. When the annotation is activated, the movie is played.
## Constructors

| Constructor | Description |
| --- | --- |
| [MovieAnnotation(IDocument document, String movieFile)](#MovieAnnotation-com.aspose.pdf.IDocument-java.lang.String-) | Constructor for using with Generator. |
| [MovieAnnotation(Page page, Rectangle rect, String movieFile)](#MovieAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-) | Creates new Sound annotation on the specified page. |
## Methods

| Method | Description |
| --- | --- |
| [getTitle()](#getTitle--) | Gets the title of the movie annotation. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Sets the title of the movie annotation. |
| [getFile()](#getFile--) | Gets a file specification identifying a self-describing movie file. |
| [setFile(FileSpecification value)](#setFile-com.aspose.pdf.FileSpecification-) | Sets a file specification identifying a self-describing movie file. |
| [getPoster()](#getPoster--) | Gets or sets a flag or stream specifying whether and how a poster image representing the movie shall be displayed. |
| [setPoster(boolean value)](#setPoster-boolean-) | Gets or sets a flag or stream specifying whether and how a poster image representing the movie shall be displayed. |
| [getAspect()](#getAspect--) | Gets or sets the width and height of the movie\\ufffds bounding box, in pixels. |
| [setAspect(Point value)](#setAspect-com.aspose.pdf.Point-) | Gets or sets the width and height of the movie\\ufffds bounding box, in pixels. |
| [getRotate()](#getRotate--) | Gets or sets the number of degrees by which the movie shall be rotated clockwise relative to the page. |
| [setRotate(int value)](#setRotate-int-) | Gets or sets the number of degrees by which the movie shall be rotated clockwise relative to the page. |
| [getAnnotationType()](#getAnnotationType--) | Gets type of annotation. |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor object to process the annotation. |
### MovieAnnotation(IDocument document, String movieFile) {#MovieAnnotation-com.aspose.pdf.IDocument-java.lang.String-}
```
public MovieAnnotation(IDocument document, String movieFile)
```


Constructor for using with Generator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Document where movie annotation will be created. |
| movieFile | java.lang.String | Name of movie file. |

### MovieAnnotation(Page page, Rectangle rect, String movieFile) {#MovieAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-}
```
public MovieAnnotation(Page page, Rectangle rect, String movieFile)
```


Creates new Sound annotation on the specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The document's page where annotation should be created. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | The annotation rectangle, defining the location of the annotation on the page. |
| movieFile | java.lang.String | A movie file to be played when the annotation is activated. |

### getTitle() {#getTitle--}
```
public String getTitle()
```


Gets the title of the movie annotation.

**Returns:**
java.lang.String - String value
### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


Sets the title of the movie annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getFile() {#getFile--}
```
public FileSpecification getFile()
```


Gets a file specification identifying a self-describing movie file.

**Returns:**
[FileSpecification](../../com.aspose.pdf/filespecification) - FileSpecification value
### setFile(FileSpecification value) {#setFile-com.aspose.pdf.FileSpecification-}
```
public void setFile(FileSpecification value)
```


Sets a file specification identifying a self-describing movie file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FileSpecification](../../com.aspose.pdf/filespecification) | FileSpecification object |

### getPoster() {#getPoster--}
```
public final boolean getPoster()
```


Gets or sets a flag or stream specifying whether and how a poster image representing the movie shall be displayed. If true, the poster image shall be retrieved from the movie file; if it is false, no poster shall be displayed.

**Returns:**
boolean - boolean value
### setPoster(boolean value) {#setPoster-boolean-}
```
public final void setPoster(boolean value)
```


Gets or sets a flag or stream specifying whether and how a poster image representing the movie shall be displayed. If true, the poster image shall be retrieved from the movie file; if it is false, no poster shall be displayed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getAspect() {#getAspect--}
```
public final Point getAspect()
```


Gets or sets the width and height of the movie\\ufffds bounding box, in pixels.

**Returns:**
[Point](../../com.aspose.pdf/point) - Point instance
### setAspect(Point value) {#setAspect-com.aspose.pdf.Point-}
```
public final void setAspect(Point value)
```


Gets or sets the width and height of the movie\\ufffds bounding box, in pixels.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.pdf/point) | Point instance |

### getRotate() {#getRotate--}
```
public final int getRotate()
```


Gets or sets the number of degrees by which the movie shall be rotated clockwise relative to the page. The value shall be a multiple of 90.

**Returns:**
int - int value
### setRotate(int value) {#setRotate-int-}
```
public final void setRotate(int value)
```


Gets or sets the number of degrees by which the movie shall be rotated clockwise relative to the page. The value shall be a multiple of 90.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### getAnnotationType() {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```


Gets type of annotation.

**Returns:**
[AnnotationType](../../com.aspose.pdf/annotationtype) - AnnotationType element as int value
### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Accepts visitor object to process the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | Visitor object. |

