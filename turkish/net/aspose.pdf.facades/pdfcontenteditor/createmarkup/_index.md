---
title: CreateMarkup
second_title: Aspose.PDF for .NET API Referansı
description: PDF belgesinde işaretleme ek açıklaması oluşturur.
type: docs
weight: 200
url: /tr/net/aspose.pdf.facades/pdfcontenteditor/createmarkup/
---
## PdfContentEditor.CreateMarkup method

PDF belgesinde işaretleme ek açıklaması oluşturur.

```csharp
public void CreateMarkup(Rectangle rect, string contents, int type, int page, Color clr)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| rect | Rectangle | Ek açıklamanın sayfadaki konumunu tanımlayan dikdörtgen. |
| contents | String | Açıklamanın içeriği. |
| type | Int32 | İşaretleme ek açıklamasının türü. 0 (Vurgu), 1 (Altı Çizili), 2 (Çizgili), 3 (Dalgalı) olabilir. |
| page | Int32 | Ek açıklamanın oluşturulacağı orijinal sayfanın sayısı. |
| clr | Color | İşaretleme rengi. |

### Örnekler

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateMarkup(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", 0, 1, System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### Ayrıca bakınız

* class [PdfContentEditor](../../pdfcontenteditor)
* ad alanı [Aspose.Pdf.Facades](../../pdfcontenteditor)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->