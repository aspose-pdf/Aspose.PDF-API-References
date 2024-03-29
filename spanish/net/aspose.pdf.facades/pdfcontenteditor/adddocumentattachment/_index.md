---
title: AddDocumentAttachment
second_title: Referencia de API de Aspose.PDF para .NET
description: Agrega documento adjunto sin anotación.
type: docs
weight: 70
url: /es/net/aspose.pdf.facades/pdfcontenteditor/adddocumentattachment/
---
## AddDocumentAttachment(string, string) {#adddocumentattachment_1}

Agrega documento adjunto sin anotación.

```csharp
public void AddDocumentAttachment(string fileAttachmentPath, string description)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fileAttachmentPath | String | Se adjuntará la ruta del archivo. |
| description | String | La información de la descripción. |

### Ejemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAttachment("attachment_file.pdf", "description of attachment_file");
editor.Save("example_out.pdf");
```

### Ver también

* class [PdfContentEditor](../../pdfcontenteditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfcontenteditor)
* asamblea [Aspose.PDF](../../../)

---

## AddDocumentAttachment(Stream, string, string) {#adddocumentattachment}

Agrega documento adjunto sin anotación.

```csharp
public void AddDocumentAttachment(Stream fileAttachmentStream, string fileAttachmentName, 
    string description)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fileAttachmentStream | Stream | Se adjuntará la transmisión del archivo. |
| fileAttachmentName | String | El nombre del archivo adjunto. |
| description | String | La información de la descripción. |

### Ejemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using(System.IO.FileStream attStream = System.IO.File.OpenRead("attachment_file.pdf"))
{
    editor.AddDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file");
    editor.Save("example_out.pdf");
}    
```

### Ver también

* class [PdfContentEditor](../../pdfcontenteditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfcontenteditor)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
