---
title: "PdfPageEditor.MovePosition"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfPageEditor-metod. Flyttar ursprunget från 0 0 till den angivna punkten. Ursprunget är vänsterunder och enheten är punkt1 tum  72 punkter"
type: docs
weight: 170
url: /sv/net/aspose.pdf.facades/pdfpageeditor/moveposition/
---
## PdfPageEditor.MovePosition method

Flyttar origo från (0, 0) till den angivna punkten. Origo är vänster‑nedre och enheten är point (1 tum = 72 punkter).

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

### Se även

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


