---
title: Enum TextEditOptions.NoCharacterAction
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextEditOptionsNoCharacterAction enum. Gerekli karakteri içermeyen bir yazı tipi durumunda yapılacak işlem
type: docs
weight: 10860
url: /tr/net/aspose.pdf.text/texteditoptions.nocharacteraction/
---
## TextEditOptions.NoCharacterAction enumerasyonu

Gerekli karakteri içermeyen bir yazı tipi durumunda yapılacak işlem

```csharp
public enum NoCharacterAction
```

### Değerler

| İsim | Değer | Açıklama |
| --- | --- | --- |
| ThrowException | `0` | Hata fırlat |
| UseStandardFont | `1` | Gerekli karakteri içeren standart yazı tipi ile yazı tipini değiştir |
| ReplaceAnyway | `2` | Yazı tipi değişikliği olmadan metni her durumda değiştir |
| ReplaceFonts | `3` | Metindeki tüm karakterlerin görüntülenebilmesini sağlamak için gerekli olduğunda yazı tiplerini değiştirir. Yazı tipi değiştirme algoritması şu adımları izler: 1. Kullanıcı açıkça Font özelliğini ayarladıysa, belirtilen yazı tipinin istenen karakterleri görüntüleyip görüntüleyemeyeceğini kontrol edin. 2. Kullanıcı tanımlı bir yazı tipi ayarlanmamışsa, [`Sources`](../fontrepository/sources/) aracılığıyla eklenen yazı tipleri arasında arama yapın. 3. Metni analiz ederek alfabesini veya yazı sistemini tanımlayın ve buna göre yazı tipi adları önerin. Bu yazı tiplerini sistemden bulmaya ve kullanmaya çalışın. 4. Yedek olarak, gerekli karakterleri görüntüleyebilen herhangi bir yazı tipi için sistemi arayın. |
| UseCustomReplacementFont | `4` | Tanımlı yedek yazı tipi ile yazı tipini değiştir |

### Ayrıca Bakınız

* sınıf [TextEditOptions](../texteditoptions/)
* ad alanı [Aspose.Pdf.Text](../../aspose.pdf.text/)
* derleme [Aspose.PDF](../../)