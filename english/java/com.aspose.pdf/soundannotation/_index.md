---
title: SoundAnnotation
second_title: Aspose.PDF for Java API Reference
description: Represents a sound annotation that contains sound recorded from the computers microphone or imported from a file.
type: docs
weight: 326
url: /java/com.aspose.pdf/soundannotation/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.MarkupAnnotation](../../com.aspose.pdf/markupannotation)
```
public final class SoundAnnotation extends MarkupAnnotation
```

Represents a sound annotation that contains sound recorded from the computer's microphone or imported from a file.
## Constructors

| Constructor | Description |
| --- | --- |
| [SoundAnnotation(Page page, Rectangle rect, String soundFile)](#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-) | Creates new Sound annotation on the specified page. |
| [SoundAnnotation(Page page, Rectangle rect, String soundFile, SoundSampleData soundSampleData)](#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-com.aspose.pdf.SoundSampleData-) | Creates new Sound annotation on the specified page. |
## Methods

| Method | Description |
| --- | --- |
| [getIcon()](#getIcon--) | Gets an icon to be used in displaying the annotation. |
| [setIcon(int value)](#setIcon-int-) | Sets an icon to be used in displaying the annotation. |
| [getSoundData()](#getSoundData--) | Gets a sound object defining the sound to be played when the annotation is activated. |
| [getAnnotationType()](#getAnnotationType--) | Gets type of annotation. |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor object to process the annotation. |
### SoundAnnotation(Page page, Rectangle rect, String soundFile) {#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-}
```
public SoundAnnotation(Page page, Rectangle rect, String soundFile)
```


Creates new Sound annotation on the specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The document's page where annotation should be created. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | The annotation rectangle, defining the location of the annotation on the page. |
| soundFile | java.lang.String | A sound file defining the sound to be played when the annotation is activated. |

### SoundAnnotation(Page page, Rectangle rect, String soundFile, SoundSampleData soundSampleData) {#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-com.aspose.pdf.SoundSampleData-}
```
public SoundAnnotation(Page page, Rectangle rect, String soundFile, SoundSampleData soundSampleData)
```


Creates new Sound annotation on the specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The document's page where annotation should be created. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | The annotation rectangle, defining the location of the annotation on the page. |
| soundFile | java.lang.String | A sound file defining the sound to be played when the annotation is activated. |
| soundSampleData | [SoundSampleData](../../com.aspose.pdf/soundsampledata) | A sound sample data contains extra of sound parameters such as sampling rate, bits per sample and so on. |

### getIcon() {#getIcon--}
```
public int getIcon()
```


Gets an icon to be used in displaying the annotation.

**Returns:**
int - SoundIcon value
### setIcon(int value) {#setIcon-int-}
```
public void setIcon(int value)
```


Sets an icon to be used in displaying the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | SoundIcon value |

### getSoundData() {#getSoundData--}
```
public SoundData getSoundData()
```


Gets a sound object defining the sound to be played when the annotation is activated.

**Returns:**
[SoundData](../../com.aspose.pdf/sounddata) - SoundData value
### getAnnotationType() {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```


Gets type of annotation.

**Returns:**
[AnnotationType](../../com.aspose.pdf/annotationtype) - AnnotationType value
### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Accepts visitor object to process the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | Visitor object. |

