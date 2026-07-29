---
title: "SoundAnnotation"
linktitle: "SoundAnnotation"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en ljudannotering som innehåller ljud inspelat från datorns mikrofon eller importerat från en fil."
type: docs
weight: 4530
url: /sv/java/com.aspose.pdf/soundannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.SoundAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.SoundAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.SoundAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.SoundAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class SoundAnnotation extends MarkupAnnotation
```

Representerar en ljudannotering som innehåller ljud inspelat från datorns mikrofon eller importerat från en fil.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [SoundAnnotation](#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-) | Skapar ny Sound-annotation på den angivna sidan. |
| [SoundAnnotation](#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-com.aspose.pdf.SoundSampleData-) | Skapar ny Sound-annotation på den angivna sidan. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepterar besökarobjekt för att bearbeta annotationen. |
| [getAnnotationType](#getAnnotationType--) | Hämtar typ av annotering. |
| [getIcon](#getIcon--) | Hämtar en ikon som ska användas vid visning av annotationen. |
| [getSoundData](#getSoundData--) | Hämtar ett ljudobjekt som definierar ljudet som ska spelas när annoteringen aktiveras. |
| [setIcon](#setIcon-int-) | Ställer in en ikon som ska användas vid visning av annotationen. |

### SoundAnnotation {#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-}
Skapar ny Sound-annotation på den angivna sidan.

### SoundAnnotation {#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-com.aspose.pdf.SoundSampleData-}
Skapar ny Sound-annotation på den angivna sidan.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepterar besökarobjekt för att bearbeta annotationen.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Hämtar typ av annotering.

**Returns:**
AnnotationType värde @see AnnotationType

### getIcon {#getIcon--}
```
public int getIcon()
```

Hämtar en ikon som ska användas vid visning av annotationen.

**Returns:**
SoundIcon värde @see SoundIcon

### getSoundData {#getSoundData--}
```
public SoundData getSoundData()
```

Hämtar ett ljudobjekt som definierar ljudet som ska spelas när annoteringen aktiveras.

**Returns:**
SoundData värde

### setIcon {#setIcon-int-}
```
public void setIcon(int value)
```

Ställer in en ikon som ska användas vid visning av annotationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | SoundIcon värde @see SoundIcon |
