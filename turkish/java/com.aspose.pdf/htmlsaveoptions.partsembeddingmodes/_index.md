---
title: "HtmlSaveOptions.PartsEmbeddingModes"
linktitle: "HtmlSaveOptions.PartsEmbeddingModes"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bu enum, HTML içinde referans verilen dosyaların gömülme olası modlarını listeler. Referans verilen dosyaların (HTML, Yazı tipleri, Görseller, CSS'ler) ana dosyaya gömülüp gömülmeyeceğini kontrol etmeye olanak tanır."
type: docs
weight: 2130
url: /tr/java/com.aspose.pdf/htmlsaveoptions.partsembeddingmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.PartsEmbeddingModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.PartsEmbeddingModes, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.PartsEmbeddingModes

```
public static final class HtmlSaveOptions.PartsEmbeddingModes extends com.aspose.ms.System.Enum
```

Bu enum, HTML içinde başvurulan dosyaların gömülme olası modlarını listeler. Başvurulan dosyaların (HTML, Yazı tipleri, Görüntüler, CSS'ler) ana HTML dosyasına gömülüp gömülmeyeceğini veya ayrı ikili varlıklar olarak oluşturulup oluşturulmayacağını kontrol etmeyi sağlar.

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [EmbedAllIntoHtml](#EmbedAllIntoHtml) | Tüm referans verilen dosyaları (CSS, Görseller, Yazı tipleri) oluşturulan HTML işaretlemesine (yani HTML'in kendisine) gömmeyi zorunlu kılar. Bu yaklaşım tek bir HTML dosyası üretir, ancak çıktı boyutu daha büyük olur (çünkü ikili dosyalar Base64 ile kodlanır) ve tüm tarayıcılar (özellikle eski olanlar) HTML içine gömülmüş ikili dosyaları başarıyla işleyemez. Ancak ek dosya olmadan tüm sonucu içeren bir HTML elde etmeyi sağlar. |
| [EmbedCssOnly](#EmbedCssOnly) | CSS dışındaki tüm referans verilen dosyaları (Görseller ve Yazı tipleri) ayrı tutmayı zorunlu kılar. Yani CSS sonuç HTML'e gömülür, diğer referans dosyalar (Görseller ve Yazı tipleri) dışsal parçalar olarak işlenir. Bu, geniş bir tarayıcı yelpazesi için uygun bir HTML üretir. |
| [NoEmbedding](#NoEmbedding) | Referans verilen dosyaları (CSS, Görseller, Yazı tipleri) ayrı tutmayı zorunlu kılar. Bu yaklaşım bir dosya seti üretir, ancak çıktı boyutu daha küçük olur (çünkü ikili dosyalar Base64 ile kodlanmaz). Ayrıca bu yaklaşım geniş bir tarayıcı yelpazesi için uygun bir HTML üretir. |

### EmbedAllIntoHtml {#EmbedAllIntoHtml}
```
public static final int EmbedAllIntoHtml
```

Tüm referans verilen dosyaları (CSS, Görseller, Yazı tipleri) oluşturulan HTML işaretlemesine (yani HTML'in kendisine) gömmeyi zorunlu kılar. Bu yaklaşım tek bir HTML dosyası üretir, ancak çıktı boyutu daha büyük olur (çünkü ikili dosyalar Base64 ile kodlanır) ve tüm tarayıcılar (özellikle eski olanlar) HTML içine gömülmüş ikili dosyaları başarıyla işleyemez. Ancak ek dosya olmadan tüm sonucu içeren bir HTML elde etmeyi sağlar.

### EmbedCssOnly {#EmbedCssOnly}
```
public static final int EmbedCssOnly
```

CSS dışındaki tüm referans verilen dosyaları (Görseller ve Yazı tipleri) ayrı tutmayı zorunlu kılar. Yani CSS sonuç HTML'e gömülür, diğer referans dosyalar (Görseller ve Yazı tipleri) dışsal parçalar olarak işlenir. Bu, geniş bir tarayıcı yelpazesi için uygun bir HTML üretir.

### NoEmbedding {#NoEmbedding}
```
public static final int NoEmbedding
```

Referans verilen dosyaları (CSS, Görseller, Yazı tipleri) ayrı tutmayı zorunlu kılar. Bu yaklaşım bir dosya seti üretir, ancak çıktı boyutu daha küçük olur (çünkü ikili dosyalar Base64 ile kodlanmaz). Ayrıca bu yaklaşım geniş bir tarayıcı yelpazesi için uygun bir HTML üretir.
