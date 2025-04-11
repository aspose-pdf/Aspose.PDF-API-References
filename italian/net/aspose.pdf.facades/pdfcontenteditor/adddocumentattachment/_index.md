---
title: PdfContentEditor.AddDocumentAttachment
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfContentEditor. Aggiunge un allegato di documento senza annotazione
type: docs
weight: 70
url: /it/net/aspose.pdf.facades/pdfcontenteditor/adddocumentattachment/
---
## AddDocumentAttachment(string, string) {#adddocumentattachment_1}

Aggiunge un allegato di documento senza annotazione.

```csharp
public void AddDocumentAttachment(string fileAttachmentPath, string description)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileAttachmentPath | String | Il percorso del file che sarà allegato. |
| description | String | Le informazioni di descrizione. |

## Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAttachment("attachment_file.pdf", "description of attachment_file");
editor.Save("example_out.pdf");
```

### Vedi Anche

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddDocumentAttachment(Stream, string, string) {#adddocumentattachment}

Aggiunge un allegato di documento senza annotazione.

```csharp
public void AddDocumentAttachment(Stream fileAttachmentStream, string fileAttachmentName, 
    string description)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileAttachmentStream | Stream | Il flusso del file che sarà allegato. |
| fileAttachmentName | String | Il nome dell'allegato. |
| description | String | Le informazioni di descrizione. |

## Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using(System.IO.FileStream attStream = System.IO.File.OpenRead("attachment_file.pdf"))
{
    editor.AddDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file");
    editor.Save("example_out.pdf");
}    
```

### Vedi Anche

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)