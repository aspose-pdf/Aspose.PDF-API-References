---
title: PdfContentEditor.DeleteStamp
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor-Methode. Löscht mehrere Stempel auf der angegebenen Seite anhand der Stempelindizes
type: docs
weight: 330
url: /de/net/aspose.pdf.facades/pdfcontenteditor/deletestamp/
---
## PdfContentEditor.DeleteStamp-Methode

Löscht mehrere Stempel auf der angegebenen Seite anhand der Stempelindizes.

```csharp
public void DeleteStamp(int pageNumber, int[] index)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumber | Int32 | Seitennummer, auf der der Stempel gelöscht wird. |
| index | Int32[] | Stempelindizes. |

## Beispiele

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStamp(1, new int[] { 2, 3, 5} );
contentEditor.Save("outfile.pdf");
```

### Siehe auch

* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)