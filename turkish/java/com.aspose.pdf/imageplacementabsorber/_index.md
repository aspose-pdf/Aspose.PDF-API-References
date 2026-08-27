---
title: "ImagePlacementAbsorber"
linktitle: "ImagePlacementAbsorber"
second_title: "Aspose.PDF for Java API Referansı"
description: "<p> Görüntü yerleştirme nesnelerinin bir emici nesnesini temsil eder. Görüntü kullanımlarını arar ve {@code aracılığıyla arama sonuçlarına erişim sağlar."
type: docs
weight: 2340
url: /tr/java/com.aspose.pdf/imageplacementabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ImagePlacementAbsorber

```
public final class ImagePlacementAbsorber extends Object
```

<p> Görüntü yerleştirme nesnelerinin bir emici nesnesini temsil eder. Görüntü kullanımlarını arar ve {@code ImagePlacementAbsorber.ImagePlacements} koleksiyonu aracılığıyla arama sonuçlarına erişim sağlar. </p> <hr> <pre> Örnek, ilk PDF belge sayfasındaki görüntüleri bulmayı ve görüntü yerleştirme özelliklerini almayı gösterir. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Display image placement properties for all placements for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { System.out.println("image width:" + imagePlacement.getRectangle().getWidth()); System.out.println("image height:" + imagePlacement.getRectangle().getHeight()); System.out.println("image LLX:" + imagePlacement.getRectangle(0).getX()); System.out.println("image LLY:" + imagePlacement.getRectangle.getY()); System.out.println("image horizontal resolution:" + imagePlacement.getResolution().getX()); System.out.println("image vertical resolution:" + imagePlacement.getResolution().getY()); } </pre> <hr> <p> {@code ImagePlacementAbsorber} nesnesi temel olarak görüntü arama senaryolarında kullanılır. Arama tamamlandığında, oluşumlar {@code ImagePlacement} nesneleriyle temsil edilir ve bu nesneler {@code ImagePlacementAbsorber.ImagePlacements} koleksiyonunda bulunur. {@code ImagePlacement} nesnesi görüntü yerleştirme özelliklerine erişim sağlar: boyutlar, çözünürlük vb. </p> Görüntünün pozitif dönüşü saat yönünün tersidir, sayfa için ise saat yönündedir. Burada, görüntü dönüş açısını temsil etmemiz gerekir, bu yüzden sayfa açısını görüntü açısından çıkarırız.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ImagePlacementAbsorber](#ImagePlacementAbsorber--) | {@code ImagePlacementAbsorber} nesnesinin yeni bir örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getImagePlacements](#getImagePlacements--) | {@code ImagePlacement} nesneleriyle sunulan görüntü yerleştirme oluşumlarının koleksiyonunu alır. |
| [isReadOnlyMode](#isReadOnlyMode--) | Ayrıştırma işlemleri koleksiyonu için yalnızca okuma modunu alır/ayarlar. Bellek yetersizliği istisnalarına karşı yardımcı olabilir. |
| [setReadOnlyMode](#setReadOnlyMode-boolean-) | Ayrıştırma işlemleri koleksiyonu için yalnızca okuma modunu alır/ayarlar. Bellek yetersizliği istisnalarına karşı yardımcı olabilir. |
| [visit](#visit-com.aspose.pdf.IDocument-) | Belirtilen belgede arama gerçekleştirir. |
| [visit](#visit-com.aspose.pdf.Page-) | Belirtilen sayfada arama gerçekleştirir. |

### ImagePlacementAbsorber {#ImagePlacementAbsorber--}
```
public ImagePlacementAbsorber()
```

{@code ImagePlacementAbsorber} nesnesinin yeni bir örneğini başlatır.

### getImagePlacements {#getImagePlacements--}
```
public ImagePlacementCollection getImagePlacements()
```

{@code ImagePlacement} nesneleriyle sunulan görüntü yerleştirme oluşumlarının koleksiyonunu alır.

**Returns:**
ImagePlacementCollection nesnesi

### isReadOnlyMode {#isReadOnlyMode--}
```
public final boolean isReadOnlyMode()
```

Ayrıştırma işlemleri koleksiyonu için yalnızca okuma modunu alır/ayarlar. Bellek yetersizliği istisnalarına karşı yardımcı olabilir.

**Returns:**
boolean değer

### setReadOnlyMode {#setReadOnlyMode-boolean-}
```
public final void setReadOnlyMode(boolean value)
```

Ayrıştırma işlemleri koleksiyonu için yalnızca okuma modunu alır/ayarlar. Bellek yetersizliği istisnalarına karşı yardımcı olabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### visit {#visit-com.aspose.pdf.IDocument-}
Belirtilen belgede arama gerçekleştirir.

### visit {#visit-com.aspose.pdf.Page-}
Belirtilen sayfada arama gerçekleştirir.
