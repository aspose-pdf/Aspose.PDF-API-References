---
title: "UnifiedSaveOptions"
linktitle: "UnifiedSaveOptions"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bu sınıf, birleşik dönüşüm yöntemi (birleşik iç belge modeli ile) kullanan kaydetme seçeneklerini temsil eder."
type: docs
weight: 5420
url: /tr/java/com.aspose.pdf/unifiedsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions

```
public class UnifiedSaveOptions extends SaveOptions
```

Bu sınıf, birleşik dönüşüm yöntemi (birleşik iç belge modeli ile) kullanan kaydetme seçeneklerini temsil eder.

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [IsMultiThreading](#IsMultiThreading) | Sayfaları birkaç iş parçacığında işleyin. |

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [UnifiedSaveOptions](#UnifiedSaveOptions--) |  |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getProgressEventsRetranslator](#getProgressEventsRetranslator--) | Dönüştürme sırasında çalışan ve iç dönüşüm aşamalarının olaylarını dış toplam ilerleme olaylarına dönüştüren internal progress events processor'ı temsil eder. Ayrıca sınıf, artık ihtiyaç duyulmayan kaynakların serbest bırakılmasını sağlayan olayları yayınlar. Bu internal sınıf, PDF'den APS'ye ve APS'den [Other format]'a ilerleme olaylarını işleyerek toplam ilerlemeyi hesaplar ve müşterinin kodunu bu toplam ilerleme olayları hakkında bilgilendirir. Bu sınıf iki tür olayı kullanır: ApsToExternal model dönüşümü ve PDF'den APS'ye dönüşüm olayları, toplam ilerleme olayları üretmek için. Dışa aktarma üç aşamadan oluşur: 1) Pdf to Aps 2) Aps recognition 3) Aps export to target format. Yapıcı, kaç sayfanın dönüştürüleceğini ve bu ya da o aşamanın toplam ilerlemedeki yaklaşık kısmını ayarlamaya izin verir. |
| [isExtractOcrSublayerOnly](#isExtractOcrSublayerOnly--) | Bu öznitelik, OCR alt katmanı ile PDF belgelerinden görüntü veya metin çıkarma işlevini etkinleştirir. Değer: {@code true} ise metin sonuç belgesine çıkarılır; aksi takdirde {@code false}. |
| [isTryMergeAdjacentSameBackgroundImages](#isTryMergeAdjacentSameBackgroundImages--) | Bazen PDF'ler, sayfaların veya tablo hücrelerinin arka planını oluşturan, yan yana yerleştirilmiş birkaç aynı döşeme arka plan görüntüsünden oluşan arka plan görüntüleri içerir. Bu durumda hedef formatların renderleyicileri (ör. DOCS formatı için MsWord) bazen arka plan görüntülerinin parçaları arasında görülebilir sınırlar oluşturur; çünkü görüntü kenar yumuşatma (anti-aliasing) teknikleri Acrobat Reader'dan farklıdır. Dışa aktarılan belgenin aynı arka plan görüntüsünün parçaları arasında böyle görülebilir sınırlar içerdiği görülürse, lütfen bu ayarı kullanarak istenmeyen etkiyi ortadan kaldırmayı deneyin. DİKKAT! Bu kalite optimizasyonu genellikle dönüşümü önemli ölçüde yavaşlatır, bu yüzden lütfen bu seçeneği yalnızca gerçekten gerekli olduğunda kullanın. |
| [setExtractOcrSublayerOnly](#setExtractOcrSublayerOnly-boolean-) | <p> Bu öznitelik, OCR alt katmanıyla PDF belgelerinden görüntü veya metin çıkarma işlevini etkinleştirir. </p>Value: {@code true} metin sonuç belgesinde çıkarılacak; aksi takdirde {@code false}. <hr> Default value == false |
| [setProgressEventsRetranslator](#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-) | Dönüştürme sırasında çalışan ve iç dönüşüm aşamalarının olaylarını dış toplam ilerleme olaylarına dönüştüren internal progress events processor'ı temsil eder. Ayrıca sınıf, artık ihtiyaç duyulmayan kaynakların serbest bırakılmasını sağlayan olayları yayınlar. Bu internal sınıf, PDF'den APS'ye ve APS'den [Other format]'a ilerleme olaylarını işleyerek toplam ilerlemeyi hesaplar ve müşterinin kodunu bu toplam ilerleme olayları hakkında bilgilendirir. Bu sınıf iki tür olayı kullanır: ApsToExternal model dönüşümü ve PDF'den APS'ye dönüşüm olayları, toplam ilerleme olayları üretmek için. Dışa aktarma üç aşamadan oluşur: 1) Pdf to Aps 2) Aps recognition 3) Aps export to target format. Yapıcı, kaç sayfanın dönüştürüleceğini ve bu ya da o aşamanın toplam ilerlemedeki yaklaşık kısmını ayarlamaya izin verir. |
| [setTryMergeAdjacentSameBackgroundImages](#setTryMergeAdjacentSameBackgroundImages-boolean-) | Bazen PDF'ler, sayfaların veya tablo hücrelerinin arka planını oluşturan, yan yana yerleştirilmiş birkaç aynı döşeme arka plan görüntüsünden oluşan arka plan görüntüleri içerir. Bu durumda hedef formatların renderleyicileri (ör. DOCS formatı için MsWord) bazen arka plan görüntülerinin parçaları arasında görülebilir sınırlar oluşturur; çünkü görüntü kenar yumuşatma (anti-aliasing) teknikleri Acrobat Reader'dan farklıdır. Dışa aktarılan belgenin aynı arka plan görüntüsünün parçaları arasında böyle görülebilir sınırlar içerdiği görülürse, lütfen bu ayarı kullanarak istenmeyen etkiyi ortadan kaldırmayı deneyin. DİKKAT! Bu kalite optimizasyonu genellikle dönüşümü önemli ölçüde yavaşlatır, bu yüzden lütfen bu seçeneği yalnızca gerçekten gerekli olduğunda kullanın. |

### IsMultiThreading {#IsMultiThreading}
```
public boolean IsMultiThreading
```

Sayfaları birkaç iş parçacığında işleyin.

### UnifiedSaveOptions {#UnifiedSaveOptions--}
```
public UnifiedSaveOptions()
```



### getProgressEventsRetranslator {#getProgressEventsRetranslator--}
```
public com.aspose.pdf.ConversionProgressEventsTranslator getProgressEventsRetranslator()
```

Dönüştürme sırasında çalışan ve iç dönüşüm aşamalarının olaylarını dış toplam ilerleme olaylarına dönüştüren internal progress events processor'ı temsil eder. Ayrıca sınıf, artık ihtiyaç duyulmayan kaynakların serbest bırakılmasını sağlayan olayları yayınlar. Bu internal sınıf, PDF'den APS'ye ve APS'den [Other format]'a ilerleme olaylarını işleyerek toplam ilerlemeyi hesaplar ve müşterinin kodunu bu toplam ilerleme olayları hakkında bilgilendirir. Bu sınıf iki tür olayı kullanır: ApsToExternal model dönüşümü ve PDF'den APS'ye dönüşüm olayları, toplam ilerleme olayları üretmek için. Dışa aktarma üç aşamadan oluşur: 1) Pdf to Aps 2) Aps recognition 3) Aps export to target format. Yapıcı, kaç sayfanın dönüştürüleceğini ve bu ya da o aşamanın toplam ilerlemedeki yaklaşık kısmını ayarlamaya izin verir.

**Returns:**
ConversionProgressEventsTranslator örneği

### isExtractOcrSublayerOnly {#isExtractOcrSublayerOnly--}
```
public boolean isExtractOcrSublayerOnly()
```

Bu öznitelik, OCR alt katmanı ile PDF belgelerinden görüntü veya metin çıkarma işlevini etkinleştirir. Değer: {@code true} ise metin sonuç belgesine çıkarılır; aksi takdirde {@code false}.

**Returns:**
boolean değer

### isTryMergeAdjacentSameBackgroundImages {#isTryMergeAdjacentSameBackgroundImages--}
```
public boolean isTryMergeAdjacentSameBackgroundImages()
```

Bazen PDF'ler, sayfaların veya tablo hücrelerinin arka planını oluşturan, yan yana yerleştirilmiş birkaç aynı döşeme arka plan görüntüsünden oluşan arka plan görüntüleri içerir. Bu durumda hedef formatların renderleyicileri (ör. DOCS formatı için MsWord) bazen arka plan görüntülerinin parçaları arasında görülebilir sınırlar oluşturur; çünkü görüntü kenar yumuşatma (anti-aliasing) teknikleri Acrobat Reader'dan farklıdır. Dışa aktarılan belgenin aynı arka plan görüntüsünün parçaları arasında böyle görülebilir sınırlar içerdiği görülürse, lütfen bu ayarı kullanarak istenmeyen etkiyi ortadan kaldırmayı deneyin. DİKKAT! Bu kalite optimizasyonu genellikle dönüşümü önemli ölçüde yavaşlatır, bu yüzden lütfen bu seçeneği yalnızca gerçekten gerekli olduğunda kullanın.

**Returns:**
boolean değer

### setExtractOcrSublayerOnly {#setExtractOcrSublayerOnly-boolean-}
```
public void setExtractOcrSublayerOnly(boolean value)
```

<p> Bu öznitelik, OCR alt katmanıyla PDF belgelerinden görüntü veya metin çıkarma işlevini etkinleştirir. </p>Value: {@code true} metin sonuç belgesinde çıkarılacak; aksi takdirde {@code false}. <hr> Default value == false

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setProgressEventsRetranslator {#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-}
Dönüştürme sırasında çalışan ve iç dönüşüm aşamalarının olaylarını dış toplam ilerleme olaylarına dönüştüren internal progress events processor'ı temsil eder. Ayrıca sınıf, artık ihtiyaç duyulmayan kaynakların serbest bırakılmasını sağlayan olayları yayınlar. Bu internal sınıf, PDF'den APS'ye ve APS'den [Other format]'a ilerleme olaylarını işleyerek toplam ilerlemeyi hesaplar ve müşterinin kodunu bu toplam ilerleme olayları hakkında bilgilendirir. Bu sınıf iki tür olayı kullanır: ApsToExternal model dönüşümü ve PDF'den APS'ye dönüşüm olayları, toplam ilerleme olayları üretmek için. Dışa aktarma üç aşamadan oluşur: 1) Pdf to Aps 2) Aps recognition 3) Aps export to target format. Yapıcı, kaç sayfanın dönüştürüleceğini ve bu ya da o aşamanın toplam ilerlemedeki yaklaşık kısmını ayarlamaya izin verir.

### setTryMergeAdjacentSameBackgroundImages {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)
```

Bazen PDF'ler, sayfaların veya tablo hücrelerinin arka planını oluşturan, yan yana yerleştirilmiş birkaç aynı döşeme arka plan görüntüsünden oluşan arka plan görüntüleri içerir. Bu durumda hedef formatların renderleyicileri (ör. DOCS formatı için MsWord) bazen arka plan görüntülerinin parçaları arasında görülebilir sınırlar oluşturur; çünkü görüntü kenar yumuşatma (anti-aliasing) teknikleri Acrobat Reader'dan farklıdır. Dışa aktarılan belgenin aynı arka plan görüntüsünün parçaları arasında böyle görülebilir sınırlar içerdiği görülürse, lütfen bu ayarı kullanarak istenmeyen etkiyi ortadan kaldırmayı deneyin. DİKKAT! Bu kalite optimizasyonu genellikle dönüşümü önemli ölçüde yavaşlatır, bu yüzden lütfen bu seçeneği yalnızca gerçekten gerekli olduğunda kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages |  | boolean değer |
