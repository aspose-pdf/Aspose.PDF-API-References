---
title: "ImagePlacement"
linktitle: "ImagePlacement"
second_title: "Aspose.PDF for Java API Referansı"
description: "<p> PDF belge sayfasına yerleştirilen bir görüntünün özelliklerini temsil eder. </p> <hr> <pre> The example demonstrates how to find images on the first PDF document page and get images as bitmaps with visible dimensions. // Open document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Retrieve images with visible dimensions for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { BufferedImage scaledImage; ByteArrayOutputStream imageStream = new ByteArrayOutputStream()) // Retrieve image from resources imagePlacement.getImage().save(imageStream, ImageFormatInternal.Png); BufferedImage resourceImage = (BufferedImage) ImageIO.read(imageStream); // Create new bitmap with actual dimensions scaledImage = new BufferedImage(resourceImage, (int)imagePlacement.getRectangle().getWidth(), (int)imagePlacement.getRectangle().getHeight()); } </pre> <hr> <p> Bir görüntü bir sayfaya yerleştirildiğinde, {@code Resources} içinde tanımlanan fiziksel boyutlardan farklı boyutlara sahip olabilir. {@code ImagePlacement} nesnesi, boyutlar, çözünürlük vb. gibi bilgileri sağlamak için tasarlanmıştır. </p>"
type: docs
weight: 2330
url: /tr/java/com.aspose.pdf/imageplacement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ImagePlacement

```
public final class ImagePlacement extends Object
```

<p> PDF belge sayfasına yerleştirilen bir görüntünün özelliklerini temsil eder. </p> <hr> <pre> The example demonstrates how to find images on the first PDF document page and get images as bitmaps with visible dimensions. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Retrieve images with visible dimensions for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { BufferedImage scaledImage; ByteArrayOutputStream imageStream = new ByteArrayOutputStream()) // Retrieve image from resources imagePlacement.getImage().save(imageStream, ImageFormatInternal.Png); BufferedImage resourceImage = (BufferedImage) ImageIO.read(imageStream); // Create new bitmap with actual dimensions scaledImage = new BufferedImage(resourceImage, (int)imagePlacement.getRectangle().getWidth(), (int)imagePlacement.getRectangle().getHeight()); } </pre> <hr> <p> Bir görüntü bir sayfaya yerleştirildiğinde, {@code Resources} içinde tanımlanan fiziksel boyutlardan farklı boyutlara sahip olabilir. {@code ImagePlacement} nesnesi, boyutlar, çözünürlük vb. gibi bilgileri sağlamak için tasarlanmıştır. </p>

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCompositingParameters](#getCompositingParameters--) | Sayfaya yerleştirilen görüntü için etkin olan grafik durumunun birleştirme parametrelerini alır. |
| [getImage](#getImage--) | İlgili XImage kaynak nesnesini alır. |
| [getMatrix](#getMatrix--) | Bu görüntü için geçerli dönüşüm matrisini alır. |
| [getOperator](#getOperator--) | Görüntüyü görüntülemek için kullanılan operatörü alır. |
| [getPage](#getPage--) | Görüntüyü içeren sayfayı alır. |
| [getRectangle](#getRectangle--) | Görüntünün dikdörtgenini alır. |
| [getResolution](#getResolution--) | Görüntünün çözünürlüğünü alır. |
| [getRotation](#getRotation--) | Görüntünün döndürme açısını alır. |
| [hide](#hide--) | Görüntüyü sayfadan sil. |
| [replace](#replace-java.io.InputStream-) | Koleksiyondaki görüntüyü başka bir görüntüyle değiştir. |
| [save](#save-java.io.OutputStream-) | Görüntüyü ilgili dönüşümlerle kaydeder: ölçekleme, döndürme ve çözünürlük. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.ImageType-) | Görüntüyü ilgili dönüşümlerle kaydeder: ölçekleme, döndürme ve çözünürlük. |

### getCompositingParameters {#getCompositingParameters--}
```
public CompositingParameters getCompositingParameters()
```

Sayfaya yerleştirilen görüntü için etkin olan grafik durumunun birleştirme parametrelerini alır.

**Returns:**
CompositingParameters nesnesi

### getImage {#getImage--}
```
public XImage getImage()
```

İlgili XImage kaynak nesnesini alır.

**Returns:**
XImage nesnesi

### getMatrix {#getMatrix--}
```
public Matrix getMatrix()
```

Bu görüntü için geçerli dönüşüm matrisini alır.

**Returns:**
Matrix nesnesi

### getOperator {#getOperator--}
```
public final Operator getOperator()
```

Görüntüyü görüntülemek için kullanılan operatörü alır.

**Returns:**
Operator örneği

### getPage {#getPage--}
```
public Page getPage()
```

Görüntüyü içeren sayfayı alır.

**Returns:**
Page nesnesi

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Görüntünün dikdörtgenini alır.

**Returns:**
Rectangle nesnesi

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

Görüntünün çözünürlüğünü alır.

**Returns:**
Resolution nesnesi

### getRotation {#getRotation--}
```
public float getRotation()
```

Görüntünün döndürme açısını alır.

**Returns:**
int değer

### hide {#hide--}
```
public final void hide()
```

Görüntüyü sayfadan sil.

### replace {#replace-java.io.InputStream-}
Koleksiyondaki görüntüyü başka bir görüntüyle değiştir.

### save {#save-java.io.OutputStream-}
Görüntüyü ilgili dönüşümlerle kaydeder: ölçekleme, döndürme ve çözünürlük.

### save {#save-java.io.OutputStream-com.aspose.pdf.ImageType-}
Görüntüyü ilgili dönüşümlerle kaydeder: ölçekleme, döndürme ve çözünürlük.
