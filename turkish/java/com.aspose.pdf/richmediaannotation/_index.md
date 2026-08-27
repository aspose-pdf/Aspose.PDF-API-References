---
title: "RichMediaAnnotation"
linktitle: "RichMediaAnnotation"
second_title: "Aspose.PDF for Java API Referansı"
description: "PDF belgesine video/audio verisi gömmeye izin veren RichMediaAnnotation'ı tanımlayan sınıf."
type: docs
weight: 4260
url: /tr/java/com.aspose.pdf/richmediaannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.RichMediaAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.RichMediaAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.RichMediaAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class RichMediaAnnotation extends Annotation
```

PDF belgesine video/audio verisi gömmeye izin veren RichMediaAnnotation'ı tanımlayan sınıf.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [RichMediaAnnotation](#RichMediaAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | RichMediaAnnotation'ı başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Bu açıklama için ziyaretçiyi kabul eder. |
| [addCustomData](#addCustomData-java.lang.String-java.io.InputStream-) | Özel adlandırılmış veri ekle (örneğin flash betiği için gerekli). |
| [getActivateOn](#getActivateOn--) | Uygulamayı etkinleştiren olay. |
| [getAnnotationType](#getAnnotationType--) | Ek açıklamanın tipini alır. |
| [getContent](#getContent--) | Rich Media içeriğinin verileri. |
| [getCustomFlashVariables](#getCustomFlashVariables--) | Oynatıcıya geçirilen flash değişkenlerini ayarlar veya alır. |
| [getCustomPlayer](#getCustomPlayer--) | Video/ ses verilerini oynatmak için özel flash oynatıcıyı ayarlar veya alır. |
| [getType](#getType--) | İçeriğin türünü alır veya ayarlar. Olası değerler: Audio, Video. |
| [setActivateOn](#setActivateOn-int-) | Uygulamayı etkinleştiren olay. |
| [setContent](#setContent-java.lang.String-java.io.InputStream-) | İçerik akışını ayarla. |
| [setCustomFlashVariables](#setCustomFlashVariables-java.lang.String-) | Oynatıcıya geçirilen flash değişkenlerini ayarlar veya alır. |
| [setCustomPlayer](#setCustomPlayer-java.io.InputStream-) | Video/ ses verilerini oynatmak için özel flash oynatıcıyı ayarlar veya alır. |
| [setPoster](#setPoster-java.io.InputStream-) | Açıklamanın posterini ayarla. |
| [setType](#setType-int-) | İçeriğin türünü alır veya ayarlar. Olası değerler: Audio, Video. |
| [update](#update--) | Belirtilen parametrelerle verileri günceller. |

### RichMediaAnnotation {#RichMediaAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
RichMediaAnnotation'ı başlatır.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Bu açıklama için ziyaretçiyi kabul eder.

### addCustomData {#addCustomData-java.lang.String-java.io.InputStream-}
Özel adlandırılmış veri ekle (örneğin flash betiği için gerekli).

### getActivateOn {#getActivateOn--}
```
public int getActivateOn()
```

Uygulamayı etkinleştiren olay.

**Returns:**
ActivationEvent öğesi

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Ek açıklamanın tipini alır.

**Returns:**
AnnotationType öğesi @see AnnotationType

### getContent {#getContent--}
```
public InputStream getContent()
```

Rich Media içeriğinin verileri.

**Returns:**
InputStream nesnesi

### getCustomFlashVariables {#getCustomFlashVariables--}
```
public String getCustomFlashVariables()
```

Oynatıcıya geçirilen flash değişkenlerini ayarlar veya alır.

**Returns:**
Dize nesnesi

### getCustomPlayer {#getCustomPlayer--}
```
public InputStream getCustomPlayer()
```

Video/ ses verilerini oynatmak için özel flash oynatıcıyı ayarlar veya alır.

**Returns:**
InputStream nesnesi

### getType {#getType--}
```
public int getType()
```

İçeriğin türünü alır veya ayarlar. Olası değerler: Audio, Video.

**Returns:**
ContentType değeri @see ContentType

### setActivateOn {#setActivateOn-int-}
```
public void setActivateOn(int value)
```

Uygulamayı etkinleştiren olay.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | ActivationEvent öğesi |

### setContent {#setContent-java.lang.String-java.io.InputStream-}
İçerik akışını ayarla.

### setCustomFlashVariables {#setCustomFlashVariables-java.lang.String-}
Oynatıcıya geçirilen flash değişkenlerini ayarlar veya alır.

### setCustomPlayer {#setCustomPlayer-java.io.InputStream-}
Video/ ses verilerini oynatmak için özel flash oynatıcıyı ayarlar veya alır.

### setPoster {#setPoster-java.io.InputStream-}
Açıklamanın posterini ayarla.

### setType {#setType-int-}
```
public void setType(int value)
```

İçeriğin türünü alır veya ayarlar. Olası değerler: Audio, Video.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | ContentType öğesi |

### update {#update--}
```
public void update()
```

Belirtilen parametrelerle verileri günceller.
