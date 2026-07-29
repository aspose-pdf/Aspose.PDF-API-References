---
title: "HtmlSaveOptions.HtmlPageMarkupSavingInfo"
linktitle: "HtmlSaveOptions.HtmlPageMarkupSavingInfo"
second_title: "Aspose.PDF for Java API Referansı"
description: "HtmlSaveOptions sınıfının SplitToPages özelliği varsa, PDF'in HTML'e dönüştürülmesi sırasında birkaç HTML dosyası (dönüştürülen her sayfa için bir HTML dosyası) oluşturulur. Bu sınıf, ... kümesini temsil eder."
type: docs
weight: 2100
url: /tr/java/com.aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo

```
public static class HtmlSaveOptions.HtmlPageMarkupSavingInfo extends Object
```

HtmlSaveOptions sınıfının SplitToPages özelliği etkinse, PDF'ten HTML'e dönüşüm sırasında birden fazla HTML dosyası (dönüştürülen her sayfa için bir HTML dosyası) oluşturulur. Bu sınıf, PDF'ten HTML'e dönüşüm sırasında bir HTML sayfasının işaretlemesinin özel olarak kaydedilmesiyle ilgili veri kümesini temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getContentStream](#getContentStream--) | Dönüştürücü tarafından ayarlanır. Kaydedilen HTML'i akış olarak temsil eder. |
| [getHtmlHostPageNumber](#getHtmlHostPageNumber--) | Dönüştürücü tarafından ayarlanır. SplitToPages özelliği ayarlanmışsa, dönüşüm sırasında birkaç HTML dosyası (dönüştürülen her sayfa için bir HTML dosyası) oluşturulur. Bu özellik, kaydedilen HTML sayfasının dosyasının sıra numarasını içerir. Özellik, özel kod mantığında HTML sayfasının nasıl işleneceğine veya nereye kaydedileceğine karar vermek için kullanılabilir ve sayfalara bölme devre dışı bırakıldığında bu değer her zaman '1' içerir; çünkü bu durumda tüm kaynak belge için yalnızca tek bir büyük HTML sayfası üretilir. |
| [getPdfHostPageNumber](#getPdfHostPageNumber--) | Dönüştürücü tarafından ayarlanır. SplitToPages özelliği ayarlanmışsa, dönüşüm sırasında birkaç HTML dosyası (dönüştürülen her sayfa için bir HTML dosyası) oluşturulur. Bu özellik, özel koda kaydedilen HTML işaretlemesinin orijinal PDF'in hangi sayfasından oluşturulduğunu bildirir. Orijinal sayfa numarası bir sebeple bilinmiyorsa veya SplitToPages=false ise, bu özellik her zaman '0' içerir; bu, dönüştürücünün sağlanan HTML işaretleme dosyası için kesin orijinal PDF sayfa numarasını sağlayamadığını gösterir. |
| [getSupposedFileName](#getSupposedFileName--) | Dönüştürücü tarafından ayarlanır. Dönüştürücünün özel metoda koduna ilettiği varsayılan dosya adı. İçeriğin nasıl işleneceğine veya nereye kaydedileceğine karar vermek için özel kodda kullanılabilir. |
| [isCustomProcessingCancelled](#isCustomProcessingCancelled--) | Gerekli olduğunda özel kodda ayarlanmalıdır. Bu bayrak, bazı nedenlerle sağlanan html‑işaretlemesinin özel kod yerine dönüştürücünün kendi kodu ile standart şekilde işlenmesi gerektiğinde, özel kodda "true" olarak ayarlanmalıdır. Bu bayrağın özel kodda ayarlanması, referans verilen dosyanın özel kod tarafından işlenmediği ve dönüştürücünün kendisinin ele alması gerektiği anlamına gelir. |
| [setContentStream](#setContentStream-java.io.InputStream-) | Dönüştürücü tarafından ayarlanır. Kaydedilen HTML'i akış olarak temsil eder. |
| [setCustomProcessingCancelled](#setCustomProcessingCancelled-boolean-) | Gerekli olduğunda özel kodda ayarlanmalıdır. Bu bayrak, bazı nedenlerle sağlanan html‑işaretlemesinin özel kod yerine dönüştürücünün kendi kodu ile standart şekilde işlenmesi gerektiğinde, özel kodda "true" olarak ayarlanmalıdır. Bu bayrağın özel kodda ayarlanması, referans verilen dosyanın özel kod tarafından işlenmediği ve dönüştürücünün kendisinin ele alması gerektiği anlamına gelir. |
| [setHtmlHostPageNumber](#setHtmlHostPageNumber-int-) | Dönüştürücü tarafından ayarlanır. SplitToPages özelliği ayarlanmışsa, dönüşüm sırasında birkaç HTML dosyası (dönüştürülen her sayfa için bir HTML dosyası) oluşturulur. Bu özellik, kaydedilen HTML sayfasının dosyasının sıra numarasını içerir. Özellik, özel kod mantığında HTML sayfasının nasıl işleneceğine veya nereye kaydedileceğine karar vermek için kullanılabilir ve sayfalara bölme devre dışı bırakıldığında bu değer her zaman '1' içerir; çünkü bu durumda tüm kaynak belge için yalnızca tek bir büyük HTML sayfası üretilir. |
| [setPdfHostPageNumber](#setPdfHostPageNumber-int-) | Dönüştürücü tarafından ayarlanır. SplitToPages özelliği ayarlanmışsa, dönüşüm sırasında birkaç HTML dosyası (dönüştürülen her sayfa için bir HTML dosyası) oluşturulur. Bu özellik, özel koda kaydedilen HTML işaretlemesinin orijinal PDF'in hangi sayfasından oluşturulduğunu bildirir. Orijinal sayfa numarası bir sebeple bilinmiyorsa veya SplitToPages=false ise, bu özellik her zaman '0' içerir; bu, dönüştürücünün sağlanan HTML işaretleme dosyası için kesin orijinal PDF sayfa numarasını sağlayamadığını gösterir. |
| [setSupposedFileName](#setSupposedFileName-java.lang.String-) | Dönüştürücü tarafından ayarlanır. Dönüştürücünün özel metoda koduna ilettiği varsayılan dosya adı. İçeriğin nasıl işleneceğine veya nereye kaydedileceğine karar vermek için özel kodda kullanılabilir. |

### getContentStream {#getContentStream--}
```
public InputStream getContentStream()
```

Dönüştürücü tarafından ayarlanır. Kaydedilen HTML'i akış olarak temsil eder.

**Returns:**
InputStream örneği.

### getHtmlHostPageNumber {#getHtmlHostPageNumber--}
```
public int getHtmlHostPageNumber()
```

Dönüştürücü tarafından ayarlanır. SplitToPages özelliği ayarlanmışsa, dönüşüm sırasında birkaç HTML dosyası (dönüştürülen her sayfa için bir HTML dosyası) oluşturulur. Bu özellik, kaydedilen HTML sayfasının dosyasının sıra numarasını içerir. Özellik, özel kod mantığında HTML sayfasının nasıl işleneceğine veya nereye kaydedileceğine karar vermek için kullanılabilir ve sayfalara bölme devre dışı bırakıldığında bu değer her zaman '1' içerir; çünkü bu durumda tüm kaynak belge için yalnızca tek bir büyük HTML sayfası üretilir.

**Returns:**
int değer

### getPdfHostPageNumber {#getPdfHostPageNumber--}
```
public int getPdfHostPageNumber()
```

Dönüştürücü tarafından ayarlanır. SplitToPages özelliği ayarlanmışsa, dönüşüm sırasında birkaç HTML dosyası (dönüştürülen her sayfa için bir HTML dosyası) oluşturulur. Bu özellik, özel koda kaydedilen HTML işaretlemesinin orijinal PDF'in hangi sayfasından oluşturulduğunu bildirir. Orijinal sayfa numarası bir sebeple bilinmiyorsa veya SplitToPages=false ise, bu özellik her zaman '0' içerir; bu, dönüştürücünün sağlanan HTML işaretleme dosyası için kesin orijinal PDF sayfa numarasını sağlayamadığını gösterir.

**Returns:**
int değer

### getSupposedFileName {#getSupposedFileName--}
```
public String getSupposedFileName()
```

Dönüştürücü tarafından ayarlanır. Dönüştürücünün özel metoda koduna ilettiği varsayılan dosya adı. İçeriğin nasıl işleneceğine veya nereye kaydedileceğine karar vermek için özel kodda kullanılabilir.

**Returns:**
String değeri

### isCustomProcessingCancelled {#isCustomProcessingCancelled--}
```
public boolean isCustomProcessingCancelled()
```

Gerekli olduğunda özel kodda ayarlanmalıdır. Bu bayrak, bazı nedenlerle sağlanan html‑işaretlemesinin özel kod yerine dönüştürücünün kendi kodu ile standart şekilde işlenmesi gerektiğinde, özel kodda "true" olarak ayarlanmalıdır. Bu bayrağın özel kodda ayarlanması, referans verilen dosyanın özel kod tarafından işlenmediği ve dönüştürücünün kendisinin ele alması gerektiği anlamına gelir.

**Returns:**
boolean değer

### setContentStream {#setContentStream-java.io.InputStream-}
Dönüştürücü tarafından ayarlanır. Kaydedilen HTML'i akış olarak temsil eder.

### setCustomProcessingCancelled {#setCustomProcessingCancelled-boolean-}
```
public void setCustomProcessingCancelled(boolean customProcessingCancelled)
```

Gerekli olduğunda özel kodda ayarlanmalıdır. Bu bayrak, bazı nedenlerle sağlanan html‑işaretlemesinin özel kod yerine dönüştürücünün kendi kodu ile standart şekilde işlenmesi gerektiğinde, özel kodda "true" olarak ayarlanmalıdır. Bu bayrağın özel kodda ayarlanması, referans verilen dosyanın özel kod tarafından işlenmediği ve dönüştürücünün kendisinin ele alması gerektiği anlamına gelir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| customProcessingCancelled |  | boolean değer |

### setHtmlHostPageNumber {#setHtmlHostPageNumber-int-}
```
public void setHtmlHostPageNumber(int htmlHostPageNumber)
```

Dönüştürücü tarafından ayarlanır. SplitToPages özelliği ayarlanmışsa, dönüşüm sırasında birkaç HTML dosyası (dönüştürülen her sayfa için bir HTML dosyası) oluşturulur. Bu özellik, kaydedilen HTML sayfasının dosyasının sıra numarasını içerir. Özellik, özel kod mantığında HTML sayfasının nasıl işleneceğine veya nereye kaydedileceğine karar vermek için kullanılabilir ve sayfalara bölme devre dışı bırakıldığında bu değer her zaman '1' içerir; çünkü bu durumda tüm kaynak belge için yalnızca tek bir büyük HTML sayfası üretilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| htmlHostPageNumber |  | int değer |

### setPdfHostPageNumber {#setPdfHostPageNumber-int-}
```
public void setPdfHostPageNumber(int pdfHostPageNumber)
```

Dönüştürücü tarafından ayarlanır. SplitToPages özelliği ayarlanmışsa, dönüşüm sırasında birkaç HTML dosyası (dönüştürülen her sayfa için bir HTML dosyası) oluşturulur. Bu özellik, özel koda kaydedilen HTML işaretlemesinin orijinal PDF'in hangi sayfasından oluşturulduğunu bildirir. Orijinal sayfa numarası bir sebeple bilinmiyorsa veya SplitToPages=false ise, bu özellik her zaman '0' içerir; bu, dönüştürücünün sağlanan HTML işaretleme dosyası için kesin orijinal PDF sayfa numarasını sağlayamadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pdfHostPageNumber |  | int değer |

### setSupposedFileName {#setSupposedFileName-java.lang.String-}
Dönüştürücü tarafından ayarlanır. Dönüştürücünün özel metoda koduna ilettiği varsayılan dosya adı. İçeriğin nasıl işleneceğine veya nereye kaydedileceğine karar vermek için özel kodda kullanılabilir.
