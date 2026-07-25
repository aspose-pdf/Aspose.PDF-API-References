---
title: "InkAnnotation"
linktitle: "InkAnnotation"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente un \\\"scribble\\\" à main levée composé d'un ou plusieurs chemins disjoints."
type: docs
weight: 2430
url: /fr/java/com.aspose.pdf/inkannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.InkAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.InkAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.InkAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.InkAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class InkAnnotation extends MarkupAnnotation
```

Représente un gribouillage à main levée composé d'un ou plusieurs chemins disjoints.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [InkAnnotation](#InkAnnotation-com.aspose.pdf.IDocument-java.util.List-) | Constructeur pour l'annotation Ink pour Generator. |
| [InkAnnotation](#InkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.util.List-) | Crée une nouvelle annotation Ink sur la page spécifiée. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepte un objet visiteur pour traiter l'annotation. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Met à jour les points dans InkList, selon la transformation matricielle. |
| [getAnnotationType](#getAnnotationType--) | Obtient le type de l'annotation. |
| [getCapStyle](#getCapStyle--) | obtient le style des terminaisons de ligne de l'annotation Ink. |
| [getInkList](#getInkList--) | <p> Obtient la liste des gestes qui sont des lignes indépendantes représentées par des tableaux Point[]. </p> |
| [setCapStyle](#setCapStyle-com.aspose.pdf.CapStyle-) | Définir le style des terminaisons de ligne d'annotation d'encre. |
| [setInkList](#setInkList-java.util.List-) | Définit la liste des gestes qui sont des lignes indépendantes représentées par des tableaux Point[]. |
| [updateAppearance](#updateAppearance--) | Met à jour l'Apparence après que le texte a été modifié/déplacé. |

### InkAnnotation {#InkAnnotation-com.aspose.pdf.IDocument-java.util.List-}
Constructeur pour l'annotation Ink pour Generator.

### InkAnnotation {#InkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.util.List-}
Crée une nouvelle annotation Ink sur la page spécifiée.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepte un objet visiteur pour traiter l'annotation.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Met à jour les points dans InkList, selon la transformation matricielle.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtient le type de l'annotation.

**Returns:**
Élément AnnotationType @see AnnotationType

### getCapStyle {#getCapStyle--}
```
public CapStyle getCapStyle()
```

obtient le style des terminaisons de ligne de l'annotation Ink.

**Returns:**
Élément CapStyle @see CapStyle

### getInkList {#getInkList--}
```
public List < Point []> getInkList()
```

<p> Obtient la liste des gestes qui sont des lignes indépendantes représentées par des tableaux Point[]. </p>

**Returns:**
objet {@code List<Point[]>}

### setCapStyle {#setCapStyle-com.aspose.pdf.CapStyle-}
Définir le style des terminaisons de ligne d'annotation d'encre.

### setInkList {#setInkList-java.util.List-}
Définit la liste des gestes qui sont des lignes indépendantes représentées par des tableaux Point[].

### updateAppearance {#updateAppearance--}
```
public void updateAppearance()
```

Met à jour l'Apparence après que le texte a été modifié/déplacé.
