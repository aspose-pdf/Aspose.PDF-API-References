---
title: "BarcodeField"
linktitle: "BarcodeField"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse stellt ein Barcode-Feld dar."
type: docs
weight: 250
url: /de/java/com.aspose.pdf/barcodefield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.Field, com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.TextBoxField, com.aspose.pdf.BarcodeField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class BarcodeField extends TextBoxField
```

Klasse stellt ein Barcode-Feld dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [BarcodeField](#BarcodeField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Initialisiert eine neue Instanz der {@code BarcodeField}-Klasse. |
| [BarcodeField](#BarcodeField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Initialisiert eine neue Instanz der {@code BarcodeField}-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCaption](#getCaption--) | Liefert die Beschriftung des Barcode-Objekts. |
| [getECC](#getECC--) | Liefert einen ganzzahligen Wert, der den Fehlerkorrekturkoeffizienten darstellt. Für PDF417 muss er zwischen 0 und 8 liegen. Für QRCode muss er zwischen 0 und 3 liegen (0 für 'L', 1 für 'M', 2 für 'Q' und 3 für 'H'). |
| [getResolution](#getResolution--) | Liefert die Auflösung in Punkten pro Zoll (dpi), mit der das Barcode-Objekt gerendert wird. |
| [getSymbology](#getSymbology--) | Gibt an, welche Barcode- oder Glyph-Technologie für diese Annotation verwendet werden soll, siehe {@code Symbology} für Details. |
| [getXSymHeight](#getXSymHeight--) | Liefert den vertikalen Abstand zwischen zwei Barcode-Modulen, gemessen in Pixeln. Das Verhältnis XSymHeight/XSymWidth muss ein ganzzahliger Wert sein. Für PDF417 liegt der zulässige Wertebereich des Verhältnisses zwischen 1 und 4. Für QRCode und DataMatrix muss dieses Verhältnis stets 1 sein. |
| [getXSymWidth](#getXSymWidth--) | Ermittelt den horizontalen Abstand in Pixeln zwischen zwei Barcode-Modulen. |

### BarcodeField {#BarcodeField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Initialisiert eine neue Instanz der {@code BarcodeField}-Klasse.

### BarcodeField {#BarcodeField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Initialisiert eine neue Instanz der {@code BarcodeField}-Klasse.

### getCaption {#getCaption--}
```
public String getCaption()
```

Liefert die Beschriftung des Barcode-Objekts.

**Returns:**
String Wert

### getECC {#getECC--}
```
public int getECC()
```

Liefert einen ganzzahligen Wert, der den Fehlerkorrekturkoeffizienten darstellt. Für PDF417 muss er zwischen 0 und 8 liegen. Für QRCode muss er zwischen 0 und 3 liegen (0 für 'L', 1 für 'M', 2 für 'Q' und 3 für 'H').

**Returns:**
int-Wert

### getResolution {#getResolution--}
```
public int getResolution()
```

Liefert die Auflösung in Punkten pro Zoll (dpi), mit der das Barcode-Objekt gerendert wird.

**Returns:**
int-Wert

### getSymbology {#getSymbology--}
```
public int getSymbology()
```

Gibt an, welche Barcode- oder Glyph-Technologie für diese Annotation verwendet werden soll, siehe {@code Symbology} für Details.

**Returns:**
Symbologie-Element @see Symbology

### getXSymHeight {#getXSymHeight--}
```
public int getXSymHeight()
```

Liefert den vertikalen Abstand zwischen zwei Barcode-Modulen, gemessen in Pixeln. Das Verhältnis XSymHeight/XSymWidth muss ein ganzzahliger Wert sein. Für PDF417 liegt der zulässige Wertebereich des Verhältnisses zwischen 1 und 4. Für QRCode und DataMatrix muss dieses Verhältnis stets 1 sein.

**Returns:**
int-Wert

### getXSymWidth {#getXSymWidth--}
```
public int getXSymWidth()
```

Ermittelt den horizontalen Abstand in Pixeln zwischen zwei Barcode-Modulen.

**Returns:**
int-Wert
