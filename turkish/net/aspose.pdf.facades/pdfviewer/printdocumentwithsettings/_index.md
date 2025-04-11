---
title: PdfViewer.PrintDocumentWithSettings
second_title: Aspose.PDF for .NET API Reference
description: PdfViewer metodu. Pdf belgesini ayarlarla yazdırır. Eğer belge boyutu sayfa boyutuna uymuyorsa, sayfa boyutuna uyacak şekilde uzatılacaktır.
type: docs
weight: 330
url: /tr/net/aspose.pdf.facades/pdfviewer/printdocumentwithsettings/
---
## PrintDocumentWithSettings(PageSettings, PrinterSettings) {#printdocumentwithsettings}

Pdf belgesini ayarlarla yazdırır. Eğer belge boyutu sayfa boyutuna uymuyorsa, sayfa boyutuna uyacak şekilde uzatılacaktır.

```csharp
public void PrintDocumentWithSettings(PageSettings pageSettings, PrinterSettings printerSettings)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageSettings | PageSettings | Yazdırılacak belgenin sayfa ayarı. |
| printerSettings | PrinterSettings | Yazdırılacak belgenin yazıcı ayarı. |

## Örnekler

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

printerSettings nesnesi belgeyi yazdırmak için kullanılır. pageSettings.PrinterSettings nesnesi göz ardı edilir.

### Ayrıca Bakınız

* sınıf [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* sınıf [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* sınıf [PdfViewer](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## PrintDocumentWithSettings(PrinterSettings) {#printdocumentwithsettings_1}

Pdf belgesini yazıcı ayarlarıyla yazdırır. Çıktı sayfa boyutu, belgenin ilk sayfa boyutuna uyacaktır.

```csharp
public void PrintDocumentWithSettings(PrinterSettings printerSettings)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| printerSettings | PrinterSettings | Yazdırılacak belgenin yazıcı ayarı. |

## Örnekler

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

### Ayrıca Bakınız

* sınıf [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* sınıf [PdfViewer](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)