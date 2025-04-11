---
title: PdfContentEditor.CreatePopup
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfContentEditor. Crée une annotation popup dans un document PDF
type: docs
weight: 250
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/createpopup/
---
## Méthode PdfContentEditor.CreatePopup

Crée une annotation popup dans un document PDF.

```csharp
public void CreatePopup(Rectangle rect, string contents, bool open, int page)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | Rectangle | Le rectangle d'annotation définissant l'emplacement de l'annotation sur la page. |
| contents | String | Le contenu de l'annotation. |
| open | Boolean | Un indicateur spécifiant si l'annotation popup doit être affichée ouverte au départ. |
| page | Int32 | Le numéro de la page originale où l'annotation sera créée. |

## Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePopup(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", true, 1);
editor.Save("example_out.pdf");
```

### Voir aussi

* classe [PdfContentEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)