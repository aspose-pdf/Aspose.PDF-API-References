---
title: PdfContentEditor.CreateBookmarksAction
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfContentEditor. Crée un signet avec l'action spécifiée
type: docs
weight: 120
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/createbookmarksaction/
---
## Méthode PdfContentEditor.CreateBookmarksAction

Crée un signet avec l'action spécifiée.

```csharp
public void CreateBookmarksAction(string title, Color color, bool boldFlag, bool italicFlag, 
    string file, string actionType, string destination)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| title | String | Le titre du signet. |
| color | Color | La couleur du titre du signet. |
| boldFlag | Boolean | Le drapeau d'attribution en gras. |
| italicFlag | Boolean | Le drapeau d'attribution en italique. |
| file | String | Un autre fichier ou application requis lorsque le type d'action est "GoToR" ou "Launch". |
| actionType | String | Le type d'action. La valeur peut être : "GoToR", "Launch", "GoTo", "URI". |
| destination | String | La destination locale ou la destination distante ou l'URL. |

## Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarksAction("bookmark title",
    System.Drawing.Color.Red, true, true, null, "GoTo", 1/*page number*/);
editor.Save("example_out.pdf");
```

### Voir aussi

* classe [PdfContentEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)