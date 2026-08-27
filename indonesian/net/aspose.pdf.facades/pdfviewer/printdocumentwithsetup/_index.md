---
title: "PdfViewer.PrintDocumentWithSetup"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfViewer. Mencetak dokumen Pdf dengan dialog pengaturan. Pilih printer menggunakan dialog tersebut."
type: docs
weight: 340
url: /id/net/aspose.pdf.facades/pdfviewer/printdocumentwithsetup/
---
## PdfViewer.PrintDocumentWithSetup method

Mencetak dokumen Pdf dengan dialog pengaturan. Pilih printer menggunakan dialog tersebut.

```csharp
public void PrintDocumentWithSetup()
```

## Contoh

```csharp
[C#]
dfViewer viewer = new PdfViewer();
iewer.BindPdf(@"d:\test.pdf");
iewer.AutoResize = true;         //print the file with adjusted size
iewer.AutoRotate = true;         //print the file with adjusted rotation
iewer.PrintPageDialog = false;   //do not produce the page number dialog when printing
iewer.PrintDocumentWithSetup();
iewer.Close();

VisualBasic]
im viewer As New PdfViewer()
iewer.BindPdf(@"d:\test.pdf")
iewer.AutoResize = True          'print the file with adjusted size
iewer.AutoRotate = True          'print the file with adjusted rotation
iewer.PrintPageDialog = False    'do not produce the page number dialog when printing
iewer.PrintDocumentWithSetup()
iewer.Close()
```

### Lihat Juga

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


