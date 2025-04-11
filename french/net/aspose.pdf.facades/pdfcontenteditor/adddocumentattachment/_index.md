---
title: PdfContentEditor.AddDocumentAttachment
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfContentEditor. Ajoute une pièce jointe de document sans annotation
type: docs
weight: 70
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/adddocumentattachment/
---
## AddDocumentAttachment(string, string) {#adddocumentattachment_1}

Ajoute une pièce jointe de document sans annotation.

```csharp
public void AddDocumentAttachment(string fileAttachmentPath, string description)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileAttachmentPath | String | Le chemin du fichier qui sera joint. |
| description | String | Les informations de description. |

## Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAttachment("attachment_file.pdf", "description of attachment_file");
editor.Save("example_out.pdf");
```

### Voir aussi

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddDocumentAttachment(Stream, string, string) {#adddocumentattachment}

Ajoute une pièce jointe de document sans annotation.

```csharp
public void AddDocumentAttachment(Stream fileAttachmentStream, string fileAttachmentName, 
    string description)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileAttachmentStream | Stream | Le flux du fichier qui sera joint. |
| fileAttachmentName | String | Le nom de la pièce jointe. |
| description | String | Les informations de description. |

## Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using(System.IO.FileStream attStream = System.IO.File.OpenRead("attachment_file.pdf"))
{
    editor.AddDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file");
    editor.Save("example_out.pdf");
}    
```

### Voir aussi

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)