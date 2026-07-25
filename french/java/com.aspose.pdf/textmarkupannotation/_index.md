---
title: "TextMarkupAnnotation"
linktitle: "TextMarkupAnnotation"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe de base abstraite pour les annotations de balisage de texte."
type: docs
weight: 5180
url: /fr/java/com.aspose.pdf/textmarkupannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextMarkupAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextMarkupAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextMarkupAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.TextMarkupAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public abstract class TextMarkupAnnotation extends MarkupAnnotation
```

Classe de base abstraite pour les annotations de balisage de texte.

## Méthodes

| Méthode | Description |
| --- | --- |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Met à jour les QuadPoints, selon la transformation de la matrice. |
| [getMarkedText](#getMarkedText--) | Obtient le texte sous l'annotation de balisage sous forme de chaîne. |
| [getMarkedTextFragments](#getMarkedTextFragments--) | Obtient le texte sous l'annotation de balisage sous forme de {@code TextFragmentCollection}. |
| [getQuadPoints](#getQuadPoints--) | Obtient un tableau de points spécifiant les coordonnées de n quadrilatères. Chaque quadrilatère englobe un mot ou un groupe de mots contigus dans le texte sous-jacent à l'annotation. |
| [setQuadPoints](#setQuadPoints-com.aspose.pdf.Point:A-) | Définit un tableau de points spécifiant les coordonnées de n quadrilatères. Chaque quadrilatère englobe un mot ou un groupe de mots contigus dans le texte sous-jacent à l'annotation. |

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Met à jour les QuadPoints, selon la transformation de la matrice.

### getMarkedText {#getMarkedText--}
```
public String getMarkedText()
```

Obtient le texte sous l'annotation de balisage sous forme de chaîne.

**Returns:**
Chaîne contenant le texte qui se trouve sous l'annotation de balisage.

### getMarkedTextFragments {#getMarkedTextFragments--}
```
public TextFragmentCollection getMarkedTextFragments()
```

Obtient le texte sous l'annotation de balisage sous forme de {@code TextFragmentCollection}.

**Returns:**
{@code TextFragmentCollection} contenant des {@code TextFragment}s qui se trouvent sous l'annotation de balisage.

### getQuadPoints {#getQuadPoints--}
```
public Point [] getQuadPoints()
```

Obtient un tableau de points spécifiant les coordonnées de n quadrilatères. Chaque quadrilatère englobe un mot ou un groupe de mots contigus dans le texte sous-jacent à l'annotation.

**Returns:**
tableau de valeurs Point

### setQuadPoints {#setQuadPoints-com.aspose.pdf.Point:A-}
Définit un tableau de points spécifiant les coordonnées de n quadrilatères. Chaque quadrilatère englobe un mot ou un groupe de mots contigus dans le texte sous-jacent à l'annotation.
