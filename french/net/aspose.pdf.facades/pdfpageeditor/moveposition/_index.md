---
title: PdfPageEditor.MovePosition
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfPageEditor. Déplace l'origine au point désigné. L'origine est en bas à gauche et l'unité est point. 1 pouce = 72 points
type: docs
weight: 170
url: /fr/net/aspose.pdf.facades/pdfpageeditor/moveposition/
---
## Méthode PdfPageEditor.MovePosition

Déplace l'origine de (0, 0) au point désigné. L'origine est en bas à gauche et l'unité est point (1 pouce = 72 points).

```csharp
public void MovePosition(float moveX, float moveY)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| moveX | Single | Coordonnée X. |
| moveY | Single | Coordonnée Y. |

## Exemples

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("input.pdf");
editor.MovePosition(-100, 60);
editor.Save("moved.pdf");
```

### Voir aussi

* classe [PdfPageEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)