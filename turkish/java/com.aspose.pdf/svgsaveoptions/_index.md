---
title: "SvgSaveOptions"
linktitle: "SvgSaveOptions"
second_title: "Aspose.PDF for Java API Referansı"
description: "SVG formatına dışa aktarma için kaydetme seçenekleri."
type: docs
weight: 4720
url: /tr/java/com.aspose.pdf/svgsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.SvgSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.SvgSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.SvgSaveOptions

```
public class SvgSaveOptions extends UnifiedSaveOptions
```

SVG formatına dışa aktarma için kaydetme seçenekleri.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SvgSaveOptions](#SvgSaveOptions--) | Yapıcı |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCustomStrategyOfEmbeddedImagesSaving](#getCustomStrategyOfEmbeddedImagesSaving--) | Bu alan, dönüştürme sırasında oluşturulan başvurulan dış görüntü dosyalarının (gömülü BMP veya JPEG gibi) kaydedilmiş SVG'ye gömülmesi için özelleştirilmiş işleme amacıyla kullanılacak (varsa) kaydetme stratejisini içerebilir. Bu strateji, kaynakları işleyip oluşturulan SVG içinde kaydedilen kaynağın istenen URI'sini temsil eden bir dize döndürmelidir. Bu veya o dosyanın işlenmesinin bir sebeple dönüştürücünün kodu tarafından, özel kodda değil, yapılması gerekiyorsa, lütfen özel kodda 'imageSavingInfo' parametresinin değişkenindeki 'CustomProcessingCancelled' bayrağını ayarlayın. Bu, dönüştürücüye, o kaynağın işlenmesi için gerekli tüm adımların dış bir özel kod yokmuş gibi dönüştürücü içinde yapılması gerektiğini bildirir. |
| [isCompressOutputToZipArchive](#isCompressOutputToZipArchive--) | Çıktının tek bir zip arşivi olarak oluşturulup oluşturulmayacağını belirtir. Çok sayfalı kaynak belgedeki sayfaların svg dosyalarının adlandırma kurallarını görmek için lütfen 'TreatTargetFileNameAsDirectory' seçeneğine ilişkin yoruma bakın; bu kurallar aynı zamanda sıkıştırılmış çıktı dosyaları kümesine de uygulanır. |
| [isScaleToPixels](#isScaleToPixels--) | Çıktı belgesinin tipografik puanlardan pikselere ölçeklendirilip ölçeklendirilmeyeceğini belirtir. |
| [isTreatTargetFileNameAsDirectory](#isTreatTargetFileNameAsDirectory--) | Bu seçenek, istenen çıktı dosyasının kendisi yerine aynı ada sahip hedef klasörün (henüz yoksa) oluşturulup oluşturulmayacağını tanımlar. Böylece klasör, sayfaların tüm çıktı SVG görüntülerini (aşağıda açıklandığı gibi) içerir. Hayır ise, ilk sayfa dışındaki sayfaların çıktı dosyaları, ana çıktı dosyasıyla aynı klasörde oluşturulur, ancak dosya adının sonuna sayfa numarasına göre _[2...n] eki eklenir; örneğin, çıktı dosyasını "C:\\AsposeTests\\output.svg" olarak belirlerseniz ve çıktı birkaç sayfanın svg dosyalarını içeriyorsa, sayfa dosyaları da "C:\\AsposeTests\\" klasöründe oluşturulur ve 'output.svg', 'output_2.svg', 'output_3.svg' gibi adlara sahip olur. |
| [setCompressOutputToZipArchive](#setCompressOutputToZipArchive-boolean-) | Çıktının tek bir zip arşivi olarak oluşturulup oluşturulmayacağını belirtir. Çok sayfalı kaynak belgedeki sayfaların svg dosyalarının adlandırma kurallarını görmek için lütfen 'TreatTargetFileNameAsDirectory' seçeneğine ilişkin yoruma bakın; bu kurallar aynı zamanda sıkıştırılmış çıktı dosyaları kümesine de uygulanır. |
| [setCustomStrategyOfEmbeddedImagesSaving](#setCustomStrategyOfEmbeddedImagesSaving-com.aspose.pdf.SvgSaveOptions.EmbeddedImagesSavingStrategy-) | Bu alan, (varsa) dönüşüm sırasında oluşturulan başvurulan dış görüntü dosyalarının (gömülü BMP veya JPEG gibi) kaydedilen SVG'ye gömülmesi için özelleştirilmiş işleme kullanılacak kaydetme stratejisini içerebilir. |
| [setScaleToPixels](#setScaleToPixels-boolean-) | Çıktı belgesinin tipografik puanlardan pikselere ölçeklendirilip ölçeklendirilmeyeceğini belirtir. |
| [setTreatTargetFileNameAsDirectory](#setTreatTargetFileNameAsDirectory-boolean-) | Bu seçenek, istenen çıktı dosyasının kendisi yerine aynı ada sahip hedef klasörün (henüz yoksa) oluşturulup oluşturulmayacağını tanımlar. Böylece klasör, sayfaların tüm çıktı SVG görüntülerini (aşağıda açıklandığı gibi) içerir. Hayır ise, ilk sayfa dışındaki sayfaların çıktı dosyaları, ana çıktı dosyasıyla aynı klasörde oluşturulur, ancak dosya adının sonuna sayfa numarasına göre _[2...n] eki eklenir; örneğin, çıktı dosyasını "C:\\AsposeTests\\output.svg" olarak belirlerseniz ve çıktı birkaç sayfanın svg dosyalarını içeriyorsa, sayfa dosyaları da "C:\\AsposeTests\\" klasöründe oluşturulur ve 'output.svg', 'output_2.svg', 'output_3.svg' gibi adlara sahip olur. |

### SvgSaveOptions {#SvgSaveOptions--}
```
public SvgSaveOptions()
```

Yapıcı

### getCustomStrategyOfEmbeddedImagesSaving {#getCustomStrategyOfEmbeddedImagesSaving--}
```
public SvgSaveOptions.EmbeddedImagesSavingStrategy getCustomStrategyOfEmbeddedImagesSaving()
```

Bu alan, dönüştürme sırasında oluşturulan başvurulan dış görüntü dosyalarının (gömülü BMP veya JPEG gibi) kaydedilmiş SVG'ye gömülmesi için özelleştirilmiş işleme amacıyla kullanılacak (varsa) kaydetme stratejisini içerebilir. Bu strateji, kaynakları işleyip oluşturulan SVG içinde kaydedilen kaynağın istenen URI'sini temsil eden bir dize döndürmelidir. Bu veya o dosyanın işlenmesinin bir sebeple dönüştürücünün kodu tarafından, özel kodda değil, yapılması gerekiyorsa, lütfen özel kodda 'imageSavingInfo' parametresinin değişkenindeki 'CustomProcessingCancelled' bayrağını ayarlayın. Bu, dönüştürücüye, o kaynağın işlenmesi için gerekli tüm adımların dış bir özel kod yokmuş gibi dönüştürücü içinde yapılması gerektiğini bildirir.

**Returns:**
EmbeddedImagesSavingStrategy örneği

### isCompressOutputToZipArchive {#isCompressOutputToZipArchive--}
```
public boolean isCompressOutputToZipArchive()
```

Çıktının tek bir zip arşivi olarak oluşturulup oluşturulmayacağını belirtir. Çok sayfalı kaynak belgedeki sayfaların svg dosyalarının adlandırma kurallarını görmek için lütfen 'TreatTargetFileNameAsDirectory' seçeneğine ilişkin yoruma bakın; bu kurallar aynı zamanda sıkıştırılmış çıktı dosyaları kümesine de uygulanır.

**Returns:**
boolean değer

### isScaleToPixels {#isScaleToPixels--}
```
public boolean isScaleToPixels()
```

Çıktı belgesinin tipografik puanlardan pikselere ölçeklendirilip ölçeklendirilmeyeceğini belirtir.

**Returns:**
boolean değer

### isTreatTargetFileNameAsDirectory {#isTreatTargetFileNameAsDirectory--}
```
public boolean isTreatTargetFileNameAsDirectory()
```

Bu seçenek, istenen çıktı dosyasının kendisi yerine aynı ada sahip hedef klasörün (henüz yoksa) oluşturulup oluşturulmayacağını tanımlar. Böylece klasör, sayfaların tüm çıktı SVG görüntülerini (aşağıda açıklandığı gibi) içerir. Hayır ise, ilk sayfa dışındaki sayfaların çıktı dosyaları, ana çıktı dosyasıyla aynı klasörde oluşturulur, ancak dosya adının sonuna sayfa numarasına göre _[2...n] eki eklenir; örneğin, çıktı dosyasını "C:\\AsposeTests\\output.svg" olarak belirlerseniz ve çıktı birkaç sayfanın svg dosyalarını içeriyorsa, sayfa dosyaları da "C:\\AsposeTests\\" klasöründe oluşturulur ve 'output.svg', 'output_2.svg', 'output_3.svg' gibi adlara sahip olur.

**Returns:**
boolean değer

### setCompressOutputToZipArchive {#setCompressOutputToZipArchive-boolean-}
```
public void setCompressOutputToZipArchive(boolean compressOutputToZipArchive)
```

Çıktının tek bir zip arşivi olarak oluşturulup oluşturulmayacağını belirtir. Çok sayfalı kaynak belgedeki sayfaların svg dosyalarının adlandırma kurallarını görmek için lütfen 'TreatTargetFileNameAsDirectory' seçeneğine ilişkin yoruma bakın; bu kurallar aynı zamanda sıkıştırılmış çıktı dosyaları kümesine de uygulanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| compressOutputToZipArchive |  | boolean değer |

### setCustomStrategyOfEmbeddedImagesSaving {#setCustomStrategyOfEmbeddedImagesSaving-com.aspose.pdf.SvgSaveOptions.EmbeddedImagesSavingStrategy-}
Bu alan, (varsa) dönüşüm sırasında oluşturulan başvurulan dış görüntü dosyalarının (gömülü BMP veya JPEG gibi) kaydedilen SVG'ye gömülmesi için özelleştirilmiş işleme kullanılacak kaydetme stratejisini içerebilir.

### setScaleToPixels {#setScaleToPixels-boolean-}
```
public void setScaleToPixels(boolean scaleToPixels)
```

Çıktı belgesinin tipografik puanlardan pikselere ölçeklendirilip ölçeklendirilmeyeceğini belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| scaleToPixels |  | boolean değer |

### setTreatTargetFileNameAsDirectory {#setTreatTargetFileNameAsDirectory-boolean-}
```
public void setTreatTargetFileNameAsDirectory(boolean treatTargetFileNameAsDirectory)
```

Bu seçenek, istenen çıktı dosyasının kendisi yerine aynı ada sahip hedef klasörün (henüz yoksa) oluşturulup oluşturulmayacağını tanımlar. Böylece klasör, sayfaların tüm çıktı SVG görüntülerini (aşağıda açıklandığı gibi) içerir. Hayır ise, ilk sayfa dışındaki sayfaların çıktı dosyaları, ana çıktı dosyasıyla aynı klasörde oluşturulur, ancak dosya adının sonuna sayfa numarasına göre _[2...n] eki eklenir; örneğin, çıktı dosyasını "C:\\AsposeTests\\output.svg" olarak belirlerseniz ve çıktı birkaç sayfanın svg dosyalarını içeriyorsa, sayfa dosyaları da "C:\\AsposeTests\\" klasöründe oluşturulur ve 'output.svg', 'output_2.svg', 'output_3.svg' gibi adlara sahip olur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| treatTargetFileNameAsDirectory |  | boolean değer |
