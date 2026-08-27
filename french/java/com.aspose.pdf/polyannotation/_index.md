---
title: "PolyAnnotation"
linktitle: "PolyAnnotation"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe de base abstraite pour les poly-annotations."
type: docs
weight: 3890
url: /fr/java/com.aspose.pdf/polyannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.PolyAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.PolyAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.PolyAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.PolyAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public abstract class PolyAnnotation extends MarkupAnnotation
```

Classe de base abstraite pour les poly-annotations.

## Méthodes

| Méthode | Description |
| --- | --- |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Met à jour les points dans Vertices, selon la transformation matricielle. |
| [getEndingStyle](#getEndingStyle--) | Obtient le style de la terminaison de la deuxième ligne. |
| [getIntent](#getIntent--) | Obtient l’intention de l’annotation de polygone ou de polyligne. |
| [getInteriorColor](#getInteriorColor--) | Obtient la couleur intérieure utilisée pour remplir les terminaisons de ligne de l’annotation. |
| [getMeasure](#getMeasure--) | Unités de mesure spécifiées pour cette annotation. |
| [getStartingStyle](#getStartingStyle--) | Obtient le style de la terminaison de la première ligne. |
| [getVertices](#getVertices--) | Obtient un tableau de points représentant les coordonnées horizontales et verticales de chaque sommet. |
| [setEndingStyle](#setEndingStyle-com.aspose.pdf.LineEnding-) | Définit le style de la terminaison de la deuxième ligne. |
| [setIntent](#setIntent-com.aspose.pdf.PolyIntent-) | Définit l’intention de l’annotation de polygone ou de polyligne. |
| [setInteriorColor](#setInteriorColor-com.aspose.pdf.Color-) | Définit la couleur intérieure utilisée pour remplir les terminaisons de ligne de l’annotation. |
| [setMeasure](#setMeasure-com.aspose.pdf.Measure-) | Unités de mesure spécifiées pour cette annotation. |
| [setStartingStyle](#setStartingStyle-com.aspose.pdf.LineEnding-) | Définit le style de la terminaison de la première ligne. |
| [setVertices](#setVertices-com.aspose.pdf.Point:A-) | Définit un tableau de points représentant les coordonnées horizontales et verticales de chaque sommet. |

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Met à jour les points dans Vertices, selon la transformation matricielle.

### getEndingStyle {#getEndingStyle--}
```
public LineEnding getEndingStyle()
```

Obtient le style de la terminaison de la deuxième ligne.

**Returns:**
Élément LineEnding @see LineEnding

### getIntent {#getIntent--}
```
public PolyIntent getIntent()
```

Obtient l’intention de l’annotation de polygone ou de polyligne.

**Returns:**
Élément PolyIntent @see PolyIntent

### getInteriorColor {#getInteriorColor--}
```
public Color getInteriorColor()
```

Obtient la couleur intérieure utilisée pour remplir les terminaisons de ligne de l’annotation.

**Returns:**
Objet Color

### getMeasure {#getMeasure--}
```
public Measure getMeasure()
```

Unités de mesure spécifiées pour cette annotation.

**Returns:**
Instance de mesure

### getStartingStyle {#getStartingStyle--}
```
public LineEnding getStartingStyle()
```

Obtient le style de la terminaison de la première ligne.

**Returns:**
Élément LineEnding @see LineEnding

### getVertices {#getVertices--}
```
public Point [] getVertices()
```

Obtient un tableau de points représentant les coordonnées horizontales et verticales de chaque sommet.

**Returns:**
tableau de valeurs Point

### setEndingStyle {#setEndingStyle-com.aspose.pdf.LineEnding-}
Définit le style de la terminaison de la deuxième ligne.

### setIntent {#setIntent-com.aspose.pdf.PolyIntent-}
Définit l’intention de l’annotation de polygone ou de polyligne.

### setInteriorColor {#setInteriorColor-com.aspose.pdf.Color-}
Définit la couleur intérieure utilisée pour remplir les terminaisons de ligne de l’annotation.

### setMeasure {#setMeasure-com.aspose.pdf.Measure-}
Unités de mesure spécifiées pour cette annotation.

### setStartingStyle {#setStartingStyle-com.aspose.pdf.LineEnding-}
Définit le style de la terminaison de la première ligne.

### setVertices {#setVertices-com.aspose.pdf.Point:A-}
Définit un tableau de points représentant les coordonnées horizontales et verticales de chaque sommet.
