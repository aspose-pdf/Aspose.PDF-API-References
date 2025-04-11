---
title: PdfContentEditor.RemoveDocumentOpenAction
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfContentEditor. Menghapus aksi buka dari dokumen. Operasi ini berguna saat menggabungkan beberapa dokumen yang menggunakan aksi 'GoTo' eksplisit saat startup
type: docs
weight: 430
url: /id/net/aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction/
---
## Metode PdfContentEditor.RemoveDocumentOpenAction

Menghapus aksi buka dari dokumen. Operasi ini berguna saat menggabungkan beberapa dokumen yang menggunakan aksi 'GoTo' eksplisit saat startup.

```csharp
public void RemoveDocumentOpenAction()
```

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.RemoveDocumentOpenAction();
editor.Save("example_out.pdf");
```

### Lihat Juga

* kelas [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)