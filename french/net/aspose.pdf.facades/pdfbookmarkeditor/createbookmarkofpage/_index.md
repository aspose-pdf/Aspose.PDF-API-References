---
title: PdfBookmarkEditor.CreateBookmarkOfPage
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfBookmarkEditor. Crée un signet pour la page spécifiée
type: docs
weight: 20
url: /fr/net/aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/
---
## CreateBookmarkOfPage(string, int) {#createbookmarkofpage}

Crée un signet pour la page spécifiée.

```csharp
public void CreateBookmarkOfPage(string bookmarkName, int pageNumber)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| bookmarkName | String | Le nom du signet spécifié. |
| pageNumber | Int32 | La page de destination spécifiée. |

## Exemples

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarkOfPage("bookmark for page 1", 1);
editor.Save("example_out.pdf");
```

### Voir aussi

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateBookmarkOfPage(string[], int[]) {#createbookmarkofpage_1}

Crée des signets pour les pages spécifiées.

```csharp
public void CreateBookmarkOfPage(string[] bookmarkName, int[] pageNumber)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| bookmarkName | String[] | Tableau de titres de signets. |
| pageNumber | Int32[] | Tableau de pages de destination des signets. |

## Exemples

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarkOfPage("bookmark for page 1", 1);
editor.Save("example_out.pdf");
```

### Voir aussi

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)