---
title: "BarcodeField"
linktitle: "BarcodeField"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa un campo de código de barras."
type: docs
weight: 250
url: /es/java/com.aspose.pdf/barcodefield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.Field, com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.TextBoxField, com.aspose.pdf.BarcodeField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class BarcodeField extends TextBoxField
```

Clase que representa un campo de código de barras.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [BarcodeField](#BarcodeField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Inicializa una nueva instancia de la clase {@code BarcodeField}. |
| [BarcodeField](#BarcodeField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Inicializa una nueva instancia de la clase {@code BarcodeField}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getCaption](#getCaption--) | Obtiene la leyenda del objeto de código de barras. |
| [getECC](#getECC--) | Obtiene un valor entero que representa el coeficiente de corrección de errores. Para PDF417, debe estar entre 0 y 8. Para QRCode, debe estar entre 0 y 3 (0 para 'L', 1 para 'M', 2 para 'Q' y 3 para 'H'). |
| [getResolution](#getResolution--) | Obtiene la resolución, en puntos por pulgada (dpi), a la que se renderiza el objeto de código de barras. |
| [getSymbology](#getSymbology--) | Especifica qué tecnología de código de barras o glifo se debe usar en esta anotación, vea {@code Symbology} para obtener más detalles. |
| [getXSymHeight](#getXSymHeight--) | Obtiene la distancia vertical entre dos módulos de código de barras, medida en píxeles. La razón XSymHeight/XSymWidth debe ser un valor entero. Para PDF417, el rango aceptable de la razón es de 1 a 4. Para QRCode y DataMatrix, esta razón siempre será 1 |
| [getXSymWidth](#getXSymWidth--) | Obtiene la distancia horizontal, en píxeles, entre dos módulos de código de barras. |

### BarcodeField {#BarcodeField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Inicializa una nueva instancia de la clase {@code BarcodeField}.

### BarcodeField {#BarcodeField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Inicializa una nueva instancia de la clase {@code BarcodeField}.

### getCaption {#getCaption--}
```
public String getCaption()
```

Obtiene la leyenda del objeto de código de barras.

**Returns:**
valor String

### getECC {#getECC--}
```
public int getECC()
```

Obtiene un valor entero que representa el coeficiente de corrección de errores. Para PDF417, debe estar entre 0 y 8. Para QRCode, debe estar entre 0 y 3 (0 para 'L', 1 para 'M', 2 para 'Q' y 3 para 'H').

**Returns:**
valor int

### getResolution {#getResolution--}
```
public int getResolution()
```

Obtiene la resolución, en puntos por pulgada (dpi), a la que se renderiza el objeto de código de barras.

**Returns:**
valor int

### getSymbology {#getSymbology--}
```
public int getSymbology()
```

Especifica qué tecnología de código de barras o glifo se debe usar en esta anotación, vea {@code Symbology} para obtener más detalles.

**Returns:**
Elemento Symbology @see Symbology

### getXSymHeight {#getXSymHeight--}
```
public int getXSymHeight()
```

Obtiene la distancia vertical entre dos módulos de código de barras, medida en píxeles. La razón XSymHeight/XSymWidth debe ser un valor entero. Para PDF417, el rango aceptable de la razón es de 1 a 4. Para QRCode y DataMatrix, esta razón siempre será 1

**Returns:**
valor int

### getXSymWidth {#getXSymWidth--}
```
public int getXSymWidth()
```

Obtiene la distancia horizontal, en píxeles, entre dos módulos de código de barras.

**Returns:**
valor int
