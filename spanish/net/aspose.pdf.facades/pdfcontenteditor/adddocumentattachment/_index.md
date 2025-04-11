---
title: PdfContentEditor.AddDocumentAttachment
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Agrega un archivo adjunto de documento sin anotación
type: docs
weight: 70
url: /es/net/aspose.pdf.facades/pdfcontenteditor/adddocumentattachment/
---
## AddDocumentAttachment(string, string) {#adddocumentattachment_1}

Agrega un archivo adjunto de documento sin anotación.

```csharp
public void AddDocumentAttachment(string fileAttachmentPath, string description)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileAttachmentPath | String | La ruta del archivo que se adjuntará. |
| description | String | La información de descripción. |

## Ejemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAttachment("attachment_file.pdf", "description of attachment_file");
editor.Save("example_out.pdf");
```

### Véase también

* clase [PdfContentEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## AddDocumentAttachment(Stream, string, string) {#adddocumentattachment}

Agrega un archivo adjunto de documento sin anotación.

```csharp
public void AddDocumentAttachment(Stream fileAttachmentStream, string fileAttachmentName, 
    string description)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileAttachmentStream | Stream | El flujo del archivo que se adjuntará. |
| fileAttachmentName | String | El nombre del archivo adjunto. |
| description | String | La información de descripción. |

## Ejemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using(System.IO.FileStream attStream = System.IO.File.OpenRead("attachment_file.pdf"))
{
    editor.AddDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file");
    editor.Save("example_out.pdf");
}    
```

### Véase también

* clase [PdfContentEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)