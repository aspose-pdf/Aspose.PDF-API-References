---
title: ModifyAnnotationsAuthor
second_title: Aspose.PDF für .NET-API-Referenz
description: Ändert den Autor von Anmerkungen im angegebenen Seitenbereich.
type: docs
weight: 120
url: /de/net/aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor/
---
## PdfAnnotationEditor.ModifyAnnotationsAuthor method

Ändert den Autor von Anmerkungen im angegebenen Seitenbereich.

```csharp
public void ModifyAnnotationsAuthor(int start, int end, string srcAuthor, string desAuthor)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| start | Int32 | Die Startseitennummer. |
| end | Int32 | Die letzte Seitenzahl. |
| srcAuthor | String | Der Autor, der geändert werden muss. |
| desAuthor | String | Der neue Autor. |

### Beispiele

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ModifyAnnotationsAuthor(1, 2, "PREV AUTHOR", "NEW AUTHOR");
editor.Save("example_out.pdf");
```

### Siehe auch

* class [PdfAnnotationEditor](../../pdfannotationeditor)
* namensraum [Aspose.Pdf.Facades](../../pdfannotationeditor)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
