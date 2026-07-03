---
title: RichMediaAnnotation
second_title: Aspose.PDF for Java API Reference
description: Class describes RichMediaAnnotation which allows embed video/audio data into PDF document.
type: docs
weight: 4260
url: /java/com.aspose.pdf/richmediaannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.RichMediaAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.RichMediaAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.RichMediaAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class RichMediaAnnotation extends Annotation
```

Class describes RichMediaAnnotation which allows embed video/audio data into PDF document.

## Constructors

| Constructor | Description |
| --- | --- |
| [RichMediaAnnotation](#RichMediaAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Initializes RichMediaAnnotation. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor for this annotation. |
| [addCustomData](#addCustomData-java.lang.String-java.io.InputStream-) | Add custom named data (for example required for flash script). |
| [getActivateOn](#getActivateOn--) | Event which activates application. |
| [getAnnotationType](#getAnnotationType--) | Gets type of annotation. |
| [getContent](#getContent--) | Data of the Rich Media content. |
| [getCustomFlashVariables](#getCustomFlashVariables--) | Sets or gets flash variables which passed to player. |
| [getCustomPlayer](#getCustomPlayer--) | Sets or gets custom flash player to play video/audio data. |
| [getType](#getType--) | Gets or sets type of content. Possible values: Audio, Video. |
| [setActivateOn](#setActivateOn-int-) | Event which activates application. |
| [setContent](#setContent-java.lang.String-java.io.InputStream-) | Set content stream. |
| [setCustomFlashVariables](#setCustomFlashVariables-java.lang.String-) | Sets or gets flash variables which passed to player. |
| [setCustomPlayer](#setCustomPlayer-java.io.InputStream-) | Sets or gets custom flash player to play video/audio data. |
| [setPoster](#setPoster-java.io.InputStream-) | Set poster of the annotation. |
| [setType](#setType-int-) | Gets or sets type of content. Possible values: Audio, Video. |
| [update](#update--) | Updates data with specified parameters. |

### RichMediaAnnotation {#RichMediaAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Initializes RichMediaAnnotation.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepts visitor for this annotation.

### addCustomData {#addCustomData-java.lang.String-java.io.InputStream-}
Add custom named data (for example required for flash script).

### getActivateOn {#getActivateOn--}
```
public int getActivateOn()
```

Event which activates application.

**Returns:**
ActivationEvent element

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Gets type of annotation.

**Returns:**
AnnotationType element @see AnnotationType

### getContent {#getContent--}
```
public InputStream getContent()
```

Data of the Rich Media content.

**Returns:**
InputStream object

### getCustomFlashVariables {#getCustomFlashVariables--}
```
public String getCustomFlashVariables()
```

Sets or gets flash variables which passed to player.

**Returns:**
String object

### getCustomPlayer {#getCustomPlayer--}
```
public InputStream getCustomPlayer()
```

Sets or gets custom flash player to play video/audio data.

**Returns:**
InputStream object

### getType {#getType--}
```
public int getType()
```

Gets or sets type of content. Possible values: Audio, Video.

**Returns:**
ContentType value @see ContentType

### setActivateOn {#setActivateOn-int-}
```
public void setActivateOn(int value)
```

Event which activates application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | ActivationEvent element |

### setContent {#setContent-java.lang.String-java.io.InputStream-}
Set content stream.

### setCustomFlashVariables {#setCustomFlashVariables-java.lang.String-}
Sets or gets flash variables which passed to player.

### setCustomPlayer {#setCustomPlayer-java.io.InputStream-}
Sets or gets custom flash player to play video/audio data.

### setPoster {#setPoster-java.io.InputStream-}
Set poster of the annotation.

### setType {#setType-int-}
```
public void setType(int value)
```

Gets or sets type of content. Possible values: Audio, Video.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | ContentType element |

### update {#update--}
```
public void update()
```

Updates data with specified parameters.
