---
title: Enum PdfFormatConversionOptions.RemoveFontsStrategy
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfFormatConversionOptionsRemoveFontsStrategy enum. Bazı belgeler PDF/A formatına dönüştürüldüğünde büyük boyutlara sahip olmaktadır. Bu belgelerin dosya boyutunu azaltmak için bir yazı tipi kaldırma stratejisi tanımlamak gereklidir. Bu enumerasyon, yazı tipi kullanımını optimize etmek için kullanılabilecek stratejileri bildirir. Bu enumerasyondaki her strateji, OptimizeFileSize bayrağı ayarlandığında anlam kazanır.
type: docs
weight: 8400
url: /tr/net/aspose.pdf/pdfformatconversionoptions.removefontsstrategy/
---
## PdfFormatConversionOptions.RemoveFontsStrategy enumerasyonu

Bazı belgeler PDF/A formatına dönüştürüldüğünde büyük boyutlara sahip olmaktadır. Bu belgelerin dosya boyutunu azaltmak için bir yazı tipi kaldırma stratejisi tanımlamak gereklidir. Bu enumerasyon, yazı tipi kullanımını optimize etmek için kullanılabilecek stratejileri bildirir. Bu enumerasyondaki her strateji, [`OptimizeFileSize`](../pdfformatconversionoptions/optimizefilesize/) bayrağı ayarlandığında anlam kazanır.

```csharp
[Flags]
public enum RemoveFontsStrategy : byte
```

### Değerler

| İsim | Değer | Açıklama |
| --- | --- | --- |
| RemoveDuplicatedFonts | `4` | Bu strateji, belgede tekrar eden tüm yazı tiplerini kaldırır. Eğer belge bir grup tekrar eden yazı tipi içeriyorsa, bu gruptan yalnızca bir yazı tipi belgede gömülüdür. Bu gruptaki diğer tüm yazı tipleri belgeden kaldırılır, her kaldırılan yazı tipi, zaten gömülü olan bir analoğu ile değiştirilir. |
| RemoveSimilarFontsWithDifferentWidths | `1` | Bu strateji, RemoveDuplicatedFonts'a benzer ancak tamamen tekrar eden yazı tiplerini değil, birbirine benzer ve yalnızca "Widths" parametresi ile farklılık gösteren yazı tiplerini kaldırır. Bu parametre, belirli yazı tipi sembollerinin bazı genişliklerini içeren bir kümedir. Bu "Widths" kümesindeki her genişlik değeri, sembolün (glyph) gerçek genişliği değildir; bu sembol için gerçek genişlik, yazı tipinin ikili verilerinde zaten tanımlanmıştır. "Widths" kümesindeki genişlik değeri, bu sembol için görsel genişliği ifade eder - PDF görüntüleme yazılımının sembolü görüntülemesi sırasında gerçek genişlik yerine ayarlaması gereken genişliktir. Daha doğru bir şekilde belirtmek gerekirse: Acrobat 5.0 ve sonraki görüntüleyiciler, yazı tipi sözlüğünde saklanan glyph genişliklerini kullanarak yazı tipi programındaki glyph genişliklerini geçersiz kılar, bu da belgenin görüntülenmesi ve yazdırılmasındaki tutarlılığı artırır. Bu strateji, RemoveDuplicatedFonts'tan daha etkilidir ancak bu stratejinin bazı durumlarda teorik olarak dönüştürülmüş belgenin görsel sunumuna zarar verebileceği durumlar vardır. Bu kusur, yazı tiplerinin tanımlanan genişliklerinin aynı sembol için farklı olabileceğinden kaynaklanabilir ve bu durumda bu sembolün genişliği, kaldırılan yazı tipi belgede zaten gömülü olan bir yazı tipi ile değiştirildiğinde yeni bir genişliğe değişecektir. Ve eğer sembolün görsel genişliği değişirse - yanlış gösterilecektir ve bu farklılık, metin üst üste binmesi veya başka sorunlar gibi görsel kusurlara neden olabilir. Ancak tanımlanan görsel kusur çok nadir bir durumdur ve bu strateji, belgenin boyutunu daha etkili bir şekilde azaltır. |
| SubsetFonts | `2` | Bu, belgenin boyutunu azaltmak için en etkili stratejidir. Tamamen gömülü yazı tipi setlerini alır ve yalnızca kullanılan alt kümelere indirger. Bu stratejinin, dosya boyutu için çoklu sıkıştırma etkisi elde etmek amacıyla RemoveDuplicatedFonts veya RemoveSimilarFontsWithDifferentWidths ile birleştirilmesi önerilir. Üç stratejinin aynı anda kullanılması mantıklı değildir ve bu durumda RemoveSimilarFontsWithDifferentWidths stratejisi kullanılmayacaktır. |

### Ayrıca Bakınız

* sınıf [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)