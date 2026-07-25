---
title: "RadioButtonField"
linktitle: "RadioButtonField"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant le champ bouton radio."
type: docs
weight: 4080
url: /fr/java/com.aspose.pdf/radiobuttonfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.Field, com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.ChoiceField, com.aspose.pdf.RadioButtonField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class RadioButtonField extends ChoiceField
```

Classe représentant le champ bouton radio.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [RadioButtonField](#RadioButtonField-com.aspose.pdf.IDocument-) | Constructeur pour RadioButtonField. |
| [RadioButtonField](#RadioButtonField-com.aspose.pdf.Page-) | Constructeur pour RadiouttonField |
| [RadioButtonField](#RadioButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Définit le champ de bouton radio |

## Méthodes

| Méthode | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.RadioButtonOptionField-) | Ajoute un nouveau champ d'option au champ RadioButton |
| [addOption](#addOption-java.lang.String-) | Ajouter une option au bouton radion. |
| [addOption](#addOption-java.lang.String-com.aspose.pdf.Rectangle-) | Ajouter à l'option du bouton radio avec un rectangle spécifié. |
| [getNoToggleToOff](#getNoToggleToOff--) | <p> Obtient ou définit le drapeau qui permet au bouton radio de ne pas avoir de valeur sélectionnée. Si {@code }, exactement un bouton radio doit être sélectionné en permanence ; sélectionner le bouton actuellement sélectionné n'a aucun effet. Si {@code }, cliquer sur le bouton sélectionné le désélectionne, laissant aucun bouton sélectionné. </p> <hr> Certains lecteurs PDF (y compris Adobe Acrobat) peuvent ignorer l'état du drapeau. |
| [getOptions](#getOptions--) | Obtient la collection d'options du bouton radio. |
| [getPageIndex](#getPageIndex--) | Obtient l'index de la page contenant ce champ RadioButton. |
| [getSelected](#getSelected--) | Obtient l'index de l'élément sélectionné. La numérotation des éléments commence à 1. |
| [getStyle](#getStyle--) | Style de la boîte de champ. |
| [getValue](#getValue--) | Obtient la valeur du champ. |
| [setNoToggleToOff](#setNoToggleToOff-boolean-) | <p> Obtient ou définit le drapeau qui permet au bouton radio de ne pas avoir de valeur sélectionnée. Si {@code }, exactement un bouton radio doit être sélectionné en permanence ; sélectionner le bouton actuellement sélectionné n'a aucun effet. Si {@code }, cliquer sur le bouton sélectionné le désélectionne, laissant aucun bouton sélectionné. </p> <hr> Certains lecteurs PDF (y compris Adobe Acrobat) peuvent ignorer l'état du drapeau. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Déplace tous les sous-éléments du bouton radio vers les positions spécifiées sur la page. |
| [setSelected](#setSelected-int-) | Définit l'index de l'élément sélectionné. La numérotation des éléments commence à 1. |
| [setStyle](#setStyle-com.aspose.pdf.BoxStyle-) | Style de la boîte de champ. |
| [setValue](#setValue-java.lang.String-) | Définit la valeur du champ. |
| [updateAppearances](#updateAppearances--) | Met à jour la valeur des apparences. |

### RadioButtonField {#RadioButtonField-com.aspose.pdf.IDocument-}
Constructeur pour RadioButtonField.

### RadioButtonField {#RadioButtonField-com.aspose.pdf.Page-}
Constructeur pour RadiouttonField

### RadioButtonField {#RadioButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Définit le champ de bouton radio

### add {#add-com.aspose.pdf.RadioButtonOptionField-}
Ajoute un nouveau champ d'option au champ RadioButton

### addOption {#addOption-java.lang.String-}
Ajouter une option au bouton radion.

### addOption {#addOption-java.lang.String-com.aspose.pdf.Rectangle-}
Ajouter à l'option du bouton radio avec un rectangle spécifié.

### getNoToggleToOff {#getNoToggleToOff--}
```
public final boolean getNoToggleToOff()
```

<p> Obtient ou définit le drapeau qui permet au bouton radio de ne pas avoir de valeur sélectionnée. Si {@code }, exactement un bouton radio doit être sélectionné en permanence ; sélectionner le bouton actuellement sélectionné n'a aucun effet. Si {@code }, cliquer sur le bouton sélectionné le désélectionne, laissant aucun bouton sélectionné. </p> <hr> Certains lecteurs PDF (y compris Adobe Acrobat) peuvent ignorer l'état du drapeau.

**Returns:**
valeur booléenne

### getOptions {#getOptions--}
```
public OptionCollection getOptions()
```

Obtient la collection d'options du bouton radio.

**Returns:**
Objet OptionCollection

### getPageIndex {#getPageIndex--}
```
public int getPageIndex()
```

Obtient l'index de la page contenant ce champ RadioButton.

**Returns:**
valeur int

### getSelected {#getSelected--}
```
public int getSelected()
```

Obtient l'index de l'élément sélectionné. La numérotation des éléments commence à 1.

**Returns:**
valeur int

### getStyle {#getStyle--}
```
public BoxStyle getStyle()
```

Style de la boîte de champ.

**Returns:**
Valeur BoxStyle @see BoxStyle

### getValue {#getValue--}
```
public String getValue()
```

Obtient la valeur du champ.

**Returns:**
valeur String

### setNoToggleToOff {#setNoToggleToOff-boolean-}
```
public final void setNoToggleToOff(boolean value)
```

<p> Obtient ou définit le drapeau qui permet au bouton radio de ne pas avoir de valeur sélectionnée. Si {@code }, exactement un bouton radio doit être sélectionné en permanence ; sélectionner le bouton actuellement sélectionné n'a aucun effet. Si {@code }, cliquer sur le bouton sélectionné le désélectionne, laissant aucun bouton sélectionné. </p> <hr> Certains lecteurs PDF (y compris Adobe Acrobat) peuvent ignorer l'état du drapeau.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setPosition {#setPosition-com.aspose.pdf.Point-}
Déplace tous les sous-éléments du bouton radio vers les positions spécifiées sur la page.

### setSelected {#setSelected-int-}
```
public void setSelected(int value)
```

Définit l'index de l'élément sélectionné. La numérotation des éléments commence à 1.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setStyle {#setStyle-com.aspose.pdf.BoxStyle-}
Style de la boîte de champ.

### setValue {#setValue-java.lang.String-}
Définit la valeur du champ.

### updateAppearances {#updateAppearances--}
```
public void updateAppearances()
```

Met à jour la valeur des apparences.
