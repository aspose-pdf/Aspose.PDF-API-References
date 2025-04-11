---
title: PdfAOptionsBase.ExcludeFontsStrategy
second_title: Aspose.PDF for .NET API Reference
description: PdfAOptionsBase özelliği. PDF/A dönüşüm sürecinde çıktı dosya boyutunu en aza indirmek için fontları kaldırma stratejisini alır veya ayarlar
type: docs
weight: 30
url: /tr/net/aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/
---
## PdfAOptionsBase.ExcludeFontsStrategy özelliği

PDF/A dönüşüm sürecinde çıktı dosya boyutunu en aza indirmek için fontları kaldırma stratejisini alır veya ayarlar.

```csharp
public RemoveFontsStrategy ExcludeFontsStrategy { get; set; }
```

### Özellik Değeri

Fontları kaldırma stratejisi. Bu, [`RemoveFontsStrategy`](../../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy/) enumerasyonundaki değerlerden biri olabilir. Varsayılan, SubsetFonts ve RemoveDuplicatedFonts kombinasyonudur.

## Açıklamalar

Bu özellik, dönüşüm sürecinde fontların nasıl işleneceğini kontrol etmenizi sağlar. Tekrar eden fontları kaldırmayı, farklı genişliklere sahip benzer fontları kaldırmayı veya fontları alt kümelemeyi seçebilirsiniz.

### Ayrıca Bakınız

* enum [RemoveFontsStrategy](../../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy/)
* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)