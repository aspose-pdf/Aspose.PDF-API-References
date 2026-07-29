---
title: "SoundAnnotation"
linktitle: "SoundAnnotation"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bilgisayar mikrofonundan kaydedilen veya bir dosyadan içe aktarılan sesi içeren ses açıklamasını temsil eder."
type: docs
weight: 4530
url: /tr/java/com.aspose.pdf/soundannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.SoundAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.SoundAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.SoundAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.SoundAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class SoundAnnotation extends MarkupAnnotation
```

Bilgisayar mikrofonundan kaydedilen veya bir dosyadan içe aktarılan sesi içeren ses açıklamasını temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SoundAnnotation](#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-) | Belirtilen sayfada yeni Ses açıklaması oluşturur. |
| [SoundAnnotation](#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-com.aspose.pdf.SoundSampleData-) | Belirtilen sayfada yeni Ses açıklaması oluşturur. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Açıklamayı işlemek için ziyaretçi nesnesini kabul eder. |
| [getAnnotationType](#getAnnotationType--) | Ek açıklamanın tipini alır. |
| [getIcon](#getIcon--) | Açıklamayı görüntülerken kullanılacak bir simge alır. |
| [getSoundData](#getSoundData--) | Ek açıklama etkinleştirildiğinde çalınacak sesi tanımlayan bir ses nesnesi alır. |
| [setIcon](#setIcon-int-) | Açıklamayı görüntülerken kullanılacak bir simge ayarlar. |

### SoundAnnotation {#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-}
Belirtilen sayfada yeni Ses açıklaması oluşturur.

### SoundAnnotation {#SoundAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-com.aspose.pdf.SoundSampleData-}
Belirtilen sayfada yeni Ses açıklaması oluşturur.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Açıklamayı işlemek için ziyaretçi nesnesini kabul eder.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Ek açıklamanın tipini alır.

**Returns:**
AnnotationType değeri @see AnnotationType

### getIcon {#getIcon--}
```
public int getIcon()
```

Açıklamayı görüntülerken kullanılacak bir simge alır.

**Returns:**
SoundIcon değeri @see SoundIcon

### getSoundData {#getSoundData--}
```
public SoundData getSoundData()
```

Ek açıklama etkinleştirildiğinde çalınacak sesi tanımlayan bir ses nesnesi alır.

**Returns:**
SoundData değeri

### setIcon {#setIcon-int-}
```
public void setIcon(int value)
```

Açıklamayı görüntülerken kullanılacak bir simge ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | SoundIcon değeri @see SoundIcon |
