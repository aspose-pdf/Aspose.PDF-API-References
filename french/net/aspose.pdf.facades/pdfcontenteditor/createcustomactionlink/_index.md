---
title: PdfContentEditor.CreateCustomActionLink
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfContentEditor. Crée un lien vers des actions personnalisées dans un document PDF
type: docs
weight: 140
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/createcustomactionlink/
---
## Méthode PdfContentEditor.CreateCustomActionLink

Crée un lien vers des actions personnalisées dans un document PDF.

```csharp
public void CreateCustomActionLink(Rectangle rect, int originalPage, Color color, Enum[] actionName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | Rectangle | Le rectangle pour le clic actif. |
| originalPage | Int32 | Le numéro de la page originale où le rectangle lié au lien sera créé. |
| color | Color | La couleur du rectangle pour le clic actif. |
| actionName | Enum[] | Le tableau d'actions (membres de l'énumération PredefinedAction) correspondant à l'exécution des éléments de menu dans le visualiseur Acrobat. |

## Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateCustomActionLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### Voir aussi

* classe [PdfContentEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)