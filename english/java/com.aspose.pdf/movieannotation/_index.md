---
title: MovieAnnotation
second_title: Aspose.PDF for Java API Reference
description: Represents a movie annotation that contains animated graphics and sound to be presented on the computer screen and through the speakers. When the annotation is activated, the.
type: docs
weight: 3090
url: /java/com.aspose.pdf/movieannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MovieAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MovieAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MovieAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class MovieAnnotation extends Annotation implements com.aspose.pdf.engine.ITitledAnnotation
```

Represents a movie annotation that contains animated graphics and sound to be presented on the computer screen and through the speakers. When the annotation is activated, the movie is played.

## Constructors

| Constructor | Description |
| --- | --- |
| [MovieAnnotation](#MovieAnnotation-com.aspose.pdf.IDocument-java.lang.String-) | Constructor for using with Generator. |
| [MovieAnnotation](#MovieAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-) | Creates new Sound annotation on the specified page. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor object to process the annotation. |
| [getAnnotationType](#getAnnotationType--) | Gets type of annotation. |
| [getAspect](#getAspect--) | Gets or sets the width and height of the movie's bounding box, in pixels. |
| [getFile](#getFile--) | Gets a file specification identifying a self-describing movie file. |
| [getPoster](#getPoster--) | Gets or sets a flag or stream specifying whether and how a poster image representing the movie shall be displayed. If true, the poster image shall be retrieved from the movie file; if it is false, no poster shall be displayed. |
| [getRotate](#getRotate--) | Gets or sets the number of degrees by which the movie shall be rotated clockwise relative to the page. The value shall be a multiple of 90. |
| [getTitle](#getTitle--) | Gets the title of the movie annotation. |
| [setAspect](#setAspect-com.aspose.pdf.Point-) | Gets or sets the width and height of the movie's bounding box, in pixels. |
| [setFile](#setFile-com.aspose.pdf.FileSpecification-) | Sets a file specification identifying a self-describing movie file. |
| [setPoster](#setPoster-boolean-) | Gets or sets a flag or stream specifying whether and how a poster image representing the movie shall be displayed. If true, the poster image shall be retrieved from the movie file; if it is false, no poster shall be displayed. |
| [setRotate](#setRotate-int-) | Gets or sets the number of degrees by which the movie shall be rotated clockwise relative to the page. The value shall be a multiple of 90. |
| [setTitle](#setTitle-java.lang.String-) | Sets the title of the movie annotation. |

### MovieAnnotation {#MovieAnnotation-com.aspose.pdf.IDocument-java.lang.String-}
Constructor for using with Generator.

### MovieAnnotation {#MovieAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-}
Creates new Sound annotation on the specified page.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepts visitor object to process the annotation.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Gets type of annotation.

**Returns:**
AnnotationType element as int value @see AnnotationType

### getAspect {#getAspect--}
```
public final Point getAspect()
```

Gets or sets the width and height of the movie's bounding box, in pixels.

**Returns:**
Point instance

### getFile {#getFile--}
```
public FileSpecification getFile()
```

Gets a file specification identifying a self-describing movie file.

**Returns:**
FileSpecification value

### getPoster {#getPoster--}
```
public final boolean getPoster()
```

Gets or sets a flag or stream specifying whether and how a poster image representing the movie shall be displayed. If true, the poster image shall be retrieved from the movie file; if it is false, no poster shall be displayed.

**Returns:**
boolean value

### getRotate {#getRotate--}
```
public final int getRotate()
```

Gets or sets the number of degrees by which the movie shall be rotated clockwise relative to the page. The value shall be a multiple of 90.

**Returns:**
int value

### getTitle {#getTitle--}
```
public String getTitle()
```

Gets the title of the movie annotation.

**Returns:**
String value

### setAspect {#setAspect-com.aspose.pdf.Point-}
Gets or sets the width and height of the movie's bounding box, in pixels.

### setFile {#setFile-com.aspose.pdf.FileSpecification-}
Sets a file specification identifying a self-describing movie file.

### setPoster {#setPoster-boolean-}
```
public final void setPoster(boolean value)
```

Gets or sets a flag or stream specifying whether and how a poster image representing the movie shall be displayed. If true, the poster image shall be retrieved from the movie file; if it is false, no poster shall be displayed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setRotate {#setRotate-int-}
```
public final void setRotate(int value)
```

Gets or sets the number of degrees by which the movie shall be rotated clockwise relative to the page. The value shall be a multiple of 90.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setTitle {#setTitle-java.lang.String-}
Sets the title of the movie annotation.
