---
title: "PDF3DCrossSection"
linktitle: "PDF3DCrossSection"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse PDF3DCrossSection."
type: docs
weight: 3590
url: /de/java/com.aspose.pdf/pdf3dcrosssection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PDF3DCrossSection

```
public class PDF3DCrossSection extends Object
```

Klasse PDF3DCrossSection.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PDF3DCrossSection](#PDF3DCrossSection-com.aspose.pdf.Document-) | Initialisiert eine neue Instanz der {@code PDF3DCrossSection} Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCenter](#getCenter--) | Erhält oder setzt das Rotationszentrum des Querschnitts. |
| [getCuttingPlaneColor](#getCuttingPlaneColor--) | Erhält oder setzt die Farbe der Schnittfläche. |
| [getCuttingPlaneOpacity](#getCuttingPlaneOpacity--) | Erhält oder setzt die Deckkraft der Schnittfläche. |
| [getCuttingPlaneOrientation](#getCuttingPlaneOrientation--) | Erhält oder setzt die Orientierung der Schnittfläche. |
| [getCuttingPlanesIntersectionColor](#getCuttingPlanesIntersectionColor--) | Erhält oder setzt die Farbe des Schnittpunkts der Schnittflächen. |
| [getVisibility](#getVisibility--) | Erhält oder setzt einen Wert, der die Sichtbarkeit des Schnittpunkts der Schnittflächen angibt. |
| [setCenter](#setCenter-com.aspose.pdf.Point3D-) | Erhält oder setzt das Rotationszentrum des Querschnitts. |
| [setCuttingPlaneColor](#setCuttingPlaneColor-com.aspose.pdf.Color-) | Erhält oder setzt die Farbe der Schnittfläche. |
| [setCuttingPlaneOpacity](#setCuttingPlaneOpacity-double-) | Erhält oder setzt die Deckkraft der Schnittfläche. |
| [setCuttingPlaneOrientation](#setCuttingPlaneOrientation-com.aspose.pdf.PDF3DCuttingPlaneOrientation-) | Erhält oder setzt die Orientierung der Schnittfläche. |
| [setCuttingPlanesIntersectionColor](#setCuttingPlanesIntersectionColor-com.aspose.pdf.Color-) | Erhält oder setzt die Farbe des Schnittpunkts der Schnittflächen. |
| [setVisibility](#setVisibility-boolean-) | Erhält oder setzt einen Wert, der die Sichtbarkeit des Schnittpunkts der Schnittflächen angibt. |

### PDF3DCrossSection {#PDF3DCrossSection-com.aspose.pdf.Document-}
Initialisiert eine neue Instanz der {@code PDF3DCrossSection} Klasse.

### getCenter {#getCenter--}
```
public Point3D getCenter()
```

Erhält oder setzt das Rotationszentrum des Querschnitts.

**Returns:**
Point3D-Objekt: Das Zentrum.

### getCuttingPlaneColor {#getCuttingPlaneColor--}
```
public Color getCuttingPlaneColor()
```

Erhält oder setzt die Farbe der Schnittfläche.

**Returns:**
com.aspose.pdf.Color-Objekt: Die Farbe der Schneidebene.

### getCuttingPlaneOpacity {#getCuttingPlaneOpacity--}
```
public double getCuttingPlaneOpacity()
```

Erhält oder setzt die Deckkraft der Schnittfläche.

**Returns:**
double value: Die Deckkraft der Schneidebene. @throws Exception Die Zahl muss im Bereich [0 , 1] liegen.

### getCuttingPlaneOrientation {#getCuttingPlaneOrientation--}
```
public PDF3DCuttingPlaneOrientation getCuttingPlaneOrientation()
```

Erhält oder setzt die Orientierung der Schnittfläche.

**Returns:**
PDF3DCuttingPlaneOrientation-Objekt: Die Orientierung der Schneidebene. @throws Exception Nur einer der Werte darf Null sein.

### getCuttingPlanesIntersectionColor {#getCuttingPlanesIntersectionColor--}
```
public Color getCuttingPlanesIntersectionColor()
```

Erhält oder setzt die Farbe des Schnittpunkts der Schnittflächen.

**Returns:**
com.aspose.pdf.Color-Objekt: Die Farbe des Schnittpunkts der Schneideebenen.

### getVisibility {#getVisibility--}
```
public boolean getVisibility()
```

Erhält oder setzt einen Wert, der die Sichtbarkeit des Schnittpunkts der Schnittflächen angibt.

**Returns:**
: {@code true} wenn sichtbar; andernfalls {@code false}.

### setCenter {#setCenter-com.aspose.pdf.Point3D-}
Erhält oder setzt das Rotationszentrum des Querschnitts.

### setCuttingPlaneColor {#setCuttingPlaneColor-com.aspose.pdf.Color-}
Erhält oder setzt die Farbe der Schnittfläche.

### setCuttingPlaneOpacity {#setCuttingPlaneOpacity-double-}
```
public void setCuttingPlaneOpacity(double value)
```

Erhält oder setzt die Deckkraft der Schnittfläche.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double value: Die Deckkraft der Schneidebene. @throws Exception Die Zahl muss im Bereich [0 , 1] liegen. |

### setCuttingPlaneOrientation {#setCuttingPlaneOrientation-com.aspose.pdf.PDF3DCuttingPlaneOrientation-}
Erhält oder setzt die Orientierung der Schnittfläche.

### setCuttingPlanesIntersectionColor {#setCuttingPlanesIntersectionColor-com.aspose.pdf.Color-}
Erhält oder setzt die Farbe des Schnittpunkts der Schnittflächen.

### setVisibility {#setVisibility-boolean-}
```
public void setVisibility(boolean value)
```

Erhält oder setzt einen Wert, der die Sichtbarkeit des Schnittpunkts der Schnittflächen angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | : {@code true} wenn sichtbar; andernfalls {@code false}. |
