---
title: "LineAnnotation"
linktitle: "LineAnnotation"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant une annotation de ligne."
type: docs
weight: 2710
url: /fr/java/com.aspose.pdf/lineannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.LineAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.LineAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.LineAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.LineAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class LineAnnotation extends MarkupAnnotation
```

Classe représentant une annotation de ligne.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [LineAnnotation](#LineAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.Point-com.aspose.pdf.Point-) | Constructeur à utiliser avec le Générateur. |
| [LineAnnotation](#LineAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.Point-com.aspose.pdf.Point-) | Crée une nouvelle annotation Line sur la page spécifiée. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepte un visiteur pour le traitement de l'annotation. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Met à jour les points de départ et d'arrivée, selon la transformation matricielle. |
| [getAnnotationType](#getAnnotationType--) | Obtient le type de l'annotation. |
| [getCaptionOffset](#getCaptionOffset--) | Obtient le décalage du texte de la légende par rapport à sa position normale. |
| [getCaptionPosition](#getCaptionPosition--) | Obtient la position de la légende de l'annotation. |
| [getEnding](#getEnding--) | Obtient le point d'extrémité de la ligne. |
| [getEndingStyle](#getEndingStyle--) | Obtient le style de terminaison pour le point final de la ligne. |
| [getIntent](#getIntent--) | Obtient l'intention de l'annotation Line. |
| [getInteriorColor](#getInteriorColor--) | Obtient la couleur intérieure de l'annotation. |
| [getLeaderLine](#getLeaderLine--) | Obtient la longueur de la ligne directrice. |
| [getLeaderLineExtension](#getLeaderLineExtension--) | Obtient la longueur de l'extension de la ligne directrice. |
| [getLeaderLineOffset](#getLeaderLineOffset--) | Obtient le décalage de la ligne directrice. |
| [getMeasure](#getMeasure--) | Unités de mesure spécifiées pour cette annotation. |
| [getShowCaption](#getShowCaption--) | Obtient le drapeau booléen qui détermine si le contenu doit être affiché comme légende. |
| [getStarting](#getStarting--) | Obtient le point de départ de la ligne. |
| [getStartingStyle](#getStartingStyle--) | Obtient le style de terminaison de ligne pour le point de départ de la ligne. |
| [setCaptionOffset](#setCaptionOffset-com.aspose.pdf.Point-) | Définit le décalage du texte de la légende par rapport à sa position normale. |
| [setCaptionPosition](#setCaptionPosition-com.aspose.pdf.CaptionPosition-) | Définit la position de la légende de l'annotation. |
| [setEnding](#setEnding-com.aspose.pdf.Point-) | Définit le point d'extrémité de la ligne. |
| [setEndingStyle](#setEndingStyle-com.aspose.pdf.LineEnding-) | Définit le style de terminaison pour le point final de la ligne. |
| [setIntent](#setIntent-com.aspose.pdf.LineIntent-) | Définit l'intention de l'annotation Line. |
| [setInteriorColor](#setInteriorColor-com.aspose.pdf.Color-) | Définit la couleur intérieure de l'annotation. |
| [setLeaderLine](#setLeaderLine-double-) | Définit la longueur de la ligne directrice. |
| [setLeaderLineExtension](#setLeaderLineExtension-double-) | Définit la longueur de l'extension de la ligne directrice. |
| [setLeaderLineOffset](#setLeaderLineOffset-double-) | Définit le décalage de la ligne directrice. |
| [setMeasure](#setMeasure-com.aspose.pdf.Measure-) | Unités de mesure spécifiées pour cette annotation. |
| [setShowCaption](#setShowCaption-boolean-) | Définit le drapeau booléen qui détermine si le contenu doit être affiché comme légende. |
| [setStarting](#setStarting-com.aspose.pdf.Point-) | Définit le point de départ de la ligne. |
| [setStartingStyle](#setStartingStyle-com.aspose.pdf.LineEnding-) | Définit le style de terminaison de ligne pour le point de départ de la ligne. |

### LineAnnotation {#LineAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.Point-com.aspose.pdf.Point-}
Constructeur à utiliser avec le Générateur.

### LineAnnotation {#LineAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.Point-com.aspose.pdf.Point-}
Crée une nouvelle annotation Line sur la page spécifiée.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepte un visiteur pour le traitement de l'annotation.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Met à jour les points de départ et d'arrivée, selon la transformation matricielle.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtient le type de l'annotation.

**Returns:**
Élément AnnotationType @see AnnotationType

### getCaptionOffset {#getCaptionOffset--}
```
public Point getCaptionOffset()
```

Obtient le décalage du texte de la légende par rapport à sa position normale.

**Returns:**
Objet Point

### getCaptionPosition {#getCaptionPosition--}
```
public CaptionPosition getCaptionPosition()
```

Obtient la position de la légende de l'annotation.

**Returns:**
Élément CaptionPosition @see CaptionPosition

### getEnding {#getEnding--}
```
public Point getEnding()
```

Obtient le point d'extrémité de la ligne.

**Returns:**
Valeur du point

### getEndingStyle {#getEndingStyle--}
```
public LineEnding getEndingStyle()
```

Obtient le style de terminaison pour le point final de la ligne.

**Returns:**
Élément LineEnding @see LineEnding

### getIntent {#getIntent--}
```
public LineIntent getIntent()
```

Obtient l'intention de l'annotation Line.

**Returns:**
Élément LineIntent @see LineIntent

### getInteriorColor {#getInteriorColor--}
```
public Color getInteriorColor()
```

Obtient la couleur intérieure de l'annotation.

**Returns:**
Objet Color

### getLeaderLine {#getLeaderLine--}
```
public double getLeaderLine()
```

Obtient la longueur de la ligne directrice.

**Returns:**
valeur double

### getLeaderLineExtension {#getLeaderLineExtension--}
```
public double getLeaderLineExtension()
```

Obtient la longueur de l'extension de la ligne directrice.

**Returns:**
valeur double

### getLeaderLineOffset {#getLeaderLineOffset--}
```
public double getLeaderLineOffset()
```

Obtient le décalage de la ligne directrice.

**Returns:**
valeur double

### getMeasure {#getMeasure--}
```
public Measure getMeasure()
```

Unités de mesure spécifiées pour cette annotation.

**Returns:**
Objet Measure

### getShowCaption {#getShowCaption--}
```
public boolean getShowCaption()
```

Obtient le drapeau booléen qui détermine si le contenu doit être affiché comme légende.

**Returns:**
valeur booléenne

### getStarting {#getStarting--}
```
public Point getStarting()
```

Obtient le point de départ de la ligne.

**Returns:**
Valeur du point

### getStartingStyle {#getStartingStyle--}
```
public LineEnding getStartingStyle()
```

Obtient le style de terminaison de ligne pour le point de départ de la ligne.

**Returns:**
Élément LineEnding @see LineEnding

### setCaptionOffset {#setCaptionOffset-com.aspose.pdf.Point-}
Définit le décalage du texte de la légende par rapport à sa position normale.

### setCaptionPosition {#setCaptionPosition-com.aspose.pdf.CaptionPosition-}
Définit la position de la légende de l'annotation.

### setEnding {#setEnding-com.aspose.pdf.Point-}
Définit le point d'extrémité de la ligne.

### setEndingStyle {#setEndingStyle-com.aspose.pdf.LineEnding-}
Définit le style de terminaison pour le point final de la ligne.

### setIntent {#setIntent-com.aspose.pdf.LineIntent-}
Définit l'intention de l'annotation Line.

### setInteriorColor {#setInteriorColor-com.aspose.pdf.Color-}
Définit la couleur intérieure de l'annotation.

### setLeaderLine {#setLeaderLine-double-}
```
public void setLeaderLine(double value)
```

Définit la longueur de la ligne directrice.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setLeaderLineExtension {#setLeaderLineExtension-double-}
```
public void setLeaderLineExtension(double value)
```

Définit la longueur de l'extension de la ligne directrice.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setLeaderLineOffset {#setLeaderLineOffset-double-}
```
public void setLeaderLineOffset(double value)
```

Définit le décalage de la ligne directrice.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setMeasure {#setMeasure-com.aspose.pdf.Measure-}
Unités de mesure spécifiées pour cette annotation.

### setShowCaption {#setShowCaption-boolean-}
```
public void setShowCaption(boolean value)
```

Définit le drapeau booléen qui détermine si le contenu doit être affiché comme légende.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setStarting {#setStarting-com.aspose.pdf.Point-}
Définit le point de départ de la ligne.

### setStartingStyle {#setStartingStyle-com.aspose.pdf.LineEnding-}
Définit le style de terminaison de ligne pour le point de départ de la ligne.
