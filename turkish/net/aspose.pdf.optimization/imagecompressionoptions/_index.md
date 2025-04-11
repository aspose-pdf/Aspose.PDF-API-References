---
title: Class ImageCompressionOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Optimization.ImageCompressionOptions sınıfı. Sınıf, resim sıkıştırma için seçenekler içerir.
type: docs
weight: 7950
url: /tr/net/aspose.pdf.optimization/imagecompressionoptions/
---
## ImageCompressionOptions sınıfı

Sınıf, resim sıkıştırma için seçenekler içerir.

```csharp
public class ImageCompressionOptions
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [ImageCompressionOptions](imagecompressionoptions/)() | Varsayılan yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [CompressImages](../../aspose.pdf.optimization/imagecompressionoptions/compressimages/) { get; set; } | Bu bayrak true olarak ayarlandığında, belgede resimler sıkıştırılacaktır. sıkıştırma seviyesi ImageQuality özelliği ile belirtilir. |
| [Encoding](../../aspose.pdf.optimization/imagecompressionoptions/encoding/) { get; set; } | Resimleri depolamak için kullanılan kodlamayı alır veya ayarlar. |
| [ImageQuality](../../aspose.pdf.optimization/imagecompressionoptions/imagequality/) { get; set; } | CompressIamges bayrağı kullanıldığında resim sıkıştırma seviyesini belirtir. |
| [MaxResolution](../../aspose.pdf.optimization/imagecompressionoptions/maxresolution/) { get; set; } | Resimlerin maksimum çözünürlüğünü belirtir. Eğer resim daha yüksek bir çözünürlüğe sahipse, ölçeklendirilecektir. |
| [ResizeImages](../../aspose.pdf.optimization/imagecompressionoptions/resizeimages/) { get; set; } | Bu bayrak true olarak ayarlandığında ve CompressImages true ise, resimler belirtilen MaxResolution parametresinden daha büyük bir çözünürlüğe sahipse yeniden boyutlandırılacaktır. |
| [Version](../../aspose.pdf.optimization/imagecompressionoptions/version/) { get; set; } | Sıkıştırma algoritmasının versiyonu. Olası değerler: 1. standart sıkıştırma, 2. hızlı (standarttan daha hızlı olan geliştirilmiş sıkıştırma ancak tüm resimler için uygulanmayabilir), 3. karışık (hızlı algoritma ile sıkıştırılamayan resimlere standart sıkıştırma uygulanır, bu en iyi sıkıştırmayı verebilir ancak "hızlı" algoritmadan daha yavaş olabilir. "Hızlı" versiyonu, resimleri yeniden boyutlandırmak için uygulanamaz (standart yöntem kullanılacaktır). Varsayılan "Standart"tır. |

### Ayrıca Bakınız

* ad alanı [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* derleme [Aspose.PDF](../../)