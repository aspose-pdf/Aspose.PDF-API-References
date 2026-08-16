---
title: "CustomPrintEventArgs"
linktitle: "CustomPrintEventArgs"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Proporciona datos para el evento PdfViewer.getCustomPrintDelegate()."
type: docs
weight: 10
url: /es/java/com.aspose.pdf.printing/customprinteventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs com.aspose.pdf.printing.CustomPrintEventArgs, com.aspose.ms.System.EventArgs, com.aspose.pdf.printing.CustomPrintEventArgs

```
public class CustomPrintEventArgs extends com.aspose.ms.System.EventArgs
```

Proporciona datos para el evento PdfViewer.getCustomPrintDelegate().

## Campos

| Campo | Descripción |
| --- | --- |
| [FileName](#FileName) | Obtiene el nombre del archivo que se está imprimiendo. |
| [PageSettings](#PageSettings) | Obtiene la configuración que debe aplicarse a cada página del documento. |
| [PrinterSettings](#PrinterSettings) | Obtiene información sobre la impresora en la que se debe imprimir el documento. |

## Constructores

| Constructor | Descripción |
| --- | --- |
| [CustomPrintEventArgs](#CustomPrintEventArgs-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-com.aspose.pdf.printing.PrintPageSettings-) | Inicializa {@link CustomPrintEventArgs} con la impresora y la configuración de página proporcionadas. |

### FileName {#FileName}
```
public final String FileName
```

Obtiene el nombre del archivo que se está imprimiendo.

### PageSettings {#PageSettings}
```
public final PrintPageSettings PageSettings
```

Obtiene la configuración que debe aplicarse a cada página del documento.

### PrinterSettings {#PrinterSettings}
```
public final PdfPrinterSettings PrinterSettings
```

Obtiene información sobre la impresora en la que se debe imprimir el documento.

### CustomPrintEventArgs {#CustomPrintEventArgs-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-com.aspose.pdf.printing.PrintPageSettings-}
Inicializa {@link CustomPrintEventArgs} con la impresora y la configuración de página proporcionadas.
