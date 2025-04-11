---
title: PdfContentEditor.DrawCurve
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfContentEditor. Crée une annotation de courbe
type: docs
weight: 360
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/drawcurve/
---
## Méthode PdfContentEditor.DrawCurve

Crée une annotation de courbe.

```csharp
public void DrawCurve(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| lineInfo | LineInfo | L'instance de la classe LineInfo. |
| page | Int32 | Le numéro de la page originale où l'annotation sera créée. |
| annotRect | Rectangle | Le rectangle d'annotation définissant l'emplacement de l'annotation sur la page. |
| annotContents | String | Le contenu de l'annotation. |

## Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
newApiEditor.BindPdf("example.pdf");
LineInfo lineInfo = new LineInfo();
lineInfo.VerticeCoordinate = new float[] { 0, 0, 100, 100 };  //x1, y1, x2, y2, .. xn, yn
lineInfo.Visibility = true;
editor.DrawCurve(lineInfo, 1, new System.Drawing.Rectangle(0, 0, 0, 0), "Welcome to Aspose");
editor.Save("example_out.pdf");
```

### Voir aussi

* classe [LineInfo](../../lineinfo/)
* classe [PdfContentEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)