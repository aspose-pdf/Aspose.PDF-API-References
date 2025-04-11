---
title: PdfViewer.PrintDocumentWithSettings
second_title: Aspose.PDF for .NET API Reference
description: PdfViewer-Methode. Druckt das Pdf-Dokument mit Einstellungen. Wenn die Dokumentgröße nicht der Seitengröße entspricht, wird es erweitert, um zur Seitengröße zu passen.
type: docs
weight: 330
url: /de/net/aspose.pdf.facades/pdfviewer/printdocumentwithsettings/
---
## PrintDocumentWithSettings(PageSettings, PrinterSettings) {#printdocumentwithsettings}

Druckt das Pdf-Dokument mit Einstellungen. Wenn die Dokumentgröße nicht der Seitengröße entspricht, wird es erweitert, um zur Seitengröße zu passen.

```csharp
public void PrintDocumentWithSettings(PageSettings pageSettings, PrinterSettings printerSettings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageSettings | PageSettings | Die Seiteneinstellungen des zu druckenden Dokuments. |
| printerSettings | PrinterSettings | Die Druckereinstellungen des zu druckenden Dokuments. |

## Beispiele

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.BindPdf(@"d:\test.pdf");
iewer.AutoResize = true;         //print the file with adjusted size
iewer.AutoRotate = true;         //print the file with adjusted rotation
iewer.PrintPageDialog = false;   //do not produce the page number dialog when printing
spose.Pdf.Printing.PrinterSettings ps = new Aspose.Pdf.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
spose.Pdf.Printing.PageSettings pgs = new Aspose.Pdf.Printing.PageSettings();
gs.PaperSize = new Aspose.Pdf.Printing.PaperSize("A4", 827, 1169);
gs.Margins = new Aspose.Pdf.Devices.Margins(0, 0, 0, 0);
iewer.PrintDocumentWithSettings(pgs, ps);
iewer.Close();

VisualBasic]
im viewer As New PdfViewer()
iewer.BindPdf(@"d:\test.pdf")
iewer.AutoResize = True            'print the file with adjusted size
iewer.AutoRotate = True            'print the file with adjusted rotation
iewer.PrintPageDialog = False      'do not produce the page number dialog when printing
im ps As New Aspose.Pdf.Printing.PrinterSettings()
im prtdoc As New PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
im pgs As New Aspose.Pdf.Printing.PageSettings()
gs.PaperSize = New Aspose.Pdf.Printing.PaperSize("A4", 827, 1169)
gs.Margins = New Aspose.Pdf.Devices.Margins(0, 0, 0, 0)
iewer.PrintDocumentWithSettings(pgs, ps)
iewer.Close()
```

printerSettings-Objekt wird verwendet, um das Dokument zu drucken. pageSettings.PrinterSettings-Objekt wird ignoriert.

### Siehe auch

* Klasse [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* Klasse [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* Klasse [PdfViewer](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## PrintDocumentWithSettings(PrinterSettings) {#printdocumentwithsettings_1}

Druckt das Pdf-Dokument mit Druckereinstellungen. Die Ausgabeseitengröße passt an die Größe der ersten Seite des Dokuments an.

```csharp
public void PrintDocumentWithSettings(PrinterSettings printerSettings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| printerSettings | PrinterSettings | Die Druckereinstellungen des zu druckenden Dokuments. |

## Beispiele

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.OpenPdfFile(@"d:\test.pdf");
iewer.AutoResize = true;         //print the file with adjusted size
iewer.AutoRotate = true;         //print the file with adjusted rotation
iewer.PrintPageDialog=false;//do not produce the page number dialog when printing
ystem.Drawing.Printing.PrinterSettings ps = new System.Drawing.Printing.PrinterSettings();
rintDocument prtdoc = new PrintDocument();
s.PrinterName = prtdoc.PrinterSettings.PrinterName;
iewer.PrintDocumentWithSettings(ps);
iewer.ClosePdfFile();

VisualBasic]
im viewer As PdfViewer = new PdfViewer()
iewer.OpenPdfFile(@"d:\test.pdf")
iewer.AutoResize = true;        'print the file with adjusted size
iewer.AutoRotate = true;        'print the file with adjusted rotation
iewer.PrintPageDialog=false;//do not produce the page number dialog when printing
im ps As System.Drawing.Printing.PrinterSettings = new System.Drawing.Printing.PrinterSettings()
im prtdoc As PrintDocument = new PrintDocument()
s.PrinterName = prtdoc.PrinterSettings.PrinterName
iewer.PrintDocumentWithSettings(ps);
iewer.ClosePdfFile()
```

### Siehe auch

* Klasse [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* Klasse [PdfViewer](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)