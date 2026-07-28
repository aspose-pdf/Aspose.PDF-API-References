---
title: "PdfFormatConversionOptions.RemoveFontsStrategy"
linktitle: "PdfFormatConversionOptions.RemoveFontsStrategy"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bazı belgeler PDF/A formatına dönüştürüldükten sonra büyük boyuta sahiptir. Bu belgelerin dosya boyutunu azaltmak için yazı tiplerini kaldırma stratejisi tanımlanması gerekir. Bu bir enumerasyondur."
type: docs
weight: 3760
url: /tr/java/com.aspose.pdf/pdfformatconversionoptions.removefontsstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.RemoveFontsStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.RemoveFontsStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.PdfFormatConversionOptions.RemoveFontsStrategy

```
public static class PdfFormatConversionOptions.RemoveFontsStrategy extends com.aspose.ms.System.Enum
```

Bazı belgeler PDF/A formatına dönüştürüldükten sonra büyük boyuta sahiptir. Bu belgeler için dosya boyutunu azaltmak, yazı tipi kaldırma stratejisini tanımlamayı gerektirir. Bu enum, yazı tiplerinin kullanımını optimize etmek için kullanılabilecek stratejileri bildirir. Bu enumdaki her strateji yalnızca {@code OptimizeFileSize} bayrağı ayarlandığında anlamlıdır.

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [RemoveDuplicatedFonts](#RemoveDuplicatedFonts) | Bu strateji, belgede yinelenen tüm yazı tiplerini kaldırır. Belge, yinelenen yazı tiplerinden oluşan bir grup içeriyorsa, bu gruptan yalnızca bir yazı tipi belgeye gömülür. Grubun diğer tüm yazı tipleri belgeden kaldırılır, kaldırılan her yazı tipi zaten gömülü olan benzeriyle değiştirilir. |
| [RemoveSimilarFontsWithDifferentWidths](#RemoveSimilarFontsWithDifferentWidths) | Bu strateji {@code RemoveDuplicatedFonts} gibi görünür ancak tamamen yinelenen yazı tiplerini değil, yalnızca \"Widths\" parametresiyle farklılık gösteren birbirine benzer yazı tiplerini kaldırır. Bu parametre, yazı tipinin belirli sembolleri için bazı genişliklerin bir kümesini içerir. \"Widths\" kümesindeki her genişlik değeri, sembolün (glyph) gerçek genişliği değildir; bu sembolün gerçek genişliği zaten yazı tipinin ikili verilerinde tanımlıdır. \"Widths\" kümesindeki genişlik değeri, bu sembol için görsel genişliği ifade eder – PDF görüntüleyici yazılımının, yazı tipinde tanımlı gerçek genişlik yerine sembolü görüntülerken ayarlaması gereken genişlik. Daha kesin bir ifadeyle, spesifikasyon şunu belirtir: Acrobat 5.0 ve sonraki sürüm görüntüleyiciler, yazı tipi sözlüğünde depolanan glyph genişliklerini, yazı tipi programındaki glyph genişliklerinin üzerine yazar, bu da belgenin görüntülenmesi ve yazdırılmasının tutarlılığını artırır. Bu strateji {@code RemoveDuplicatedFonts} stratejisinden daha etkilidir ancak bazı durumlarda teorik olarak dönüştürülmüş belgenin görsel sunumuna zarar verebilir. Bu kusur, aynı sembol için bildirilen genişliklerin farklı olabilmesinden kaynaklanır; bu durumda, font değişimi sonrasında sembolün genişliği yeni bir değere değişir – kaldırılan font, belgede zaten gömülü olan bir fontla değiştirildiğinde. Eğer sembolün görsel genişliği değişirse, sembol yanlış görüntülenir ve bu fark, metin çakışması gibi görsel kusurlara ya da başka problemlere yol açabilir. Ancak açıklanan görsel kusur çok nadir bir durumdur ve bu strateji belge boyutunu daha etkili bir şekilde azaltır. |
| [SubsetFonts](#SubsetFonts) | Bu, belgenin boyutunu azaltmak için en etkili stratejidir. Tamamen gömülü font setlerini alır ve yalnızca kullanılan alt kümelere kadar küçültür. Dosya boyutu üzerinde birden fazla sıkıştırma etkisi elde etmek için bu stratejinin {@code RemoveDuplicatedFonts} veya {@code RemoveSimilarFontsWithDifferentWidths} ile birlikte kullanılması önerilir. Üç stratejinin aynı anda kullanılması bir anlam ifade etmez ve bu durumda {@code RemoveSimilarFontsWithDifferentWidths} stratejisi kullanılmaz. |

### RemoveDuplicatedFonts {#RemoveDuplicatedFonts}
```
public static final byte RemoveDuplicatedFonts
```

Bu strateji, belgede yinelenen tüm yazı tiplerini kaldırır. Belge, yinelenen yazı tiplerinden oluşan bir grup içeriyorsa, bu gruptan yalnızca bir yazı tipi belgeye gömülür. Grubun diğer tüm yazı tipleri belgeden kaldırılır, kaldırılan her yazı tipi zaten gömülü olan benzeriyle değiştirilir.

### RemoveSimilarFontsWithDifferentWidths {#RemoveSimilarFontsWithDifferentWidths}
```
public static final byte RemoveSimilarFontsWithDifferentWidths
```

Bu strateji {@code RemoveDuplicatedFonts} gibi görünür ancak tamamen yinelenen yazı tiplerini değil, yalnızca \"Widths\" parametresiyle farklılık gösteren birbirine benzer yazı tiplerini kaldırır. Bu parametre, yazı tipinin belirli sembolleri için bazı genişliklerin bir kümesini içerir. \"Widths\" kümesindeki her genişlik değeri, sembolün (glyph) gerçek genişliği değildir; bu sembolün gerçek genişliği zaten yazı tipinin ikili verilerinde tanımlıdır. \"Widths\" kümesindeki genişlik değeri, bu sembol için görsel genişliği ifade eder – PDF görüntüleyici yazılımının, yazı tipinde tanımlı gerçek genişlik yerine sembolü görüntülerken ayarlaması gereken genişlik. Daha kesin bir ifadeyle, spesifikasyon şunu belirtir: Acrobat 5.0 ve sonraki sürüm görüntüleyiciler, yazı tipi sözlüğünde depolanan glyph genişliklerini, yazı tipi programındaki glyph genişliklerinin üzerine yazar, bu da belgenin görüntülenmesi ve yazdırılmasının tutarlılığını artırır. Bu strateji {@code RemoveDuplicatedFonts} stratejisinden daha etkilidir ancak bazı durumlarda teorik olarak dönüştürülmüş belgenin görsel sunumuna zarar verebilir. Bu kusur, aynı sembol için bildirilen genişliklerin farklı olabilmesinden kaynaklanır; bu durumda, font değişimi sonrasında sembolün genişliği yeni bir değere değişir – kaldırılan font, belgede zaten gömülü olan bir fontla değiştirildiğinde. Eğer sembolün görsel genişliği değişirse, sembol yanlış görüntülenir ve bu fark, metin çakışması gibi görsel kusurlara ya da başka problemlere yol açabilir. Ancak açıklanan görsel kusur çok nadir bir durumdur ve bu strateji belge boyutunu daha etkili bir şekilde azaltır.

### SubsetFonts {#SubsetFonts}
```
public static final byte SubsetFonts
```

Bu, belgenin boyutunu azaltmak için en etkili stratejidir. Tamamen gömülü font setlerini alır ve yalnızca kullanılan alt kümelere kadar küçültür. Dosya boyutu üzerinde birden fazla sıkıştırma etkisi elde etmek için bu stratejinin {@code RemoveDuplicatedFonts} veya {@code RemoveSimilarFontsWithDifferentWidths} ile birlikte kullanılması önerilir. Üç stratejinin aynı anda kullanılması bir anlam ifade etmez ve bu durumda {@code RemoveSimilarFontsWithDifferentWidths} stratejisi kullanılmaz.
