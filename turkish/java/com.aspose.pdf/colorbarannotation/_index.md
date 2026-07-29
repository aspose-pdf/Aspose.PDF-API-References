---
title: "ColorBarAnnotation"
linktitle: "ColorBarAnnotation"
second_title: "Aspose.PDF for Java API Referansı"
description: "ColorBarAnnotation açıklamasını temsil eden sınıf. Property Color yok sayılır, bunun yerine ColorsOfCMYK rengi kullanılır. Oluşturulurken, genişlik ve yükseklik oranı yönelimi belirler."
type: docs
weight: 680
url: /tr/java/com.aspose.pdf/colorbarannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.PrinterMarkAnnotation, com.aspose.pdf.ColorBarAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class ColorBarAnnotation extends PrinterMarkAnnotation
```

ColorBarAnnotation açıklamasını temsil eden sınıf. Property Color göz ardı edilir, bunun yerine ColorsOfCMYK rengi kullanılır. Oluşturulurken, genişlik ve yükseklik oranı açıklamanın yönünü belirler - yatay veya dikey. Sonra, annotation rectangle'ın TrimBox dışına çıkıp çıkmadığı kontrol edilir; çıkmazsa, açıklama en yakın TrimBox dışı konuma, açıklamanın yönü dikkate alınarak kaydırılır. Genişlik (yükseklik) azaltılarak açıklamanın TrimBox dışına sığması sağlanabilir. Yerleşim için alan yoksa, genişlik/yükseklik sıfıra ayarlanabilir (bu durumda açıklama sayfada bulunur ancak görüntülenmez).

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ColorBarAnnotation](#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Belirtilen sayfada yeni bir ColorBar açıklaması oluşturur. Varsayılan ColorsOfCMYK.Black |
| [ColorBarAnnotation](#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.ColorsOfCMYK-) | Belirtilen sayfada yeni bir ColorBar açıklaması oluşturur. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Açıklamayı işlemek için ziyaretçi nesnesini kabul eder. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Parametreleri ve görünümü, matris dönüşümüne ve gerekirse TrimBox dışına hareket etmeye göre günceller. |
| [getAnnotationType](#getAnnotationType--) | Ek açıklamanın tipini alır. |
| [getColorOfCMYK](#getColorOfCMYK--) | Açıklamanın çizildiği rengi (camgöbeği, macenta, sarı, siyah) alır veya ayarlar. |
| [setColorOfCMYK](#setColorOfCMYK-com.aspose.pdf.ColorsOfCMYK-) | Açıklamanın çizildiği rengi (camgöbeği, macenta, sarı, siyah) alır veya ayarlar. |

### ColorBarAnnotation {#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Belirtilen sayfada yeni bir ColorBar açıklaması oluşturur. Varsayılan ColorsOfCMYK.Black

### ColorBarAnnotation {#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.ColorsOfCMYK-}
Belirtilen sayfada yeni bir ColorBar açıklaması oluşturur.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Açıklamayı işlemek için ziyaretçi nesnesini kabul eder.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Parametreleri ve görünümü, matris dönüşümüne ve gerekirse TrimBox dışına hareket etmeye göre günceller.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Ek açıklamanın tipini alır.

**Returns:**
int değer

### getColorOfCMYK {#getColorOfCMYK--}
```
public final ColorsOfCMYK getColorOfCMYK()
```

Açıklamanın çizildiği rengi (camgöbeği, macenta, sarı, siyah) alır veya ayarlar.

**Returns:**
ColorsOfCMYK öğesi

### setColorOfCMYK {#setColorOfCMYK-com.aspose.pdf.ColorsOfCMYK-}
Açıklamanın çizildiği rengi (camgöbeği, macenta, sarı, siyah) alır veya ayarlar.
