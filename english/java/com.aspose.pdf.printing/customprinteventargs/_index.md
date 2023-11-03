---
title: CustomPrintEventArgs
second_title: Aspose.PDF for Java API Reference
description: Provides data for the  PdfViewer.getCustomPrintDelegate event.
type: docs
weight: 10
url: /java/com.aspose.pdf.printing/customprinteventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class CustomPrintEventArgs extends System.EventArgs
```

Provides data for the PdfViewer.getCustomPrintDelegate() event.
## Constructors

| Constructor | Description |
| --- | --- |
| [CustomPrintEventArgs(String fileName, PdfPrinterSettings printerSettings, PrintPageSettings pageSettings)](#CustomPrintEventArgs-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-com.aspose.pdf.printing.PrintPageSettings-) | Initializes [CustomPrintEventArgs](../../com.aspose.pdf.printing/customprinteventargs) with the given printer and page settings. |
## Fields

| Field | Description |
| --- | --- |
| [FileName](#FileName) | Gets the name of the file that is being printed. |
| [PrinterSettings](#PrinterSettings) | Gets information about the printer the document should be printed on. |
| [PageSettings](#PageSettings) | Gets settings that should be applied to each page of the document. |
### CustomPrintEventArgs(String fileName, PdfPrinterSettings printerSettings, PrintPageSettings pageSettings) {#CustomPrintEventArgs-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-com.aspose.pdf.printing.PrintPageSettings-}
```
public CustomPrintEventArgs(String fileName, PdfPrinterSettings printerSettings, PrintPageSettings pageSettings)
```


Initializes [CustomPrintEventArgs](../../com.aspose.pdf.printing/customprinteventargs) with the given printer and page settings.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Name of the file that is being printed. |
| printerSettings | [PdfPrinterSettings](../../com.aspose.pdf.printing/pdfprintersettings) | Information about the printer the document should be printed on. |
| pageSettings | [PrintPageSettings](../../com.aspose.pdf.printing/printpagesettings) | Settings that should be applied to each page of the document. |

### FileName {#FileName}
```
public final String FileName
```


Gets the name of the file that is being printed.

### PrinterSettings {#PrinterSettings}
```
public final PdfPrinterSettings PrinterSettings
```


Gets information about the printer the document should be printed on.

### PageSettings {#PageSettings}
```
public final PrintPageSettings PageSettings
```


Gets settings that should be applied to each page of the document.

