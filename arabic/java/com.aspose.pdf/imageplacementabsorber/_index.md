---
title: "ImagePlacementAbsorber"
linktitle: "ImagePlacementAbsorber"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "<p> يمثل كائن ماص لكائنات وضع الصورة. يقوم بالبحث عن استخدامات الصور ويوفر الوصول إلى نتائج البحث عبر {@code."
type: docs
weight: 2340
url: /ar/java/com.aspose.pdf/imageplacementabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ImagePlacementAbsorber

```
public final class ImagePlacementAbsorber extends Object
```

<p> يمثل كائن ماص لكائنات وضع الصورة. يقوم بالبحث عن استخدامات الصور ويوفر الوصول إلى نتائج البحث عبر مجموعة {@code ImagePlacementAbsorber.ImagePlacements}. </p> <hr> <pre> يوضح المثال كيفية العثور على الصور في الصفحة الأولى من مستند PDF والحصول على خصائص وضع الصورة. // Open document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Display image placement properties for all placements for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { System.out.println(\"image width:\" + imagePlacement.getRectangle().getWidth()); System.out.println(\"image height:\" + imagePlacement.getRectangle().getHeight()); System.out.println(\"image LLX:\" + imagePlacement.getRectangle(0).getX()); System.out.println(\"image LLY:\" + imagePlacement.getRectangle.getY()); System.out.println(\"image horizontal resolution:\" + imagePlacement.getResolution().getX()); System.out.println(\"image vertical resolution:\" + imagePlacement.getResolution().getY()); } </pre> <hr> <p> يُستخدم كائن {@code ImagePlacementAbsorber} أساسًا في سيناريو البحث عن الصور. عند اكتمال البحث تُمثَّل الوقائع بكائنات {@code ImagePlacement} التي يحتويها مجموعة {@code ImagePlacementAbsorber.ImagePlacements}. يوفر كائن {@code ImagePlacement} الوصول إلى خصائص وضع الصورة: الأبعاد، الدقة، إلخ. </p> دوران الصورة الإيجابي يكون عكس اتجاه عقارب الساعة، بالنسبة للصفحة يكون مع اتجاه عقارب الساعة. هنا، نحتاج إلى تمثيل زاوية دوران الصورة، لذا نطرح زاوية الصفحة من زاوية الصورة.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ImagePlacementAbsorber](#ImagePlacementAbsorber--) | يُهيئ نسخة جديدة من كائن {@code ImagePlacementAbsorber}. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getImagePlacements](#getImagePlacements--) | يحصل على مجموعة من حالات وضع الصورة التي تُقدَّم بكائنات {@code ImagePlacement}. |
| [isReadOnlyMode](#isReadOnlyMode--) | يحصل/يضبط وضع القراءة فقط لمجموعة عمليات التحليل. قد يساعد ذلك في تجنب استثناءات نفاد الذاكرة. |
| [setReadOnlyMode](#setReadOnlyMode-boolean-) | يحصل/يضبط وضع القراءة فقط لمجموعة عمليات التحليل. قد يساعد ذلك في تجنب استثناءات نفاد الذاكرة. |
| [visit](#visit-com.aspose.pdf.IDocument-) | ينفّذ البحث على المستند المحدد. |
| [visit](#visit-com.aspose.pdf.Page-) | ينفذ البحث على الصفحة المحددة. |

### ImagePlacementAbsorber {#ImagePlacementAbsorber--}
```
public ImagePlacementAbsorber()
```

يُهيئ نسخة جديدة من كائن {@code ImagePlacementAbsorber}.

### getImagePlacements {#getImagePlacements--}
```
public ImagePlacementCollection getImagePlacements()
```

يحصل على مجموعة من حالات وضع الصورة التي تُقدَّم بكائنات {@code ImagePlacement}.

**Returns:**
كائن ImagePlacementCollection

### isReadOnlyMode {#isReadOnlyMode--}
```
public final boolean isReadOnlyMode()
```

يحصل/يضبط وضع القراءة فقط لمجموعة عمليات التحليل. قد يساعد ذلك في تجنب استثناءات نفاد الذاكرة.

**Returns:**
قيمة منطقية

### setReadOnlyMode {#setReadOnlyMode-boolean-}
```
public final void setReadOnlyMode(boolean value)
```

يحصل/يضبط وضع القراءة فقط لمجموعة عمليات التحليل. قد يساعد ذلك في تجنب استثناءات نفاد الذاكرة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### visit {#visit-com.aspose.pdf.IDocument-}
ينفّذ البحث على المستند المحدد.

### visit {#visit-com.aspose.pdf.Page-}
ينفذ البحث على الصفحة المحددة.
