---
title: PdfContentEditor.CreatePolyLine
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfContentEditor. Crée une annotation de polyligne
type: docs
weight: 240
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/createpolyline/
---
## Méthode PdfContentEditor.CreatePolyLine

Crée une annotation de polyligne.

```csharp
public void CreatePolyLine(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
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
editor.BindPdf("example.pdf");
LineInfo lineInfo = new LineInfo();
lineInfo.VerticeCoordinate = new float[] { 0, 0, 100, 100, 100, 50 };
lineInfo.Visibility = true;
editor.CreatePolyLine(lineInfo, 1 , new System.Drawing.Rectangle(0, 0, 0, 0), "Welcome to Aspose");
editor.Save("example_out.pdf");
```

### Voir aussi

* classe [LineInfo](../../lineinfo/)
* classe [PdfContentEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)