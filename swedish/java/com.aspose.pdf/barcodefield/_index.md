---
title: "BarcodeField"
linktitle: "BarcodeField"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass representerar ett streckkodsfält."
type: docs
weight: 250
url: /sv/java/com.aspose.pdf/barcodefield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.Field, com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.TextBoxField, com.aspose.pdf.BarcodeField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class BarcodeField extends TextBoxField
```

Klass representerar ett streckkodsfält.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [BarcodeField](#BarcodeField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Initierar en ny instans av klassen {@code BarcodeField}. |
| [BarcodeField](#BarcodeField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Initierar en ny instans av klassen {@code BarcodeField}. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCaption](#getCaption--) | Hämtar rubriken för streckkodobjektet. |
| [getECC](#getECC--) | Hämtar ett heltalsvärde som representerar felkorrigeringskoefficienten. För PDF417 ska det vara mellan 0 och 8. För QRCode ska det vara mellan 0 och 3 (0 för 'L', 1 för 'M', 2 för 'Q' och 3 för 'H'). |
| [getResolution](#getResolution--) | Hämtar upplösningen, i punkter per tum (dpi), som streckkodobjektet renderas med. |
| [getSymbology](#getSymbology--) | Specificerar vilken streckkod- eller glyfteknik som ska användas på denna annotation, se {@code Symbology} för detaljer. |
| [getXSymHeight](#getXSymHeight--) | Hämtar det vertikala avståndet mellan två streckkodmoduler, mätt i pixlar. Förhållandet XSymHeight/XSymWidth ska vara ett heltal. För PDF417 är det acceptabla förhållandet mellan 1 och 4. För QRCode och DataMatrix ska detta förhållande alltid vara 1. |
| [getXSymWidth](#getXSymWidth--) | Hämtar det horisontella avståndet, i pixlar, mellan två streckkodmoduler. |

### BarcodeField {#BarcodeField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Initierar en ny instans av klassen {@code BarcodeField}.

### BarcodeField {#BarcodeField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Initierar en ny instans av klassen {@code BarcodeField}.

### getCaption {#getCaption--}
```
public String getCaption()
```

Hämtar rubriken för streckkodobjektet.

**Returns:**
String värde

### getECC {#getECC--}
```
public int getECC()
```

Hämtar ett heltalsvärde som representerar felkorrigeringskoefficienten. För PDF417 ska det vara mellan 0 och 8. För QRCode ska det vara mellan 0 och 3 (0 för 'L', 1 för 'M', 2 för 'Q' och 3 för 'H').

**Returns:**
int‑värde

### getResolution {#getResolution--}
```
public int getResolution()
```

Hämtar upplösningen, i punkter per tum (dpi), som streckkodobjektet renderas med.

**Returns:**
int‑värde

### getSymbology {#getSymbology--}
```
public int getSymbology()
```

Specificerar vilken streckkod- eller glyfteknik som ska användas på denna annotation, se {@code Symbology} för detaljer.

**Returns:**
Symbology-element @see Symbology

### getXSymHeight {#getXSymHeight--}
```
public int getXSymHeight()
```

Hämtar det vertikala avståndet mellan två streckkodmoduler, mätt i pixlar. Förhållandet XSymHeight/XSymWidth ska vara ett heltal. För PDF417 är det acceptabla förhållandet mellan 1 och 4. För QRCode och DataMatrix ska detta förhållande alltid vara 1.

**Returns:**
int‑värde

### getXSymWidth {#getXSymWidth--}
```
public int getXSymWidth()
```

Hämtar det horisontella avståndet, i pixlar, mellan två streckkodmoduler.

**Returns:**
int‑värde
