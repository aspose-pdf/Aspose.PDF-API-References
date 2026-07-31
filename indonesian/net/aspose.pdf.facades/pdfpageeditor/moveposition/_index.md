---
title: "PdfPageEditor.MovePosition"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "PdfPageEditor method. Memindahkan asal dari 0 0 ke titik yang ditunjuk. Asal berada di kiri-bawah dan satuannya adalah point1 inch  72 points"
type: docs
weight: 170
url: /id/net/aspose.pdf.facades/pdfpageeditor/moveposition/
---
## PdfPageEditor.MovePosition method

Memindahkan asal dari (0, 0) ke titik yang ditunjuk. Asal berada di kiri-bawah dan satuannya adalah point (1 inci = 72 point).

```csharp
public void MovePosition(float moveX, float moveY)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| moveX | Single | Koordinat X. |
| moveY | Single | Koordinat Y. |

## Contoh

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("input.pdf");
editor.MovePosition(-100, 60);
editor.Save("moved.pdf");
```

### Lihat Juga

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


