---
title: PdfAOptionsBase.AlignText
second_title: Aspose.PDF for .NET API Reference
description: PdfAOptionsBase özelliği. PDF/A dönüşüm sürecinde metin hizalamasını korumak için ek araçların gerekli olup olmadığını belirten bir değeri alır veya ayarlar.
type: docs
weight: 10
url: /tr/net/aspose.pdf.plugins/pdfaoptionsbase/aligntext/
---
## PdfAOptionsBase.AlignText özelliği

PDF/A dönüşüm sürecinde metin hizalamasını korumak için ek araçların gerekli olup olmadığını belirten bir değeri alır veya ayarlar.

```csharp
public bool AlignText { get; set; }
```

### Özellik Değeri

Metin hizalaması değişirse ve eski haline getirmek için ek işlemler gerekli ise `true`; aksi takdirde `false`.

## Açıklamalar

`true` olarak ayarlandığında, dönüşüm süreci orijinal metin segmenti sınırlarını geri yüklemeye çalışacaktır. Çoğu belge için, metin hizalaması varsayılan dönüşüm sürecinde değişmediğinden, bu özelliği varsayılan `false` değerinden değiştirmeye gerek yoktur.

### Ayrıca Bakınız

* sınıf [PdfAOptionsBase](../)
* ad alanı [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* derleme [Aspose.PDF](../../../)