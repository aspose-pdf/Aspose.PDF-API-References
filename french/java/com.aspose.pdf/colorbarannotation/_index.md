---
title: "ColorBarAnnotation"
linktitle: "ColorBarAnnotation"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant l'annotation ColorBarAnnotation. Propriété Color ignorée, à la place utilisée la couleur ColorsOfCMYK. Lors de la création, le rapport largeur/hauteur détermine l'orientation."
type: docs
weight: 680
url: /fr/java/com.aspose.pdf/colorbarannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.PrinterMarkAnnotation, com.aspose.pdf.ColorBarAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class ColorBarAnnotation extends PrinterMarkAnnotation
```

Classe représentant l'annotation ColorBarAnnotation. La propriété Color est ignorée, à la place la couleur ColorsOfCMYK est utilisée. Lors de la création, le rapport entre la largeur et la hauteur détermine l'orientation de l'annotation – horizontale ou verticale. Ensuite, il vérifie que le rectangle de l'annotation se trouve à l'extérieur du TrimBox, et si ce n'est pas le cas, il est déplacé vers l'emplacement le plus proche à l'extérieur du TrimBox, en tenant compte de l'orientation de l'annotation. Il est possible de réduire la largeur (ou la hauteur) afin que l'annotation tienne à l'extérieur du TrimBox. S'il n'y a pas d'espace pour la mise en page, la largeur/hauteur peut être mise à zéro (dans ce cas, l'annotation est présente sur la page, mais n'est pas affichée).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ColorBarAnnotation](#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Crée une nouvelle annotation ColorBar sur la page spécifiée. Valeur par défaut ColorsOfCMYK.Black |
| [ColorBarAnnotation](#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.ColorsOfCMYK-) | Crée une nouvelle annotation ColorBar sur la page spécifiée. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepte un objet visiteur pour traiter l'annotation. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Met à jour les paramètres et l'apparence, selon la transformation matricielle et le déplacement hors du TrimBox si nécessaire. |
| [getAnnotationType](#getAnnotationType--) | Obtient le type de l'annotation. |
| [getColorOfCMYK](#getColorOfCMYK--) | Obtient ou définit la couleur (l'une de cyan, magenta, jaune, noir) pour laquelle l'annotation est dessinée. |
| [setColorOfCMYK](#setColorOfCMYK-com.aspose.pdf.ColorsOfCMYK-) | Obtient ou définit la couleur (l'une de cyan, magenta, jaune, noir) pour laquelle l'annotation est dessinée. |

### ColorBarAnnotation {#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Crée une nouvelle annotation ColorBar sur la page spécifiée. Valeur par défaut ColorsOfCMYK.Black

### ColorBarAnnotation {#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.ColorsOfCMYK-}
Crée une nouvelle annotation ColorBar sur la page spécifiée.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepte un objet visiteur pour traiter l'annotation.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Met à jour les paramètres et l'apparence, selon la transformation matricielle et le déplacement hors du TrimBox si nécessaire.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtient le type de l'annotation.

**Returns:**
valeur int

### getColorOfCMYK {#getColorOfCMYK--}
```
public final ColorsOfCMYK getColorOfCMYK()
```

Obtient ou définit la couleur (l'une de cyan, magenta, jaune, noir) pour laquelle l'annotation est dessinée.

**Returns:**
Élément ColorsOfCMYK

### setColorOfCMYK {#setColorOfCMYK-com.aspose.pdf.ColorsOfCMYK-}
Obtient ou définit la couleur (l'une de cyan, magenta, jaune, noir) pour laquelle l'annotation est dessinée.
