---
title: PdfPageEditor.MovePosition
second_title: Aspose.PDF for .NET API Reference
description: PdfPageEditor-Methode. Bewegt den Ursprung von 0 0 zu dem angegebenen Punkt. Der Ursprung ist unten links und die Einheit ist Punkt (1 Zoll = 72 Punkte).
type: docs
weight: 170
url: /de/net/aspose.pdf.facades/pdfpageeditor/moveposition/
---
## PdfPageEditor.MovePosition-Methode

Bewegt den Ursprung von (0, 0) zu dem angegebenen Punkt. Der Ursprung ist unten links und die Einheit ist Punkt (1 Zoll = 72 Punkte).

```csharp
public void MovePosition(float moveX, float moveY)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| moveX | Einzel | X-Koordinate. |
| moveY | Einzel | Y-Koordinate. |

## Beispiele

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("input.pdf");
editor.MovePosition(-100, 60);
editor.Save("moved.pdf");
```

### Siehe auch

* Klasse [PdfPageEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)