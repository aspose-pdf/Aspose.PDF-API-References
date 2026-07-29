---
title: "PDF3DCrossSection"
linktitle: "PDF3DCrossSection"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة PDF3DCrossSection."
type: docs
weight: 3590
url: /ar/java/com.aspose.pdf/pdf3dcrosssection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PDF3DCrossSection

```
public class PDF3DCrossSection extends Object
```

فئة PDF3DCrossSection.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PDF3DCrossSection](#PDF3DCrossSection-com.aspose.pdf.Document-) | يُنشئ مثيلًا جديدًا للفئة {@code PDF3DCrossSection} class. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCenter](#getCenter--) | يحصل أو يضبط مركز دوران المقطع العرضي. |
| [getCuttingPlaneColor](#getCuttingPlaneColor--) | يحصل أو يضبط لون سطح القطع. |
| [getCuttingPlaneOpacity](#getCuttingPlaneOpacity--) | يحصل أو يضبط شفافية سطح القطع. |
| [getCuttingPlaneOrientation](#getCuttingPlaneOrientation--) | يحصل أو يضبط اتجاه سطح القطع. |
| [getCuttingPlanesIntersectionColor](#getCuttingPlanesIntersectionColor--) | يحصل أو يضبط لون تقاطع أسطح القطع. |
| [getVisibility](#getVisibility--) | يحصل أو يضبط قيمة تشير إلى ظهور تقاطع أسطح القطع. |
| [setCenter](#setCenter-com.aspose.pdf.Point3D-) | يحصل أو يضبط مركز دوران المقطع العرضي. |
| [setCuttingPlaneColor](#setCuttingPlaneColor-com.aspose.pdf.Color-) | يحصل أو يضبط لون سطح القطع. |
| [setCuttingPlaneOpacity](#setCuttingPlaneOpacity-double-) | يحصل أو يضبط شفافية سطح القطع. |
| [setCuttingPlaneOrientation](#setCuttingPlaneOrientation-com.aspose.pdf.PDF3DCuttingPlaneOrientation-) | يحصل أو يضبط اتجاه سطح القطع. |
| [setCuttingPlanesIntersectionColor](#setCuttingPlanesIntersectionColor-com.aspose.pdf.Color-) | يحصل أو يضبط لون تقاطع أسطح القطع. |
| [setVisibility](#setVisibility-boolean-) | يحصل أو يضبط قيمة تشير إلى ظهور تقاطع أسطح القطع. |

### PDF3DCrossSection {#PDF3DCrossSection-com.aspose.pdf.Document-}
يُنشئ مثيلًا جديدًا للفئة {@code PDF3DCrossSection} class.

### getCenter {#getCenter--}
```
public Point3D getCenter()
```

يحصل أو يضبط مركز دوران المقطع العرضي.

**Returns:**
كائن Point3D: المركز.

### getCuttingPlaneColor {#getCuttingPlaneColor--}
```
public Color getCuttingPlaneColor()
```

يحصل أو يضبط لون سطح القطع.

**Returns:**
كائن com.aspose.pdf.Color: لون سطح القطع.

### getCuttingPlaneOpacity {#getCuttingPlaneOpacity--}
```
public double getCuttingPlaneOpacity()
```

يحصل أو يضبط شفافية سطح القطع.

**Returns:**
قيمة مزدوجة: شفافية مستوى القطع. @throws Exception يجب أن يكون الرقم في النطاق [0 , 1]

### getCuttingPlaneOrientation {#getCuttingPlaneOrientation--}
```
public PDF3DCuttingPlaneOrientation getCuttingPlaneOrientation()
```

يحصل أو يضبط اتجاه سطح القطع.

**Returns:**
كائن PDF3DCuttingPlaneOrientation: اتجاه مستوى القطع. @throws Exception يجب أن تكون إحدى القيم فقط Null

### getCuttingPlanesIntersectionColor {#getCuttingPlanesIntersectionColor--}
```
public Color getCuttingPlanesIntersectionColor()
```

يحصل أو يضبط لون تقاطع أسطح القطع.

**Returns:**
كائن com.aspose.pdf.Color: لون تقاطع مستويات القطع.

### getVisibility {#getVisibility--}
```
public boolean getVisibility()
```

يحصل أو يضبط قيمة تشير إلى ظهور تقاطع أسطح القطع.

**Returns:**
: {@code true} إذا كان مرئياً؛ وإلا {@code false}.

### setCenter {#setCenter-com.aspose.pdf.Point3D-}
يحصل أو يضبط مركز دوران المقطع العرضي.

### setCuttingPlaneColor {#setCuttingPlaneColor-com.aspose.pdf.Color-}
يحصل أو يضبط لون سطح القطع.

### setCuttingPlaneOpacity {#setCuttingPlaneOpacity-double-}
```
public void setCuttingPlaneOpacity(double value)
```

يحصل أو يضبط شفافية سطح القطع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة مزدوجة: شفافية مستوى القطع. @throws Exception يجب أن يكون الرقم في النطاق [0 , 1] |

### setCuttingPlaneOrientation {#setCuttingPlaneOrientation-com.aspose.pdf.PDF3DCuttingPlaneOrientation-}
يحصل أو يضبط اتجاه سطح القطع.

### setCuttingPlanesIntersectionColor {#setCuttingPlanesIntersectionColor-com.aspose.pdf.Color-}
يحصل أو يضبط لون تقاطع أسطح القطع.

### setVisibility {#setVisibility-boolean-}
```
public void setVisibility(boolean value)
```

يحصل أو يضبط قيمة تشير إلى ظهور تقاطع أسطح القطع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | : {@code true} إذا كان مرئياً؛ وإلا {@code false}. |
