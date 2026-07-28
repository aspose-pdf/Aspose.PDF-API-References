---
title: "PdfFormatConversionOptions.PuaProcessingStrategy"
linktitle: "PdfFormatConversionOptions.PuaProcessingStrategy"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bazı PDF belgelerinde, Özel Kullanım Alanı (PUA)'na ait özel unicode sembolleri bulunur, açıklamayı https://en.wikipedia.org/wiki/Private_Use_Areas adresinde görebilirsiniz. Bu semboller."
type: docs
weight: 3750
url: /tr/java/com.aspose.pdf/pdfformatconversionoptions.puaprocessingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.PuaProcessingStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.PuaProcessingStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.PdfFormatConversionOptions.PuaProcessingStrategy

```
public static final class PdfFormatConversionOptions.PuaProcessingStrategy extends com.aspose.ms.System.Enum
```

Bazı PDF belgelerinde, Özel Kullanım Alanı (PUA)'na ait özel unicode sembolleri bulunur; https://en.wikipedia.org/wiki/Private_Use_Areas adresindeki açıklamaya bakın. Bu semboller, "Text is mapped to Unicode Private Use Area but no ActualText entry is present" gibi PDF/A uyum hatalarına neden olur. Bu enum, PUA sembollerini ele almak için kullanılabilecek stratejileri bildirir.

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [None](#None) | PUA sembol işleme devre dışı bırakılır. Bu strateji, Seviye B uyumluluğuna sahip PDF/A belgeleri için varsayılan olarak kullanılır. |
| [SubstitutePuaSymbols](#SubstitutePuaSymbols) | Bu strateji, 'SurroundPuaTextWithEmptyActualText' yönteminden daha yavaş çalışır ancak SurroundPuaTextWithEmptyActualText tarafından düzgün işlenemeyen belgelerde PUA uyumlu hataları kaldırabilir. PUA sembolleri, 'space' sembolü veya özel unicode (bazı PUA sembollerinin unicode karşılıkları vardır) ile değiştirilir. Değiştirme, belgenin metnine değil, yazı tipinin iç veri ToUnicode'ına uygulanır; bu, sembolün görünümünü etkilemez ancak kopyala/yapıştır işlemi sırasında sistem tamponundaki sembol sunumunu etkiler. |
| [SurroundPuaTextWithEmptyActualText](#SurroundPuaTextWithEmptyActualText) | Boş metin içeren ActualText girdisine sahip işaretli içerik bloğu ekler. Bu strateji, işaretli içerik blokları olmayan belgelerde iyi sonuç verir. Seviye A uyumluluğuna sahip PDF/A belgeleri için varsayılan olarak kullanılır. |

### None {#None}
```
public static final int None
```

PUA sembol işleme devre dışı bırakılır. Bu strateji, Seviye B uyumluluğuna sahip PDF/A belgeleri için varsayılan olarak kullanılır.

### SubstitutePuaSymbols {#SubstitutePuaSymbols}
```
public static final int SubstitutePuaSymbols
```

Bu strateji, 'SurroundPuaTextWithEmptyActualText' yönteminden daha yavaş çalışır ancak SurroundPuaTextWithEmptyActualText tarafından düzgün işlenemeyen belgelerde PUA uyumlu hataları kaldırabilir. PUA sembolleri, 'space' sembolü veya özel unicode (bazı PUA sembollerinin unicode karşılıkları vardır) ile değiştirilir. Değiştirme, belgenin metnine değil, yazı tipinin iç veri ToUnicode'ına uygulanır; bu, sembolün görünümünü etkilemez ancak kopyala/yapıştır işlemi sırasında sistem tamponundaki sembol sunumunu etkiler.

### SurroundPuaTextWithEmptyActualText {#SurroundPuaTextWithEmptyActualText}
```
public static final int SurroundPuaTextWithEmptyActualText
```

Boş metin içeren ActualText girdisine sahip işaretli içerik bloğu ekler. Bu strateji, işaretli içerik blokları olmayan belgelerde iyi sonuç verir. Seviye A uyumluluğuna sahip PDF/A belgeleri için varsayılan olarak kullanılır.
