---
title: PdfBookmarkEditor.ModifyBookmarks
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfBookmarkEditor. Modifie le titre du signet selon le titre de signet spécifié
type: docs
weight: 80
url: /fr/net/aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/
---
## Méthode PdfBookmarkEditor.ModifyBookmarks

Modifie le titre du signet selon le titre de signet spécifié.

```csharp
public void ModifyBookmarks(string sTitle, string dTitle)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sTitle | String | Titre du signet source. |
| dTitle | String | Titre du signet modifié. |

## Exemples

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ModifyBookmarks("existing bookmark title", "new bookmark title");
editor.Save("example_out.pdf");
```

### Voir aussi

* classe [PdfBookmarkEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)