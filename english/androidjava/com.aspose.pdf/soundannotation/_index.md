---
title: SoundAnnotation
second_title: Aspose.PDF for Java API Reference
description: Represents a sound annotation that contains sound recorded from the computerufffds microphone or imported from a file.
type: docs
weight: 265
url: /java/com.aspose.pdf/soundannotation/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.MarkupAnnotation](../../com.aspose.pdf/markupannotation)
```
public final class SoundAnnotation extends MarkupAnnotation
```

Represents a sound annotation that contains sound recorded from the computer\\ufffds microphone or imported from a file.
## Constructors

| Constructor | Description |
| --- | --- |
| [SoundAnnotation(Page page, Rectangle rect, String soundFile)](#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-) | Creates new Sound annotation on the specified page. |
## Methods

| Method | Description |
| --- | --- |
| [writeXfdf(System.Xml.XmlWriter writer)](#writeXfdf-com.aspose.ms.System.Xml.XmlWriter-) |  |
| [getIcon()](#getIcon--) | Gets an icon to be used in displaying the annotation. |
| [setIcon(int value)](#setIcon-int-) | Sets an icon to be used in displaying the annotation. |
| [getSoundData()](#getSoundData--) | Gets a sound object defining the sound to be played when the annotation is activated. |
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


Gets an icon to be used in displaying the annotation.

**Returns:**
int
### setIcon(int value) {#setIcon-int-}
```
public void setIcon(int value)
```


Sets an icon to be used in displaying the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSoundData() {#getSoundData--}
```
public SoundData getSoundData()
```


Gets a sound object defining the sound to be played when the annotation is activated.

**Returns:**
[SoundData](../../com.aspose.pdf/sounddata)
### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Accepts visitor object to process the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | Visitor object. |

