---
title: "PdfBookmarkEditor.ModifyBookmarks"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "PdfBookmarkEditor méthode. Modifie le titre du signet selon le titre de signet spécifié"
type: docs
weight: 80
url: /fr/net/aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/
---
## PdfBookmarkEditor.ModifyBookmarks method

Modifie le titre du signet selon le titre du signet spécifié.

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

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


