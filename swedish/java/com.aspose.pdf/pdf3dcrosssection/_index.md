---
title: "PDF3DCrossSection"
linktitle: "PDF3DCrossSection"
second_title: "Aspose.PDF för Java API-referens"
description: "Klassen PDF3DCrossSection."
type: docs
weight: 3590
url: /sv/java/com.aspose.pdf/pdf3dcrosssection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PDF3DCrossSection

```
public class PDF3DCrossSection extends Object
```

Klassen PDF3DCrossSection.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PDF3DCrossSection](#PDF3DCrossSection-com.aspose.pdf.Document-) | Initierar en ny instans av {@code PDF3DCrossSection} klassen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCenter](#getCenter--) | Hämtar eller anger rotationscentrum för tvärsnittet. |
| [getCuttingPlaneColor](#getCuttingPlaneColor--) | Hämtar eller anger färgen på skärplanet. |
| [getCuttingPlaneOpacity](#getCuttingPlaneOpacity--) | Hämtar eller anger opaciteten för skärplanet. |
| [getCuttingPlaneOrientation](#getCuttingPlaneOrientation--) | Hämtar eller anger orienteringen för skärplanet. |
| [getCuttingPlanesIntersectionColor](#getCuttingPlanesIntersectionColor--) | Hämtar eller anger färgen på skärplanens skärningspunkt. |
| [getVisibility](#getVisibility--) | Hämtar eller anger ett värde som indikerar synligheten för skärplanens skärningspunkt. |
| [setCenter](#setCenter-com.aspose.pdf.Point3D-) | Hämtar eller anger rotationscentrum för tvärsnittet. |
| [setCuttingPlaneColor](#setCuttingPlaneColor-com.aspose.pdf.Color-) | Hämtar eller anger färgen på skärplanet. |
| [setCuttingPlaneOpacity](#setCuttingPlaneOpacity-double-) | Hämtar eller anger opaciteten för skärplanet. |
| [setCuttingPlaneOrientation](#setCuttingPlaneOrientation-com.aspose.pdf.PDF3DCuttingPlaneOrientation-) | Hämtar eller anger orienteringen för skärplanet. |
| [setCuttingPlanesIntersectionColor](#setCuttingPlanesIntersectionColor-com.aspose.pdf.Color-) | Hämtar eller anger färgen på skärplanens skärningspunkt. |
| [setVisibility](#setVisibility-boolean-) | Hämtar eller anger ett värde som indikerar synligheten för skärplanens skärningspunkt. |

### PDF3DCrossSection {#PDF3DCrossSection-com.aspose.pdf.Document-}
Initierar en ny instans av {@code PDF3DCrossSection} klassen.

### getCenter {#getCenter--}
```
public Point3D getCenter()
```

Hämtar eller anger rotationscentrum för tvärsnittet.

**Returns:**
Point3D objekt: Centrum.

### getCuttingPlaneColor {#getCuttingPlaneColor--}
```
public Color getCuttingPlaneColor()
```

Hämtar eller anger färgen på skärplanet.

**Returns:**
com.aspose.pdf.Color objekt: Färgen på skärningsplanet.

### getCuttingPlaneOpacity {#getCuttingPlaneOpacity--}
```
public double getCuttingPlaneOpacity()
```

Hämtar eller anger opaciteten för skärplanet.

**Returns:**
double värde: Skärningsplanets opacitet. @throws Exception Numret måste vara i intervallet [0 , 1]

### getCuttingPlaneOrientation {#getCuttingPlaneOrientation--}
```
public PDF3DCuttingPlaneOrientation getCuttingPlaneOrientation()
```

Hämtar eller anger orienteringen för skärplanet.

**Returns:**
PDF3DCuttingPlaneOrientation objekt: Skärningsplanets orientering. @throws Exception Endast ett av värdena får vara Null

### getCuttingPlanesIntersectionColor {#getCuttingPlanesIntersectionColor--}
```
public Color getCuttingPlanesIntersectionColor()
```

Hämtar eller anger färgen på skärplanens skärningspunkt.

**Returns:**
com.aspose.pdf.Color objekt: Färgen på skärningsplanens skärningspunkt.

### getVisibility {#getVisibility--}
```
public boolean getVisibility()
```

Hämtar eller anger ett värde som indikerar synligheten för skärplanens skärningspunkt.

**Returns:**
: {@code true} om synlig; annars, {@code false}.

### setCenter {#setCenter-com.aspose.pdf.Point3D-}
Hämtar eller anger rotationscentrum för tvärsnittet.

### setCuttingPlaneColor {#setCuttingPlaneColor-com.aspose.pdf.Color-}
Hämtar eller anger färgen på skärplanet.

### setCuttingPlaneOpacity {#setCuttingPlaneOpacity-double-}
```
public void setCuttingPlaneOpacity(double value)
```

Hämtar eller anger opaciteten för skärplanet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double värde: Skärningsplanets opacitet. @throws Exception Numret måste vara i intervallet [0 , 1] |

### setCuttingPlaneOrientation {#setCuttingPlaneOrientation-com.aspose.pdf.PDF3DCuttingPlaneOrientation-}
Hämtar eller anger orienteringen för skärplanet.

### setCuttingPlanesIntersectionColor {#setCuttingPlanesIntersectionColor-com.aspose.pdf.Color-}
Hämtar eller anger färgen på skärplanens skärningspunkt.

### setVisibility {#setVisibility-boolean-}
```
public void setVisibility(boolean value)
```

Hämtar eller anger ett värde som indikerar synligheten för skärplanens skärningspunkt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | : {@code true} om synlig; annars, {@code false}. |
