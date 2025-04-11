---
title: PdfPageEditor.MovePosition
second_title: Aspose.PDF for .NET API Reference
description: Método PdfPageEditor. Mueve el origen de (0, 0) al punto que se indica. El origen es la esquina inferior izquierda y la unidad es punto (1 pulgada = 72 puntos).
type: docs
weight: 170
url: /es/net/aspose.pdf.facades/pdfpageeditor/moveposition/
---
## Método PdfPageEditor.MovePosition

Mueve el origen de (0, 0) al punto que se indica. El origen es la esquina inferior izquierda y la unidad es punto (1 pulgada = 72 puntos).

```csharp
public void MovePosition(float moveX, float moveY)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| moveX | Single | Coordenada X. |
| moveY | Single | Coordenada Y. |

## Ejemplos

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("input.pdf");
editor.MovePosition(-100, 60);
editor.Save("moved.pdf");
```

### Ver También

* clase [PdfPageEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)