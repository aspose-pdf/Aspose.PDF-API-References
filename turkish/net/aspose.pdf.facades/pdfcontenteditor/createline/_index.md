---
title: PdfContentEditor.CreateLine
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metodu. Çizgi notasyonu oluşturur
type: docs
weight: 180
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/createline/
---
## PdfContentEditor.CreateLine metodu

Çizgi notasyonu oluşturur.

```csharp
public void CreateLine(Rectangle rect, string contents, float x1, float y1, float x2, float y2, 
    int page, int border, Color clr, string borderStyle, int[] dashArray, string[] LEArray)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | Rectangle | Notasyonun sayfadaki konumunu tanımlayan notasyon dikdörtgeni. |
| contents | String | Notasyonun içeriği. |
| x1 | Single | Çizginin başlangıç yatay koordinatı. |
| y1 | Single | Çizginin başlangıç dikey koordinatı. |
| x2 | Single | Çizginin bitiş yatay koordinatı. |
| y2 | Single | Çizginin bitiş dikey koordinatı. |
| page | Int32 | Notasyonun oluşturulacağı orijinal sayfa numarası. |
| border | Int32 | Nokta cinsinden kenar genişliği. Bu değer 0 ise kenar çizilmez. Varsayılan değer 1'dir. |
| clr | Color | Çizginin rengi. |
| borderStyle | String | Çizgiyi çizerken kullanılacak genişlik ve kesik desenini belirten kenar stili. Bu değerler şunlar olabilir: "S" (Düz), "D" (Kesik), "B" (Eğik), "I" (İçte), "U" (Altı Çizili). |
| dashArray | Int32[] | Kesik bir kenar çizmek için kullanılacak kesik ve boşluk desenini tanımlayan bir kesik dizisi. Kullanıldığında, borderStyle buna göre "D" olarak ayarlanmalıdır. |
| LEArray | String[] | Çizgi çiziminin başlangıç ve bitiş stilini belirten iki değerden oluşan bir dizi. Değerler şunlar olabilir: "Kare", "Daire", "Elmas", "Açık Ok", "Kapalı Ok", "Yok", "Düz", "ROpenArrow", "RClosedArrow", "Eğik". |

## Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLine(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 0, 0, 100, 100,
    1, 1, System.Drawing.Color.Red, "D", new int[] {2, 3}, new string[] {"OpenArrow", "ClosedArrow"});
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfContentEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)