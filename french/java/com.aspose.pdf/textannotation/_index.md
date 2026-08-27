---
title: "TextAnnotation"
linktitle: "TextAnnotation"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une annotation texte qui est un \\\"post-it\\\" attaché à un point dans le document PDF."
type: docs
weight: 4920
url: /fr/java/com.aspose.pdf/textannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.TextAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class TextAnnotation extends MarkupAnnotation
```

Représente une annotation de texte qui est un "sticky note" attaché à un point dans le document PDF.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TextAnnotation](#TextAnnotation--) | Créer une instance de TextAnnotation |
| [TextAnnotation](#TextAnnotation-com.aspose.pdf.IDocument-) | Créer une instance de TextAnnotation |
| [TextAnnotation](#TextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Créer une instance de TextAnnotation |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepte un objet visiteur pour traiter l'annotation. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Remplace la définition dans la classe de base avec un corps vide. |
| [getAnnotationType](#getAnnotationType--) | Obtient le type de l'annotation. |
| [getIcon](#getIcon--) | Obtient une icône à utiliser pour l'affichage de l'annotation. |
| [getOpen](#getOpen--) | Obtient un indicateur spécifiant si l'annotation doit être affichée ouverte initialement. |
| [setIcon](#setIcon-int-) | Définit une icône à utiliser pour l'affichage de l'annotation. |
| [setOpen](#setOpen-boolean-) | Définit un indicateur spécifiant si l'annotation doit être affichée ouverte initialement. |

### TextAnnotation {#TextAnnotation--}
```
public TextAnnotation()
```

Créer une instance de TextAnnotation

### TextAnnotation {#TextAnnotation-com.aspose.pdf.IDocument-}
Créer une instance de TextAnnotation

### TextAnnotation {#TextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Créer une instance de TextAnnotation

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepte un objet visiteur pour traiter l'annotation.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Remplace la définition dans la classe de base avec un corps vide.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtient le type de l'annotation.

**Returns:**
Valeur AnnotationType @see AnnotationState

### getIcon {#getIcon--}
```
public int getIcon()
```

Obtient une icône à utiliser pour l'affichage de l'annotation.

**Returns:**
Valeur TextIcon @see TextIcon

### getOpen {#getOpen--}
```
public boolean getOpen()
```

Obtient un indicateur spécifiant si l'annotation doit être affichée ouverte initialement.

**Returns:**
valeur booléenne

### setIcon {#setIcon-int-}
```
public void setIcon(int value)
```

Définit une icône à utiliser pour l'affichage de l'annotation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur TextIcon @see TextIcon |

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

Définit un indicateur spécifiant si l'annotation doit être affichée ouverte initialement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |
