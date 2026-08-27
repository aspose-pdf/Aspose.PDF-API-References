---
title: "EpubSaveOptions.RecognitionMode"
linktitle: "EpubSaveOptions.RecognitionMode"
second_title: "Aspose.PDF for Java API Referansı"
description: "PDF dosyası (genellikle sabit bir düzene sahiptir) dönüştürülürken, dönüşüm motoru orijinal belgeyi geri getirmek için gruplama ve çok seviyeli analiz yapmaya çalışır."
type: docs
weight: 1250
url: /tr/java/com.aspose.pdf/epubsaveoptions.recognitionmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < EpubSaveOptions.RecognitionMode > com.aspose.pdf.EpubSaveOptions.RecognitionMode, java.lang.Enum < EpubSaveOptions.RecognitionMode >, com.aspose.pdf.EpubSaveOptions.RecognitionMode

**All Implemented Interfaces:**
Serializable, Comparable < EpubSaveOptions.RecognitionMode >

```
public static enum EpubSaveOptions.RecognitionMode extends Enum < EpubSaveOptions.RecognitionMode >
```

PDF dosyası (genellikle sabit düzenli) dönüştürülürken, dönüşüm motoru orijinal belge yazarının niyetini geri kazandırmak ve sonucu akış düzeninde üretmek için gruplama ve çok seviyeli analiz yapmaya çalışır. Bu özellik, içeriğin tanınması için istenen yönteme göre bu dönüşümü ayarlar.

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Fixed](#Fixed) | Bu mod hızlıdır ve sayfaların orijinal görünümünü en üst düzeyde korumak için iyidir, ancak ne yazık ki birçok EPUB okuyucu sabit düzenli xhtml'i desteklememektedir. |
| [Flow](#Flow) | Tam tanıma modu, motor belge yazarının orijinal niyetini geri kazandırmak ve akış düzeninde xhtml üretmek için gruplama ve çok seviyeli analiz yapmaya çalışır. |
| [PdfFlow](#PdfFlow) | Bu dönüşümün temel fikri, pdf belgelerinin işlenmesi sırasında oluşan içeriğin render edilme "doğal" sırasını korumaya dayanır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Bu tipin belirtilen adla enum sabitini döndürür. |
| [values](#values--) | Bu enum tipinin sabitlerini içeren bir dizi döndürür, tanımlandıkları sırada. |

### Fixed {#Fixed}
```
public static final EpubSaveOptions.RecognitionMode Fixed
```

Bu mod hızlıdır ve sayfaların orijinal görünümünü en üst düzeyde korumak için iyidir, ancak ne yazık ki birçok EPUB okuyucu sabit düzenli xhtml'i desteklememektedir.

### Flow {#Flow}
```
public static final EpubSaveOptions.RecognitionMode Flow
```

Tam tanıma modu, motor belge yazarının orijinal niyetini geri kazandırmak ve akış düzeninde xhtml üretmek için gruplama ve çok seviyeli analiz yapmaya çalışır.

### PdfFlow {#PdfFlow}
```
public static final EpubSaveOptions.RecognitionMode PdfFlow
```

Bu dönüşümün temel fikri, pdf belgelerinin işlenmesi sırasında oluşan içeriğin render edilme "doğal" sırasını korumaya dayanır.

### getByValue {#getByValue-int-}
```
public static EpubSaveOptions.RecognitionMode getByValue(int value)
```



### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Bu tipin belirtilen adla enum sabitini döndürür.

### values {#values--}
```
public static EpubSaveOptions.RecognitionMode [] values()
```

Bu enum tipinin sabitlerini içeren bir dizi döndürür, tanımlandıkları sırada.

**Returns:**
Bu enum tipinin sabitlerini içeren bir dizi, tanımlandıkları sırada
