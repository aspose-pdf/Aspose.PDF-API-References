---
title: "SaveOptions.ResourceSavingInfo"
linktitle: "SaveOptions.ResourceSavingInfo"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bu sınıf, PDF'nin başka bir formata (ör. HTML) dönüştürülmesi sırasında gerçekleşen dış kaynak dosyasının kaydedilmesiyle ilgili veri kümesini temsil eder."
type: docs
weight: 4440
url: /tr/java/com.aspose.pdf/saveoptions.resourcesavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions.ResourceSavingInfo

```
public static class SaveOptions.ResourceSavingInfo extends Object
```

Bu sınıf, PDF'nin başka bir formata (ör. HTML) dönüştürülmesi sırasında gerçekleşen dış kaynak dosyasının kaydedilmesiyle ilgili veri kümesini temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getContentStream](#getContentStream--) | Dönüştürücü tarafından ayarlanır. Kaydedilen dosyanın ikili içeriğini temsil eder. |
| [getResourceType](#getResourceType--) | Dönüştürücü tarafından ayarlanır. Dönüştürücünün özel yöntem koduna gönderdiği varsayılan dosya adı. Bu dosyanın nasıl işleneceğine veya nereye kaydedileceğine karar vermek için özel kodda kullanılabilir. |
| [getSupposedFileName](#getSupposedFileName--) | Dönüştürücü tarafından ayarlanır. Dönüştürücünün özel yöntem koduna gönderdiği varsayılan dosya adı. Bu dosyanın nasıl işleneceğine veya nereye kaydedileceğine karar vermek için özel kodda kullanılabilir. |
| [isCustomProcessingCancelled](#isCustomProcessingCancelled--) | Bu bayrak, özel kodda bazı nedenlerle önerilen dosyanın özel kodla değil, dönüştürücünün koduyla standart dönüştürücü yöntemiyle işlenmesi gerektiğinde "true" olarak ayarlanmalıdır. Bu nedenle, ayar true olduğunda, özel kodun referans verilen dosyayı işlemediği ve dönüştürücünün (hem bir yerde kaydetme hem de referans dosyanın adlandırılması açısından) dosyayı kendisinin ele alması gerektiği anlamına gelir. |
| [setCustomProcessingCancelled](#setCustomProcessingCancelled-boolean-) | Bu bayrak, özel kodda bazı nedenlerle önerilen dosyanın özel kod yerine dönüştürücünün koduyla standart bir şekilde işlenmesi gerektiğinde "true" olarak ayarlanmalıdır. Ayar true olduğunda, özel kodun referans verilen dosyayı işlemediği ve dönüştürücünün (hem bir yerde kaydetme hem de referans dosyanın adlandırılması açısından) dosyayı kendisinin ele alması gerektiği anlamına gelir. |

### getContentStream {#getContentStream--}
```
public byte[] getContentStream()
```

Dönüştürücü tarafından ayarlanır. Kaydedilen dosyanın ikili içeriğini temsil eder.

**Returns:**
bayt dizisi

### getResourceType {#getResourceType--}
```
public SaveOptions.NodeLevelResourceType getResourceType()
```

Dönüştürücü tarafından ayarlanır. Dönüştürücünün özel yöntem koduna gönderdiği varsayılan dosya adı. Bu dosyanın nasıl işleneceğine veya nereye kaydedileceğine karar vermek için özel kodda kullanılabilir.

**Returns:**
NodeLevelResourceType öğesi @see NodeLevelResourceType

### getSupposedFileName {#getSupposedFileName--}
```
public String getSupposedFileName()
```

Dönüştürücü tarafından ayarlanır. Dönüştürücünün özel yöntem koduna gönderdiği varsayılan dosya adı. Bu dosyanın nasıl işleneceğine veya nereye kaydedileceğine karar vermek için özel kodda kullanılabilir.

**Returns:**
String değeri

### isCustomProcessingCancelled {#isCustomProcessingCancelled--}
```
public boolean isCustomProcessingCancelled()
```

Bu bayrak, özel kodda bazı nedenlerle önerilen dosyanın özel kodla değil, dönüştürücünün koduyla standart dönüştürücü yöntemiyle işlenmesi gerektiğinde "true" olarak ayarlanmalıdır. Bu nedenle, ayar true olduğunda, özel kodun referans verilen dosyayı işlemediği ve dönüştürücünün (hem bir yerde kaydetme hem de referans dosyanın adlandırılması açısından) dosyayı kendisinin ele alması gerektiği anlamına gelir.

**Returns:**
boolean değer

### setCustomProcessingCancelled {#setCustomProcessingCancelled-boolean-}
```
public void setCustomProcessingCancelled(boolean customProcessingCancelled)
```

Bu bayrak, özel kodda bazı nedenlerle önerilen dosyanın özel kod yerine dönüştürücünün koduyla standart bir şekilde işlenmesi gerektiğinde "true" olarak ayarlanmalıdır. Ayar true olduğunda, özel kodun referans verilen dosyayı işlemediği ve dönüştürücünün (hem bir yerde kaydetme hem de referans dosyanın adlandırılması açısından) dosyayı kendisinin ele alması gerektiği anlamına gelir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| customProcessingCancelled |  | boolean değer |
