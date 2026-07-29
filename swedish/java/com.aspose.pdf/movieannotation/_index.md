---
title: "MovieAnnotation"
linktitle: "MovieAnnotation"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en filmannotering som innehåller animerad grafik och ljud som ska visas på datorskärmen och spelas upp via högtalarna. När annoteringen aktiveras, den."
type: docs
weight: 3090
url: /sv/java/com.aspose.pdf/movieannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MovieAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MovieAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MovieAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class MovieAnnotation extends Annotation implements com.aspose.pdf.engine.ITitledAnnotation
```

Representerar en filmanteckning som innehåller animerad grafik och ljud som ska visas på datorskärmen och spelas upp via högtalarna. När anteckningen aktiveras spelas filmen.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [MovieAnnotation](#MovieAnnotation-com.aspose.pdf.IDocument-java.lang.String-) | Konstruktor för användning med Generator. |
| [MovieAnnotation](#MovieAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-) | Skapar ny Sound-annotation på den angivna sidan. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepterar besökarobjekt för att bearbeta annotationen. |
| [getAnnotationType](#getAnnotationType--) | Hämtar typ av annotering. |
| [getAspect](#getAspect--) | Hämtar eller anger bredden och höjden på filmens avgränsningsruta, i pixlar. |
| [getFile](#getFile--) | Hämtar en filspecificering som identifierar en självbeskrivande filmfil. |
| [getPoster](#getPoster--) | Hämtar eller anger en flagga eller ström som specificerar om och hur en posterbild som representerar filmen ska visas. Om true, hämtas posterbilden från filmfilen; om false visas ingen poster. |
| [getRotate](#getRotate--) | Hämtar eller anger antalet grader som filmen ska roteras medurs i förhållande till sidan. Värdet ska vara en multipel av 90. |
| [getTitle](#getTitle--) | Hämtar titeln på filmannoteringen. |
| [setAspect](#setAspect-com.aspose.pdf.Point-) | Hämtar eller anger bredden och höjden på filmens avgränsningsruta, i pixlar. |
| [setFile](#setFile-com.aspose.pdf.FileSpecification-) | Anger en filspecificering som identifierar en självbeskrivande filmfil. |
| [setPoster](#setPoster-boolean-) | Hämtar eller anger en flagga eller ström som specificerar om och hur en posterbild som representerar filmen ska visas. Om true, hämtas posterbilden från filmfilen; om false visas ingen poster. |
| [setRotate](#setRotate-int-) | Hämtar eller anger antalet grader som filmen ska roteras medurs i förhållande till sidan. Värdet ska vara en multipel av 90. |
| [setTitle](#setTitle-java.lang.String-) | Anger titeln på filmannoteringen. |

### MovieAnnotation {#MovieAnnotation-com.aspose.pdf.IDocument-java.lang.String-}
Konstruktor för användning med Generator.

### MovieAnnotation {#MovieAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-}
Skapar ny Sound-annotation på den angivna sidan.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepterar besökarobjekt för att bearbeta annotationen.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Hämtar typ av annotering.

**Returns:**
AnnotationType-element som heltalsvärde @see AnnotationType

### getAspect {#getAspect--}
```
public final Point getAspect()
```

Hämtar eller anger bredden och höjden på filmens avgränsningsruta, i pixlar.

**Returns:**
Point-instans

### getFile {#getFile--}
```
public FileSpecification getFile()
```

Hämtar en filspecificering som identifierar en självbeskrivande filmfil.

**Returns:**
FileSpecification-värde

### getPoster {#getPoster--}
```
public final boolean getPoster()
```

Hämtar eller anger en flagga eller ström som specificerar om och hur en posterbild som representerar filmen ska visas. Om true, hämtas posterbilden från filmfilen; om false visas ingen poster.

**Returns:**
booleskt värde

### getRotate {#getRotate--}
```
public final int getRotate()
```

Hämtar eller anger antalet grader som filmen ska roteras medurs i förhållande till sidan. Värdet ska vara en multipel av 90.

**Returns:**
int‑värde

### getTitle {#getTitle--}
```
public String getTitle()
```

Hämtar titeln på filmannoteringen.

**Returns:**
String värde

### setAspect {#setAspect-com.aspose.pdf.Point-}
Hämtar eller anger bredden och höjden på filmens avgränsningsruta, i pixlar.

### setFile {#setFile-com.aspose.pdf.FileSpecification-}
Anger en filspecificering som identifierar en självbeskrivande filmfil.

### setPoster {#setPoster-boolean-}
```
public final void setPoster(boolean value)
```

Hämtar eller anger en flagga eller ström som specificerar om och hur en posterbild som representerar filmen ska visas. Om true, hämtas posterbilden från filmfilen; om false visas ingen poster.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setRotate {#setRotate-int-}
```
public final void setRotate(int value)
```

Hämtar eller anger antalet grader som filmen ska roteras medurs i förhållande till sidan. Värdet ska vara en multipel av 90.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setTitle {#setTitle-java.lang.String-}
Anger titeln på filmannoteringen.
