---
title: "ChoiceField"
linktitle: "ChoiceField"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente la classe de base pour les champs de choix."
type: docs
weight: 590
url: /fr/java/com.aspose.pdf/choicefield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.Field, com.aspose.pdf.ChoiceField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public abstract class ChoiceField extends Field
```

Représente la classe de base pour les champs de choix.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ChoiceField](#ChoiceField-com.aspose.pdf.IDocument-) | Crée un champ de choix (pour le générateur) |
| [ChoiceField](#ChoiceField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Constructeur pour ChoiceField. |
| [ChoiceField](#ChoiceField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Constructeur pour ChoiceField. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [addOption](#addOption-java.lang.String-) | Ajoute une nouvelle option avec le nom spécifié. |
| [addOption](#addOption-java.lang.String-java.lang.String-) | Ajoute une nouvelle option avec la valeur d'exportation et le nom spécifiés. |
| [deleteOption](#deleteOption-java.lang.String-) | Supprime l'option par son nom. |
| [getCommitImmediately](#getCommitImmediately--) | Obtient le drapeau de validation lors du changement de sélection. |
| [getMultiSelect](#getMultiSelect--) | Obtient le drapeau de sélection multiple. |
| [getOptions](#getOptions--) | Obtient la collection d'options de choix. |
| [getSelected](#getSelected--) | Obtient l'index de l'option sélectionnée. Cette propriété permet de modifier la sélection. |
| [getSelectedItems](#getSelectedItems--) | Définit le tableau des éléments sélectionnés. Pour une liste à sélection multiple, le tableau contient plus d'un élément. Pour une liste à sélection unique, il contient un seul élément. |
| [getValue](#getValue--) | Obtient la valeur du champ. |
| [setCommitImmediately](#setCommitImmediately-boolean-) | Définit le drapeau de validation lors du changement de sélection. |
| [setMultiSelect](#setMultiSelect-boolean-) | Définit le drapeau de sélection multiple. |
| [setOptions](#setOptions-java.util.List-) | Remplace les options disponibles par celles dont les noms sont fournis dans le paramètre options. |
| [setSelected](#setSelected-int-) | Définit l'index de l'option sélectionnée. Cette propriété permet de modifier la sélection. |
| [setSelectedItems](#setSelectedItems-int:A-) | Définit le tableau des éléments sélectionnés. Pour une liste à sélection multiple, le tableau contient plus d'un élément. Pour une liste à sélection unique, il contient un seul élément. |
| [setValue](#setValue-java.lang.String-) | Définit la valeur du champ. |

### ChoiceField {#ChoiceField-com.aspose.pdf.IDocument-}
Crée un champ de choix (pour le générateur)

### ChoiceField {#ChoiceField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Constructeur pour ChoiceField.

### ChoiceField {#ChoiceField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Constructeur pour ChoiceField.

### addOption {#addOption-java.lang.String-}
Ajoute une nouvelle option avec le nom spécifié.

### addOption {#addOption-java.lang.String-java.lang.String-}
Ajoute une nouvelle option avec la valeur d'exportation et le nom spécifiés.

### deleteOption {#deleteOption-java.lang.String-}
Supprime l'option par son nom.

### getCommitImmediately {#getCommitImmediately--}
```
public boolean getCommitImmediately()
```

Obtient le drapeau de validation lors du changement de sélection.

**Returns:**
valeur booléenne

### getMultiSelect {#getMultiSelect--}
```
public boolean getMultiSelect()
```

Obtient le drapeau de sélection multiple.

**Returns:**
valeur booléenne

### getOptions {#getOptions--}
```
public OptionCollection getOptions()
```

Obtient la collection d'options de choix.

**Returns:**
Objet OptionCollection

### getSelected {#getSelected--}
```
public int getSelected()
```

Obtient l'index de l'option sélectionnée. Cette propriété permet de modifier la sélection.

**Returns:**
valeur int

### getSelectedItems {#getSelectedItems--}
```
public int[] getSelectedItems()
```

Définit le tableau des éléments sélectionnés. Pour une liste à sélection multiple, le tableau contient plus d'un élément. Pour une liste à sélection unique, il contient un seul élément.

**Returns:**
tableau de valeurs int

### getValue {#getValue--}
```
public String getValue()
```

Obtient la valeur du champ.

**Returns:**
valeur String

### setCommitImmediately {#setCommitImmediately-boolean-}
```
public void setCommitImmediately(boolean value)
```

Définit le drapeau de validation lors du changement de sélection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setMultiSelect {#setMultiSelect-boolean-}
```
public void setMultiSelect(boolean value)
```

Définit le drapeau de sélection multiple.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setOptions {#setOptions-java.util.List-}
Remplace les options disponibles par celles dont les noms sont fournis dans le paramètre options.

### setSelected {#setSelected-int-}
```
public void setSelected(int value)
```

Définit l'index de l'option sélectionnée. Cette propriété permet de modifier la sélection.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setSelectedItems {#setSelectedItems-int:A-}
```
public void setSelectedItems(int[] value)
```

Définit le tableau des éléments sélectionnés. Pour une liste à sélection multiple, le tableau contient plus d'un élément. Pour une liste à sélection unique, il contient un seul élément.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | tableau de valeurs int |

### setValue {#setValue-java.lang.String-}
Définit la valeur du champ.
