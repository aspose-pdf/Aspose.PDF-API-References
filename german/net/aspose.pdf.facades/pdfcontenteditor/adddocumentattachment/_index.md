---
title: PdfContentEditor.AddDocumentAttachment
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor-Methode. Fügt eine Dokumentanhang ohne Annotation hinzu
type: docs
weight: 70
url: /de/net/aspose.pdf.facades/pdfcontenteditor/adddocumentattachment/
---
## AddDocumentAttachment(string, string) {#adddocumentattachment_1}

Fügt eine Dokumentanhang ohne Annotation hinzu.

```csharp
public void AddDocumentAttachment(string fileAttachmentPath, string description)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileAttachmentPath | String | Der Pfad der Datei, die angehängt wird. |
| description | String | Die Beschreibungsinformationen. |

## Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAttachment("attachment_file.pdf", "description of attachment_file");
editor.Save("example_out.pdf");
```

### Siehe auch

* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## AddDocumentAttachment(Stream, string, string) {#adddocumentattachment}

Fügt eine Dokumentanhang ohne Annotation hinzu.

```csharp
public void AddDocumentAttachment(Stream fileAttachmentStream, string fileAttachmentName, 
    string description)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileAttachmentStream | Stream | Der Stream der Datei, die angehängt wird. |
| fileAttachmentName | String | Der Name des Anhangs. |
| description | String | Die Beschreibungsinformationen. |

## Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using(System.IO.FileStream attStream = System.IO.File.OpenRead("attachment_file.pdf"))
{
    editor.AddDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file");
    editor.Save("example_out.pdf");
}    
```

### Siehe auch

* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)