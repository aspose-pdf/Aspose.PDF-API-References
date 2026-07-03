---
title: SoundAnnotation
linktitle: SoundAnnotation
second_title: Aspose.PDF for Java API Reference
description: Represents a sound annotation that contains sound recorded from the computer's microphone or imported from a file.
type: docs
weight: 4530
url: /java/com.aspose.pdf/soundannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.SoundAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.SoundAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.SoundAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.SoundAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class SoundAnnotation extends MarkupAnnotation
```

Represents a sound annotation that contains sound recorded from the computer's microphone or imported from a file.

## Constructors

| Constructor | Description |
| --- | --- |
| [SoundAnnotation](#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-) | Creates new Sound annotation on the specified page. |
| [SoundAnnotation](#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-com.aspose.pdf.SoundSampleData-) | Creates new Sound annotation on the specified page. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor object to process the annotation. |
| [getAnnotationType](#getAnnotationType--) | Gets type of annotation. |
| [getIcon](#getIcon--) | Gets an icon to be used in displaying the annotation. |
| [getSoundData](#getSoundData--) | Gets a sound object defining the sound to be played when the annotation is activated. |
| [setIcon](#setIcon-int-) | Sets an icon to be used in displaying the annotation. |

### SoundAnnotation {#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-}
Creates new Sound annotation on the specified page.

### SoundAnnotation {#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-com.aspose.pdf.SoundSampleData-}
Creates new Sound annotation on the specified page.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepts visitor object to process the annotation.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Gets type of annotation.

**Returns:**
AnnotationType value @see AnnotationType

### getIcon {#getIcon--}
```
public int getIcon()
```

Gets an icon to be used in displaying the annotation.

**Returns:**
SoundIcon value @see SoundIcon

### getSoundData {#getSoundData--}
```
public SoundData getSoundData()
```

Gets a sound object defining the sound to be played when the annotation is activated.

**Returns:**
SoundData value

### setIcon {#setIcon-int-}
```
public void setIcon(int value)
```

Sets an icon to be used in displaying the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | SoundIcon value @see SoundIcon |
