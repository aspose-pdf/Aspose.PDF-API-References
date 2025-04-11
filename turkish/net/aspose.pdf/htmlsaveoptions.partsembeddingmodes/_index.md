---
title: Enum HtmlSaveOptions.PartsEmbeddingModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsPartsEmbeddingModes enum. Bu enum, HTML'de referans verilen dosyaların gömülmesi için olası modları sıralar. Referans verilen dosyaların (HTML, Fontlar, Görseller, CSS'ler) ana HTML dosyasına gömülüp gömülmeyeceğini veya ayrı ikili varlıklar olarak mı oluşturulacağını kontrol etmeye olanak tanır.
type: docs
weight: 5710
url: /tr/net/aspose.pdf/htmlsaveoptions.partsembeddingmodes/
---
## HtmlSaveOptions.PartsEmbeddingModes enumerasyonu

Bu enum, HTML'de referans verilen dosyaların gömülmesi için olası modları sıralar. Referans verilen dosyaların (HTML, Fontlar, Görseller, CSS'ler) ana HTML dosyasına gömülüp gömülmeyeceğini veya ayrı ikili varlıklar olarak mı oluşturulacağını kontrol etmeye olanak tanır.

```csharp
public enum PartsEmbeddingModes
```

### Değerler

| İsim | Değer | Açıklama |
| --- | --- | --- |
| EmbedAllIntoHtml | `0` | Tüm referans verilen dosyaları (CSS, Görseller, Fontlar) oluşturulan HTML işaretlemesine (yani HTML'nin kendisine) gömülmesini zorunlu kılar. Bu yaklaşım bir HTML dosyası oluşturur, ancak çıktı boyutunun toplamı büyür (çünkü ikililerin Base64 kodlaması kullanılır) ve tüm tarayıcılar (özellikle eski olanlar) HTML'ye gömülü ikilileri başarıyla işleyemez. Ancak, ek dosyalar olmadan tüm sonucu içeren bir HTML elde etmeyi sağlar. |
| EmbedCssOnly | `1` | CSS dışındaki tüm referans verilen dosyaların (Görseller ve Fontlar) ayrı tutulmasını zorunlu kılar. Yani, CSS sonuç HTML'sine gömülür ve diğer tüm referans verilen dosyalar (Görseller ve Fontlar) harici parçalar olarak işlenir. Bu, geniş bir tarayıcı seti için uygun HTML oluşturur. |
| NoEmbedding | `2` | Referans verilen dosyaların (CSS, Görseller, Fontlar) ayrı tutulmasını zorunlu kılar. Bu yaklaşım bir dosya seti oluşturur, ancak çıktı boyutunun toplamı daha küçük hale gelir (çünkü ikililerin Base64 kodlaması kullanılmaz). Ayrıca, bu yaklaşım geniş bir tarayıcı seti için uygun HTML oluşturur. |

### Ayrıca Bakınız

* sınıf [HtmlSaveOptions](../htmlsaveoptions/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)