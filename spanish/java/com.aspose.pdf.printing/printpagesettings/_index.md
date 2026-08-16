---
title: "PrintPageSettings"
linktitle: "PrintPageSettings"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Especifica la configuración que se aplica a una sola página impresa."
type: docs
weight: 90
url: /es/java/com.aspose.pdf.printing/printpagesettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PrintPageSettings

```
public class PrintPageSettings extends Object
```

Especifica la configuración que se aplica a una sola página impresa.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PrintPageSettings](#PrintPageSettings--) | Inicializa una nueva instancia de la clase PageSettings usando la impresora predeterminada. |
| [PrintPageSettings](#PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | Inicializa una nueva instancia de la clase PageSettings usando la impresora predeterminada. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getBounds](#getBounds--) | Obtiene el tamaño de la página, teniendo en cuenta la orientación de la página especificada por la propiedad Landscape. |
| [getHardMarginX](#getHardMarginX--) | Obtiene la coordenada x, en centésimas de pulgada, del margen rígido en el lado izquierdo de la página. |
| [getHardMarginY](#getHardMarginY--) | Obtiene la coordenada y, en centésimas de pulgada, del margen rígido en la parte superior de la página. |
| [getMargins](#getMargins--) | Obtiene los márgenes de esta página. |
| [getPageSettings](#getPageSettings--) | Obtiene la configuración de página |
| [getPaperSize](#getPaperSize--) | Obtiene el tamaño del papel para la página. |
| [getPaperSource](#getPaperSource--) | Obtiene la fuente de papel de la página; por ejemplo, la bandeja superior de la impresora. |
| [getPrintableArea](#getPrintableArea--) | Obtiene los límites del área imprimible de la página para la impresora. |
| [getPrinterResolution](#getPrinterResolution--) | Obtiene la resolución de la impresora para la página. |
| [getPrinterSettings](#getPrinterSettings--) | Obtiene la configuración de la impresora asociada a la página. |
| [isColor](#isColor--) | Obtiene o establece un valor que indica si la página debe imprimirse en color. |
| [isLandscape](#isLandscape--) | Obtiene o establece un valor que indica si la página se imprime en orientación horizontal o vertical. |
| [setColor](#setColor-boolean-) | Obtiene o establece un valor que indica si la página debe imprimirse en color. |
| [setLandscape](#setLandscape-boolean-) | Obtiene o establece un valor que indica si la página se imprime en orientación horizontal o vertical. |
| [setMargins](#setMargins-com.aspose.pdf.printing.PrinterMargins-) | Establece los márgenes de esta página. |
| [setPaperSize](#setPaperSize-com.aspose.pdf.printing.PrintPaperSize-) | Establece el tamaño del papel para la página. |
| [setPaperSource](#setPaperSource-com.aspose.pdf.printing.PrintPaperSource-) | Establece la fuente de papel de la página; por ejemplo, la bandeja superior de la impresora. |
| [setPrinterResolution](#setPrinterResolution-com.aspose.pdf.printing.PdfPrinterResolution-) | Establece la resolución de la impresora para la página. |
| [setPrinterSettings](#setPrinterSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | Establece la configuración de la impresora asociada con la página. |

### PrintPageSettings {#PrintPageSettings--}
```
public PrintPageSettings()
```

Inicializa una nueva instancia de la clase PageSettings usando la impresora predeterminada.

### PrintPageSettings {#PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
Inicializa una nueva instancia de la clase PageSettings usando la impresora predeterminada.

### getBounds {#getBounds--}
```
public Rectangle getBounds()
```

Obtiene el tamaño de la página, teniendo en cuenta la orientación de la página especificada por la propiedad Landscape.

**Returns:**
objeto Rectangle

### getHardMarginX {#getHardMarginX--}
```
public float getHardMarginX()
```

Obtiene la coordenada x, en centésimas de pulgada, del margen rígido en el lado izquierdo de la página.

**Returns:**
valor flotante

### getHardMarginY {#getHardMarginY--}
```
public float getHardMarginY()
```

Obtiene la coordenada y, en centésimas de pulgada, del margen rígido en la parte superior de la página.

**Returns:**
valor flotante

### getMargins {#getMargins--}
```
public PrinterMargins getMargins()
```

Obtiene los márgenes de esta página.

**Returns:**
Objeto PrinterMargins

### getPageSettings {#getPageSettings--}
```
public com.aspose.ms.System.Drawing.Printing.PageSettings getPageSettings()
```

Obtiene la configuración de página

**Returns:**
Objeto PageSettings

### getPaperSize {#getPaperSize--}
```
public PrintPaperSize getPaperSize()
```

Obtiene el tamaño del papel para la página.

**Returns:**
Objeto PrintPaperSize

### getPaperSource {#getPaperSource--}
```
public PrintPaperSource getPaperSource()
```

Obtiene la fuente de papel de la página; por ejemplo, la bandeja superior de la impresora.

**Returns:**
Objeto PrintPaperSource

### getPrintableArea {#getPrintableArea--}
```
public Rectangle getPrintableArea()
```

Obtiene los límites del área imprimible de la página para la impresora.

**Returns:**
objeto Rectangle

### getPrinterResolution {#getPrinterResolution--}
```
public PdfPrinterResolution getPrinterResolution()
```

Obtiene la resolución de la impresora para la página.

**Returns:**
Objeto PdfPrinterResolution

### getPrinterSettings {#getPrinterSettings--}
```
public PdfPrinterSettings getPrinterSettings()
```

Obtiene la configuración de la impresora asociada a la página.

**Returns:**
Objeto PdfPrinterSettings

### isColor {#isColor--}
```
public boolean isColor()
```

Obtiene o establece un valor que indica si la página debe imprimirse en color.

**Returns:**
valor booleano

### isLandscape {#isLandscape--}
```
public boolean isLandscape()
```

Obtiene o establece un valor que indica si la página se imprime en orientación horizontal o vertical.

**Returns:**
valor booleano

### setColor {#setColor-boolean-}
```
public void setColor(boolean value)
```

Obtiene o establece un valor que indica si la página debe imprimirse en color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setLandscape {#setLandscape-boolean-}
```
public void setLandscape(boolean value)
```

Obtiene o establece un valor que indica si la página se imprime en orientación horizontal o vertical.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setMargins {#setMargins-com.aspose.pdf.printing.PrinterMargins-}
Establece los márgenes de esta página.

### setPaperSize {#setPaperSize-com.aspose.pdf.printing.PrintPaperSize-}
Establece el tamaño del papel para la página.

### setPaperSource {#setPaperSource-com.aspose.pdf.printing.PrintPaperSource-}
Establece la fuente de papel de la página; por ejemplo, la bandeja superior de la impresora.

### setPrinterResolution {#setPrinterResolution-com.aspose.pdf.printing.PdfPrinterResolution-}
Establece la resolución de la impresora para la página.

### setPrinterSettings {#setPrinterSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
Establece la configuración de la impresora asociada con la página.
