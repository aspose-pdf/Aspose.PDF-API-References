---
title: "ButtonField"
linktitle: "ButtonField"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant le champ bouton poussoir."
type: docs
weight: 440
url: /fr/java/com.aspose.pdf/buttonfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.Field, com.aspose.pdf.ButtonField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class ButtonField extends Field
```

Classe représentant le champ bouton poussoir.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ButtonField](#ButtonField--) | Constructeur du champ bouton pour Generator. |
| [ButtonField](#ButtonField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Constructeur du champ bouton pour Generator. |
| [ButtonField](#ButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Constructeur du champ bouton pour Generator. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [addImage](#addImage-java.awt.image.BufferedImage-) | Ajoute une image dans les ressources du champ et la dessine. |
| [addImage](#addImage-java.awt.image.BufferedImage-boolean-) | Ajoute l'image dans les ressources du champ et la dessine. |
| [getAlternateCaption](#getAlternateCaption--) | Obtient la légende alternative du bouton qui doit être affichée lorsque le bouton de la souris est enfoncé dans sa zone active. |
| [getAlternateIcon](#getAlternateIcon--) | Obtient l'icône alternative qui doit être affichée lorsque le bouton de la souris est enfoncé dans sa zone active. |
| [getIconFit](#getIconFit--) | Obtient l'objet d'ajustement d'icône spécifiant comment l'icône de l'annotation widget doit être affichée dans son rectangle d'annotation. |
| [getICPosition](#getICPosition--) | Obtient la position de la légende de l'icône. |
| [getNormalCaption](#getNormalCaption--) | Obtient la légende normale. |
| [getNormalIcon](#getNormalIcon--) | Obtient l'icône normale du bouton qui doit être affichée lorsqu'il n'interagit pas avec l'utilisateur. |
| [getRolloverCaption](#getRolloverCaption--) | Obtient la légende de survol du bouton qui doit être affichée lorsque l'utilisateur déplace le curseur dans sa zone active sans appuyer sur le bouton de la souris. |
| [getRolloverIcon](#getRolloverIcon--) | Obtient l'icône de survol du bouton qui doit être affichée lorsque l'utilisateur déplace le curseur dans sa zone active sans appuyer sur le bouton de la souris. |
| [setAlternateCaption](#setAlternateCaption-java.lang.String-) | Définit la légende alternative du bouton qui doit être affichée lorsque le bouton de la souris est enfoncé dans sa zone active. |
| [setAlternateIcon](#setAlternateIcon-com.aspose.pdf.XForm-) | Définit l'icône alternative qui doit être affichée lorsque le bouton de la souris est enfoncé dans sa zone active. |
| [setICPosition](#setICPosition-com.aspose.pdf.IconCaptionPosition-) | Définit la position de la légende de l'icône. |
| [setNormalCaption](#setNormalCaption-java.lang.String-) | Définit la légende normale. |
| [setNormalIcon](#setNormalIcon-com.aspose.pdf.XForm-) | Définit l'icône normale du bouton qui doit être affichée lorsqu'il n'interagit pas avec l'utilisateur. |
| [setRolloverCaption](#setRolloverCaption-java.lang.String-) | Définit la légende de survol du bouton qui doit être affichée lorsque l'utilisateur déplace le curseur dans sa zone active sans appuyer sur le bouton de la souris. |
| [setRolloverIcon](#setRolloverIcon-com.aspose.pdf.XForm-) | Définit l'icône de survol du bouton qui doit être affichée lorsque l'utilisateur déplace le curseur dans sa zone active sans appuyer sur le bouton de la souris. |

### ButtonField {#ButtonField--}
```
public ButtonField()
```

Constructeur du champ bouton pour Generator.

### ButtonField {#ButtonField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Constructeur du champ bouton pour Generator.

### ButtonField {#ButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Constructeur du champ bouton pour Generator.

### addImage {#addImage-java.awt.image.BufferedImage-}
Ajoute une image dans les ressources du champ et la dessine.

### addImage {#addImage-java.awt.image.BufferedImage-boolean-}
Ajoute l'image dans les ressources du champ et la dessine.

### getAlternateCaption {#getAlternateCaption--}
```
public String getAlternateCaption()
```

Obtient la légende alternative du bouton qui doit être affichée lorsque le bouton de la souris est enfoncé dans sa zone active.

**Returns:**
valeur String

### getAlternateIcon {#getAlternateIcon--}
```
public XForm getAlternateIcon()
```

Obtient l'icône alternative qui doit être affichée lorsque le bouton de la souris est enfoncé dans sa zone active.

**Returns:**
objet XForm

### getIconFit {#getIconFit--}
```
public IconFit getIconFit()
```

Obtient l'objet d'ajustement d'icône spécifiant comment l'icône de l'annotation widget doit être affichée dans son rectangle d'annotation.

**Returns:**
Objet IconFit

### getICPosition {#getICPosition--}
```
public IconCaptionPosition getICPosition()
```

Obtient la position de la légende de l'icône.

**Returns:**
position de la légende de l'icône. @see IconCaptionPosition

### getNormalCaption {#getNormalCaption--}
```
public String getNormalCaption()
```

Obtient la légende normale.

**Returns:**
valeur String

### getNormalIcon {#getNormalIcon--}
```
public XForm getNormalIcon()
```

Obtient l'icône normale du bouton qui doit être affichée lorsqu'il n'interagit pas avec l'utilisateur.

**Returns:**
objet XForm

### getRolloverCaption {#getRolloverCaption--}
```
public String getRolloverCaption()
```

Obtient la légende de survol du bouton qui doit être affichée lorsque l'utilisateur déplace le curseur dans sa zone active sans appuyer sur le bouton de la souris.

**Returns:**
valeur String

### getRolloverIcon {#getRolloverIcon--}
```
public XForm getRolloverIcon()
```

Obtient l'icône de survol du bouton qui doit être affichée lorsque l'utilisateur déplace le curseur dans sa zone active sans appuyer sur le bouton de la souris.

**Returns:**
objet XForm

### setAlternateCaption {#setAlternateCaption-java.lang.String-}
Définit la légende alternative du bouton qui doit être affichée lorsque le bouton de la souris est enfoncé dans sa zone active.

### setAlternateIcon {#setAlternateIcon-com.aspose.pdf.XForm-}
Définit l'icône alternative qui doit être affichée lorsque le bouton de la souris est enfoncé dans sa zone active.

### setICPosition {#setICPosition-com.aspose.pdf.IconCaptionPosition-}
Définit la position de la légende de l'icône.

### setNormalCaption {#setNormalCaption-java.lang.String-}
Définit la légende normale.

### setNormalIcon {#setNormalIcon-com.aspose.pdf.XForm-}
Définit l'icône normale du bouton qui doit être affichée lorsqu'il n'interagit pas avec l'utilisateur.

### setRolloverCaption {#setRolloverCaption-java.lang.String-}
Définit la légende de survol du bouton qui doit être affichée lorsque l'utilisateur déplace le curseur dans sa zone active sans appuyer sur le bouton de la souris.

### setRolloverIcon {#setRolloverIcon-com.aspose.pdf.XForm-}
Définit l'icône de survol du bouton qui doit être affichée lorsque l'utilisateur déplace le curseur dans sa zone active sans appuyer sur le bouton de la souris.
