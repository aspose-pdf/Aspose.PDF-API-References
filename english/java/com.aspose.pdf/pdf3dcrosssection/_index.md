---
title: PDF3DCrossSection
second_title: Aspose.PDF for Java API Reference
description: Class PDF3DCrossSection.
type: docs
weight: 3590
url: /java/com.aspose.pdf/pdf3dcrosssection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PDF3DCrossSection

```
public class PDF3DCrossSection extends Object
```

Class PDF3DCrossSection.

## Constructors

| Constructor | Description |
| --- | --- |
| [PDF3DCrossSection](#PDF3DCrossSection-com.aspose.pdf.Document-) | Initializes a new instance of the {@code PDF3DCrossSection} class. |

## Methods

| Method | Description |
| --- | --- |
| [getCenter](#getCenter--) | Gets or sets the cross section rotation center. |
| [getCuttingPlaneColor](#getCuttingPlaneColor--) | Gets or sets the color of the cutting plane. |
| [getCuttingPlaneOpacity](#getCuttingPlaneOpacity--) | Gets or sets the cutting plane opacity. |
| [getCuttingPlaneOrientation](#getCuttingPlaneOrientation--) | Gets or sets the cutting plane orientation. |
| [getCuttingPlanesIntersectionColor](#getCuttingPlanesIntersectionColor--) | Gets or sets the color of the cutting planes intersection. |
| [getVisibility](#getVisibility--) | Gets or sets a value indicating visibility of the cutting planes intersection. |
| [setCenter](#setCenter-com.aspose.pdf.Point3D-) | Gets or sets the cross section rotation center. |
| [setCuttingPlaneColor](#setCuttingPlaneColor-com.aspose.pdf.Color-) | Gets or sets the color of the cutting plane. |
| [setCuttingPlaneOpacity](#setCuttingPlaneOpacity-double-) | Gets or sets the cutting plane opacity. |
| [setCuttingPlaneOrientation](#setCuttingPlaneOrientation-com.aspose.pdf.PDF3DCuttingPlaneOrientation-) | Gets or sets the cutting plane orientation. |
| [setCuttingPlanesIntersectionColor](#setCuttingPlanesIntersectionColor-com.aspose.pdf.Color-) | Gets or sets the color of the cutting planes intersection. |
| [setVisibility](#setVisibility-boolean-) | Gets or sets a value indicating visibility of the cutting planes intersection. |

### PDF3DCrossSection {#PDF3DCrossSection-com.aspose.pdf.Document-}
Initializes a new instance of the {@code PDF3DCrossSection} class.

### getCenter {#getCenter--}
```
public Point3D getCenter()
```

Gets or sets the cross section rotation center.

**Returns:**
Point3D object: The center.

### getCuttingPlaneColor {#getCuttingPlaneColor--}
```
public Color getCuttingPlaneColor()
```

Gets or sets the color of the cutting plane.

**Returns:**
com.aspose.pdf.Color object: The color of the cutting plane.

### getCuttingPlaneOpacity {#getCuttingPlaneOpacity--}
```
public double getCuttingPlaneOpacity()
```

Gets or sets the cutting plane opacity.

**Returns:**
double value: The cutting plane opacity. @throws Exception The number must be in the range [0 , 1]

### getCuttingPlaneOrientation {#getCuttingPlaneOrientation--}
```
public PDF3DCuttingPlaneOrientation getCuttingPlaneOrientation()
```

Gets or sets the cutting plane orientation.

**Returns:**
PDF3DCuttingPlaneOrientation object: The cutting plane orientation. @throws Exception Only one of the values shall be Null

### getCuttingPlanesIntersectionColor {#getCuttingPlanesIntersectionColor--}
```
public Color getCuttingPlanesIntersectionColor()
```

Gets or sets the color of the cutting planes intersection.

**Returns:**
com.aspose.pdf.Color object: The color of the cutting planes intersection.

### getVisibility {#getVisibility--}
```
public boolean getVisibility()
```

Gets or sets a value indicating visibility of the cutting planes intersection.

**Returns:**
: {@code true} if visible; otherwise, {@code false}.

### setCenter {#setCenter-com.aspose.pdf.Point3D-}
Gets or sets the cross section rotation center.

### setCuttingPlaneColor {#setCuttingPlaneColor-com.aspose.pdf.Color-}
Gets or sets the color of the cutting plane.

### setCuttingPlaneOpacity {#setCuttingPlaneOpacity-double-}
```
public void setCuttingPlaneOpacity(double value)
```

Gets or sets the cutting plane opacity.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value: The cutting plane opacity. @throws Exception The number must be in the range [0 , 1] |

### setCuttingPlaneOrientation {#setCuttingPlaneOrientation-com.aspose.pdf.PDF3DCuttingPlaneOrientation-}
Gets or sets the cutting plane orientation.

### setCuttingPlanesIntersectionColor {#setCuttingPlanesIntersectionColor-com.aspose.pdf.Color-}
Gets or sets the color of the cutting planes intersection.

### setVisibility {#setVisibility-boolean-}
```
public void setVisibility(boolean value)
```

Gets or sets a value indicating visibility of the cutting planes intersection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | : {@code true} if visible; otherwise, {@code false}. |
