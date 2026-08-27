---
title: "PdfContentEditor.CreateMarkup"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfContentEditor. Crée une annotation de balisage dans le document PDF"
type: docs
weight: 200
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/createmarkup/
---
## PdfContentEditor.CreateMarkup method

Crée une annotation de balisage dans le document PDF.

```csharp
public void CreateMarkup(Rectangle rect, string contents, int type, int page, Color clr)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | Rectangle | Le rectangle définissant l'emplacement de l'annotation sur la page. |
| contents | String | Le contenu de l'annotation. |
| type | Int32 | Le type d'annotation de balisage. Peut être 0 (Surlignage), 1 (Soulignement), 2 (Barré), 3 (Ondulé). |
| page | Int32 | Le numéro de la page d'origine où l'annotation sera créée. |
| clr | Color | La couleur du balisage. |

## Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateMarkup(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", 0, 1, System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### Voir aussi

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


