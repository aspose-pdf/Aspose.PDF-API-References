---
title: "PDF3DCrossSection"
linktitle: "PDF3DCrossSection"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe PDF3DCrossSection."
type: docs
weight: 3590
url: /fr/java/com.aspose.pdf/pdf3dcrosssection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PDF3DCrossSection

```
public class PDF3DCrossSection extends Object
```

Classe PDF3DCrossSection.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PDF3DCrossSection](#PDF3DCrossSection-com.aspose.pdf.Document-) | Initialise une nouvelle instance de la classe {@code PDF3DCrossSection}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getCenter](#getCenter--) | Obtient ou définit le centre de rotation de la section transversale. |
| [getCuttingPlaneColor](#getCuttingPlaneColor--) | Obtient ou définit la couleur du plan de coupe. |
| [getCuttingPlaneOpacity](#getCuttingPlaneOpacity--) | Obtient ou définit l'opacité du plan de coupe. |
| [getCuttingPlaneOrientation](#getCuttingPlaneOrientation--) | Obtient ou définit l'orientation du plan de coupe. |
| [getCuttingPlanesIntersectionColor](#getCuttingPlanesIntersectionColor--) | Obtient ou définit la couleur de l'intersection des plans de coupe. |
| [getVisibility](#getVisibility--) | Obtient ou définit une valeur indiquant la visibilité de l'intersection des plans de coupe. |
| [setCenter](#setCenter-com.aspose.pdf.Point3D-) | Obtient ou définit le centre de rotation de la section transversale. |
| [setCuttingPlaneColor](#setCuttingPlaneColor-com.aspose.pdf.Color-) | Obtient ou définit la couleur du plan de coupe. |
| [setCuttingPlaneOpacity](#setCuttingPlaneOpacity-double-) | Obtient ou définit l'opacité du plan de coupe. |
| [setCuttingPlaneOrientation](#setCuttingPlaneOrientation-com.aspose.pdf.PDF3DCuttingPlaneOrientation-) | Obtient ou définit l'orientation du plan de coupe. |
| [setCuttingPlanesIntersectionColor](#setCuttingPlanesIntersectionColor-com.aspose.pdf.Color-) | Obtient ou définit la couleur de l'intersection des plans de coupe. |
| [setVisibility](#setVisibility-boolean-) | Obtient ou définit une valeur indiquant la visibilité de l'intersection des plans de coupe. |

### PDF3DCrossSection {#PDF3DCrossSection-com.aspose.pdf.Document-}
Initialise une nouvelle instance de la classe {@code PDF3DCrossSection}.

### getCenter {#getCenter--}
```
public Point3D getCenter()
```

Obtient ou définit le centre de rotation de la section transversale.

**Returns:**
Objet Point3D : le centre.

### getCuttingPlaneColor {#getCuttingPlaneColor--}
```
public Color getCuttingPlaneColor()
```

Obtient ou définit la couleur du plan de coupe.

**Returns:**
Objet com.aspose.pdf.Color : la couleur du plan de coupe.

### getCuttingPlaneOpacity {#getCuttingPlaneOpacity--}
```
public double getCuttingPlaneOpacity()
```

Obtient ou définit l'opacité du plan de coupe.

**Returns:**
double value: L'opacité du plan de coupe. @throws Exception Le nombre doit être dans la plage [0 , 1]

### getCuttingPlaneOrientation {#getCuttingPlaneOrientation--}
```
public PDF3DCuttingPlaneOrientation getCuttingPlaneOrientation()
```

Obtient ou définit l'orientation du plan de coupe.

**Returns:**
PDF3DCuttingPlaneOrientation object: L'orientation du plan de coupe. @throws Exception Une seule des valeurs doit être Null

### getCuttingPlanesIntersectionColor {#getCuttingPlanesIntersectionColor--}
```
public Color getCuttingPlanesIntersectionColor()
```

Obtient ou définit la couleur de l'intersection des plans de coupe.

**Returns:**
com.aspose.pdf.Color object: La couleur de l'intersection des plans de coupe.

### getVisibility {#getVisibility--}
```
public boolean getVisibility()
```

Obtient ou définit une valeur indiquant la visibilité de l'intersection des plans de coupe.

**Returns:**
: {@code true} si visible ; sinon, {@code false}.

### setCenter {#setCenter-com.aspose.pdf.Point3D-}
Obtient ou définit le centre de rotation de la section transversale.

### setCuttingPlaneColor {#setCuttingPlaneColor-com.aspose.pdf.Color-}
Obtient ou définit la couleur du plan de coupe.

### setCuttingPlaneOpacity {#setCuttingPlaneOpacity-double-}
```
public void setCuttingPlaneOpacity(double value)
```

Obtient ou définit l'opacité du plan de coupe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | double value: L'opacité du plan de coupe. @throws Exception Le nombre doit être dans la plage [0 , 1] |

### setCuttingPlaneOrientation {#setCuttingPlaneOrientation-com.aspose.pdf.PDF3DCuttingPlaneOrientation-}
Obtient ou définit l'orientation du plan de coupe.

### setCuttingPlanesIntersectionColor {#setCuttingPlanesIntersectionColor-com.aspose.pdf.Color-}
Obtient ou définit la couleur de l'intersection des plans de coupe.

### setVisibility {#setVisibility-boolean-}
```
public void setVisibility(boolean value)
```

Obtient ou définit une valeur indiquant la visibilité de l'intersection des plans de coupe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | : {@code true} si visible ; sinon, {@code false}. |
