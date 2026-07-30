---
title: "PdfPageEditor.MovePosition"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfPageEditor. Déplace l'origine de 0 0 vers le point indiqué. L'origine est en bas à gauche et l'unité est le point (1 pouce = 72 points)"
type: docs
weight: 170
url: /fr/net/aspose.pdf.facades/pdfpageeditor/moveposition/
---
## PdfPageEditor.MovePosition method

Déplace l'origine de (0, 0) vers le point indiqué. L'origine est en bas à gauche et l'unité est le point (1 pouce = 72 points).

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

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


