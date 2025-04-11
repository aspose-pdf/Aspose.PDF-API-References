---
title: PdfPageEditor.MovePosition
second_title: Aspose.PDF for .NET API Reference
description: PdfPageEditor metodu. Orijini (0, 0) noktasından belirlenen noktaya taşır. Orijin sol-alt köşededir ve birim point(1 inç = 72 point)dir.
type: docs
weight: 170
url: /tr/net/aspose.pdf.facades/pdfpageeditor/moveposition/
---
## PdfPageEditor.MovePosition metodu

Orijini (0, 0) noktasından belirlenen noktaya taşır. Orijin sol-alt köşededir ve birim point(1 inç = 72 point)dir.

```csharp
public void MovePosition(float moveX, float moveY)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| moveX | Tekil | X-koordinatı. |
| moveY | Tekil | Y-koordinatı. |

## Örnekler

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("input.pdf");
editor.MovePosition(-100, 60);
editor.Save("moved.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfPageEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)