---
title: "PdfBookmarkEditor.DeleteBookmarks"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfBookmarkEditor. Elimina tutti i segnalibri del documento PDF."
type: docs
weight: 40
url: /it/net/aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/
---
## DeleteBookmarks() {#deletebookmarks}

Elimina tutti i segnalibri del PDF Document.

```csharp
public void DeleteBookmarks()
```

## Esempi

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.DeleteBookmarks();
editor.Save("example_out.pdf");
```

### Vedi anche

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteBookmarks(string) {#deletebookmarks_1}

Elimina il segnalibro del PDF Document.

```csharp
public void DeleteBookmarks(string title)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| title | String | Il titolo del segnalibro eliminato. |

## Esempi

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.DeleteBookmarks("existing bookmark title");
editor.Save("example_out.pdf");
```

### Vedi anche

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


