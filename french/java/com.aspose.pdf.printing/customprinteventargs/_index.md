---
title: "CustomPrintEventArgs"
linktitle: "CustomPrintEventArgs"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Fournit les données pour l'événement PdfViewer.getCustomPrintDelegate()."
type: docs
weight: 10
url: /fr/java/com.aspose.pdf.printing/customprinteventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs com.aspose.pdf.printing.CustomPrintEventArgs, com.aspose.ms.System.EventArgs, com.aspose.pdf.printing.CustomPrintEventArgs

```
public class CustomPrintEventArgs extends com.aspose.ms.System.EventArgs
```

Fournit les données pour l'événement PdfViewer.getCustomPrintDelegate().

## Champs

| Champ | Description |
| --- | --- |
| [FileName](#FileName) | Obtient le nom du fichier qui est imprimé. |
| [PageSettings](#PageSettings) | Obtient les paramètres qui doivent être appliqués à chaque page du document. |
| [PrinterSettings](#PrinterSettings) | Obtient des informations sur l'imprimante sur laquelle le document doit être imprimé. |

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [CustomPrintEventArgs](#CustomPrintEventArgs-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-com.aspose.pdf.printing.PrintPageSettings-) | Initialise {@link CustomPrintEventArgs} avec l'imprimante et les paramètres de page fournis. |

### FileName {#FileName}
```
public final String FileName
```

Obtient le nom du fichier qui est imprimé.

### PageSettings {#PageSettings}
```
public final PrintPageSettings PageSettings
```

Obtient les paramètres qui doivent être appliqués à chaque page du document.

### PrinterSettings {#PrinterSettings}
```
public final PdfPrinterSettings PrinterSettings
```

Obtient des informations sur l'imprimante sur laquelle le document doit être imprimé.

### CustomPrintEventArgs {#CustomPrintEventArgs-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-com.aspose.pdf.printing.PrintPageSettings-}
Initialise {@link CustomPrintEventArgs} avec l'imprimante et les paramètres de page fournis.
