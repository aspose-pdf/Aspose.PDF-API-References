---
title: MovePosition
second_title: Référence de l'API Aspose.PDF pour .NET
description: Déplace lorigine de 0 0 au point désigné. Lorigine est en bas à gauche et lunité est le point 1 pouce  72 points.
type: docs
weight: 170
url: /fr/net/aspose.pdf.facades/pdfpageeditor/moveposition/
---
## PdfPageEditor.MovePosition method

Déplace l'origine de (0, 0) au point désigné. L'origine est en bas à gauche et l'unité est le point (1 pouce = 72 points).

```csharp
public void MovePosition(float moveX, float moveY)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| moveX | Single | Coordonnée X. |
| moveY | Single | Coordonnée Y. |

### Exemples

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("input.pdf");
editor.MovePosition(-100, 60);
editor.Save("moved.pdf");
```

### Voir également

* class [PdfPageEditor](../../pdfpageeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdfpageeditor)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
