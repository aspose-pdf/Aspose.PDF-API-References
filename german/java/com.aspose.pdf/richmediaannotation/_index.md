---
title: "RichMediaAnnotation"
linktitle: "RichMediaAnnotation"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse beschreibt RichMediaAnnotation, die das Einbetten von Video-/Audio-Daten in ein PDF-Dokument ermöglicht."
type: docs
weight: 4260
url: /de/java/com.aspose.pdf/richmediaannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.RichMediaAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.RichMediaAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.RichMediaAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class RichMediaAnnotation extends Annotation
```

Klasse beschreibt RichMediaAnnotation, die das Einbetten von Video-/Audio-Daten in ein PDF-Dokument ermöglicht.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [RichMediaAnnotation](#RichMediaAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Initialisiert RichMediaAnnotation. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Akzeptiert Besucher für diese Annotation. |
| [addCustomData](#addCustomData-java.lang.String-java.io.InputStream-) | Fügt benutzerdefinierte benannte Daten hinzu (zum Beispiel für Flash‑Skript erforderlich). |
| [getActivateOn](#getActivateOn--) | Ereignis, das die Anwendung aktiviert. |
| [getAnnotationType](#getAnnotationType--) | Liefert den Typ der Annotation. |
| [getContent](#getContent--) | Daten des Rich‑Media-Inhalts. |
| [getCustomFlashVariables](#getCustomFlashVariables--) | Setzt oder liest Flash‑Variablen, die an den Player übergeben werden. |
| [getCustomPlayer](#getCustomPlayer--) | Setzt oder liest benutzerdefinierten Flash‑Player zum Abspielen von Video‑/Audiodaten. |
| [getType](#getType--) | Liest oder setzt den Inhaltstyp. Mögliche Werte: Audio, Video. |
| [setActivateOn](#setActivateOn-int-) | Ereignis, das die Anwendung aktiviert. |
| [setContent](#setContent-java.lang.String-java.io.InputStream-) | Setzt Inhaltsstream. |
| [setCustomFlashVariables](#setCustomFlashVariables-java.lang.String-) | Setzt oder liest Flash‑Variablen, die an den Player übergeben werden. |
| [setCustomPlayer](#setCustomPlayer-java.io.InputStream-) | Setzt oder liest benutzerdefinierten Flash‑Player zum Abspielen von Video‑/Audiodaten. |
| [setPoster](#setPoster-java.io.InputStream-) | Setzt Poster der Annotation. |
| [setType](#setType-int-) | Liest oder setzt den Inhaltstyp. Mögliche Werte: Audio, Video. |
| [update](#update--) | Aktualisiert Daten mit angegebenen Parametern. |

### RichMediaAnnotation {#RichMediaAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Initialisiert RichMediaAnnotation.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Akzeptiert Besucher für diese Annotation.

### addCustomData {#addCustomData-java.lang.String-java.io.InputStream-}
Fügt benutzerdefinierte benannte Daten hinzu (zum Beispiel für Flash‑Skript erforderlich).

### getActivateOn {#getActivateOn--}
```
public int getActivateOn()
```

Ereignis, das die Anwendung aktiviert.

**Returns:**
ActivationEvent Element

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Liefert den Typ der Annotation.

**Returns:**
AnnotationType-Element @see AnnotationType

### getContent {#getContent--}
```
public InputStream getContent()
```

Daten des Rich‑Media-Inhalts.

**Returns:**
InputStream‑Objekt

### getCustomFlashVariables {#getCustomFlashVariables--}
```
public String getCustomFlashVariables()
```

Setzt oder liest Flash‑Variablen, die an den Player übergeben werden.

**Returns:**
String-Objekt

### getCustomPlayer {#getCustomPlayer--}
```
public InputStream getCustomPlayer()
```

Setzt oder liest benutzerdefinierten Flash‑Player zum Abspielen von Video‑/Audiodaten.

**Returns:**
InputStream‑Objekt

### getType {#getType--}
```
public int getType()
```

Liest oder setzt den Inhaltstyp. Mögliche Werte: Audio, Video.

**Returns:**
ContentType Wert @see ContentType

### setActivateOn {#setActivateOn-int-}
```
public void setActivateOn(int value)
```

Ereignis, das die Anwendung aktiviert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | ActivationEvent Element |

### setContent {#setContent-java.lang.String-java.io.InputStream-}
Setzt Inhaltsstream.

### setCustomFlashVariables {#setCustomFlashVariables-java.lang.String-}
Setzt oder liest Flash‑Variablen, die an den Player übergeben werden.

### setCustomPlayer {#setCustomPlayer-java.io.InputStream-}
Setzt oder liest benutzerdefinierten Flash‑Player zum Abspielen von Video‑/Audiodaten.

### setPoster {#setPoster-java.io.InputStream-}
Setzt Poster der Annotation.

### setType {#setType-int-}
```
public void setType(int value)
```

Liest oder setzt den Inhaltstyp. Mögliche Werte: Audio, Video.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | ContentType Element |

### update {#update--}
```
public void update()
```

Aktualisiert Daten mit angegebenen Parametern.
