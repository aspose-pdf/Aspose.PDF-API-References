---
title: "TextSearchOptions"
linktitle: "TextSearchOptions"
second_title: "Aspose.PDF for Java API Referansı"
description: "Metin arama seçeneklerini temsil eder"
type: docs
weight: 5290
url: /tr/java/com.aspose.pdf/textsearchoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextSearchOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextSearchOptions

```
public final class TextSearchOptions extends TextOptions
```

Metin arama seçeneklerini temsil eder

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TextSearchOptions](#TextSearchOptions-boolean-) | Yeni {@code TextSearchOptions} nesnesinin bir örneğini başlatır. Düzenli ifade kullanım modunu belirtir. |
| [TextSearchOptions](#TextSearchOptions-com.aspose.pdf.Rectangle-) | Yeni TextSearchOptions nesnesinin bir örneğini başlatır. Aranan metni sınırlayan dikdörtgeni belirtir. |
| [TextSearchOptions](#TextSearchOptions-com.aspose.pdf.Rectangle-boolean-) | Yeni TextSearchOptions nesnesinin bir örneğini başlatır. Aranan metni sınırlayan dikdörtgeni ve düzenli ifade kullanım modunu belirtir. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getExcludeRectangles](#getExcludeRectangles--) | Aramadan metni dışlayan kenarları olan dikdörtgenleri alır veya ayarlar. |
| [getIgnoreResourceFontErrors](#getIgnoreResourceFontErrors--) | Metin (parçacık) emici tarafından yazı tipinin eksikliğiyle ilgili hataların göz ardı edilmesini alır veya ayarlar. true - yazı tipinin eksikliği hatalarının göz ardı edileceği anlamına gelir. Yanlış kaynaklara başvuran metin segmentleri işleme sırasında atlanır. false (varsayılan) - yazı tipi eksikliği hatası, istisna fırlatarak işleme sonlandırır. |
| [getLimitToPageBounds](#getLimitToPageBounds--) | Metnin sayfa sınırları içinde aranacağını alır. |
| [getLogTextExtractionErrors](#getLogTextExtractionErrors--) | Metin çıkarma (kod çözme) hatalarının metin (parçacık) emicide kaydedileceğini alır veya ayarlar. true - metin çıkarma (kod çözme) hatalarının kaydedileceği anlamına gelir. Performansı düşürebilir. false (varsayılan) - hata kaydı yok. |
| [getRectangle](#getRectangle--) | Aranan metni sınırlayan dikdörtgeni alır. Özellik, metin çıkarma veya metin değiştirme bölgesini sınırlamak gerektiğinde kullanılabilir. |
| [getSearchForTextRelatedGraphics](#getSearchForTextRelatedGraphics--) | Metin arama sırasında metinle ilgili grafiklerin (alt çizgi, arka plan vb.) aranmasına izin veren değeri alır veya ayarlar. true - metinle ilgili grafiklerin aranması gerçekleştirilir (varsayılan değer). false - kaynak belgede bulunabilecek grafik öğeler göz ardı edilir. Performans sorunları olduğunda veya alt çizgi, arka plan veya kırpma işleme ihtiyacı olmadığında bunu ayarlayın. |
| [getStoredGraphicElementsMaxCount](#getStoredGraphicElementsMaxCount--) | Bir sayfada metinle ilgili grafiklerin (alt çizgi, arka plan vb.) aranmasını belirli sayıda öğe ile sınırlayan değeri alır. Varsayılan değer 250'dir. Performans sorunları durumunda daha düşük bir değer ayarlayın, bazı grafik öğeler bulunamadıysa daha büyük bir değer deneyin. |
| [getUseFontEngineEncoding](#getUseFontEngineEncoding--) | Metnin yazı tipi motoru kodlamasını kullanarak aranacağını alır. true - yazı tipi motoru kodlaması kullanılacak (belgedeki kodlamanın kusurlu olması nedeniyle metin araması başarısız olursa bunu deneyin). false - belge yazı tipi kodlaması kullanılacak (varsayılan değer). |
| [isDotallMode](#isDotallMode--) | <p> Dotall modunda, <tt>.</tt> ifadesi satır sonlandırıcısı dahil olmak üzere herhangi bir karakterle eşleşir. Varsayılan olarak bu ifade satır sonlandırıcılarıyla eşleşmez. |
| [isIgnoreShadowText](#isIgnoreShadowText--) | Metin (parçacık) emicide normal metnin gölgesini temsil eden metin parçacıklarının arama sırasında göz ardı edileceğini alır veya ayarlar. true - gölge metin bulunmayacak (metin araması yakın konumlarda yinelenen parçacıklar döndürdüğünde bunu deneyin). false - gölge metin normal metin gibi bulunacak (varsayılan değer). |
| [isRegularExpressionUsed](#isRegularExpressionUsed--) | Düzenli ifadenin kullanılıp kullanılmadığını gösterir. |
| [isSearchInAnnotations](#isSearchInAnnotations--) | Metnin Açıklamalarda aranmasına izin veren değeri alır veya ayarlar. true - metin Açıklamalarda aranacak. false - Açıklamalardaki metin TextFragmentAbsorber tarafından işlenmeyecek. |
| [setDotallMode](#setDotallMode-boolean-) | Dotall modunu etkinleştirir. <p> Dotall modunda, <tt>.</tt> ifadesi satır sonlandırıcısı dahil olmak üzere herhangi bir karakterle eşleşir. Varsayılan olarak bu ifade satır sonlandırıcılarıyla eşleşmez. |
| [setExcludeRectangles](#setExcludeRectangles-com.aspose.pdf.Rectangle:A-) | Aramadan metni dışlayan kenarları olan dikdörtgenleri alır veya ayarlar. |
| [setIgnoreResourceFontErrors](#setIgnoreResourceFontErrors-boolean-) | Metin (parçacık) emici tarafından yazı tipinin eksikliğiyle ilgili hataların göz ardı edilmesini alır veya ayarlar. true - yazı tipinin eksikliği hatalarının göz ardı edileceği anlamına gelir. Yanlış kaynaklara başvuran metin segmentleri işleme sırasında atlanır. false (varsayılan) - yazı tipi eksikliği hatası, istisna fırlatarak işleme sonlandırır. |
| [setIgnoreShadowText](#setIgnoreShadowText-boolean-) | Metin (parçacık) emicide normal metnin gölgesini temsil eden metin parçacıklarının arama sırasında göz ardı edileceğini alır veya ayarlar. true - gölge metin bulunmayacak (metin araması yakın konumlarda yinelenen parçacıklar döndürdüğünde bunu deneyin). false - gölge metin normal metin gibi bulunacak (varsayılan değer). |
| [setLimitToPageBounds](#setLimitToPageBounds-boolean-) | Metnin sayfa sınırları içinde aranacağını ayarlar. |
| [setLogTextExtractionErrors](#setLogTextExtractionErrors-boolean-) | Metin çıkarma (kod çözme) hatalarının metin (parçacık) emicide kaydedileceğini alır veya ayarlar. true - metin çıkarma (kod çözme) hatalarının kaydedileceği anlamına gelir. Performansı düşürebilir. false (varsayılan) - hata kaydı yok. |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | Aranan metni sınırlayan dikdörtgeni ayarlar. Özellik, metin çıkarma veya metin değiştirme bölgesini sınırlamak gerektiğinde kullanılabilir. |
| [setRegularExpressionUsed](#setRegularExpressionUsed-boolean-) | Düzenli ifadenin kullanılıp kullanılmadığını gösterir. |
| [setSearchForTextRelatedGraphics](#setSearchForTextRelatedGraphics-boolean-) | Metin arama sırasında metinle ilgili grafiklerin (alt çizgi, arka plan vb.) aranmasına izin veren değeri alır veya ayarlar. true - metinle ilgili grafiklerin aranması gerçekleştirilir (varsayılan değer). false - kaynak belgede bulunabilecek grafik öğeler göz ardı edilir. Performans sorunları olduğunda veya alt çizgi, arka plan veya kırpma işleme ihtiyacı olmadığında bunu ayarlayın. |
| [setSearchInAnnotations](#setSearchInAnnotations-boolean-) | Metnin Açıklamalarda aranmasına izin veren değeri alır veya ayarlar. true - metin Açıklamalarda aranacak. false - Açıklamalardaki metin TextFragmentAbsorber tarafından işlenmeyecek. |
| [setStoredGraphicElementsMaxCount](#setStoredGraphicElementsMaxCount-int-) | Bir sayfada metinle ilgili grafiklerin (alt çizgi, arka plan vb.) aranmasını belirli sayıda öğe ile sınırlayan değeri ayarlar. Varsayılan değer 250'dir. Performans sorunları durumunda daha düşük bir değer ayarlayın, bazı grafik öğeler bulunamadıysa daha büyük bir değer deneyin. |
| [setUseFontEngineEncoding](#setUseFontEngineEncoding-boolean-) | Metnin yazı tipi motoru kodlamasını kullanarak aranacağını ayarlar. true - yazı tipi motoru kodlaması kullanılacak (belgedeki kodlamanın kusurlu olması nedeniyle metin araması başarısız olursa bunu deneyin). false - belge yazı tipi kodlaması kullanılacak (varsayılan değer). |

### TextSearchOptions {#TextSearchOptions-boolean-}
```
public TextSearchOptions(boolean isRegularExpressionUsed)
```

Yeni {@code TextSearchOptions} nesnesinin bir örneğini başlatır. Düzenli ifade kullanım modunu belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isRegularExpressionUsed |  | Düzenli ifadenin kullanıldığını gösteren değer. |

### TextSearchOptions {#TextSearchOptions-com.aspose.pdf.Rectangle-}
Yeni TextSearchOptions nesnesinin bir örneğini başlatır. Aranan metni sınırlayan dikdörtgeni belirtir.

### TextSearchOptions {#TextSearchOptions-com.aspose.pdf.Rectangle-boolean-}
Yeni TextSearchOptions nesnesinin bir örneğini başlatır. Aranan metni sınırlayan dikdörtgeni ve düzenli ifade kullanım modunu belirtir.

### getExcludeRectangles {#getExcludeRectangles--}
```
public final Rectangle [] getExcludeRectangles()
```

Aramadan metni dışlayan kenarları olan dikdörtgenleri alır veya ayarlar.

**Returns:**
Rectangle örneklerinin dizisi

### getIgnoreResourceFontErrors {#getIgnoreResourceFontErrors--}
```
public final boolean getIgnoreResourceFontErrors()
```

Metin (parçacık) emici tarafından yazı tipinin eksikliğiyle ilgili hataların göz ardı edilmesini alır veya ayarlar. true - yazı tipinin eksikliği hatalarının göz ardı edileceği anlamına gelir. Yanlış kaynaklara başvuran metin segmentleri işleme sırasında atlanır. false (varsayılan) - yazı tipi eksikliği hatası, istisna fırlatarak işleme sonlandırır.

**Returns:**
boolean değer

### getLimitToPageBounds {#getLimitToPageBounds--}
```
public boolean getLimitToPageBounds()
```

Metnin sayfa sınırları içinde aranacağını alır.

**Returns:**
boolean değer

### getLogTextExtractionErrors {#getLogTextExtractionErrors--}
```
public boolean getLogTextExtractionErrors()
```

Metin çıkarma (kod çözme) hatalarının metin (parçacık) emicide kaydedileceğini alır veya ayarlar. true - metin çıkarma (kod çözme) hatalarının kaydedileceği anlamına gelir. Performansı düşürebilir. false (varsayılan) - hata kaydı yok.

**Returns:**
boolean değer

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Aranan metni sınırlayan dikdörtgeni alır. Özellik, metin çıkarma veya metin değiştirme bölgesini sınırlamak gerektiğinde kullanılabilir.

**Returns:**
Dikdörtgen değeri

### getSearchForTextRelatedGraphics {#getSearchForTextRelatedGraphics--}
```
public final boolean getSearchForTextRelatedGraphics()
```

Metin arama sırasında metinle ilgili grafiklerin (alt çizgi, arka plan vb.) aranmasına izin veren değeri alır veya ayarlar. true - metinle ilgili grafiklerin aranması gerçekleştirilir (varsayılan değer). false - kaynak belgede bulunabilecek grafik öğeler göz ardı edilir. Performans sorunları olduğunda veya alt çizgi, arka plan veya kırpma işleme ihtiyacı olmadığında bunu ayarlayın.

**Returns:**
boolean değer

### getStoredGraphicElementsMaxCount {#getStoredGraphicElementsMaxCount--}
```
public final int getStoredGraphicElementsMaxCount()
```

Bir sayfada metinle ilgili grafiklerin (alt çizgi, arka plan vb.) aranmasını belirli sayıda öğe ile sınırlayan değeri alır. Varsayılan değer 250'dir. Performans sorunları durumunda daha düşük bir değer ayarlayın, bazı grafik öğeler bulunamadıysa daha büyük bir değer deneyin.

**Returns:**
int değer

### getUseFontEngineEncoding {#getUseFontEngineEncoding--}
```
public boolean getUseFontEngineEncoding()
```

Metnin yazı tipi motoru kodlamasını kullanarak aranacağını alır. true - yazı tipi motoru kodlaması kullanılacak (belgedeki kodlamanın kusurlu olması nedeniyle metin araması başarısız olursa bunu deneyin). false - belge yazı tipi kodlaması kullanılacak (varsayılan değer).

**Returns:**
boolean değer

### isDotallMode {#isDotallMode--}
```
public static boolean isDotallMode()
```

<p> Dotall modunda, <tt>.</tt> ifadesi satır sonlandırıcısı dahil olmak üzere herhangi bir karakterle eşleşir. Varsayılan olarak bu ifade satır sonlandırıcılarıyla eşleşmez.

**Returns:**
boolean değer

### isIgnoreShadowText {#isIgnoreShadowText--}
```
public boolean isIgnoreShadowText()
```

Metin (parçacık) emicide normal metnin gölgesini temsil eden metin parçacıklarının arama sırasında göz ardı edileceğini alır veya ayarlar. true - gölge metin bulunmayacak (metin araması yakın konumlarda yinelenen parçacıklar döndürdüğünde bunu deneyin). false - gölge metin normal metin gibi bulunacak (varsayılan değer).

**Returns:**
boolean değer

### isRegularExpressionUsed {#isRegularExpressionUsed--}
```
public boolean isRegularExpressionUsed()
```

Düzenli ifadenin kullanılıp kullanılmadığını gösterir.

**Returns:**
boolean değer

### isSearchInAnnotations {#isSearchInAnnotations--}
```
public final boolean isSearchInAnnotations()
```

Metnin Açıklamalarda aranmasına izin veren değeri alır veya ayarlar. true - metin Açıklamalarda aranacak. false - Açıklamalardaki metin TextFragmentAbsorber tarafından işlenmeyecek.

**Returns:**
boolean değer

### setDotallMode {#setDotallMode-boolean-}
```
public static void setDotallMode(boolean dotallMode)
```

Dotall modunu etkinleştirir. <p> Dotall modunda, <tt>.</tt> ifadesi satır sonlandırıcısı dahil olmak üzere herhangi bir karakterle eşleşir. Varsayılan olarak bu ifade satır sonlandırıcılarıyla eşleşmez.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dotallMode |  | boolean değer |

### setExcludeRectangles {#setExcludeRectangles-com.aspose.pdf.Rectangle:A-}
Aramadan metni dışlayan kenarları olan dikdörtgenleri alır veya ayarlar.

### setIgnoreResourceFontErrors {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```

Metin (parçacık) emici tarafından yazı tipinin eksikliğiyle ilgili hataların göz ardı edilmesini alır veya ayarlar. true - yazı tipinin eksikliği hatalarının göz ardı edileceği anlamına gelir. Yanlış kaynaklara başvuran metin segmentleri işleme sırasında atlanır. false (varsayılan) - yazı tipi eksikliği hatası, istisna fırlatarak işleme sonlandırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setIgnoreShadowText {#setIgnoreShadowText-boolean-}
```
public void setIgnoreShadowText(boolean value)
```

Metin (parçacık) emicide normal metnin gölgesini temsil eden metin parçacıklarının arama sırasında göz ardı edileceğini alır veya ayarlar. true - gölge metin bulunmayacak (metin araması yakın konumlarda yinelenen parçacıklar döndürdüğünde bunu deneyin). false - gölge metin normal metin gibi bulunacak (varsayılan değer).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setLimitToPageBounds {#setLimitToPageBounds-boolean-}
```
public void setLimitToPageBounds(boolean value)
```

Metnin sayfa sınırları içinde aranacağını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setLogTextExtractionErrors {#setLogTextExtractionErrors-boolean-}
```
public void setLogTextExtractionErrors(boolean value)
```

Metin çıkarma (kod çözme) hatalarının metin (parçacık) emicide kaydedileceğini alır veya ayarlar. true - metin çıkarma (kod çözme) hatalarının kaydedileceği anlamına gelir. Performansı düşürebilir. false (varsayılan) - hata kaydı yok.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
Aranan metni sınırlayan dikdörtgeni ayarlar. Özellik, metin çıkarma veya metin değiştirme bölgesini sınırlamak gerektiğinde kullanılabilir.

### setRegularExpressionUsed {#setRegularExpressionUsed-boolean-}
```
public void setRegularExpressionUsed(boolean value)
```

Düzenli ifadenin kullanılıp kullanılmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setSearchForTextRelatedGraphics {#setSearchForTextRelatedGraphics-boolean-}
```
public final void setSearchForTextRelatedGraphics(boolean value)
```

Metin arama sırasında metinle ilgili grafiklerin (alt çizgi, arka plan vb.) aranmasına izin veren değeri alır veya ayarlar. true - metinle ilgili grafiklerin aranması gerçekleştirilir (varsayılan değer). false - kaynak belgede bulunabilecek grafik öğeler göz ardı edilir. Performans sorunları olduğunda veya alt çizgi, arka plan veya kırpma işleme ihtiyacı olmadığında bunu ayarlayın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setSearchInAnnotations {#setSearchInAnnotations-boolean-}
```
public final void setSearchInAnnotations(boolean value)
```

Metnin Açıklamalarda aranmasına izin veren değeri alır veya ayarlar. true - metin Açıklamalarda aranacak. false - Açıklamalardaki metin TextFragmentAbsorber tarafından işlenmeyecek.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setStoredGraphicElementsMaxCount {#setStoredGraphicElementsMaxCount-int-}
```
public final void setStoredGraphicElementsMaxCount(int value)
```

Bir sayfada metinle ilgili grafiklerin (alt çizgi, arka plan vb.) aranmasını belirli sayıda öğe ile sınırlayan değeri ayarlar. Varsayılan değer 250'dir. Performans sorunları durumunda daha düşük bir değer ayarlayın, bazı grafik öğeler bulunamadıysa daha büyük bir değer deneyin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setUseFontEngineEncoding {#setUseFontEngineEncoding-boolean-}
```
public void setUseFontEngineEncoding(boolean value)
```

Metnin yazı tipi motoru kodlamasını kullanarak aranacağını ayarlar. true - yazı tipi motoru kodlaması kullanılacak (belgedeki kodlamanın kusurlu olması nedeniyle metin araması başarısız olursa bunu deneyin). false - belge yazı tipi kodlaması kullanılacak (varsayılan değer).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |
