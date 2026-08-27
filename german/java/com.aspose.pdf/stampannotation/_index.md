---
title: "StampAnnotation"
linktitle: "StampAnnotation"
second_title: "Aspose.PDF für Java API-Referenz"
description: "<p> Stellt eine Gummistempel-Anmerkung dar. Dieser Anmerkungstyp zeigt Text oder Grafiken an, die so aussehen sollen, als wären sie mit einem Gummistempel auf die Seite gestempelt worden. </p> <hr>."
type: docs
weight: 4630
url: /de/java/com.aspose.pdf/stampannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.StampAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.StampAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.StampAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.StampAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class StampAnnotation extends MarkupAnnotation
```

<p> Stellt die Gummistempel-Anmerkung dar. Dieser Anmerkungstyp zeigt Text oder Grafiken an, die so aussehen sollen, als wären sie mit einem Gummistempel auf die Seite gestempelt worden. </p> <hr> <pre> Das nächste Code‑Snippet demonstriert, wie man 2 Stempel zur ersten PDF‑Dokumentenseite hinzufügt. Das Eingabedokument stammt aus inFile und Änderungen werden in outFile gespeichert. Der erste Stempel hat das Symbol NotForPublicRelease und der zweite verwendet das Bild aus rubber.jpg. Document document = new Document(inFile); StampAnnotation stamp1 = new StampAnnotation(StampIcon.NotForPublicRelease); stamp1.setRect ( new Rectangle(100, 100, 120, 120)) document.getPages().get(1).getAnnotations().add(stamp1); StampAnnotation stamp2 = new StampAnnotation(new FileStream(\"rubber.jpg\", FileMode.Open)); stamp2.setRect ( new Rectangle(200, 200, 220, 220)) document.getPages().get(1).getAnnotations().add(stamp2); document.save(outFile); </pre>

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [StampAnnotation](#StampAnnotation-com.aspose.pdf.IDocument-) | Konstruktor |
| [StampAnnotation](#StampAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Erstellt eine neue Stempel-Anmerkung auf der angegebenen Seite. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Akzeptiert {@code AnnotationSelector}-Besucher beim Durchsuchen der Anmerkungssammlung. |
| [clear](#clear--) | Statische Instanzen löschen |
| [getAnnotationType](#getAnnotationType--) | Liefert den Typ der Annotation. |
| [getIcon](#getIcon--) | Ruft das Symbol für den Gummistempel ab. |
| [getImage](#getImage--) | Ruft das Bild der Anmerkung ab. |
| [setBase64SVGImage](#setBase64SVGImage-java.lang.String-) | Setzt das SVG-Bild der Anmerkung als Base64‑Zeichenkette. |
| [setIcon](#setIcon-com.aspose.pdf.StampIcon-) | Setzt das Symbol für den Gummistempel. |
| [setImage](#setImage-java.io.InputStream-) | Setzt das Bild der Anmerkung. |

### StampAnnotation {#StampAnnotation-com.aspose.pdf.IDocument-}
Konstruktor

### StampAnnotation {#StampAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Erstellt eine neue Stempel-Anmerkung auf der angegebenen Seite.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Akzeptiert {@code AnnotationSelector}-Besucher beim Durchsuchen der Anmerkungssammlung.

### clear {#clear--}
```
public static void clear()
```

Statische Instanzen löschen

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Liefert den Typ der Annotation.

**Returns:**
AnnotationType-Element @see AnnotationType

### getIcon {#getIcon--}
```
public StampIcon getIcon()
```

Ruft das Symbol für den Gummistempel ab.

**Returns:**
StampIcon‑Wert

### getImage {#getImage--}
```
public InputStream getImage()
```

Ruft das Bild der Anmerkung ab.

**Returns:**
InputStream‑Objekt

### setBase64SVGImage {#setBase64SVGImage-java.lang.String-}
Setzt das SVG-Bild der Anmerkung als Base64‑Zeichenkette.

### setIcon {#setIcon-com.aspose.pdf.StampIcon-}
Setzt das Symbol für den Gummistempel.

### setImage {#setImage-java.io.InputStream-}
Setzt das Bild der Anmerkung.
