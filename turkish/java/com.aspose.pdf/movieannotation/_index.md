---
title: "MovieAnnotation"
linktitle: "MovieAnnotation"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bilgisayar ekranında ve hoparlörlerden sunulacak animasyonlu grafikler ve ses içeren bir film ek açıklamasını temsil eder. Ek açıklama etkinleştirildiğinde, the."
type: docs
weight: 3090
url: /tr/java/com.aspose.pdf/movieannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MovieAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MovieAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MovieAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class MovieAnnotation extends Annotation implements com.aspose.pdf.engine.ITitledAnnotation
```

Bilgisayar ekranında ve hoparlörler aracılığıyla sunulacak animasyonlu grafikler ve ses içeren bir film ek açıklamasını temsil eder. Ek açıklama etkinleştirildiğinde film oynatılır.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MovieAnnotation](#MovieAnnotation-com.aspose.pdf.IDocument-java.lang.String-) | Generator ile kullanılmak için yapıcı. |
| [MovieAnnotation](#MovieAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-) | Belirtilen sayfada yeni Ses açıklaması oluşturur. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Açıklamayı işlemek için ziyaretçi nesnesini kabul eder. |
| [getAnnotationType](#getAnnotationType--) | Ek açıklamanın tipini alır. |
| [getAspect](#getAspect--) | Filmin sınırlama kutusunun genişliğini ve yüksekliğini piksel cinsinden alır veya ayarlar. |
| [getFile](#getFile--) | Kendini tanımlayan bir film dosyasını tanımlayan dosya spesifikasyonunu alır. |
| [getPoster](#getPoster--) | Filmi temsil eden poster görüntüsünün görüntülenip görüntülenmeyeceğini ve nasıl görüntüleneceğini belirten bir bayrak veya akışı alır veya ayarlar. True ise poster görüntüsü film dosyasından alınır; false ise hiçbir poster görüntülenmez. |
| [getRotate](#getRotate--) | Filmin sayfaya göre saat yönünde döndürüleceği derece sayısını alır veya ayarlar. Değer 90'ın katı olmalıdır. |
| [getTitle](#getTitle--) | Film açıklamasının başlığını alır. |
| [setAspect](#setAspect-com.aspose.pdf.Point-) | Filmin sınırlama kutusunun genişliğini ve yüksekliğini piksel cinsinden alır veya ayarlar. |
| [setFile](#setFile-com.aspose.pdf.FileSpecification-) | Kendini tanımlayan bir film dosyasını tanımlayan dosya spesifikasyonunu ayarlar. |
| [setPoster](#setPoster-boolean-) | Filmi temsil eden poster görüntüsünün görüntülenip görüntülenmeyeceğini ve nasıl görüntüleneceğini belirten bir bayrak veya akışı alır veya ayarlar. True ise poster görüntüsü film dosyasından alınır; false ise hiçbir poster görüntülenmez. |
| [setRotate](#setRotate-int-) | Filmin sayfaya göre saat yönünde döndürüleceği derece sayısını alır veya ayarlar. Değer 90'ın katı olmalıdır. |
| [setTitle](#setTitle-java.lang.String-) | Film açıklamasının başlığını ayarlar. |

### MovieAnnotation {#MovieAnnotation-com.aspose.pdf.IDocument-java.lang.String-}
Generator ile kullanılmak için yapıcı.

### MovieAnnotation {#MovieAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-}
Belirtilen sayfada yeni Ses açıklaması oluşturur.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Açıklamayı işlemek için ziyaretçi nesnesini kabul eder.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Ek açıklamanın tipini alır.

**Returns:**
AnnotationType öğesi int değer olarak @see AnnotationType

### getAspect {#getAspect--}
```
public final Point getAspect()
```

Filmin sınırlama kutusunun genişliğini ve yüksekliğini piksel cinsinden alır veya ayarlar.

**Returns:**
Nokta örneği

### getFile {#getFile--}
```
public FileSpecification getFile()
```

Kendini tanımlayan bir film dosyasını tanımlayan dosya spesifikasyonunu alır.

**Returns:**
FileSpecification değeri

### getPoster {#getPoster--}
```
public final boolean getPoster()
```

Filmi temsil eden poster görüntüsünün görüntülenip görüntülenmeyeceğini ve nasıl görüntüleneceğini belirten bir bayrak veya akışı alır veya ayarlar. True ise poster görüntüsü film dosyasından alınır; false ise hiçbir poster görüntülenmez.

**Returns:**
boolean değer

### getRotate {#getRotate--}
```
public final int getRotate()
```

Filmin sayfaya göre saat yönünde döndürüleceği derece sayısını alır veya ayarlar. Değer 90'ın katı olmalıdır.

**Returns:**
int değer

### getTitle {#getTitle--}
```
public String getTitle()
```

Film açıklamasının başlığını alır.

**Returns:**
String değeri

### setAspect {#setAspect-com.aspose.pdf.Point-}
Filmin sınırlama kutusunun genişliğini ve yüksekliğini piksel cinsinden alır veya ayarlar.

### setFile {#setFile-com.aspose.pdf.FileSpecification-}
Kendini tanımlayan bir film dosyasını tanımlayan dosya spesifikasyonunu ayarlar.

### setPoster {#setPoster-boolean-}
```
public final void setPoster(boolean value)
```

Filmi temsil eden poster görüntüsünün görüntülenip görüntülenmeyeceğini ve nasıl görüntüleneceğini belirten bir bayrak veya akışı alır veya ayarlar. True ise poster görüntüsü film dosyasından alınır; false ise hiçbir poster görüntülenmez.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setRotate {#setRotate-int-}
```
public final void setRotate(int value)
```

Filmin sayfaya göre saat yönünde döndürüleceği derece sayısını alır veya ayarlar. Değer 90'ın katı olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setTitle {#setTitle-java.lang.String-}
Film açıklamasının başlığını ayarlar.
