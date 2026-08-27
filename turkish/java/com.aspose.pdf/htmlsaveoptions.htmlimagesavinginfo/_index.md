---
title: "HtmlSaveOptions.HtmlImageSavingInfo"
linktitle: "HtmlSaveOptions.HtmlImageSavingInfo"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bu sınıf, PDF'ten HTML'e dönüşüm sırasında harici kaynak görüntü dosyasının kaydedilmesiyle ilgili veri kümesini temsil eder."
type: docs
weight: 2070
url: /tr/java/com.aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions.ResourceSavingInfo com.aspose.pdf.HtmlSaveOptions.HtmlImageSavingInfo, com.aspose.pdf.SaveOptions.ResourceSavingInfo, com.aspose.pdf.HtmlSaveOptions.HtmlImageSavingInfo

```
public static class HtmlSaveOptions.HtmlImageSavingInfo extends SaveOptions.ResourceSavingInfo
```

Bu sınıf, PDF'ten HTML'e dönüşüm sırasında harici kaynak görüntü dosyasının kaydedilmesiyle ilgili veri kümesini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [HtmlImageSavingInfo](#HtmlImageSavingInfo--) | HtmlImageSavingInfo yeni bir örnek oluşturur |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getHtmlHostPageNumber](#getHtmlHostPageNumber--) | Kaydedilen görüntünün, oluşturulan HTML sayfa dosyaları kümesinin hangi sayfasına ait olduğunu özel koda bildirir. Sayfalara bölme kapalıysa bu değer her zaman '1' içerir, çünkü bu durumda yalnızca bir HTML sayfası üretilir. |
| [getImageType](#getImageType--) | HTML içinde referans verilen kaydedilen görüntünün tipini temsil eder. Dönüştürücü tarafından ayarlanır ve ne yapılacağına karar vermek için özel kodda kullanılabilir. |
| [getParentType](#getParentType--) | Kaydedilen görüntü HTML'e ait olabilir veya HTML'e gömülü SVG'den çıkarılabilir. Bu özellik, işlenen görüntünün ebeveyn tipinin ne olduğunu özel koda bildirebilir. Dönüştürücü tarafından ayarlanır ve bu görüntüyle ne yapılacağına karar vermek için özel kodda kullanılabilir (ör. özel kod görüntünün nereye kaydedileceğini veya ebeveyn içeriğinde nasıl referans verileceğini belirleyebilir). |
| [getPdfHostPageNumber](#getPdfHostPageNumber--) | Kaydedilen görüntünün orijinal PDF belgesinin hangi sayfasına ait olduğunu özel koda bildirir. Orijinal belgenin tüm sayfaları kaydedilmeyebilir, bu değer orijinal PDF'teki ana sayfa numarasını verir. Eğer orijinal sayfa numarası bir sebeple bilinmiyorsa, her zaman '1' döndürür. |
| [setHtmlHostPageNumber](#setHtmlHostPageNumber-int-) | Kaydedilen görüntünün, oluşturulan HTML sayfa dosyaları kümesinin hangi sayfasına ait olduğunu özel koda bildirir. Sayfalara bölme kapalıysa bu değer her zaman '1' içerir, çünkü bu durumda yalnızca bir HTML sayfası üretilir. |
| [setImageType](#setImageType-int-) | HTML içinde referans verilen kaydedilen görüntünün tipini temsil eder. Dönüştürücü tarafından ayarlanır ve ne yapılacağına karar vermek için özel kodda kullanılabilir. |
| [setParentType](#setParentType-int-) | Kaydedilen görüntü HTML'e ait olabilir veya HTML'e gömülü SVG'den çıkarılabilir. Bu özellik, işlenen görüntünün ebeveyn tipinin ne olduğunu özel koda bildirebilir. Dönüştürücü tarafından ayarlanır ve bu görüntüyle ne yapılacağına karar vermek için özel kodda kullanılabilir (ör. özel kod görüntünün nereye kaydedileceğini veya ebeveyn içeriğinde nasıl referans verileceğini belirleyebilir). |
| [setPdfHostPageNumber](#setPdfHostPageNumber-int-) | Kaydedilen görüntünün orijinal PDF belgesinin hangi sayfasına ait olduğunu özel koda bildirir. Orijinal belgenin tüm sayfaları kaydedilmeyebilir, bu değer orijinal PDF'teki ana sayfa numarasını verir. Eğer orijinal sayfa numarası bir sebeple bilinmiyorsa, her zaman '1' döndürür. |

### HtmlImageSavingInfo {#HtmlImageSavingInfo--}
```
public HtmlImageSavingInfo()
```

HtmlImageSavingInfo yeni bir örnek oluşturur

### getHtmlHostPageNumber {#getHtmlHostPageNumber--}
```
public int getHtmlHostPageNumber()
```

Kaydedilen görüntünün, oluşturulan HTML sayfa dosyaları kümesinin hangi sayfasına ait olduğunu özel koda bildirir. Sayfalara bölme kapalıysa bu değer her zaman '1' içerir, çünkü bu durumda yalnızca bir HTML sayfası üretilir.

**Returns:**
int değer

### getImageType {#getImageType--}
```
public int getImageType()
```

HTML içinde referans verilen kaydedilen görüntünün tipini temsil eder. Dönüştürücü tarafından ayarlanır ve ne yapılacağına karar vermek için özel kodda kullanılabilir.

**Returns:**
HtmlImageType öğesi @see HtmlImageType

### getParentType {#getParentType--}
```
public int getParentType()
```

Kaydedilen görüntü HTML'e ait olabilir veya HTML'e gömülü SVG'den çıkarılabilir. Bu özellik, işlenen görüntünün ebeveyn tipinin ne olduğunu özel koda bildirebilir. Dönüştürücü tarafından ayarlanır ve bu görüntüyle ne yapılacağına karar vermek için özel kodda kullanılabilir (ör. özel kod görüntünün nereye kaydedileceğini veya ebeveyn içeriğinde nasıl referans verileceğini belirleyebilir).

**Returns:**
ImageParentTypes öğesi @see ImageParentTypes

### getPdfHostPageNumber {#getPdfHostPageNumber--}
```
public int getPdfHostPageNumber()
```

Kaydedilen görüntünün orijinal PDF belgesinin hangi sayfasına ait olduğunu özel koda bildirir. Orijinal belgenin tüm sayfaları kaydedilmeyebilir, bu değer orijinal PDF'teki ana sayfa numarasını verir. Eğer orijinal sayfa numarası bir sebeple bilinmiyorsa, her zaman '1' döndürür.

**Returns:**
int değer

### setHtmlHostPageNumber {#setHtmlHostPageNumber-int-}
```
public void setHtmlHostPageNumber(int htmlHostPageNumber)
```

Kaydedilen görüntünün, oluşturulan HTML sayfa dosyaları kümesinin hangi sayfasına ait olduğunu özel koda bildirir. Sayfalara bölme kapalıysa bu değer her zaman '1' içerir, çünkü bu durumda yalnızca bir HTML sayfası üretilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| htmlHostPageNumber |  | int değer |

### setImageType {#setImageType-int-}
```
public void setImageType(int imageType)
```

HTML içinde referans verilen kaydedilen görüntünün tipini temsil eder. Dönüştürücü tarafından ayarlanır ve ne yapılacağına karar vermek için özel kodda kullanılabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageType |  | HtmlImageType öğesi @see HtmlImageType |

### setParentType {#setParentType-int-}
```
public void setParentType(int parentType)
```

Kaydedilen görüntü HTML'e ait olabilir veya HTML'e gömülü SVG'den çıkarılabilir. Bu özellik, işlenen görüntünün ebeveyn tipinin ne olduğunu özel koda bildirebilir. Dönüştürücü tarafından ayarlanır ve bu görüntüyle ne yapılacağına karar vermek için özel kodda kullanılabilir (ör. özel kod görüntünün nereye kaydedileceğini veya ebeveyn içeriğinde nasıl referans verileceğini belirleyebilir).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parentType |  | ImageParentTypes öğesi @see ImageParentTypes |

### setPdfHostPageNumber {#setPdfHostPageNumber-int-}
```
public void setPdfHostPageNumber(int pdfHostPageNumber)
```

Kaydedilen görüntünün orijinal PDF belgesinin hangi sayfasına ait olduğunu özel koda bildirir. Orijinal belgenin tüm sayfaları kaydedilmeyebilir, bu değer orijinal PDF'teki ana sayfa numarasını verir. Eğer orijinal sayfa numarası bir sebeple bilinmiyorsa, her zaman '1' döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pdfHostPageNumber |  | int değer |
