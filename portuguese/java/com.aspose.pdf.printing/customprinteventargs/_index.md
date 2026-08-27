---
title: "CustomPrintEventArgs"
linktitle: "CustomPrintEventArgs"
second_title: "Referência da API Aspose.PDF para Java"
description: "Fornece dados para o evento PdfViewer.getCustomPrintDelegate()."
type: docs
weight: 10
url: /pt/java/com.aspose.pdf.printing/customprinteventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs com.aspose.pdf.printing.CustomPrintEventArgs, com.aspose.ms.System.EventArgs, com.aspose.pdf.printing.CustomPrintEventArgs

```
public class CustomPrintEventArgs extends com.aspose.ms.System.EventArgs
```

Fornece dados para o evento PdfViewer.getCustomPrintDelegate().

## Campos

| Campo | Descrição |
| --- | --- |
| [FileName](#FileName) | Obtém o nome do arquivo que está sendo impresso. |
| [PageSettings](#PageSettings) | Obtém as configurações que devem ser aplicadas a cada página do documento. |
| [PrinterSettings](#PrinterSettings) | Obtém informações sobre a impressora na qual o documento deve ser impresso. |

## Construtores

| Construtor | Descrição |
| --- | --- |
| [CustomPrintEventArgs](#CustomPrintEventArgs-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-com.aspose.pdf.printing.PrintPageSettings-) | Inicializa {@link CustomPrintEventArgs} com a impressora e as configurações de página fornecidas. |

### FileName {#FileName}
```
public final String FileName
```

Obtém o nome do arquivo que está sendo impresso.

### PageSettings {#PageSettings}
```
public final PrintPageSettings PageSettings
```

Obtém as configurações que devem ser aplicadas a cada página do documento.

### PrinterSettings {#PrinterSettings}
```
public final PdfPrinterSettings PrinterSettings
```

Obtém informações sobre a impressora na qual o documento deve ser impresso.

### CustomPrintEventArgs {#CustomPrintEventArgs-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-com.aspose.pdf.printing.PrintPageSettings-}
Inicializa {@link CustomPrintEventArgs} com a impressora e as configurações de página fornecidas.
