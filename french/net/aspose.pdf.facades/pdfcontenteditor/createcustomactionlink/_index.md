---
title: "PdfContentEditor.CreateCustomActionLink"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfContentEditor. Crée un lien vers des actions personnalisées dans le document PDF"
type: docs
weight: 140
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/createcustomactionlink/
---
## PdfContentEditor.CreateCustomActionLink method

Crée un lien vers des actions personnalisées dans le document PDF.

```csharp
public void CreateCustomActionLink(Rectangle rect, int originalPage, Color color, Enum[] actionName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | Rectangle | Le rectangle pour le clic actif. |
| originalPage | Int32 | Le numéro de la page d'origine où le rectangle lié au lien sera créé. |
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

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


