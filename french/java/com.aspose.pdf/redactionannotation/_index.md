---
title: "RedactionAnnotation"
linktitle: "RedactionAnnotation"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente l'annotation Redact."
type: docs
weight: 4120
url: /fr/java/com.aspose.pdf/redactionannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.RedactionAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.RedactionAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.RedactionAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.RedactionAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class RedactionAnnotation extends MarkupAnnotation
```

Représente l'annotation Redact.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [RedactionAnnotation](#RedactionAnnotation-com.aspose.pdf.IDocument-) | Constructeur pour RedactionAnnotation. À utiliser dans Generator. |
| [RedactionAnnotation](#RedactionAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Constructeur pour RedactAnnotation. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepte un objet visiteur pour traiter l'annotation. |
| [flatten](#flatten--) | Aplatisse l'annotation, c.-à-d. supprime l'annotation et ajoute son contenu |
| [getAnnotationType](#getAnnotationType--) | Obtient le type de l'annotation. |
| [getBorderColor](#getBorderColor--) | Obtient la couleur de la bordure qui est dessinée lorsque la rédaction n'est pas active. |
| [getDefaultAppearance](#getDefaultAppearance--) | Obtient ou définit la chaîne d'apparence par défaut à utiliser lors du formatage du texte. |
| [getFillColor](#getFillColor--) | Obtient la couleur pour remplir l'annotation. |
| [getFontSize](#getFontSize--) | Obtient la taille de police pour OverlayText. |
| [getOverlayText](#getOverlayText--) | Obtient le texte à imprimer sur l'annotation de rédaction. |
| [getQuadPoint](#getQuadPoint--) | Un tableau de nombres 8xN spécifiant les coordonnées de la région de contenu qui doit être supprimée. |
| [getQuadPoints](#getQuadPoints--) | Obtient un tableau de points spécifiant les coordonnées de n quadrilatères. Chaque quadrilatère englobe un mot ou un groupe de mots contigus dans le texte sous-jacent à l'annotation. |
| [getTextAlignment](#getTextAlignment--) | Obtient l'alignement du texte de superposition. |
| [isRepeat](#isRepeat--) | Si vrai, le texte de superposition sera répété sur l'annotation. |
| [redact](#redact--) | Aplati l'annotation et censure le contenu de la page (c.-à-d. supprime le texte et le contenu image sous l'annotation censurée) |
| [redactExact](#redactExact--) | Aplati l'annotation et censure le contenu de la page (c.-à-d. supprime le texte et le contenu image exactement sous l'annotation censurée) |
| [setBorderColor](#setBorderColor-com.aspose.pdf.Color-) | Définit la couleur de la bordure qui est dessinée lorsque la censure n'est pas active. |
| [setDefaultAppearance](#setDefaultAppearance-java.lang.String-) | Obtient ou définit la chaîne d'apparence par défaut à utiliser lors du formatage du texte. |
| [setFillColor](#setFillColor-com.aspose.pdf.Color-) | Définit la couleur de remplissage de l'annotation. |
| [setFontSize](#setFontSize-float-) | Définit la taille de police pour OverlayText. La valeur par défaut est 10. |
| [setOverlayText](#setOverlayText-java.lang.String-) | Définit le texte à imprimer sur l'annotation de rédaction. |
| [setQuadPoint](#setQuadPoint-com.aspose.pdf.Point:A-) | Un tableau de nombres 8xN spécifiant les coordonnées de la région de contenu qui doit être supprimée. |
| [setQuadPoints](#setQuadPoints-com.aspose.pdf.Point:A-) | Définit un tableau de points spécifiant les coordonnées de n quadrilatères. Chaque quadrilatère englobe un mot ou un groupe de mots contigus dans le texte sous-jacent à l'annotation. |
| [setRepeat](#setRepeat-boolean-) | Si vrai, le texte de superposition sera répété sur l'annotation. |
| [setTextAlignment](#setTextAlignment-com.aspose.pdf.HorizontalAlignment-) | Définit l'alignement du texte de superposition. |

### RedactionAnnotation {#RedactionAnnotation-com.aspose.pdf.IDocument-}
Constructeur pour RedactionAnnotation. À utiliser dans Generator.

### RedactionAnnotation {#RedactionAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Constructeur pour RedactAnnotation.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepte un objet visiteur pour traiter l'annotation.

### flatten {#flatten--}
```
public void flatten()
```

Aplatisse l'annotation, c.-à-d. supprime l'annotation et ajoute son contenu

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtient le type de l'annotation.

**Returns:**
Élément AnnotationType @see AnnotationType

### getBorderColor {#getBorderColor--}
```
public Color getBorderColor()
```

Obtient la couleur de la bordure qui est dessinée lorsque la rédaction n'est pas active.

**Returns:**
Valeur de couleur

### getDefaultAppearance {#getDefaultAppearance--}
```
public final String getDefaultAppearance()
```

Obtient ou définit la chaîne d'apparence par défaut à utiliser lors du formatage du texte.

**Returns:**
valeur String

### getFillColor {#getFillColor--}
```
public Color getFillColor()
```

Obtient la couleur pour remplir l'annotation.

**Returns:**
valeur de couleur

### getFontSize {#getFontSize--}
```
public final float getFontSize()
```

Obtient la taille de police pour OverlayText.

**Returns:**
valeur int

### getOverlayText {#getOverlayText--}
```
public String getOverlayText()
```

Obtient le texte à imprimer sur l'annotation de rédaction.

**Returns:**
valeur de chaîne

### getQuadPoint {#getQuadPoint--}
```
public Point [] getQuadPoint()
```

Un tableau de nombres 8xN spécifiant les coordonnées de la région de contenu qui doit être supprimée.

**Returns:**
tableau de points

### getQuadPoints {#getQuadPoints--}
```
@Deprecated public Point [] getQuadPoints()
```

Obtient un tableau de points spécifiant les coordonnées de n quadrilatères. Chaque quadrilatère englobe un mot ou un groupe de mots contigus dans le texte sous-jacent à l'annotation.

**Returns:**
tableau de valeurs Point

### getTextAlignment {#getTextAlignment--}
```
public HorizontalAlignment getTextAlignment()
```

Obtient l'alignement du texte de superposition.

**Returns:**
Valeur HorizontalAlignment @see HorizontalAlignment

### isRepeat {#isRepeat--}
```
public boolean isRepeat()
```

Si vrai, le texte de superposition sera répété sur l'annotation.

**Returns:**
valeur booléenne

### redact {#redact--}
```
public void redact()
```

Aplati l'annotation et censure le contenu de la page (c.-à-d. supprime le texte et le contenu image sous l'annotation censurée)

### redactExact {#redactExact--}
```
public void redactExact()
```

Aplati l'annotation et censure le contenu de la page (c.-à-d. supprime le texte et le contenu image exactement sous l'annotation censurée)

### setBorderColor {#setBorderColor-com.aspose.pdf.Color-}
Définit la couleur de la bordure qui est dessinée lorsque la censure n'est pas active.

### setDefaultAppearance {#setDefaultAppearance-java.lang.String-}
Obtient ou définit la chaîne d'apparence par défaut à utiliser lors du formatage du texte.

### setFillColor {#setFillColor-com.aspose.pdf.Color-}
Définit la couleur de remplissage de l'annotation.

### setFontSize {#setFontSize-float-}
```
public final void setFontSize(float fontSize)
```

Définit la taille de police pour OverlayText. La valeur par défaut est 10.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontSize |  | valeur int |

### setOverlayText {#setOverlayText-java.lang.String-}
Définit le texte à imprimer sur l'annotation de rédaction.

### setQuadPoint {#setQuadPoint-com.aspose.pdf.Point:A-}
Un tableau de nombres 8xN spécifiant les coordonnées de la région de contenu qui doit être supprimée.

### setQuadPoints {#setQuadPoints-com.aspose.pdf.Point:A-}
Définit un tableau de points spécifiant les coordonnées de n quadrilatères. Chaque quadrilatère englobe un mot ou un groupe de mots contigus dans le texte sous-jacent à l'annotation.

### setRepeat {#setRepeat-boolean-}
```
public void setRepeat(boolean value)
```

Si vrai, le texte de superposition sera répété sur l'annotation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setTextAlignment {#setTextAlignment-com.aspose.pdf.HorizontalAlignment-}
Définit l'alignement du texte de superposition.
