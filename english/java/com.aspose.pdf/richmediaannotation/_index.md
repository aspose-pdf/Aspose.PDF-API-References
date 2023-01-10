---
title: RichMediaAnnotation
second_title: Aspose.PDF for Java API Reference
description: Class describes RichMediaAnnotation which allows embed video/audio data into PDF document.
type: docs
weight: 313
url: /java/com.aspose.pdf/richmediaannotation/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation)
```
public class RichMediaAnnotation extends Annotation
```

Class describes RichMediaAnnotation which allows embed video/audio data into PDF document.
## Constructors

| Constructor | Description |
| --- | --- |
| [RichMediaAnnotation(Page page, Rectangle rect)](#RichMediaAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Initializes RichMediaAnnotation. |
## Methods

| Method | Description |
| --- | --- |
| [getAnnotationType()](#getAnnotationType--) | Gets type of annotation. |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor for this annotation. |
| [getCustomPlayer()](#getCustomPlayer--) | Sets or gets custom flash player to play video/audio data. |
| [setCustomPlayer(InputStream value)](#setCustomPlayer-java.io.InputStream-) | Sets or gets custom flash player to play video/audio data. |
| [getCustomFlashVariables()](#getCustomFlashVariables--) | Sets or gets flash variables which passed to player. |
| [setCustomFlashVariables(String value)](#setCustomFlashVariables-java.lang.String-) | Sets or gets flash variables which passed to player. |
| [addCustomData(String name, InputStream data)](#addCustomData-java.lang.String-java.io.InputStream-) | Add custom named data (for example required for flash script). |
| [setContent(String fileName, InputStream audio)](#setContent-java.lang.String-java.io.InputStream-) | Set content stream. |
| [getContent()](#getContent--) | Data of the Rich Media content. |
| [getType()](#getType--) | Gets or sets type of content. |
| [setType(int value)](#setType-int-) | Gets or sets type of content. |
| [getActivateOn()](#getActivateOn--) | Event which activates application. |
| [setActivateOn(int value)](#setActivateOn-int-) | Event which activates application. |
| [setPoster(InputStream imageStream)](#setPoster-java.io.InputStream-) | Set poster of the annotation. |
| [update()](#update--) | Updates data with specified parameters. |
### RichMediaAnnotation(Page page, Rectangle rect) {#RichMediaAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public RichMediaAnnotation(Page page, Rectangle rect)
```


Initializes RichMediaAnnotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Page where object being created. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle coordinates. |

### getAnnotationType() {#getAnnotationType--}
```
public int getAnnotationType()
```


Gets type of annotation.

**Returns:**
int - AnnotationType element
### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Accepts visitor for this annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | Visitor instance. |

### getCustomPlayer() {#getCustomPlayer--}
```
public InputStream getCustomPlayer()
```


Sets or gets custom flash player to play video/audio data.

**Returns:**
java.io.InputStream - InputStream object
### setCustomPlayer(InputStream value) {#setCustomPlayer-java.io.InputStream-}
```
public void setCustomPlayer(InputStream value)
```


Sets or gets custom flash player to play video/audio data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.InputStream | InputStream object |

### getCustomFlashVariables() {#getCustomFlashVariables--}
```
public String getCustomFlashVariables()
```


Sets or gets flash variables which passed to player.

**Returns:**
java.lang.String - String object
### setCustomFlashVariables(String value) {#setCustomFlashVariables-java.lang.String-}
```
public void setCustomFlashVariables(String value)
```


Sets or gets flash variables which passed to player.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String object |

### addCustomData(String name, InputStream data) {#addCustomData-java.lang.String-java.io.InputStream-}
```
public void addCustomData(String name, InputStream data)
```


Add custom named data (for example required for flash script).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the data. |
| data | java.io.InputStream | Data. |

### setContent(String fileName, InputStream audio) {#setContent-java.lang.String-java.io.InputStream-}
```
public void setContent(String fileName, InputStream audio)
```


Set content stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Name of the stream. |
| audio | java.io.InputStream | Data stream. |

### getContent() {#getContent--}
```
public InputStream getContent()
```


Data of the Rich Media content.

**Returns:**
java.io.InputStream - InputStream object
### getType() {#getType--}
```
public int getType()
```


Gets or sets type of content. Possible values: Audio, Video.

**Returns:**
int - ContentType value
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Gets or sets type of content. Possible values: Audio, Video.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ContentType element |

### getActivateOn() {#getActivateOn--}
```
public int getActivateOn()
```


Event which activates application.

**Returns:**
int - ActivationEvent element
### setActivateOn(int value) {#setActivateOn-int-}
```
public void setActivateOn(int value)
```


Event which activates application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ActivationEvent element |

### setPoster(InputStream imageStream) {#setPoster-java.io.InputStream-}
```
public void setPoster(InputStream imageStream)
```


Set poster of the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | java.io.InputStream | Stream containing poster image. |

### update() {#update--}
```
public void update()
```


Updates data with specified parameters.

