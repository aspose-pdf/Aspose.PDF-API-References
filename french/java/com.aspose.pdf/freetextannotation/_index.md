---
title: "FreeTextAnnotation"
linktitle: "FreeTextAnnotation"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une annotation de texte libre qui affiche le texte directement sur la page. Contrairement à une annotation de texte ordinaire, une annotation de texte libre n'a aucun état ouvert ou fermé ; au lieu de cela."
type: docs
weight: 1790
url: /fr/java/com.aspose.pdf/freetextannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FreeTextAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FreeTextAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FreeTextAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.FreeTextAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class FreeTextAnnotation extends MarkupAnnotation
```

Représente une annotation de texte libre qui affiche le texte directement sur la page. Contrairement à une annotation de texte ordinaire, une annotation de texte libre n'a aucun état ouvert ou fermé ; au lieu d'être affichée dans une fenêtre contextuelle, le texte est toujours visible.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FreeTextAnnotation](#FreeTextAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.DefaultAppearance-) | Constructeur à utiliser avec Generator. |
| [FreeTextAnnotation](#FreeTextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.DefaultAppearance-) | Crée une nouvelle annotation FreeText sur la page spécifiée. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepte un objet visiteur pour traiter l'annotation. |
| [getAnnotationType](#getAnnotationType--) | Obtient le type de l'annotation. |
| [getCallout](#getCallout--) | Tableau de points spécifiant la ligne d'appel. |
| [getDefaultAppearance](#getDefaultAppearance--) | Obtient la chaîne d'apparence par défaut à utiliser pour le formatage du texte. |
| [getDefaultAppearanceObject](#getDefaultAppearanceObject--) | Objet qui représente l'apparence par défaut de l'annotation FreeText. |
| [getDefaultStyle](#getDefaultStyle--) | Obtient une chaîne de style par défaut. |
| [getEndingStyle](#getEndingStyle--) | Obtient le style de terminaison de ligne pour le point de terminaison. |
| [getIntent](#getIntent--) | Obtient l'intention de l'annotation de texte libre. |
| [getJustification](#getJustification--) | Obtient un code spécifiant la forme de justification (quadding) à utiliser lors de l'affichage du texte de l'annotation. |
| [getRotate](#getRotate--) | Angle de rotation de l'annotation. |
| [getStartingStyle](#getStartingStyle--) | Obtient ou définit le style de terminaison de ligne pour le point de terminaison. Cette propriété est obsolète, veuillez utiliser EndingStyle. |
| [getTextRectangle](#getTextRectangle--) | Rectangle décrivant les différences numériques entre deux rectangles : l'entrée Rect de l'annotation et un rectangle contenu dans ce rectangle. Le rectangle interne est l'endroit où le texte de l'annotation doit être affiché. |
| [getTextStyle](#getTextStyle--) | Obtient ou définit le style du texte dans l'apparence. Lorsque le style du texte est modifié, l'apparence du texte est mise à jour. |
| [isValidXml](#isValidXml-java.lang.String-) |  |
| [setCallout](#setCallout-com.aspose.pdf.Point:A-) | Tableau de points spécifiant la ligne d'appel. |
| [setDefaultAppearance](#setDefaultAppearance-java.lang.String-) | Définit la chaîne d'apparence par défaut à utiliser pour le formatage du texte. |
| [setDefaultStyle](#setDefaultStyle-java.lang.String-) | Définit une chaîne de style par défaut. |
| [setEndingStyle](#setEndingStyle-com.aspose.pdf.LineEnding-) | Définit le style de terminaison de ligne pour le point de terminaison. |
| [setIntent](#setIntent-com.aspose.pdf.FreeTextIntent-) | Définit l'intention de l'annotation de texte libre. |
| [setJustification](#setJustification-com.aspose.pdf.Justification-) | Définit un code spécifiant la forme de justification (quadding) à utiliser lors de l'affichage du texte de l'annotation. |
| [setRotate](#setRotate-com.aspose.pdf.Rotation-) | Angle de rotation de l'annotation. |
| [setStartingStyle](#setStartingStyle-com.aspose.pdf.LineEnding-) | Obtient ou définit le style de terminaison de ligne pour le point de terminaison. Cette propriété est obsolète, veuillez utiliser EndingStyle. |
| [setTextRectangle](#setTextRectangle-com.aspose.pdf.Rectangle-) | Rectangle décrivant les différences numériques entre deux rectangles : l'entrée Rect de l'annotation et un rectangle contenu dans ce rectangle. Le rectangle interne est l'endroit où le texte de l'annotation doit être affiché. |
| [setTextStyle](#setTextStyle-int-int-int-) | Définit le formatage déterminé par le paramètre textStyle pour un fragment de texte depuis l'index fromInd jusqu'à l'index toInd. |
| [setTextStyle](#setTextStyle-int-java.lang.String-double-java.awt.Color-) | Définit le formatage déterminé par le paramètre textStyle pour tout le texte d'annotation. |
| [setTextStyle](#setTextStyle-com.aspose.pdf.TextStyle-) | Définit le style du texte dans l'apparence. Lorsque le style du texte est modifié, l'apparence du texte est mise à jour. |
| [updateAppearance](#updateAppearance--) | Met à jour l'Apparence après que le texte a été modifié/déplacé. |

### FreeTextAnnotation {#FreeTextAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.DefaultAppearance-}
Constructeur à utiliser avec Generator.

### FreeTextAnnotation {#FreeTextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.DefaultAppearance-}
Crée une nouvelle annotation FreeText sur la page spécifiée.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepte un objet visiteur pour traiter l'annotation.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtient le type de l'annotation.

**Returns:**
valeur int

### getCallout {#getCallout--}
```
public final Point [] getCallout()
```

Tableau de points spécifiant la ligne d'appel.

**Returns:**
tableau de Point

### getDefaultAppearance {#getDefaultAppearance--}
```
public String getDefaultAppearance()
```

Obtient la chaîne d'apparence par défaut à utiliser pour le formatage du texte.

**Returns:**
valeur String

### getDefaultAppearanceObject {#getDefaultAppearanceObject--}
```
public final DefaultAppearance getDefaultAppearanceObject()
```

Objet qui représente l'apparence par défaut de l'annotation FreeText.

**Returns:**
objet DefaultAppearance

### getDefaultStyle {#getDefaultStyle--}
```
public String getDefaultStyle()
```

Obtient une chaîne de style par défaut.

**Returns:**
valeur String

### getEndingStyle {#getEndingStyle--}
```
public LineEnding getEndingStyle()
```

Obtient le style de terminaison de ligne pour le point de terminaison.

**Returns:**
valeur LineEnding @see LineEnding

### getIntent {#getIntent--}
```
public FreeTextIntent getIntent()
```

Obtient l'intention de l'annotation de texte libre.

**Returns:**
valeur int @see FreeTextIntent

### getJustification {#getJustification--}
```
public Justification getJustification()
```

Obtient un code spécifiant la forme de justification (quadding) à utiliser lors de l'affichage du texte de l'annotation.

**Returns:**
valeur int @see Justification

### getRotate {#getRotate--}
```
public Rotation getRotate()
```

Angle de rotation de l'annotation.

**Returns:**
élément Rotation @see Rotation

### getStartingStyle {#getStartingStyle--}
```
public final LineEnding getStartingStyle()
```

Obtient ou définit le style de terminaison de ligne pour le point de terminaison. Cette propriété est obsolète, veuillez utiliser EndingStyle.

**Returns:**
élément LineEnding

### getTextRectangle {#getTextRectangle--}
```
public final Rectangle getTextRectangle()
```

Rectangle décrivant les différences numériques entre deux rectangles : l'entrée Rect de l'annotation et un rectangle contenu dans ce rectangle. Le rectangle interne est l'endroit où le texte de l'annotation doit être affiché.

**Returns:**
Instance de Rectangle

### getTextStyle {#getTextStyle--}
```
public TextStyle getTextStyle()
```

Obtient ou définit le style du texte dans l'apparence. Lorsque le style du texte est modifié, l'apparence du texte est mise à jour.

**Returns:**
valeur TextStyle

### isValidXml {#isValidXml-java.lang.String-}


### setCallout {#setCallout-com.aspose.pdf.Point:A-}
Tableau de points spécifiant la ligne d'appel.

### setDefaultAppearance {#setDefaultAppearance-java.lang.String-}
Définit la chaîne d'apparence par défaut à utiliser pour le formatage du texte.

### setDefaultStyle {#setDefaultStyle-java.lang.String-}
Définit une chaîne de style par défaut.

### setEndingStyle {#setEndingStyle-com.aspose.pdf.LineEnding-}
Définit le style de terminaison de ligne pour le point de terminaison.

### setIntent {#setIntent-com.aspose.pdf.FreeTextIntent-}
Définit l'intention de l'annotation de texte libre.

### setJustification {#setJustification-com.aspose.pdf.Justification-}
Définit un code spécifiant la forme de justification (quadding) à utiliser lors de l'affichage du texte de l'annotation.

### setRotate {#setRotate-com.aspose.pdf.Rotation-}
Angle de rotation de l'annotation.

### setStartingStyle {#setStartingStyle-com.aspose.pdf.LineEnding-}
Obtient ou définit le style de terminaison de ligne pour le point de terminaison. Cette propriété est obsolète, veuillez utiliser EndingStyle.

### setTextRectangle {#setTextRectangle-com.aspose.pdf.Rectangle-}
Rectangle décrivant les différences numériques entre deux rectangles : l'entrée Rect de l'annotation et un rectangle contenu dans ce rectangle. Le rectangle interne est l'endroit où le texte de l'annotation doit être affiché.

### setTextStyle {#setTextStyle-int-int-int-}
```
public final void setTextStyle(int fromInd, int toInd, int textStyles)
```

Définit le formatage déterminé par le paramètre textStyle pour un fragment de texte depuis l'index fromInd jusqu'à l'index toInd.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fromInd |  | Index de départ du fragment de texte (à partir de 0). |
| toInd |  | Index de fin du fragment de texte (en comptant à partir de 0, cet index n'est pas inclus). |
| textStyles |  | Style(s) appliqué(s) au fragment de texte. |

### setTextStyle {#setTextStyle-int-java.lang.String-double-java.awt.Color-}
Définit le formatage déterminé par le paramètre textStyle pour tout le texte d'annotation.

### setTextStyle {#setTextStyle-com.aspose.pdf.TextStyle-}
Définit le style du texte dans l'apparence. Lorsque le style du texte est modifié, l'apparence du texte est mise à jour.

### updateAppearance {#updateAppearance--}
```
public void updateAppearance()
```

Met à jour l'Apparence après que le texte a été modifié/déplacé.
