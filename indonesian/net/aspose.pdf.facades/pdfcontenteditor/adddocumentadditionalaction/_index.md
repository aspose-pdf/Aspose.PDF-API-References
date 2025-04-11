---
title: PdfContentEditor.AddDocumentAdditionalAction
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfContentEditor. Menambahkan aksi tambahan untuk peristiwa dokumen
type: docs
weight: 60
url: /id/net/aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction/
---
## Metode PdfContentEditor.AddDocumentAdditionalAction

Menambahkan aksi tambahan untuk peristiwa dokumen.

```csharp
public void AddDocumentAdditionalAction(string eventType, string code)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| eventType | String | Jenis peristiwa dokumen. |
| code | String | Kode JavaScript. |

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');");
editor.Save("example_out.pdf");
```

### Lihat Juga

* kelas [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)