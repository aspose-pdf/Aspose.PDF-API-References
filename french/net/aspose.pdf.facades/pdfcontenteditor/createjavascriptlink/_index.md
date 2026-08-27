---
title: "PdfContentEditor.CreateJavaScriptLink"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfContentEditor. Crée un lien vers JavaScript dans le document PDF"
type: docs
weight: 170
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/createjavascriptlink/
---
## PdfContentEditor.CreateJavaScriptLink method

Crée un lien vers JavaScript dans le document PDF.

```csharp
public void CreateJavaScriptLink(string code, Rectangle rect, int originalPage, Color color)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| code | String | Le code JavaScript. |
| rect | Rectangle | Le rectangle pour le clic actif. |
| originalPage | Int32 | Le numéro de la page d'origine où le rectangle lié au lien sera créé. |
| color | Color | La couleur du rectangle pour le clic actif. |

## Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateJavaScriptLink("app.alert('welcome to aspose!');",
    new System.Drawing.Rectangle(0, 0, 100, 100), 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### Voir aussi

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


