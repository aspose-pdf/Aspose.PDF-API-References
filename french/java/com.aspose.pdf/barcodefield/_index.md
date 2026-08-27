---
title: "BarcodeField"
linktitle: "BarcodeField"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant un champ de code-barres."
type: docs
weight: 250
url: /fr/java/com.aspose.pdf/barcodefield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.Field, com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.TextBoxField, com.aspose.pdf.BarcodeField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class BarcodeField extends TextBoxField
```

Classe représentant un champ de code-barres.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [BarcodeField](#BarcodeField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Initialise une nouvelle instance de la classe {@code BarcodeField}. |
| [BarcodeField](#BarcodeField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Initialise une nouvelle instance de la classe {@code BarcodeField}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getCaption](#getCaption--) | Obtient la légende de l'objet code‑barres. |
| [getECC](#getECC--) | Obtient une valeur entière représentant le coefficient de correction d'erreur. Pour PDF417, elle doit être comprise entre 0 et 8. Pour QRCode, elle doit être comprise entre 0 et 3 (0 pour 'L', 1 pour 'M', 2 pour 'Q' et 3 pour 'H'). |
| [getResolution](#getResolution--) | Obtient la résolution, en points par pouce (dpi), à laquelle l'objet code‑barres est rendu. |
| [getSymbology](#getSymbology--) | Spécifie la technologie de code‑barres ou de glyphe à utiliser sur cette annotation, voir {@code Symbology} pour plus de détails. |
| [getXSymHeight](#getXSymHeight--) | Obtient la distance verticale entre deux modules de code‑barres, mesurée en pixels. Le rapport XSymHeight/XSymWidth doit être une valeur entière. Pour PDF417, la plage de rapport acceptable est de 1 à 4. Pour QRCode et DataMatrix, ce rapport doit toujours être de 1. |
| [getXSymWidth](#getXSymWidth--) | Obtient la distance horizontale, en pixels, entre deux modules de code‑barres. |

### BarcodeField {#BarcodeField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Initialise une nouvelle instance de la classe {@code BarcodeField}.

### BarcodeField {#BarcodeField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Initialise une nouvelle instance de la classe {@code BarcodeField}.

### getCaption {#getCaption--}
```
public String getCaption()
```

Obtient la légende de l'objet code‑barres.

**Returns:**
valeur String

### getECC {#getECC--}
```
public int getECC()
```

Obtient une valeur entière représentant le coefficient de correction d'erreur. Pour PDF417, elle doit être comprise entre 0 et 8. Pour QRCode, elle doit être comprise entre 0 et 3 (0 pour 'L', 1 pour 'M', 2 pour 'Q' et 3 pour 'H').

**Returns:**
valeur int

### getResolution {#getResolution--}
```
public int getResolution()
```

Obtient la résolution, en points par pouce (dpi), à laquelle l'objet code‑barres est rendu.

**Returns:**
valeur int

### getSymbology {#getSymbology--}
```
public int getSymbology()
```

Spécifie la technologie de code‑barres ou de glyphe à utiliser sur cette annotation, voir {@code Symbology} pour plus de détails.

**Returns:**
Élément Symbology @see Symbology

### getXSymHeight {#getXSymHeight--}
```
public int getXSymHeight()
```

Obtient la distance verticale entre deux modules de code‑barres, mesurée en pixels. Le rapport XSymHeight/XSymWidth doit être une valeur entière. Pour PDF417, la plage de rapport acceptable est de 1 à 4. Pour QRCode et DataMatrix, ce rapport doit toujours être de 1.

**Returns:**
valeur int

### getXSymWidth {#getXSymWidth--}
```
public int getXSymWidth()
```

Obtient la distance horizontale, en pixels, entre deux modules de code‑barres.

**Returns:**
valeur int
