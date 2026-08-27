---
title: "DocSaveOptions.RecognitionMode"
linktitle: "DocSaveOptions.RecognitionMode"
second_title: "Aspose.PDF for Java API Referansı"
description: "PDF belgesinin bir kelime işlem belgesine nasıl dönüştürüleceğini kontrol etmeye izin verir. Sonuç belgesinin yoğun bir şekilde düzenlenmeyeceği zaman RecognitionMode.Textbox modunu kullanın."
type: docs
weight: 1050
url: /tr/java/com.aspose.pdf/docsaveoptions.recognitionmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < DocSaveOptions.RecognitionMode > com.aspose.pdf.DocSaveOptions.RecognitionMode, java.lang.Enum < DocSaveOptions.RecognitionMode >, com.aspose.pdf.DocSaveOptions.RecognitionMode

**All Implemented Interfaces:**
Serializable, Comparable < DocSaveOptions.RecognitionMode >

```
public static enum DocSaveOptions.RecognitionMode extends Enum < DocSaveOptions.RecognitionMode >
```

Bir PDF belgesinin bir kelime işlem belgesine nasıl dönüştürüleceğini kontrol etmeye izin verir. Ortaya çıkan belge yoğun bir şekilde düzenlenmeyecekse RecognitionMode.Textbox modunu kullanın. Metin kutuları, yapılacak çok az şey olduğunda kolayca değiştirilebilir. Çıktı belgesinin daha fazla düzenlenmesi gerekiyorsa RecognitionMode.Flow modunu kullanın. Akış modundaki paragraflar ve metin satırları metnin kolayca değiştirilmesini sağlar, ancak desteklenmeyen biçimlendirme nesneleri RecognitionMode.Textbox moduna göre daha kötü görünecektir.

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [EnhancedFlow](#EnhancedFlow) | Tabloların tanınmasını destekleyen alternatif bir Akış modudur. |
| [Flow](#Flow) | Tam tanıma modu, motor gruplama ve çok seviyeli analiz yaparak orijinal belgenin yazarının niyetini geri kazandırır ve mümkün olduğunca düzenlenebilir bir belge üretir. |
| [Textbox](#Textbox) | Bu mod hızlıdır ve PDF dosyasının orijinal görünümünü mümkün olduğunca korumak için iyidir, ancak sonuç belgesinin düzenlenebilirliği sınırlı olabilir. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Bu tipin belirtilen adla enum sabitini döndürür. |
| [values](#values--) | Bu enum tipinin sabitlerini içeren bir dizi döndürür, tanımlandıkları sırada. |

### EnhancedFlow {#EnhancedFlow}
```
public static final DocSaveOptions.RecognitionMode EnhancedFlow
```

Tabloların tanınmasını destekleyen alternatif bir Akış modudur.

### Flow {#Flow}
```
public static final DocSaveOptions.RecognitionMode Flow
```

Tam tanıma modu, motor gruplama ve çok seviyeli analiz yaparak orijinal belgenin yazarının niyetini geri kazandırır ve mümkün olduğunca düzenlenebilir bir belge üretir.

### Textbox {#Textbox}
```
public static final DocSaveOptions.RecognitionMode Textbox
```

Bu mod hızlıdır ve PDF dosyasının orijinal görünümünü mümkün olduğunca korumak için iyidir, ancak sonuç belgesinin düzenlenebilirliği sınırlı olabilir.

### getByValue {#getByValue-int-}
```
public static DocSaveOptions.RecognitionMode getByValue(int value)
```



### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Bu tipin belirtilen adla enum sabitini döndürür.

### values {#values--}
```
public static DocSaveOptions.RecognitionMode [] values()
```

Bu enum tipinin sabitlerini içeren bir dizi döndürür, tanımlandıkları sırada.

**Returns:**
Bu enum tipinin sabitlerini içeren bir dizi, tanımlandıkları sırada
