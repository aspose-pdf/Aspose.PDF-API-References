---
title: "RichMediaAnnotation"
linktitle: "RichMediaAnnotation"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass beskriver RichMediaAnnotation som möjliggör inbäddning av video-/ljuddata i PDF-dokument."
type: docs
weight: 4260
url: /sv/java/com.aspose.pdf/richmediaannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.RichMediaAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.RichMediaAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.RichMediaAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class RichMediaAnnotation extends Annotation
```

Klass beskriver RichMediaAnnotation som möjliggör inbäddning av video-/ljuddata i PDF-dokument.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [RichMediaAnnotation](#RichMediaAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Initierar RichMediaAnnotation. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepterar besökare för denna annotation. |
| [addCustomData](#addCustomData-java.lang.String-java.io.InputStream-) | Lägg till anpassad namngiven data (till exempel krävs för flash‑script). |
| [getActivateOn](#getActivateOn--) | Händelse som aktiverar applikationen. |
| [getAnnotationType](#getAnnotationType--) | Hämtar typ av annotering. |
| [getContent](#getContent--) | Data för Rich Media-innehållet. |
| [getCustomFlashVariables](#getCustomFlashVariables--) | Ställer in eller hämtar flash‑variabler som skickas till spelaren. |
| [getCustomPlayer](#getCustomPlayer--) | Ställer in eller hämtar anpassad flash‑spelare för att spela video-/ljuddata. |
| [getType](#getType--) | Hämtar eller ställer in typ av innehåll. Möjliga värden: Audio, Video. |
| [setActivateOn](#setActivateOn-int-) | Händelse som aktiverar applikationen. |
| [setContent](#setContent-java.lang.String-java.io.InputStream-) | Ange innehållsström. |
| [setCustomFlashVariables](#setCustomFlashVariables-java.lang.String-) | Ställer in eller hämtar flash‑variabler som skickas till spelaren. |
| [setCustomPlayer](#setCustomPlayer-java.io.InputStream-) | Ställer in eller hämtar anpassad flash‑spelare för att spela video-/ljuddata. |
| [setPoster](#setPoster-java.io.InputStream-) | Ange poster för annotationen. |
| [setType](#setType-int-) | Hämtar eller ställer in typ av innehåll. Möjliga värden: Audio, Video. |
| [update](#update--) | Uppdaterar data med angivna parametrar. |

### RichMediaAnnotation {#RichMediaAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Initierar RichMediaAnnotation.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepterar besökare för denna annotation.

### addCustomData {#addCustomData-java.lang.String-java.io.InputStream-}
Lägg till anpassad namngiven data (till exempel krävs för flash‑script).

### getActivateOn {#getActivateOn--}
```
public int getActivateOn()
```

Händelse som aktiverar applikationen.

**Returns:**
ActivationEvent element

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Hämtar typ av annotering.

**Returns:**
AnnotationType-element @see AnnotationType

### getContent {#getContent--}
```
public InputStream getContent()
```

Data för Rich Media-innehållet.

**Returns:**
InputStream-objekt

### getCustomFlashVariables {#getCustomFlashVariables--}
```
public String getCustomFlashVariables()
```

Ställer in eller hämtar flash‑variabler som skickas till spelaren.

**Returns:**
String-objekt

### getCustomPlayer {#getCustomPlayer--}
```
public InputStream getCustomPlayer()
```

Ställer in eller hämtar anpassad flash‑spelare för att spela video-/ljuddata.

**Returns:**
InputStream-objekt

### getType {#getType--}
```
public int getType()
```

Hämtar eller ställer in typ av innehåll. Möjliga värden: Audio, Video.

**Returns:**
ContentType värde @see ContentType

### setActivateOn {#setActivateOn-int-}
```
public void setActivateOn(int value)
```

Händelse som aktiverar applikationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | ActivationEvent element |

### setContent {#setContent-java.lang.String-java.io.InputStream-}
Ange innehållsström.

### setCustomFlashVariables {#setCustomFlashVariables-java.lang.String-}
Ställer in eller hämtar flash‑variabler som skickas till spelaren.

### setCustomPlayer {#setCustomPlayer-java.io.InputStream-}
Ställer in eller hämtar anpassad flash‑spelare för att spela video-/ljuddata.

### setPoster {#setPoster-java.io.InputStream-}
Ange poster för annotationen.

### setType {#setType-int-}
```
public void setType(int value)
```

Hämtar eller ställer in typ av innehåll. Möjliga värden: Audio, Video.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | ContentType element |

### update {#update--}
```
public void update()
```

Uppdaterar data med angivna parametrar.
