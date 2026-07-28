---
title: "PDF3DAnnotation"
linktitle: "PDF3DAnnotation"
second_title: "Aspose.PDF för Java API-referens"
description: "Klassen PDF3DAnnotation. Denna klass kan inte ärvas. @see Annotation"
type: docs
weight: 3560
url: /sv/java/com.aspose.pdf/pdf3dannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PDF3DAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PDF3DAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PDF3DAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class PDF3DAnnotation extends Annotation
```

Klassen PDF3DAnnotation. Denna klass kan inte ärvas. @see Annotation

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PDF3DAnnotation](#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-) | Initierar en ny instans av klassen {@code PDF3DAnnotation}. |
| [PDF3DAnnotation](#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-com.aspose.pdf.PDF3DActivation-) | Initierar en ny instans av klassen {@code PDF3DAnnotation}. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepterar besökare för annoteringsbearbetning. |
| [clearImagePreview](#clearImagePreview--) | Rensar bildförhandsvisningen. |
| [getAnnotationType](#getAnnotationType--) | Hämtar typ av annotation. Värde: Typen av annotationen. |
| [getContent](#getContent--) | Hämtar eller anger innehållet. Värde: Innehållet. |
| [getImagePreview](#getImagePreview--) | Hämtar bildförhandsvisningen. |
| [getLightingScheme](#getLightingScheme--) | Hämtar belysningsschemat. Värde: Belysningsschemat. |
| [getPdf3DArtwork](#getPdf3DArtwork--) | Hämtar 3D-konstverket. Värde: PDF3 d-konstverket. |
| [getRenderMode](#getRenderMode--) | Hämtar renderingsläget. Värde: Renderingsläget. |
| [getViewArray](#getViewArray--) | Hämtar vyarrayen. Värde: Vyarrayen. |
| [setContent](#setContent-com.aspose.pdf.PDF3DContent-) | Hämtar eller anger innehållet. Värde: Innehållet. |
| [setDefaultViewIndex](#setDefaultViewIndex-int-) | Ställer in indexet för standardvyn. |
| [setImagePreview](#setImagePreview-java.io.InputStream-) | Ställer in bildförhandsvisningen. |
| [setImagePreview](#setImagePreview-java.lang.String-) | Ställer in bildförhandsvisningen. |

### PDF3DAnnotation {#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-}
Initierar en ny instans av klassen {@code PDF3DAnnotation}.

### PDF3DAnnotation {#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-com.aspose.pdf.PDF3DActivation-}
Initierar en ny instans av klassen {@code PDF3DAnnotation}.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepterar besökare för annoteringsbearbetning.

### clearImagePreview {#clearImagePreview--}
```
public void clearImagePreview()
```

Rensar bildförhandsvisningen.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Hämtar typ av annotation. Värde: Typen av annotationen.

**Returns:**
int‑värde

### getContent {#getContent--}
```
public PDF3DContent getContent()
```

Hämtar eller anger innehållet. Värde: Innehållet.

**Returns:**
PDF3DContent-objekt

### getImagePreview {#getImagePreview--}
```
public InputStream getImagePreview()
```

Hämtar bildförhandsvisningen.

**Returns:**
Bildförhandsvisning som ström.

### getLightingScheme {#getLightingScheme--}
```
public PDF3DLightingScheme getLightingScheme()
```

Hämtar belysningsschemat. Värde: Belysningsschemat.

**Returns:**
PDF3DLightingScheme-objekt

### getPdf3DArtwork {#getPdf3DArtwork--}
```
public PDF3DArtwork getPdf3DArtwork()
```

Hämtar 3D-konstverket. Värde: PDF3 d-konstverket.

**Returns:**
PDF3DArtwork objekt

### getRenderMode {#getRenderMode--}
```
public PDF3DRenderMode getRenderMode()
```

Hämtar renderingsläget. Värde: Renderingsläget.

**Returns:**
PDF3DRenderMode objekt

### getViewArray {#getViewArray--}
```
public PDF3DViewArray getViewArray()
```

Hämtar vyarrayen. Värde: Vyarrayen.

**Returns:**
PDF3DViewArray objekt

### setContent {#setContent-com.aspose.pdf.PDF3DContent-}
Hämtar eller anger innehållet. Värde: Innehållet.

### setDefaultViewIndex {#setDefaultViewIndex-int-}
```
public void setDefaultViewIndex(int index)
```

Ställer in indexet för standardvyn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | Det standardvyindexet. |

### setImagePreview {#setImagePreview-java.io.InputStream-}
Ställer in bildförhandsvisningen.

### setImagePreview {#setImagePreview-java.lang.String-}
Ställer in bildförhandsvisningen.
