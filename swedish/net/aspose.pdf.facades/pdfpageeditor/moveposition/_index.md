---
title: PdfPageEditor.MovePosition
second_title: Aspose.PDF for .NET API Reference
description: PdfPageEditor-metod. Flyttar ursprunget från 0 0 till den angivna punkten. Ursprunget är vänster-nederst och enheten är punkt(1 tum = 72 punkter).
type: docs
weight: 170
url: /sv/net/aspose.pdf.facades/pdfpageeditor/moveposition/
---
## PdfPageEditor.MovePosition metod

Flyttar ursprunget från (0, 0) till den angivna punkten. Ursprunget är vänster-nederst och enheten är punkt(1 tum = 72 punkter).

```csharp
public void MovePosition(float moveX, float moveY)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| moveX | Single | X-koordinat. |
| moveY | Single | Y-koordinat. |

## Exempel

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("input.pdf");
editor.MovePosition(-100, 60);
editor.Save("moved.pdf");
```

### Se Även

* klass [PdfPageEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)