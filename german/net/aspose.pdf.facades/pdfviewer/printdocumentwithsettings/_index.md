---
title: PrintDocumentWithSettings
second_title: Aspose.PDF für .NET-API-Referenz
description: Druckt das PDF-Dokument mit Einstellungen. Wenn die Dokumentgröße nicht mit der Seitengröße kompatibel ist erweitert pdf.kit sie um sie an die Seitengröße anzupassen.
type: docs
weight: 300
url: /de/net/aspose.pdf.facades/pdfviewer/printdocumentwithsettings/
---
## PrintDocumentWithSettings(PageSettings, PrinterSettings) {#printdocumentwithsettings}

Druckt das PDF-Dokument mit Einstellungen. Wenn die Dokumentgröße nicht mit der Seitengröße kompatibel ist, erweitert pdf.kit sie, um sie an die Seitengröße anzupassen.

```csharp
public void PrintDocumentWithSettings(PageSettings pageSettings, PrinterSettings printerSettings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageSettings | PageSettings | Die Seiteneinstellung des Druckdokuments. |
| printerSettings | PrinterSettings | Die Druckereinstellung des zu druckenden Dokuments. |

### Beispiele

printerSettings-Objekt wird verwendet, um das Dokument zu drucken. pageSettings.PrinterSettings-Objekt wird ignoriert.

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.OpenPdfFile(@"d:\test.pdf");
iewer.AutoResize = true;         //Drucken Sie die Datei mit angepasster Größe
iewer.AutoRotate = true;         // Datei mit angepasster Rotation drucken
iewer.PrintPageDialog=false;// erzeugt beim Drucken keinen Seitenzahldialog
ystem.Drawing.Printing.PrinterSettings ps = new System.Drawing.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
ageSettings pgs = new PageSettings();
gs.PaperSize = new System.Drawing.Printing.PaperSize("A4", 827, 1169);
gs.Margins = new Margins(0, 0, 0, 0);
iewer.PrintDocumentWithSettings(pgs, ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer()
iewer.OpenPdfFile(@"d:\test.pdf")
iewer.AutoResize = true;           'Drucken Sie die Datei mit angepasster Größe
iewer.AutoRotate = true;           'Drucken Sie die Datei mit angepasster Drehung
iewer.PrintPageDialog=false;// erzeugt beim Drucken keinen Seitenzahldialog
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
im pgs As PageSettings=new PageSettings()
gs.PaperSize = new System.Drawing.Printing.PaperSize("A4", 827, 1169)
gs.Margins = new Margins(0, 0, 0, 0)
iewer.PrintDocumentWithSettings(pgs, ps)
iewer.ClosePdfFile()
```

### Siehe auch

* class [PdfViewer](../../pdfviewer)
* namensraum [Aspose.Pdf.Facades](../../pdfviewer)
* Montage [Aspose.PDF](../../../)

---

## PrintDocumentWithSettings(PrinterSettings) {#printdocumentwithsettings_1}

Druckt das PDF-Dokument mit den Druckereinstellungen. Die Größe der Ausgabeseite entspricht der Größe der ersten Seite des Dokuments.

```csharp
public void PrintDocumentWithSettings(PrinterSettings printerSettings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| printerSettings | PrinterSettings | Die Druckereinstellung des zu druckenden Dokuments. |

### Beispiele

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.OpenPdfFile(@"d:\test.pdf");
iewer.AutoResize = true;         //Drucken Sie die Datei mit angepasster Größe
iewer.AutoRotate = true;         // Datei mit angepasster Rotation drucken
iewer.PrintPageDialog=false;// erzeugt beim Drucken keinen Seitenzahldialog
ystem.Drawing.Printing.PrinterSettings ps = new System.Drawing.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
iewer.PrintDocumentWithSettings(ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer()
iewer.OpenPdfFile(@"d:\test.pdf")
iewer.AutoResize = true;        'Drucken Sie die Datei mit angepasster Größe
iewer.AutoRotate = true;        'Drucken Sie die Datei mit angepasster Drehung
iewer.PrintPageDialog=false;// erzeugt beim Drucken keinen Seitenzahldialog
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
iewer.PrintDocumentWithSettings(ps);
iewer.ClosePdfFile()
```

### Siehe auch

* class [PdfViewer](../../pdfviewer)
* namensraum [Aspose.Pdf.Facades](../../pdfviewer)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
