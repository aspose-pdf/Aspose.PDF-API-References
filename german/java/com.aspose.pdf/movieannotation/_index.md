---
title: "MovieAnnotation"
linktitle: "MovieAnnotation"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Film-Anmerkung dar, die animierte Grafiken und Ton enthält, die auf dem Computerbildschirm und über die Lautsprecher wiedergegeben werden. Wenn die Anmerkung aktiviert wird, die."
type: docs
weight: 3090
url: /de/java/com.aspose.pdf/movieannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MovieAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MovieAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MovieAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class MovieAnnotation extends Annotation implements com.aspose.pdf.engine.ITitledAnnotation
```

Repräsentiert eine Filmannotation, die animierte Grafiken und Ton enthält, die auf dem Computerbildschirm und über die Lautsprecher wiedergegeben werden. Wenn die Annotation aktiviert wird, wird der Film abgespielt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MovieAnnotation](#MovieAnnotation-com.aspose.pdf.IDocument-java.lang.String-) | Konstruktor zur Verwendung mit Generator. |
| [MovieAnnotation](#MovieAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-) | Erstellt eine neue Sound-Anmerkung auf der angegebenen Seite. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Akzeptiert ein Besucherobjekt, um die Annotation zu verarbeiten. |
| [getAnnotationType](#getAnnotationType--) | Liefert den Typ der Annotation. |
| [getAspect](#getAspect--) | Ruft die Breite und Höhe des Begrenzungsrahmens des Films ab oder legt sie fest, in Pixel. |
| [getFile](#getFile--) | Ruft eine Dateispezifikation ab, die eine selbsterklärende Filmdatei identifiziert. |
| [getPoster](#getPoster--) | Ruft ein Flag oder einen Stream ab bzw. legt ihn fest, der angibt, ob und wie ein Posterbild, das den Film darstellt, angezeigt werden soll. Wenn true, wird das Posterbild aus der Filmdatei abgerufen; wenn false, wird kein Poster angezeigt. |
| [getRotate](#getRotate--) | Ruft die Anzahl der Grad ab bzw. legt sie fest, um die der Film im Uhrzeigersinn relativ zur Seite gedreht wird. Der Wert muss ein Vielfaches von 90 sein. |
| [getTitle](#getTitle--) | Ruft den Titel der Film-Anmerkung ab. |
| [setAspect](#setAspect-com.aspose.pdf.Point-) | Ruft die Breite und Höhe des Begrenzungsrahmens des Films ab oder legt sie fest, in Pixel. |
| [setFile](#setFile-com.aspose.pdf.FileSpecification-) | Legt eine Dateispezifikation fest, die eine selbsterklärende Filmdatei identifiziert. |
| [setPoster](#setPoster-boolean-) | Ruft ein Flag oder einen Stream ab bzw. legt ihn fest, der angibt, ob und wie ein Posterbild, das den Film darstellt, angezeigt werden soll. Wenn true, wird das Posterbild aus der Filmdatei abgerufen; wenn false, wird kein Poster angezeigt. |
| [setRotate](#setRotate-int-) | Ruft die Anzahl der Grad ab bzw. legt sie fest, um die der Film im Uhrzeigersinn relativ zur Seite gedreht wird. Der Wert muss ein Vielfaches von 90 sein. |
| [setTitle](#setTitle-java.lang.String-) | Legt den Titel der Film-Anmerkung fest. |

### MovieAnnotation {#MovieAnnotation-com.aspose.pdf.IDocument-java.lang.String-}
Konstruktor zur Verwendung mit Generator.

### MovieAnnotation {#MovieAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-}
Erstellt eine neue Sound-Anmerkung auf der angegebenen Seite.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Akzeptiert ein Besucherobjekt, um die Annotation zu verarbeiten.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Liefert den Typ der Annotation.

**Returns:**
AnnotationType-Element als int-Wert @see AnnotationType

### getAspect {#getAspect--}
```
public final Point getAspect()
```

Ruft die Breite und Höhe des Begrenzungsrahmens des Films ab oder legt sie fest, in Pixel.

**Returns:**
Point-Instanz

### getFile {#getFile--}
```
public FileSpecification getFile()
```

Ruft eine Dateispezifikation ab, die eine selbsterklärende Filmdatei identifiziert.

**Returns:**
FileSpecification-Wert

### getPoster {#getPoster--}
```
public final boolean getPoster()
```

Ruft ein Flag oder einen Stream ab bzw. legt ihn fest, der angibt, ob und wie ein Posterbild, das den Film darstellt, angezeigt werden soll. Wenn true, wird das Posterbild aus der Filmdatei abgerufen; wenn false, wird kein Poster angezeigt.

**Returns:**
boolescher Wert

### getRotate {#getRotate--}
```
public final int getRotate()
```

Ruft die Anzahl der Grad ab bzw. legt sie fest, um die der Film im Uhrzeigersinn relativ zur Seite gedreht wird. Der Wert muss ein Vielfaches von 90 sein.

**Returns:**
int-Wert

### getTitle {#getTitle--}
```
public String getTitle()
```

Ruft den Titel der Film-Anmerkung ab.

**Returns:**
String Wert

### setAspect {#setAspect-com.aspose.pdf.Point-}
Ruft die Breite und Höhe des Begrenzungsrahmens des Films ab oder legt sie fest, in Pixel.

### setFile {#setFile-com.aspose.pdf.FileSpecification-}
Legt eine Dateispezifikation fest, die eine selbsterklärende Filmdatei identifiziert.

### setPoster {#setPoster-boolean-}
```
public final void setPoster(boolean value)
```

Ruft ein Flag oder einen Stream ab bzw. legt ihn fest, der angibt, ob und wie ein Posterbild, das den Film darstellt, angezeigt werden soll. Wenn true, wird das Posterbild aus der Filmdatei abgerufen; wenn false, wird kein Poster angezeigt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setRotate {#setRotate-int-}
```
public final void setRotate(int value)
```

Ruft die Anzahl der Grad ab bzw. legt sie fest, um die der Film im Uhrzeigersinn relativ zur Seite gedreht wird. Der Wert muss ein Vielfaches von 90 sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setTitle {#setTitle-java.lang.String-}
Legt den Titel der Film-Anmerkung fest.
