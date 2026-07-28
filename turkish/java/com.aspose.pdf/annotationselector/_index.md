---
title: "AnnotationSelector"
linktitle: "AnnotationSelector"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bu sınıf, Visitor şablonu fikri kullanılarak açıklamaları seçmek için kullanılır."
type: docs
weight: 100
url: /tr/java/com.aspose.pdf/annotationselector/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AnnotationSelector

**All Implemented Interfaces:**
IAnnotationVisitor

```
public final class AnnotationSelector extends Object implements IAnnotationVisitor
```

Bu sınıf, Visitor şablonu fikri kullanılarak açıklamaları seçmek için kullanılır.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [AnnotationSelector](#AnnotationSelector--) | AnnotationSelector sınıfının yeni bir örneğini başlatır. |
| [AnnotationSelector](#AnnotationSelector-com.aspose.pdf.Annotation-) | AnnotationSelector sınıfının yeni bir örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSelected](#getSelected--) | Seçilen nesnelerin listesi. |
| [visit](#visit-com.aspose.pdf.BleedMarkAnnotation-) | Eğer {@link AnnotationSelector}, bir {@link BleedMarkAnnotation} nesnesiyle başlatıldıysa {@code bleedMark}'ı seçer. |
| [visit](#visit-com.aspose.pdf.CaretAnnotation-) | AnnotationSelector, bir CaretAnnotation nesnesiyle başlatıldıysa caret ek açıklamasını seçer. |
| [visit](#visit-com.aspose.pdf.CircleAnnotation-) | AnnotationSelector, bir CircleAnnotation nesnesiyle başlatıldıysa daire ek açıklamasını seçer. |
| [visit](#visit-com.aspose.pdf.ColorBarAnnotation-) | AnnotationSelector, bir ColorBar nesnesiyle başlatıldıysa ColorBar ek açıklamasını seçer. |
| [visit](#visit-com.aspose.pdf.FileAttachmentAnnotation-) | AnnotationSelector, bir FileAttachmentAnnotation nesnesiyle başlatıldıysa ek dosya ek açıklamasını seçer. |
| [visit](#visit-com.aspose.pdf.FreeTextAnnotation-) | AnnotationSelector, bir FreeTextAnnotation nesnesiyle başlatıldıysa serbest metin ek açıklamasını seçer. |
| [visit](#visit-com.aspose.pdf.HighlightAnnotation-) | AnnotationSelector, bir FreeTextAnnotation nesnesiyle başlatıldıysa ek dosya ek açıklamasını seçer. |
| [visit](#visit-com.aspose.pdf.InkAnnotation-) | AnnotationSelector, bir InkAnnotation nesnesiyle başlatıldıysa mürekkep ek açıklamasını seçer. |
| [visit](#visit-com.aspose.pdf.LineAnnotation-) | AnnotationSelector, bir LineAnnotation nesnesiyle başlatıldıysa çizgi ek açıklamasını seçer. |
| [visit](#visit-com.aspose.pdf.LinkAnnotation-) | AnnotationSelector, bir LinkAnnotation nesnesiyle başlatıldıysa bağlantı ek açıklamasını seçer. |
| [visit](#visit-com.aspose.pdf.MovieAnnotation-) | AnnotationSelector, bir MovieAnnotation nesnesiyle başlatıldıysa film ek açıklamasını seçer. |
| [visit](#visit-com.aspose.pdf.PageInformationAnnotation-) | Eğer {@link AnnotationSelector}, bir {@link PageInformationAnnotation} nesnesiyle başlatıldıysa {@code pageInformation}'ı seçer. |
| [visit](#visit-com.aspose.pdf.PDF3DAnnotation-) | AnnotationSelector, bir PDF3DAnnotation nesnesiyle başlatıldıysa PDF3D ek açıklamasını seçer. |
| [visit](#visit-com.aspose.pdf.PolygonAnnotation-) | AnnotationSelector, bir PolygonAnnotation nesnesiyle başlatıldıysa çokgen ek açıklamasını seçer. |
| [visit](#visit-com.aspose.pdf.PolylineAnnotation-) | AnnotationSelector, PolylineAnnotation nesnesiyle başlatıldıysa polyline açıklamasını seçin. |
| [visit](#visit-com.aspose.pdf.PopupAnnotation-) | AnnotationSelector, PopupAnnotation nesnesiyle başlatıldıysa popup açıklamasını seçin. |
| [visit](#visit-com.aspose.pdf.RedactionAnnotation-) | AnnotationSelector, RedactAnnotation nesnesiyle başlatıldıysa redact açıklamasını seçin. |
| [visit](#visit-com.aspose.pdf.RegistrationMarkAnnotation-) | Seçer {@code registrationMark} eğer {@link AnnotationSelector} bir {@link RegistrationMarkAnnotation} nesnesiyle başlatıldıysa. |
| [visit](#visit-com.aspose.pdf.RichMediaAnnotation-) | AnnotationSelector, RichMedia açıklaması nesnesiyle başlatıldıysa film açıklamasını seçin. |
| [visit](#visit-com.aspose.pdf.ScreenAnnotation-) | AnnotationSelector, ScreenAnnotation nesnesiyle başlatıldıysa ekran açıklamasını seçin. |
| [visit](#visit-com.aspose.pdf.SquareAnnotation-) | AnnotationSelector, SquareAnnotation nesnesiyle başlatıldıysa kare açıklamasını seçin. |
| [visit](#visit-com.aspose.pdf.SquigglyAnnotation-) | AnnotationSelector, SquigglyAnnotation nesnesiyle başlatıldıysa dalgalı açıklamayı seçin. |
| [visit](#visit-com.aspose.pdf.StampAnnotation-) | AnnotationSelector, StampAnnotation nesnesiyle başlatıldıysa damga açıklamasını seçin. |
| [visit](#visit-com.aspose.pdf.StrikeOutAnnotation-) | AnnotationSelector, StrikeOutAnnotation nesnesiyle başlatıldıysa üstü çizili açıklamayı seçin. |
| [visit](#visit-com.aspose.pdf.TextAnnotation-) | AnnotationSelector, TextAnnotation nesnesiyle başlatıldıysa metin açıklamasını seçin. |
| [visit](#visit-com.aspose.pdf.TrimMarkAnnotation-) | Seçer {@code trimMark} eğer {@link AnnotationSelector} bir {@link TrimMarkAnnotation} nesnesiyle başlatıldıysa. |
| [visit](#visit-com.aspose.pdf.UnderlineAnnotation-) | AnnotationSelector, UnderlineAnnotation nesnesiyle başlatıldıysa alt çizgi açıklamasını seçin. |
| [visit](#visit-com.aspose.pdf.WatermarkAnnotation-) | AnnotationSelector, WatermarkAnnotation nesnesiyle başlatıldıysa filigran açıklamasını seçin. |
| [visit](#visit-com.aspose.pdf.WidgetAnnotation-) | AnnotationSelector, WidgetAnnotation nesnesiyle başlatıldıysa widget açıklamasını seçin. |

### AnnotationSelector {#AnnotationSelector--}
```
public AnnotationSelector()
```

AnnotationSelector sınıfının yeni bir örneğini başlatır.

### AnnotationSelector {#AnnotationSelector-com.aspose.pdf.Annotation-}
AnnotationSelector sınıfının yeni bir örneğini başlatır.

### getSelected {#getSelected--}
```
public List < Annotation > getSelected()
```

Seçilen nesnelerin listesi.

**Returns:**
Annotation örneklerinin listesi

### visit {#visit-com.aspose.pdf.BleedMarkAnnotation-}
Eğer {@link AnnotationSelector}, bir {@link BleedMarkAnnotation} nesnesiyle başlatıldıysa {@code bleedMark}'ı seçer.

### visit {#visit-com.aspose.pdf.CaretAnnotation-}
AnnotationSelector, bir CaretAnnotation nesnesiyle başlatıldıysa caret ek açıklamasını seçer.

### visit {#visit-com.aspose.pdf.CircleAnnotation-}
AnnotationSelector, bir CircleAnnotation nesnesiyle başlatıldıysa daire ek açıklamasını seçer.

### visit {#visit-com.aspose.pdf.ColorBarAnnotation-}
AnnotationSelector, bir ColorBar nesnesiyle başlatıldıysa ColorBar ek açıklamasını seçer.

### visit {#visit-com.aspose.pdf.FileAttachmentAnnotation-}
AnnotationSelector, bir FileAttachmentAnnotation nesnesiyle başlatıldıysa ek dosya ek açıklamasını seçer.

### visit {#visit-com.aspose.pdf.FreeTextAnnotation-}
AnnotationSelector, bir FreeTextAnnotation nesnesiyle başlatıldıysa serbest metin ek açıklamasını seçer.

### visit {#visit-com.aspose.pdf.HighlightAnnotation-}
AnnotationSelector, bir FreeTextAnnotation nesnesiyle başlatıldıysa ek dosya ek açıklamasını seçer.

### visit {#visit-com.aspose.pdf.InkAnnotation-}
AnnotationSelector, bir InkAnnotation nesnesiyle başlatıldıysa mürekkep ek açıklamasını seçer.

### visit {#visit-com.aspose.pdf.LineAnnotation-}
AnnotationSelector, bir LineAnnotation nesnesiyle başlatıldıysa çizgi ek açıklamasını seçer.

### visit {#visit-com.aspose.pdf.LinkAnnotation-}
AnnotationSelector, bir LinkAnnotation nesnesiyle başlatıldıysa bağlantı ek açıklamasını seçer.

### visit {#visit-com.aspose.pdf.MovieAnnotation-}
AnnotationSelector, bir MovieAnnotation nesnesiyle başlatıldıysa film ek açıklamasını seçer.

### visit {#visit-com.aspose.pdf.PageInformationAnnotation-}
Eğer {@link AnnotationSelector}, bir {@link PageInformationAnnotation} nesnesiyle başlatıldıysa {@code pageInformation}'ı seçer.

### visit {#visit-com.aspose.pdf.PDF3DAnnotation-}
AnnotationSelector, bir PDF3DAnnotation nesnesiyle başlatıldıysa PDF3D ek açıklamasını seçer.

### visit {#visit-com.aspose.pdf.PolygonAnnotation-}
AnnotationSelector, bir PolygonAnnotation nesnesiyle başlatıldıysa çokgen ek açıklamasını seçer.

### visit {#visit-com.aspose.pdf.PolylineAnnotation-}
AnnotationSelector, PolylineAnnotation nesnesiyle başlatıldıysa polyline açıklamasını seçin.

### visit {#visit-com.aspose.pdf.PopupAnnotation-}
AnnotationSelector, PopupAnnotation nesnesiyle başlatıldıysa popup açıklamasını seçin.

### visit {#visit-com.aspose.pdf.RedactionAnnotation-}
AnnotationSelector, RedactAnnotation nesnesiyle başlatıldıysa redact açıklamasını seçin.

### visit {#visit-com.aspose.pdf.RegistrationMarkAnnotation-}
Seçer {@code registrationMark} eğer {@link AnnotationSelector} bir {@link RegistrationMarkAnnotation} nesnesiyle başlatıldıysa.

### visit {#visit-com.aspose.pdf.RichMediaAnnotation-}
AnnotationSelector, RichMedia açıklaması nesnesiyle başlatıldıysa film açıklamasını seçin.

### visit {#visit-com.aspose.pdf.ScreenAnnotation-}
AnnotationSelector, ScreenAnnotation nesnesiyle başlatıldıysa ekran açıklamasını seçin.

### visit {#visit-com.aspose.pdf.SquareAnnotation-}
AnnotationSelector, SquareAnnotation nesnesiyle başlatıldıysa kare açıklamasını seçin.

### visit {#visit-com.aspose.pdf.SquigglyAnnotation-}
AnnotationSelector, SquigglyAnnotation nesnesiyle başlatıldıysa dalgalı açıklamayı seçin.

### visit {#visit-com.aspose.pdf.StampAnnotation-}
AnnotationSelector, StampAnnotation nesnesiyle başlatıldıysa damga açıklamasını seçin.

### visit {#visit-com.aspose.pdf.StrikeOutAnnotation-}
AnnotationSelector, StrikeOutAnnotation nesnesiyle başlatıldıysa üstü çizili açıklamayı seçin.

### visit {#visit-com.aspose.pdf.TextAnnotation-}
AnnotationSelector, TextAnnotation nesnesiyle başlatıldıysa metin açıklamasını seçin.

### visit {#visit-com.aspose.pdf.TrimMarkAnnotation-}
Seçer {@code trimMark} eğer {@link AnnotationSelector} bir {@link TrimMarkAnnotation} nesnesiyle başlatıldıysa.

### visit {#visit-com.aspose.pdf.UnderlineAnnotation-}
AnnotationSelector, UnderlineAnnotation nesnesiyle başlatıldıysa alt çizgi açıklamasını seçin.

### visit {#visit-com.aspose.pdf.WatermarkAnnotation-}
AnnotationSelector, WatermarkAnnotation nesnesiyle başlatıldıysa filigran açıklamasını seçin.

### visit {#visit-com.aspose.pdf.WidgetAnnotation-}
AnnotationSelector, WidgetAnnotation nesnesiyle başlatıldıysa widget açıklamasını seçin.
