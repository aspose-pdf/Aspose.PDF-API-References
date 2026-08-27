---
title: "BarcodeField"
linktitle: "BarcodeField"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta il campo barcode."
type: docs
weight: 250
url: /it/java/com.aspose.pdf/barcodefield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.Field, com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.TextBoxField, com.aspose.pdf.BarcodeField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class BarcodeField extends TextBoxField
```

Classe che rappresenta il campo barcode.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [BarcodeField](#BarcodeField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Inizializza una nuova istanza della classe {@code BarcodeField}. |
| [BarcodeField](#BarcodeField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Inizializza una nuova istanza della classe {@code BarcodeField}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCaption](#getCaption--) | Ottiene la didascalia dell'oggetto barcode. |
| [getECC](#getECC--) | Ottiene un valore intero che rappresenta il coefficiente di correzione degli errori. Per PDF417, deve essere da 0 a 8. Per QRCode, deve essere da 0 a 3 (0 per 'L', 1 per 'M', 2 per 'Q' e 3 per 'H'). |
| [getResolution](#getResolution--) | Ottiene la risoluzione, in punti per pollice (dpi), con cui viene renderizzato l'oggetto barcode. |
| [getSymbology](#getSymbology--) | Specifica quale tecnologia di barcode o glifo deve essere utilizzata in questa annotazione, vedere {@code Symbology} per i dettagli. |
| [getXSymHeight](#getXSymHeight--) | Ottiene la distanza verticale tra due moduli di barcode, misurata in pixel. Il rapporto XSymHeight/XSymWidth deve essere un valore intero. Per PDF417, l'intervallo di rapporto accettabile è da 1 a 4. Per QRCode e DataMatrix, questo rapporto deve essere sempre 1. |
| [getXSymWidth](#getXSymWidth--) | Ottiene la distanza orizzontale, in pixel, tra due moduli di barcode. |

### BarcodeField {#BarcodeField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Inizializza una nuova istanza della classe {@code BarcodeField}.

### BarcodeField {#BarcodeField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Inizializza una nuova istanza della classe {@code BarcodeField}.

### getCaption {#getCaption--}
```
public String getCaption()
```

Ottiene la didascalia dell'oggetto barcode.

**Returns:**
valore String

### getECC {#getECC--}
```
public int getECC()
```

Ottiene un valore intero che rappresenta il coefficiente di correzione degli errori. Per PDF417, deve essere da 0 a 8. Per QRCode, deve essere da 0 a 3 (0 per 'L', 1 per 'M', 2 per 'Q' e 3 per 'H').

**Returns:**
valore int

### getResolution {#getResolution--}
```
public int getResolution()
```

Ottiene la risoluzione, in punti per pollice (dpi), con cui viene renderizzato l'oggetto barcode.

**Returns:**
valore int

### getSymbology {#getSymbology--}
```
public int getSymbology()
```

Specifica quale tecnologia di barcode o glifo deve essere utilizzata in questa annotazione, vedere {@code Symbology} per i dettagli.

**Returns:**
Elemento Symbology @see Symbology

### getXSymHeight {#getXSymHeight--}
```
public int getXSymHeight()
```

Ottiene la distanza verticale tra due moduli di barcode, misurata in pixel. Il rapporto XSymHeight/XSymWidth deve essere un valore intero. Per PDF417, l'intervallo di rapporto accettabile è da 1 a 4. Per QRCode e DataMatrix, questo rapporto deve essere sempre 1.

**Returns:**
valore int

### getXSymWidth {#getXSymWidth--}
```
public int getXSymWidth()
```

Ottiene la distanza orizzontale, in pixel, tra due moduli di barcode.

**Returns:**
valore int
