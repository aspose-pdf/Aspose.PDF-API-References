---
title: "ImagePlacement"
linktitle: "ImagePlacement"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "<p> يمثل خصائص صورة موضوعة في صفحة مستند Pdf. </p> <hr> <pre> يوضح المثال كيفية العثور على الصور في الصفحة الأولى من مستند PDF والحصول على الصور كصور نقطية بأبعاد مرئية. // Open document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Retrieve images with visible dimensions for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { BufferedImage scaledImage; ByteArrayOutputStream imageStream = new ByteArrayOutputStream()) // Retrieve image from resources imagePlacement.getImage().save(imageStream, ImageFormatInternal.Png); BufferedImage resourceImage = (BufferedImage) ImageIO.read(imageStream); // Create new bitmap with actual dimensions scaledImage = new BufferedImage(resourceImage, (int)imagePlacement.getRectangle().getWidth(), (int)imagePlacement.getRectangle().getHeight()); } </pre> <hr> <p> عندما يتم وضع صورة في صفحة قد تكون أبعادها مختلفة عن الأبعاد الفعلية المحددة في {@code Resources}. الكائن {@code ImagePlacement} يهدف إلى توفير مثل هذه المعلومات مثل الأبعاد، الدقة وما إلى ذلك. </p>"
type: docs
weight: 2330
url: /ar/java/com.aspose.pdf/imageplacement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ImagePlacement

```
public final class ImagePlacement extends Object
```

<p> يمثل خصائص صورة موضوعة في صفحة مستند Pdf. </p> <hr> <pre> يوضح المثال كيفية العثور على الصور في الصفحة الأولى من مستند PDF والحصول على الصور كصور نقطية بأبعاد مرئية. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Retrieve images with visible dimensions for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { BufferedImage scaledImage; ByteArrayOutputStream imageStream = new ByteArrayOutputStream()) // Retrieve image from resources imagePlacement.getImage().save(imageStream, ImageFormatInternal.Png); BufferedImage resourceImage = (BufferedImage) ImageIO.read(imageStream); // Create new bitmap with actual dimensions scaledImage = new BufferedImage(resourceImage, (int)imagePlacement.getRectangle().getWidth(), (int)imagePlacement.getRectangle().getHeight()); } </pre> <hr> <p> عندما يتم وضع صورة في صفحة قد تكون أبعادها مختلفة عن الأبعاد الفعلية المحددة في {@code Resources}. الكائن {@code ImagePlacement} يهدف إلى توفير مثل هذه المعلومات مثل الأبعاد، الدقة وما إلى ذلك. </p>

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCompositingParameters](#getCompositingParameters--) | يحصل على معلمات التركيب لحالة الرسومات النشطة للصورة الموضوعة في الصفحة. |
| [getImage](#getImage--) | يحصل على كائن مورد XImage المتعلق. |
| [getMatrix](#getMatrix--) | مصفوفة التحويل الحالية لهذه الصورة. |
| [getOperator](#getOperator--) | المعامل المستخدم لعرض الصورة. |
| [getPage](#getPage--) | يحصل على الصفحة التي تحتوي على الصورة. |
| [getRectangle](#getRectangle--) | يحصل على مستطيل الصورة. |
| [getResolution](#getResolution--) | يحصل على دقة الصورة. |
| [getRotation](#getRotation--) | يحصل على زاوية دوران الصورة. |
| [hide](#hide--) | حذف الصورة من الصفحة. |
| [replace](#replace-java.io.InputStream-) | استبدال الصورة في المجموعة بصورة أخرى. |
| [save](#save-java.io.OutputStream-) | يحفظ الصورة مع التحويلات المقابلة: التحجيم، الدوران والدقة. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.ImageType-) | يحفظ الصورة مع التحويلات المقابلة: التحجيم، الدوران والدقة. |

### getCompositingParameters {#getCompositingParameters--}
```
public CompositingParameters getCompositingParameters()
```

يحصل على معلمات التركيب لحالة الرسومات النشطة للصورة الموضوعة في الصفحة.

**Returns:**
كائن CompositingParameters

### getImage {#getImage--}
```
public XImage getImage()
```

يحصل على كائن مورد XImage المتعلق.

**Returns:**
كائن XImage

### getMatrix {#getMatrix--}
```
public Matrix getMatrix()
```

مصفوفة التحويل الحالية لهذه الصورة.

**Returns:**
كائن Matrix

### getOperator {#getOperator--}
```
public final Operator getOperator()
```

المعامل المستخدم لعرض الصورة.

**Returns:**
مثيل Operator

### getPage {#getPage--}
```
public Page getPage()
```

يحصل على الصفحة التي تحتوي على الصورة.

**Returns:**
كائن Page

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

يحصل على مستطيل الصورة.

**Returns:**
كائن Rectangle

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

يحصل على دقة الصورة.

**Returns:**
كائن Resolution

### getRotation {#getRotation--}
```
public float getRotation()
```

يحصل على زاوية دوران الصورة.

**Returns:**
قيمة int

### hide {#hide--}
```
public final void hide()
```

حذف الصورة من الصفحة.

### replace {#replace-java.io.InputStream-}
استبدال الصورة في المجموعة بصورة أخرى.

### save {#save-java.io.OutputStream-}
يحفظ الصورة مع التحويلات المقابلة: التحجيم، الدوران والدقة.

### save {#save-java.io.OutputStream-com.aspose.pdf.ImageType-}
يحفظ الصورة مع التحويلات المقابلة: التحجيم، الدوران والدقة.
