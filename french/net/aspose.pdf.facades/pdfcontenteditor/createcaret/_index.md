---
title: PdfContentEditor.CreateCaret
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfContentEditor. Crée une annotation de caret
type: docs
weight: 130
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/createcaret/
---
## Méthode PdfContentEditor.CreateCaret

Crée une annotation de caret.

```csharp
public void CreateCaret(int page, Rectangle annotRect, Rectangle caretRect, string symbol, 
    string annotContents, Color color)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| page | Int32 | Le numéro de la page originale où l'annotation sera créée. |
| annotRect | Rectangle | Le rectangle d'annotation définissant l'emplacement de l'annotation sur la page. |
| caretRect | Rectangle | Les limites réelles du caret sous-jacent. |
| symbol | String | Un symbole sera associé au caret. La valeur peut être : "P" (Paragraphe), "Aucun". |
| annotContents | String | Le contenu de l'annotation. |
| color | Color | La couleur de l'annotation. |

## Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateCaret(1,
    new System.Drawing.Rectangle(50, 50, 100, 100),
    new System.Drawing.Rectangle(60, 60, 70, 70),
    "None", "Welcome to Aspose", System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### Voir aussi

* classe [PdfContentEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)