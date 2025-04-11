---
title: PdfContentEditor.CreateCustomActionLink
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metodu. PDF belgesinde özel eylemlere bir bağlantı oluşturur
type: docs
weight: 140
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/createcustomactionlink/
---
## PdfContentEditor.CreateCustomActionLink metodu

PDF belgesinde özel eylemlere bir bağlantı oluşturur.

```csharp
public void CreateCustomActionLink(Rectangle rect, int originalPage, Color color, Enum[] actionName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | Rectangle | Aktif tıklama için dikdörtgen. |
| originalPage | Int32 | Bağlantı ile birlikte dikdörtgenin oluşturulacağı orijinal sayının numarası. |
| color | Color | Aktif tıklama için dikdörtgenin rengi. |
| actionName | Enum[] | Acrobat görüntüleyicisinde menü öğelerini yürütmekle ilgili eylemlerin (PredefinedAction enum'unun üyeleri) dizisi. |

## Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateCustomActionLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfContentEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)