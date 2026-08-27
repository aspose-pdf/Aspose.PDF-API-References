---
title: "PdfBookmarkEditor.DeleteBookmarks"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "PdfBookmarkEditor méthode. Supprime tous les signets du document PDF"
type: docs
weight: 40
url: /fr/net/aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/
---
## DeleteBookmarks() {#deletebookmarks}

Supprime tous les signets du document PDF.

```csharp
public void DeleteBookmarks()
```

## Exemples

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.DeleteBookmarks();
editor.Save("example_out.pdf");
```

### Voir aussi

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteBookmarks(string) {#deletebookmarks_1}

Supprime le signet du document PDF.

```csharp
public void DeleteBookmarks(string title)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| title | String | Le titre du signet supprimé. |

## Exemples

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.DeleteBookmarks("existing bookmark title");
editor.Save("example_out.pdf");
```

### Voir aussi

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


