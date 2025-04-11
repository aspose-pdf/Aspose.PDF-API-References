---
title: PdfPageEditor.MovePosition
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfPageEditor. Memindahkan titik asal dari 0 0 ke titik yang ditunjuk. Titik asal berada di kiri-bawah dan satuannya adalah point(1 inci = 72 poin)
type: docs
weight: 170
url: /id/net/aspose.pdf.facades/pdfpageeditor/moveposition/
---
## Metode PdfPageEditor.MovePosition

Memindahkan titik asal dari (0, 0) ke titik yang ditunjuk. Titik asal berada di kiri-bawah dan satuannya adalah point(1 inci = 72 poin).

```csharp
public void MovePosition(float moveX, float moveY)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| moveX | Single | Koordinat-X. |
| moveY | Single | Koordinat-Y. |

## Contoh

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("input.pdf");
editor.MovePosition(-100, 60);
editor.Save("moved.pdf");
```

### Lihat Juga

* kelas [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)