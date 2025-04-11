---
title: PdfContentEditor.AddDocumentAttachment
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Adiciona anexo de documento sem anotação
type: docs
weight: 70
url: /pt/net/aspose.pdf.facades/pdfcontenteditor/adddocumentattachment/
---
## AddDocumentAttachment(string, string) {#adddocumentattachment_1}

Adiciona anexo de documento sem anotação.

```csharp
public void AddDocumentAttachment(string fileAttachmentPath, string description)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fileAttachmentPath | String | O caminho do arquivo que será anexado. |
| description | String | As informações de descrição. |

## Exemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAttachment("attachment_file.pdf", "description of attachment_file");
editor.Save("example_out.pdf");
```

### Veja Também

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddDocumentAttachment(Stream, string, string) {#adddocumentattachment}

Adiciona anexo de documento sem anotação.

```csharp
public void AddDocumentAttachment(Stream fileAttachmentStream, string fileAttachmentName, 
    string description)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fileAttachmentStream | Stream | O fluxo do arquivo que será anexado. |
| fileAttachmentName | String | O nome do anexo. |
| description | String | As informações de descrição. |

## Exemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using(System.IO.FileStream attStream = System.IO.File.OpenRead("attachment_file.pdf"))
{
    editor.AddDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file");
    editor.Save("example_out.pdf");
}    
```

### Veja Também

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)