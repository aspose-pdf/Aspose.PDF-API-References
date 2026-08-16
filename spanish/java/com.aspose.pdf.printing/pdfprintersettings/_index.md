---
title: "PdfPrinterSettings"
linktitle: "PdfPrinterSettings"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Especifica información sobre cómo se imprime un documento, incluida la impresora que lo imprime."
type: docs
weight: 50
url: /es/java/com.aspose.pdf.printing/pdfprintersettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PdfPrinterSettings

```
public class PdfPrinterSettings extends Object
```

Especifica información sobre cómo se imprime un documento, incluida la impresora que lo imprime.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfPrinterSettings](#PdfPrinterSettings--) | Inicializa una nueva instancia de la clase PrinterSettings. |

## Métodos

| Método | Descripción |
| --- | --- |
| [canDuplex](#canDuplex--) | Obtiene un valor que indica si la impresora admite impresión a doble cara. |
| [createMeasurementGraphics](#createMeasurementGraphics--) | Obtener objeto Graphics2D |
| [createMeasurementGraphics](#createMeasurementGraphics-boolean-) | Obtener objeto Graphics2D |
| [createMeasurementGraphics](#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-) | Obtener objeto Graphics2D |
| [createMeasurementGraphics](#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-boolean-) | Obtener objeto Graphics2D |
| [deepClone](#deepClone--) | Obtener objeto clonado |
| [getCopies](#getCopies--) | Obtiene el número de copias del documento a imprimir. |
| [getDefaultPageSettings](#getDefaultPageSettings--) | Obtiene la configuración de página predeterminada para esta impresora. |
| [getDuplex](#getDuplex--) | Obtiene o establece la configuración de la impresora para la impresión a doble cara. |
| [getFromPage](#getFromPage--) | Obtiene o establece el número de página de la primera página a imprimir. |
| [getInstalledPrinters](#getInstalledPrinters--) | Obtiene los nombres de todas las impresoras instaladas en el equipo. |
| [getLandscapeAngle](#getLandscapeAngle--) | Obtiene el ángulo, en grados, con el que la orientación vertical se gira para producir la orientación horizontal. |
| [getMaximumCopies](#getMaximumCopies--) | Obtiene el número máximo de copias que la impresora permite al usuario imprimir a la vez. |
| [getMaximumPage](#getMaximumPage--) | Obtiene o establece el máximo FromPage o ToPage que puede seleccionarse en un PrintDialog. |
| [getMinimumPage](#getMinimumPage--) | Obtiene o establece el mínimo FromPage o ToPage que puede seleccionarse en un PrintDialog. |
| [getPaperSizes](#getPaperSizes--) | Obtiene los tamaños de papel que son compatibles con esta impresora. |
| [getPaperSources](#getPaperSources--) | Obtiene las bandejas de origen de papel que están disponibles en la impresora. |
| [getPrinterName](#getPrinterName--) | Obtiene o establece el nombre de la impresora a usar. |
| [getPrinterResolutions](#getPrinterResolutions--) | Obtiene todas las resoluciones que son compatibles con esta impresora. |
| [getPrinterSettings](#getPrinterSettings--) | Devuelve el objeto PrinterSettings |
| [getPrintFileName](#getPrintFileName--) | Obtiene o establece el nombre de archivo, al imprimir a un archivo. |
| [getPrintRange](#getPrintRange--) | Obtiene o establece los números de página que el usuario ha especificado para imprimir. |
| [getSelectedPages](#getSelectedPages--) | Obtiene el número de páginas seleccionadas para imprimir. |
| [getToPage](#getToPage--) | Obtiene o establece el número de la última página a imprimir. |
| [isCollate](#isCollate--) | Obtiene o establece un valor que indica si el documento impreso está encuadernado. |
| [isDefaultPrinter](#isDefaultPrinter--) | Obtiene un valor que indica si la propiedad PrinterName designa la impresora predeterminada, excepto cuando el usuario establece explícitamente PrinterName. |
| [isDirectPrintingSupported](#isDirectPrintingSupported-com.aspose.pdf.ImageType-) | Obtiene un valor que indica si la impresora es compatible con DirectPrinting. |
| [isDirectPrintingSupported](#isDirectPrintingSupported-java.lang.String-) | Obtiene un valor que indica si la impresora es compatible con DirectPrinting. |
| [isPlotter](#isPlotter--) | Obtiene un valor que indica si la impresora es una plotter. |
| [isPrintToFile](#isPrintToFile--) | Obtiene un valor que indica si la salida de impresión se envía a un archivo en lugar de a un puerto. |
| [isSupportsColor](#isSupportsColor--) | Obtiene un valor que indica si esta impresora admite impresión en color. |
| [isValid](#isValid--) | Obtiene un valor que indica si la propiedad PrinterName designa una impresora válida. |
| [setCollate](#setCollate-boolean-) | Obtiene o establece un valor que indica si el documento impreso está encuadernado. |
| [setCopies](#setCopies-short-) | Establece el número de copias del documento a imprimir. |
| [setDuplex](#setDuplex-int-) | Obtiene o establece la configuración de la impresora para la impresión a doble cara. |
| [setFromPage](#setFromPage-int-) | Obtiene o establece el número de página de la primera página a imprimir. |
| [setMaximumPage](#setMaximumPage-int-) | Obtiene o establece el máximo FromPage o ToPage que puede seleccionarse en un PrintDialog. |
| [setMinimumPage](#setMinimumPage-int-) | Obtiene o establece el mínimo FromPage o ToPage que puede seleccionarse en un PrintDialog. |
| [setPrinterName](#setPrinterName-java.lang.String-) | Establece el nombre de la impresora a usar. |
| [setPrintFileName](#setPrintFileName-java.lang.String-) | Establece el nombre del archivo a imprimir. |
| [setPrintRange](#setPrintRange-int-) | Establece los números de página que el usuario ha especificado para imprimir. |
| [setPrintToFile](#setPrintToFile-boolean-) | Establece un valor que indica si la salida de impresión se envía a un archivo en lugar de a un puerto. |
| [setSelectedPages](#setSelectedPages-int:A-) | Establece el número de páginas seleccionadas para imprimir. |
| [setToPage](#setToPage-int-) | Establece el número de la última página a imprimir. |

### PdfPrinterSettings {#PdfPrinterSettings--}
```
public PdfPrinterSettings()
```

Inicializa una nueva instancia de la clase PrinterSettings.

### canDuplex {#canDuplex--}
```
public boolean canDuplex()
```

Obtiene un valor que indica si la impresora admite impresión a doble cara.

**Returns:**
valor booleano

### createMeasurementGraphics {#createMeasurementGraphics--}
```
public Graphics2D createMeasurementGraphics()
```

Obtener objeto Graphics2D

**Returns:**
Objeto Graphics2D

### createMeasurementGraphics {#createMeasurementGraphics-boolean-}
```
public Graphics2D createMeasurementGraphics(boolean value)
```

Obtener objeto Graphics2D

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

**Returns:**
Objeto Graphics2D

### createMeasurementGraphics {#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-}
Obtener objeto Graphics2D

**Returns:**
Objeto Graphics2D

### createMeasurementGraphics {#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-boolean-}
Obtener objeto Graphics2D

**Returns:**
Objeto Graphics2D

### deepClone {#deepClone--}
```
public PdfPrinterSettings deepClone()
```

Obtener objeto clonado

**Returns:**
Objeto PdfPrinterSettings

### getCopies {#getCopies--}
```
public short getCopies()
```

Obtiene el número de copias del documento a imprimir.

**Returns:**
número de copias

### getDefaultPageSettings {#getDefaultPageSettings--}
```
public PrintPageSettings getDefaultPageSettings()
```

Obtiene la configuración de página predeterminada para esta impresora.

**Returns:**
configuración de página predeterminada

### getDuplex {#getDuplex--}
```
public int getDuplex()
```

Obtiene o establece la configuración de la impresora para la impresión a doble cara.

**Returns:**
valor int @see DuplexKind

### getFromPage {#getFromPage--}
```
public int getFromPage()
```

Obtiene o establece el número de página de la primera página a imprimir.

**Returns:**
valor int

### getInstalledPrinters {#getInstalledPrinters--}
```
public static ArrayList < String > getInstalledPrinters()
```

Obtiene los nombres de todas las impresoras instaladas en el equipo.

**Returns:**
objeto {@code ArrayList<String>}

### getLandscapeAngle {#getLandscapeAngle--}
```
public int getLandscapeAngle()
```

Obtiene el ángulo, en grados, con el que la orientación vertical se gira para producir la orientación horizontal.

**Returns:**
valor int

### getMaximumCopies {#getMaximumCopies--}
```
public int getMaximumCopies()
```

Obtiene el número máximo de copias que la impresora permite al usuario imprimir a la vez.

**Returns:**
valor int

### getMaximumPage {#getMaximumPage--}
```
public int getMaximumPage()
```

Obtiene o establece el máximo FromPage o ToPage que puede seleccionarse en un PrintDialog.

**Returns:**
valor int

### getMinimumPage {#getMinimumPage--}
```
public int getMinimumPage()
```

Obtiene o establece el mínimo FromPage o ToPage que puede seleccionarse en un PrintDialog.

**Returns:**
valor int

### getPaperSizes {#getPaperSizes--}
```
public ArrayList < PrintPaperSize > getPaperSizes()
```

Obtiene los tamaños de papel que son compatibles con esta impresora.

**Returns:**
objeto {@code ArrayList<PrintPaperSize> }

### getPaperSources {#getPaperSources--}
```
public ArrayList < PrintPaperSource > getPaperSources()
```

Obtiene las bandejas de origen de papel que están disponibles en la impresora.

**Returns:**
objeto {@code ArrayList<PrintPaperSource> }

### getPrinterName {#getPrinterName--}
```
public String getPrinterName()
```

Obtiene o establece el nombre de la impresora a usar.

**Returns:**
objeto string

### getPrinterResolutions {#getPrinterResolutions--}
```
public com.aspose.ms.System.Drawing.Printing.PrinterSettings.PrinterResolutionCollection getPrinterResolutions()
```

Obtiene todas las resoluciones que son compatibles con esta impresora.

**Returns:**
objeto PrinterResolutionCollection

### getPrinterSettings {#getPrinterSettings--}
```
public com.aspose.ms.System.Drawing.Printing.PrinterSettings getPrinterSettings()
```

Devuelve el objeto PrinterSettings

**Returns:**
objeto PrinterSettings

### getPrintFileName {#getPrintFileName--}
```
public String getPrintFileName()
```

Obtiene o establece el nombre de archivo, al imprimir a un archivo.

**Returns:**
objeto string

### getPrintRange {#getPrintRange--}
```
public int getPrintRange()
```

Obtiene o establece los números de página que el usuario ha especificado para imprimir.

**Returns:**
valor int @see PdfPrintRange

### getSelectedPages {#getSelectedPages--}
```
public int[] getSelectedPages()
```

Obtiene el número de páginas seleccionadas para imprimir.

**Returns:**
matriz int pagesList @see PdfPrintRange

### getToPage {#getToPage--}
```
public int getToPage()
```

Obtiene o establece el número de la última página a imprimir.

**Returns:**
valor int

### isCollate {#isCollate--}
```
public boolean isCollate()
```

Obtiene o establece un valor que indica si el documento impreso está encuadernado.

**Returns:**
valor booleano

### isDefaultPrinter {#isDefaultPrinter--}
```
public boolean isDefaultPrinter()
```

Obtiene un valor que indica si la propiedad PrinterName designa la impresora predeterminada, excepto cuando el usuario establece explícitamente PrinterName.

**Returns:**
valor booleano

### isDirectPrintingSupported {#isDirectPrintingSupported-com.aspose.pdf.ImageType-}
Obtiene un valor que indica si la impresora es compatible con DirectPrinting.

### isDirectPrintingSupported {#isDirectPrintingSupported-java.lang.String-}
Obtiene un valor que indica si la impresora es compatible con DirectPrinting.

### isPlotter {#isPlotter--}
```
public boolean isPlotter()
```

Obtiene un valor que indica si la impresora es una plotter.

**Returns:**
valor booleano

### isPrintToFile {#isPrintToFile--}
```
public boolean isPrintToFile()
```

Obtiene un valor que indica si la salida de impresión se envía a un archivo en lugar de a un puerto.

**Returns:**
valor booleano

### isSupportsColor {#isSupportsColor--}
```
public boolean isSupportsColor()
```

Obtiene un valor que indica si esta impresora admite impresión en color.

**Returns:**
valor booleano

### isValid {#isValid--}
```
public boolean isValid()
```

Obtiene un valor que indica si la propiedad PrinterName designa una impresora válida.

**Returns:**
valor booleano

### setCollate {#setCollate-boolean-}
```
public void setCollate(boolean value)
```

Obtiene o establece un valor que indica si el documento impreso está encuadernado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setCopies {#setCopies-short-}
```
public void setCopies(short value)
```

Establece el número de copias del documento a imprimir.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | número de copias |

### setDuplex {#setDuplex-int-}
```
public void setDuplex(int value)
```

Obtiene o establece la configuración de la impresora para la impresión a doble cara.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int @see DuplexKind |

### setFromPage {#setFromPage-int-}
```
public void setFromPage(int value)
```

Obtiene o establece el número de página de la primera página a imprimir.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setMaximumPage {#setMaximumPage-int-}
```
public void setMaximumPage(int value)
```

Obtiene o establece el máximo FromPage o ToPage que puede seleccionarse en un PrintDialog.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setMinimumPage {#setMinimumPage-int-}
```
public void setMinimumPage(int value)
```

Obtiene o establece el mínimo FromPage o ToPage que puede seleccionarse en un PrintDialog.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setPrinterName {#setPrinterName-java.lang.String-}
Establece el nombre de la impresora a usar.

### setPrintFileName {#setPrintFileName-java.lang.String-}
Establece el nombre del archivo a imprimir.

### setPrintRange {#setPrintRange-int-}
```
public void setPrintRange(int value)
```

Establece los números de página que el usuario ha especificado para imprimir.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | elemento PdfPrintRange @see PdfPrintRange |

### setPrintToFile {#setPrintToFile-boolean-}
```
public void setPrintToFile(boolean value)
```

Establece un valor que indica si la salida de impresión se envía a un archivo en lugar de a un puerto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setSelectedPages {#setSelectedPages-int:A-}
```
public void setSelectedPages(int[] pagesList)
```

Establece el número de páginas seleccionadas para imprimir.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pagesList |  | matriz int @see PdfPrintRange |

### setToPage {#setToPage-int-}
```
public void setToPage(int value)
```

Establece el número de la última página a imprimir.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | elemento PdfPrintRange @see PdfPrintRange |
