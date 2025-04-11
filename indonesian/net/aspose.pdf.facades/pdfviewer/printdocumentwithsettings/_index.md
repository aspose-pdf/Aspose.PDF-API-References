---
title: PdfViewer.PrintDocumentWithSettings
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfViewer. Mencetak dokumen Pdf dengan pengaturan. Jika ukuran dokumen tidak sesuai dengan ukuran halaman, itu akan diperpanjang untuk sesuai dengan ukuran halaman
type: docs
weight: 330
url: /id/net/aspose.pdf.facades/pdfviewer/printdocumentwithsettings/
---
## PrintDocumentWithSettings(PageSettings, PrinterSettings) {#printdocumentwithsettings}

Mencetak dokumen Pdf dengan pengaturan. Jika ukuran dokumen tidak sesuai dengan ukuran halaman, itu akan diperpanjang untuk sesuai dengan ukuran halaman.

```csharp
public void PrintDocumentWithSettings(PageSettings pageSettings, PrinterSettings printerSettings)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageSettings | PageSettings | Pengaturan halaman dari dokumen yang dicetak. |
| printerSettings | PrinterSettings | Pengaturan printer dari dokumen yang dicetak. |

## Contoh

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

objek printerSettings digunakan untuk mencetak dokumen. objek pageSettings.PrinterSettings diabaikan.

### Lihat Juga

* kelas [PageSettings](../../../aspose.pdf.printing/pagesettings/)
* kelas [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* kelas [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PrintDocumentWithSettings(PrinterSettings) {#printdocumentwithsettings_1}

Mencetak dokumen Pdf dengan pengaturan printer. Ukuran halaman keluaran akan sesuai dengan ukuran halaman pertama dokumen.

```csharp
public void PrintDocumentWithSettings(PrinterSettings printerSettings)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| printerSettings | PrinterSettings | Pengaturan printer dari dokumen yang dicetak. |

## Contoh

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

### Lihat Juga

* kelas [PrinterSettings](../../../aspose.pdf.printing/printersettings/)
* kelas [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)