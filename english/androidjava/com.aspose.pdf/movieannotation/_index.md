---
title: MovieAnnotation
second_title: Aspose.PDF for Java API Reference
description: Represents a movie annotation that contains animated graphics and sound to be presented on the computer screen and through the speakers.
type: docs
weight: 179
url: /java/com.aspose.pdf/movieannotation/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation)
```
public final class MovieAnnotation extends Annotation
```

Represents a movie annotation that contains animated graphics and sound to be presented on the computer screen and through the speakers. When the annotation is activated, the movie is played.
## Constructors

| Constructor | Description |
| --- | --- |
| [MovieAnnotation(Page page, Rectangle rect, String movieFile)](#MovieAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-) | Creates new Sound annotation on the specified page. |
## Methods

| Method | Description |
| --- | --- |
| [getTitle()](#getTitle--) | Gets the title of the movie annotation. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Sets the title of the movie annotation. |
| [getFile()](#getFile--) | Gets a file specification identifying a self-describing movie file. |
| [setFile(FileSpecification value)](#setFile-com.aspose.pdf.FileSpecification-) | Sets a file specification identifying a self-describing movie file. |
| [getAspect()](#getAspect--) | Gets the width and height of the movie\\ufffds bounding box, in pixels, specified as [ width height ]. |
| [setAspect(Point value)](#setAspect-com.aspose.pdf.Point-) | Sets the width and height of the movie\\ufffds bounding box, in pixels, specified as [ width height ]. |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor object to process the annotation. |
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
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


Sets the title of the movie annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getFile() {#getFile--}
```
public FileSpecification getFile()
```


Gets a file specification identifying a self-describing movie file.

**Returns:**
[FileSpecification](../../com.aspose.pdf/filespecification)
### setFile(FileSpecification value) {#setFile-com.aspose.pdf.FileSpecification-}
```
public void setFile(FileSpecification value)
```


Sets a file specification identifying a self-describing movie file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FileSpecification](../../com.aspose.pdf/filespecification) |  |

### getAspect() {#getAspect--}
```
public Point getAspect()
```


Gets the width and height of the movie\\ufffds bounding box, in pixels, specified as [ width height ].

**Returns:**
[Point](../../com.aspose.pdf/point)
### setAspect(Point value) {#setAspect-com.aspose.pdf.Point-}
```
public void setAspect(Point value)
```


Sets the width and height of the movie\\ufffds bounding box, in pixels, specified as [ width height ].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.pdf/point) |  |

### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Accepts visitor object to process the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | Visitor object. |

