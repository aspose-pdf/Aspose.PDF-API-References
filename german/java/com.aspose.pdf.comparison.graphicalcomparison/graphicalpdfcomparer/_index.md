---
title: "GraphicalPdfComparer"
linktitle: "GraphicalPdfComparer"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Klasse zum grafischen Vergleich von PDF-Dokumenten dar. Sie sollte verwendet werden, um kleine Änderungen, hauptsächlich grafischer Art, zu suchen. Für den Vergleich von Textinhaltsänderungen verwenden Sie andere."
type: docs
weight: 10
url: /de/java/com.aspose.pdf.comparison.graphicalcomparison/graphicalpdfcomparer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.graphicalcomparison.GraphicalPdfComparer

```
public class GraphicalPdfComparer extends Object
```

Stellt eine Klasse zum grafischen Vergleich von PDF-Dokumenten bereit. Sie sollte verwendet werden, um kleine Änderungen, hauptsächlich grafischer Art, zu suchen. Zum Vergleich von Textinhaltsänderungen verwenden Sie andere PDF-Vergleichsklassen.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [GraphicalPdfComparer](#GraphicalPdfComparer--) | Erstellt eine Instanz der {@link GraphicalPdfComparer}-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [compareDocumentsToImages](#compareDocumentsToImages-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-java.lang.String-com.aspose.ms.System.Drawing.Imaging.ImageFormat-) | Vergleicht Dokumente grafisch. |
| [compareDocumentsToPdf](#compareDocumentsToPdf-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-) | Vergleicht Dokumente grafisch. Das Vergleichsergebnis wird in einem PDF-Dokument abgelegt. |
| [comparePagesToImage](#comparePagesToImage-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-) | Vergleicht Seiten grafisch. Das Vergleichsergebnis wird in einem Bild abgelegt. |
| [comparePagesToPdf](#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-com.aspose.pdf.Document-) | Vergleicht Seiten grafisch. Das Vergleichsergebnis wird in einem PDF-Dokument abgelegt. |
| [comparePagesToPdf](#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-) | Vergleicht Seiten grafisch. Das Vergleichsergebnis wird in einem PDF-Dokument abgelegt. |
| [getColor](#getColor--) | Liest und setzt die Farbe der Änderungskennzeichnung. Die Standardfarbe ist Rot. |
| [getDifference](#getDifference-com.aspose.pdf.Page-com.aspose.pdf.Page-) | Liest Unterschiede zwischen Seitenbildern. Das Ergebnis enthält ein Bild der verglichenen ersten Seite und ein Array von Unterschieden. |
| [getResolution](#getResolution--) | Liest und setzt die Auflösung der resultierenden Bilder. Der Standardwert ist 150 dpi. |
| [getThreshold](#getThreshold--) | Liest und setzt den Schwellenwert in Prozent. Dieser Wert ermöglicht es, kleine Änderungen zu ignorieren, wenn sie für Sie nicht signifikant sind. Der Standardwert ist 0 %. |
| [setColor](#setColor-com.aspose.pdf.Color-) | Liest und setzt die Farbe der Änderungskennzeichnung. Die Standardfarbe ist Rot. |
| [setResolution](#setResolution-com.aspose.pdf.devices.Resolution-) | Liest und setzt die Auflösung der resultierenden Bilder. Der Standardwert ist 150 dpi. |
| [setThreshold](#setThreshold-double-) | Liest und setzt den Schwellenwert in Prozent. Dieser Wert ermöglicht es, kleine Änderungen zu ignorieren, wenn sie für Sie nicht signifikant sind. Der Standardwert ist 0 %. |

### GraphicalPdfComparer {#GraphicalPdfComparer--}
```
public GraphicalPdfComparer()
```

Erstellt eine Instanz der {@link GraphicalPdfComparer}-Klasse.

### compareDocumentsToImages {#compareDocumentsToImages-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-java.lang.String-com.aspose.ms.System.Drawing.Imaging.ImageFormat-}
Vergleicht Dokumente grafisch.

### compareDocumentsToPdf {#compareDocumentsToPdf-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-}
Vergleicht Dokumente grafisch. Das Vergleichsergebnis wird in einem PDF-Dokument abgelegt.

### comparePagesToImage {#comparePagesToImage-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-}
Vergleicht Seiten grafisch. Das Vergleichsergebnis wird in einem Bild abgelegt.

### comparePagesToPdf {#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-com.aspose.pdf.Document-}
Vergleicht Seiten grafisch. Das Vergleichsergebnis wird in einem PDF-Dokument abgelegt.

### comparePagesToPdf {#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-}
Vergleicht Seiten grafisch. Das Vergleichsergebnis wird in einem PDF-Dokument abgelegt.

### getColor {#getColor--}
```
public final Color getColor()
```

Liest und setzt die Farbe der Änderungskennzeichnung. Die Standardfarbe ist Rot.

**Returns:**
Color-Instanz

### getDifference {#getDifference-com.aspose.pdf.Page-com.aspose.pdf.Page-}
Liest Unterschiede zwischen Seitenbildern. Das Ergebnis enthält ein Bild der verglichenen ersten Seite und ein Array von Unterschieden.

### getResolution {#getResolution--}
```
public final Resolution getResolution()
```

Liest und setzt die Auflösung der resultierenden Bilder. Der Standardwert ist 150 dpi.

**Returns:**
Auflösung-Instanz

### getThreshold {#getThreshold--}
```
public final double getThreshold()
```

Liest und setzt den Schwellenwert in Prozent. Dieser Wert ermöglicht es, kleine Änderungen zu ignorieren, wenn sie für Sie nicht signifikant sind. Der Standardwert ist 0 %.

**Returns:**
double-Wert

### setColor {#setColor-com.aspose.pdf.Color-}
Liest und setzt die Farbe der Änderungskennzeichnung. Die Standardfarbe ist Rot.

### setResolution {#setResolution-com.aspose.pdf.devices.Resolution-}
Liest und setzt die Auflösung der resultierenden Bilder. Der Standardwert ist 150 dpi.

### setThreshold {#setThreshold-double-}
```
public final void setThreshold(double value)
```

Liest und setzt den Schwellenwert in Prozent. Dieser Wert ermöglicht es, kleine Änderungen zu ignorieren, wenn sie für Sie nicht signifikant sind. Der Standardwert ist 0 %.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |
