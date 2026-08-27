---
title: "PdfContentEditor.AddDocumentAttachment"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "PdfContentEditor method. Menambahkan lampiran dokumen tanpa anotasi"
type: docs
weight: 70
url: /id/net/aspose.pdf.facades/pdfcontenteditor/adddocumentattachment/
---
## AddDocumentAttachment(string, string) {#adddocumentattachment_1}

Menambahkan lampiran dokumen tanpa anotasi.

```csharp
public void AddDocumentAttachment(string fileAttachmentPath, string description)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileAttachmentPath | String | Jalur file akan dilampirkan. |
| deskripsi | String | Informasi deskripsi. |

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAttachment("attachment_file.pdf", "description of attachment_file");
editor.Save("example_out.pdf");
```

### Lihat Juga

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddDocumentAttachment(Stream, string, string) {#adddocumentattachment}

Menambahkan lampiran dokumen tanpa anotasi.

```csharp
public void AddDocumentAttachment(Stream fileAttachmentStream, string fileAttachmentName, 
    string description)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileAttachmentStream | Stream | Aliran file akan dilampirkan. |
| fileAttachmentName | String | Nama lampiran. |
| deskripsi | String | Informasi deskripsi. |

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using(System.IO.FileStream attStream = System.IO.File.OpenRead("attachment_file.pdf"))
{
    editor.AddDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file");
    editor.Save("example_out.pdf");
}    
```

### Lihat Juga

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


