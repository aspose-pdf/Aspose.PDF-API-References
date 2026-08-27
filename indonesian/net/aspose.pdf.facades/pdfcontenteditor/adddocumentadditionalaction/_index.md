---
title: "PdfContentEditor.AddDocumentAdditionalAction"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfContentEditor. Menambahkan aksi tambahan untuk peristiwa dokumen"
type: docs
weight: 60
url: /id/net/aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction/
---
## PdfContentEditor.AddDocumentAdditionalAction method

Menambahkan aksi tambahan untuk acara dokumen.

```csharp
public void AddDocumentAdditionalAction(string eventType, string code)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| eventType | String | Jenis-jenis peristiwa dokumen. |
| code | String | Kode JavaScript. |

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');");
editor.Save("example_out.pdf");
```

### Lihat Juga

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


