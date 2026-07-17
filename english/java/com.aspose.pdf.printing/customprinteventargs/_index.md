---
title: CustomPrintEventArgs
linktitle: CustomPrintEventArgs
second_title: Aspose.PDF for Java API Reference
description: Provides data for the PdfViewer.getCustomPrintDelegate() event.
type: docs
weight: 10
url: /java/com.aspose.pdf.printing/customprinteventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs com.aspose.pdf.printing.CustomPrintEventArgs, com.aspose.ms.System.EventArgs, com.aspose.pdf.printing.CustomPrintEventArgs

```
public class CustomPrintEventArgs extends com.aspose.ms.System.EventArgs
```

Provides data for the PdfViewer.getCustomPrintDelegate() event.

## Fields

| Field | Description |
| --- | --- |
| [FileName](#FileName) | Gets the name of the file that is being printed. |
| [PageSettings](#PageSettings) | Gets settings that should be applied to each page of the document. |
| [PrinterSettings](#PrinterSettings) | Gets information about the printer the document should be printed on. |

## Constructors

| Constructor | Description |
| --- | --- |
| [CustomPrintEventArgs](#CustomPrintEventArgs-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-com.aspose.pdf.printing.PrintPageSettings-) | Initializes {@link CustomPrintEventArgs} with the given printer and page settings. |

### FileName {#FileName}
```
public final String FileName
```

Gets the name of the file that is being printed.

### PageSettings {#PageSettings}
```
public final PrintPageSettings PageSettings
```

Gets settings that should be applied to each page of the document.

### PrinterSettings {#PrinterSettings}
```
public final PdfPrinterSettings PrinterSettings
```

Gets information about the printer the document should be printed on.

### CustomPrintEventArgs {#CustomPrintEventArgs-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-com.aspose.pdf.printing.PrintPageSettings-}
Initializes {@link CustomPrintEventArgs} with the given printer and page settings.
