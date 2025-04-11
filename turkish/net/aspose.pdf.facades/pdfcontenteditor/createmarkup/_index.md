---
title: PdfContentEditor.CreateMarkup
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metodu. PDF belgesinde işaretleme notu oluşturur
type: docs
weight: 200
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/createmarkup/
---
## PdfContentEditor.CreateMarkup metodu

PDF belgesinde işaretleme notu oluşturur.

```csharp
public void CreateMarkup(Rectangle rect, string contents, int type, int page, Color clr)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | Rectangle | Notun sayfadaki konumunu tanımlayan dikdörtgen. |
| contents | String | Notun içeriği. |
| type | Int32 | İşaretleme notunun türü. 0 (Vurgulama), 1 (Altını Çizme), 2 (Üstü Çizili), 3 (Dalgalı) olabilir. |
| page | Int32 | Notun oluşturulacağı orijinal sayfanın numarası. |
| clr | Color | İşaretlemenin rengi. |

## Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateMarkup(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", 0, 1, System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfContentEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)