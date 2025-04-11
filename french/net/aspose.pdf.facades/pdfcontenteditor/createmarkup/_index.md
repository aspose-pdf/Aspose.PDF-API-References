---
title: PdfContentEditor.CreateMarkup
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfContentEditor. Crée une annotation de marquage dans un document PDF
type: docs
weight: 200
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/createmarkup/
---
## Méthode PdfContentEditor.CreateMarkup

Crée une annotation de marquage dans un document PDF.

```csharp
public void CreateMarkup(Rectangle rect, string contents, int type, int page, Color clr)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | Rectangle | Le rectangle définissant l'emplacement de l'annotation sur la page. |
| contents | String | Le contenu de l'annotation. |
| type | Int32 | Le type d'annotation de marquage. Peut être 0 (Surligner), 1 (Souligner), 2 (Barré), 3 (Ondulé). |
| page | Int32 | Le numéro de la page originale où l'annotation sera créée. |
| clr | Color | La couleur du marquage. |

## Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateMarkup(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", 0, 1, System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### Voir aussi

* classe [PdfContentEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)